![Jenkins](https://github.com/user-attachments/assets/459065a7-2166-47fc-a9be-9b68fa335e5f)
## Jenkins instalation
 - [How to install jenkins](https://www.jenkins.io/download/)

## Why Jenkins?

### Jenkins is one of the most popular tools for Continuous Integration (CI) and Continuous Delivery (CD), and has been the backbone of countless DevOps pipelines for years. The key reasons for its widespread adoption include:
 - **Open Source & Free** – JAs an open‑source project with a vast community of contributors, Jenkins benefits from continuous development, transparent roadmap and zero licensing costs.
 - **Extensibility & Flexibility** – With over 1,500 plugins available in the Jenkins Plugin Index, you can integrate Jenkins with virtually any tool in your development lifecycle: version control systems (e.g. Git), cloud platforms, testing frameworks, deployment tools, and more.
 - **Language & Platform Agnostic** – Whether your project is written in Java, Python, Go, or any other language, Jenkins can build it—and it runs on Linux, Windows, and macOS.
 - **Pipeline as Code** – Jenkinsfiles let you define your entire CI/CD process as code, enabling versioning, peer review of pipeline changes, and full reproducibility.
 - **Vibrant Community & Documentation** – A large user base means plenty of tutorials, examples, and community‑driven solutions to common challenges.


In short, Jenkins automates the critical stages of building, testing, and delivering software, boosting teams’ efficiency, consistency, and overall quality of output.


## First test of jenkins
### Setting Up Jenkins on Azure (Ubuntu VM)

After familiarizing myself with Jenkins and its core concepts, I provisioned a dedicated Ubuntu virtual machine in Microsoft Azure to host my own Jenkins server. Follow these steps to set it up:

1. **Create an Ubuntu VM in Azure**
   - Choose an appropriate VM size (e.g. Standard B1ms) and Ubuntu LTS image.  
   - Configure networking, SSH access and resource group as needed.

2. **Install Jenkins**
   ```bash
   # Add key and repository
   curl -fsSL https://pkg.jenkins.io/debian-stable/jenkins.io.key | sudo tee \
     /usr/share/keyrings/jenkins-keyring.asc > /dev/null
   echo deb [signed-by=/usr/share/keyrings/jenkins-keyring.asc] \
     https://pkg.jenkins.io/debian-stable binary/ | sudo tee \
     /etc/apt/sources.list.d/jenkins.list > /dev/null

   # Update and install
   sudo apt-get update
   sudo apt-get install -y openjdk-11-jdk jenkins
   # Jenkins Setup Guide

## 3. Open Required Ports

- In the Azure Portal, add an inbound security rule to allow TCP/8080.
- On the VM itself, if using UFW:

```bash
sudo ufw allow OpenSSH
sudo ufw allow 8080/tcp
sudo ufw enable
```

## 4. Enable and Start Jenkins

```bash
sudo systemctl enable jenkins
sudo systemctl start jenkins
```

## 5. Access the Jenkins Web UI

Open your browser and go to:

```
http://<YOUR_VM_PUBLIC_IP>:8080
```

You will be prompted to unlock Jenkins and complete the initial setup via the web interface.

## Backups in Jenkins

Regular backups of your Jenkins data are essential for security and business continuity. In case of hardware failure, accidental deletion, or configuration corruption, backups allow you to restore your Jenkins server quickly. In Jenkins there are three main approaches to backing up:

1. **Filesystem Snapshots**  
   - **Description**: Take a snapshot of the entire volume or partition that contains `JENKINS_HOME` (e.g. LVM snapshot, Azure Disk Snapshot, AWS EBS Snapshot).  
   - **Advantages**:  
     - Instant, consistent copy of everything (including binaries, logs, and workspaces).  
     - Minimal downtime if your snapshot technology supports hot snapshots.  
   - **Disadvantages**:  
     - Consumes significant storage unless you use deduplication.  
     - Restoration requires provisioning a full volume or partition from the snapshot.

2. **Backup Plugins**  
   - **Examples**:  
     - **ThinBackup** – backs up critical files only (`config.xml`, job folders, plugins).  
     - **Backup Plugin** – flexible scheduling, versioning, and the ability to send backups to FTP/SCP.  
   - **Advantages**:  
     - GUI inside Jenkins for scheduling and configuring backups.  
     - Selective backup (e.g. only config, only jobs).  
   - **Disadvantages**:  
     - Often excludes workspaces and logs by default.  
     - Can put load on the controller during archive operations.

3. **Custom Shell Script**  
   - **Description**: A Bash or PowerShell script that extracts key data from `JENKINS_HOME`, dumps a list of installed plugins, packages everything into an archive, and optionally pushes it to remote storage.  
   - **Advantages**:  
     - Full control over what and when you back up.  
     - Easy to integrate with custom retention policies or external storage.  
   - **Disadvantages**:  
     - You must maintain and test the script yourself.  
     - To guarantee 100% consistency, you may need to stop or quiet down Jenkins during the backup.

---

### Example Bash Backup Script

This script will:
1. Dump the list of installed plugins  
2. Archive `JENKINS_HOME` (excluding large `workspace` and `logs` directories)  
3. Rotate backups older than a specified retention period  

Save as `backup-jenkins.sh`, make executable (`chmod +x`), and schedule with cron.

**shell script** - [jenkins-backup.sh](https://github.com/sue445/jenkins-backup-script/blob/master/jenkins-backup.sh)
