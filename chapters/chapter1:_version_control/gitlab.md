# GitLab

## CI/CD in GitLab

### Terminology
- **Pipeline**\
  The top-level component used to define a CI/CD process. Within a pipeline we can define stages and jobs
- **Jobs**
  - Associated with stages
  - Define the actual steps to be executed (such as running commands to compile code)
- **Stages**\
  Define he chronological order of jobs
- **Runners**
  - Open-source application that executes the instructions defined within jobs\
  - It can be installed on your local machine, a cloud server or on-perm\
  - Shared runners are hosted by GitLab
