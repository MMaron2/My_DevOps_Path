# Notes, Commands and resources for all my git teaching

## 1. Notes

### 1.1. Staging area

If I want to connect to **GitHub/GitLab** by SSH at first i neet to generate ssh key by comman below in commands->ssh section
By using a **git add** command there is fiew things behind it\

![Zrzut ekranu 2024-11-10 005626](https://github.com/user-attachments/assets/cbb0a2c8-084f-47cb-a288-652f6cad5a28)\

**More staging area and git add** - https://git-scm.com/about/staging-area

---
### 1.2. Branching Strategy
**A branching strategy is a:**\
**1.**  A software development workflow within the context of Git(o other Version Control System)\
**2.**  Describes how a development team will create collaborate on, and merge branches of source code i codebase
- **Git**\
  ![Zrzut ekranu 2024-11-10 200505](https://github.com/user-attachments/assets/cf25e331-ea2a-4a66-b943-a0f322b0505c)
- **GitHub**\
  ![Zrzut ekranu 2024-11-10 200302](https://github.com/user-attachments/assets/53a1e259-6817-4f2b-a4e4-578e88e2c627)
- **GitLab**\
  ![Zrzut ekranu 2024-11-10 200728](https://github.com/user-attachments/assets/66e2f307-aac9-428c-bcee-d9c8199cad29)\
  **GitLab flow summary**
  - There are two options
    - Environment Branches\
      Changes are promoted through one or more pre-production branches
    - Release Branches\
      Used when releasing software to the outside world(such as open-source project)
## 2. Commands
- **SSH Commands**
  - **key_gen** - ssh-keygen -t ed25519 -C "Title for your key"
- **version control commands**
  - **git pull** - fetch all changes in remote repository
      - **git pull --prune** - fetcha all changes in branches in remote repository (if branch does not exist in remote repo deletes it from your local list) 
  - **git push** - push the changes to remote repository
      - **git push -u origin [branch name]** - push the new branch to the remote repository\
        you can use only ***git push*** without parameters if your branch already exist in remote repositor
  - **git checkout** - change the branch which you works now
      - **git checkout -b [branch name]** - creates a new branch and changes to it
  - **git branch**
      - **git branch -d [branch name]** - deletes the breanch 
## 3. Resources
<details>

<summary>Logs from terminal</summary>
-[Git and GitLab Flow](https://github.com/MMaron2/My_DevOps_Path/blob/main/resources/logs_from_terminal/GitLabPracticeV1.txt)


</details>
