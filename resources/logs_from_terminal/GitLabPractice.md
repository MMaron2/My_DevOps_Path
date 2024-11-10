mmaron@DESKTOP-AL3UD1R:~$ ls -l
total 12
drwxr-xr-x  2 mmaron mmaron 4096 Nov 10 15:08 BashScriptPr
drwxr-xr-x  5 mmaron mmaron 4096 Nov 10 01:13 My_DevOps_Path
drwxr-xr-x 19 mmaron mmaron 4096 Nov 10 13:49 ardupilot
mmaron@DESKTOP-AL3UD1R:~$
mmaron@DESKTOP-AL3UD1R:~$
mmaron@DESKTOP-AL3UD1R:~$
mmaron@DESKTOP-AL3UD1R:~$ cd BashScriptPr/
mmaron@DESKTOP-AL3UD1R:~/BashScriptPr$
mmaron@DESKTOP-AL3UD1R:~/BashScriptPr$
mmaron@DESKTOP-AL3UD1R:~/BashScriptPr$
mmaron@DESKTOP-AL3UD1R:~/BashScriptPr$ ls -l
total 0
mmaron@DESKTOP-AL3UD1R:~/BashScriptPr$ mkdir file-jaintor
mmaron@DESKTOP-AL3UD1R:~/BashScriptPr$
mmaron@DESKTOP-AL3UD1R:~/BashScriptPr$
mmaron@DESKTOP-AL3UD1R:~/BashScriptPr$ cd file-jaintor/
mmaron@DESKTOP-AL3UD1R:~/BashScriptPr/file-jaintor$
mmaron@DESKTOP-AL3UD1R:~/BashScriptPr/file-jaintor$
mmaron@DESKTOP-AL3UD1R:~/BashScriptPr/file-jaintor$ code .
mmaron@DESKTOP-AL3UD1R:~/BashScriptPr/file-jaintor$ cd ../../
mmaron@DESKTOP-AL3UD1R:~$ ls -l
total 12
drwxr-xr-x  3 mmaron mmaron 4096 Nov 10 19:51 BashScriptPr
drwxr-xr-x  5 mmaron mmaron 4096 Nov 10 01:13 My_DevOps_Path
drwxr-xr-x 19 mmaron mmaron 4096 Nov 10 13:49 ardupilot
mmaron@DESKTOP-AL3UD1R:~$
mmaron@DESKTOP-AL3UD1R:~$
mmaron@DESKTOP-AL3UD1R:~$ mkdir DevOpsPath
mmaron@DESKTOP-AL3UD1R:~$
mmaron@DESKTOP-AL3UD1R:~$
mmaron@DESKTOP-AL3UD1R:~$ cd DevOpsPath/
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath$ GitLab_projects
GitLab_projects: command not found
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath$
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath$
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath$ mkdir GitLabProjects
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath$
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath$ cd GitLabProjects/
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects$ git clone git@gitlab.com:devops-test-group2675845/mmaron_test_project.git
Cloning into 'mmaron_test_project'...
remote: Enumerating objects: 3, done.
remote: Counting objects: 100% (3/3), done.
remote: Compressing objects: 100% (2/2), done.
remote: Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
Receiving objects: 100% (3/3), done.
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects$
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects$
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects$
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects$ ls -l
total 4
drwxr-xr-x 3 mmaron mmaron 4096 Nov 10 21:06 mmaron_test_project
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects$ cd mmaron_test_project/
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$ ls -l
total 8
-rw-r--r-- 1 mmaron mmaron 6231 Nov 10 21:06 README.md
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$ ls -la
total 20
drwxr-xr-x 3 mmaron mmaron 4096 Nov 10 21:06 .
drwxr-xr-x 3 mmaron mmaron 4096 Nov 10 21:06 ..
drwxr-xr-x 8 mmaron mmaron 4096 Nov 10 21:06 .git
-rw-r--r-- 1 mmaron mmaron 6231 Nov 10 21:06 README.md
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$ git status
On branch main
Your branch is up to date with 'origin/main'.

nothing to commit, working tree clean
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$ git checkout
HEAD                origin/HEAD         origin/production
main                origin/main         production
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$ git checkout -b readme-introdction
Switched to a new branch 'readme-introdction'
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$ git status
On branch readme-introdction
nothing to commit, working tree clean
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$ ls -l
total 8
-rw-r--r-- 1 mmaron mmaron 6231 Nov 10 21:06 README.md
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$ vim README.md
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$ git status
On branch readme-introdction
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   README.md

no changes added to commit (use "git add" and/or "git commit -a")
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$ git add README.md
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$ git status
On branch readme-introdction
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        modified:   README.md

mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$ git log
commit 0530665d0ba386349a404484a6fdfca1cbc0c42f (HEAD -> readme-introdction, origin/production, origin/main, origin/HEAD, main)
Author: Mateusz Maron <273150@student.pwr.edu.pl>
Date:   Sat Nov 9 17:08:28 2024 +0000

    Initial commit
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$ git commit -m "Updat
ing project readme with introduction"
Author identity unknown

*** Please tell me who you are.

Run

  git config --global user.email "you@example.com"
  git config --global user.name "Your Name"

to set your account's default identity.
Omit --global to set the identity only in this repository.

fatal: empty ident name (for <mmaron@DESKTOP-AL3UD1R.>) not allowed
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$ git config --globaluser.email "matesz.maron12@gmail.com
> ^C
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$ git config --globaluser.email "matesz.maron12@gmail.com"
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$ git config --globaluser.name "MMaron"
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$ git commit -m "Updating project readme with introduction"
[readme-introdction 4c19d0a] Updating project readme with introduction
 1 file changed, 3 insertions(+)
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$ git status
On branch readme-introdction
nothing to commit, working tree clean
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$ git push -u origin r
eadme-introduction
error: src refspec readme-introduction does not match any
error: failed to push some refs to 'gitlab.com:devops-test-group2675845/mmaron_test_project.git'
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$ git config --global
user.name "MMaronC"
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$ git push -u origin readme-introduction
error: src refspec readme-introduction does not match any
error: failed to push some refs to 'gitlab.com:devops-test-group2675845/mmaron_test_project.git'
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$ ssh -T MMaronC@gitla
b.com
MMaronC@gitlab.com: Permission denied (publickey).
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$ ssh -T git@gitlab.co
m
Welcome to GitLab, @MMaronC!
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$ git push -u origin readme-introduction
error: src refspec readme-introduction does not match any
error: failed to push some refs to 'gitlab.com:devops-test-group2675845/mmaron_test_project.git'
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$ git push -u origin main
Branch 'main' set up to track remote branch 'main' from 'origin'.
Everything up-to-date
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$ git push -u main
fatal: 'main' does not appear to be a git repository
fatal: Could not read from remote repository.

Please make sure you have the correct access rights
and the repository exists.
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$ git stasus
git: 'stasus' is not a git command. See 'git --help'.

The most similar command is
        status
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$ git status
On branch main
Your branch is up to date with 'origin/main'.

nothing to commit, working tree clean
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$ ls -l
total 8
-rw-r--r-- 1 mmaron mmaron 6231 Nov 10 21:18 README.md
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$ vim README.md
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$ git status
On branch main
Your branch is up to date with 'origin/main'.

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   README.md

no changes added to commit (use "git add" and/or "git commit -a")
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$ git add Re
fatal: pathspec 'Re' did not match any files
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$ git add README.md
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$ git commit -m "editREADME-init"
[main 61579ad] edit README-init
 1 file changed, 1 insertion(+), 1 deletion(-)
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$ git push -u origin m
ain
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 16 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 299 bytes | 299.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0
To gitlab.com:devops-test-group2675845/mmaron_test_project.git
   0530665..61579ad  main -> main
Branch 'main' set up to track remote branch 'main' from 'origin'.
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$ git branch
HEAD                 origin/HEAD          origin/production
main                 origin/main          readme-introdction
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$ git branch readme-introdction
fatal: A branch named 'readme-introdction' already exists.
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$ git checkout
HEAD                 origin/HEAD          origin/production    readme-introdction
main                 origin/main          production
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$ git checkout readme-introdction
Switched to branch 'readme-introdction'
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$ git status
On branch readme-introdction
nothing to commit, working tree clean
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$ git push -u origin readme-introduction
error: src refspec readme-introduction does not match any
error: failed to push some refs to 'gitlab.com:devops-test-group2675845/mmaron_test_project.git'
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$ git push -u origin readme-introdction
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 16 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 354 bytes | 354.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0
remote:
remote: To create a merge request for readme-introdction, visit:
remote:   https://gitlab.com/devops-test-group2675845/mmaron_test_project/-/merge_requests/new?merge_request%5Bsource_branch%5D=readme-introdction
remote:
To gitlab.com:devops-test-group2675845/mmaron_test_project.git
 * [new branch]      readme-introdction -> readme-introdction
Branch 'readme-introdction' set up to track remote branch 'readme-introdction' from 'origin'.
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$ vim README.md
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$ git status
On branch readme-introdction
Your branch is up to date with 'origin/readme-introdction'.

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   README.md

no changes added to commit (use "git add" and/or "git commit -a")
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$ git add README.md
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$ git commit -m "addin
g third activity to project README"
[readme-introdction 11cb9cc] adding third activity to project README
 1 file changed, 1 insertion(+), 1 deletion(-)
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$ git status
On branch readme-introdction
Your branch is ahead of 'origin/readme-introdction' by 1 commit.
  (use "git push" to publish your local commits)

nothing to commit, working tree clean
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$ git log
commit 11cb9ccd5cfa59086cd4bc94b5ee3befdd3482e3 (HEAD -> readme-introdction)
Author: MMaronC <matesz.maron12@gmail.com>
Date:   Sun Nov 10 21:39:08 2024 +0100

    adding third activity to project README

commit 4c19d0afa9b9e62e1582f3048908f3b4244c7f7e (origin/readme-introdction)
Author: MMaron <matesz.maron12@gmail.com>
Date:   Sun Nov 10 21:10:41 2024 +0100

    Updating project readme with introduction

commit 0530665d0ba386349a404484a6fdfca1cbc0c42f (origin/production)
Author: Mateusz Maron <273150@student.pwr.edu.pl>
Date:   Sat Nov 9 17:08:28 2024 +0000

    Initial commit
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$ git log -l
error: switch `l' requires a value
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$ git push
To gitlab.com:devops-test-group2675845/mmaron_test_project.git
 ! [rejected]        readme-introdction -> readme-introdction (fetch first)
error: failed to push some refs to 'gitlab.com:devops-test-group2675845/mmaron_test_project.git'
hint: Updates were rejected because the remote contains work that you do
hint: not have locally. This is usually caused by another repository pushing
hint: to the same ref. You may want to first integrate the remote changes
hint: (e.g., 'git pull ...') before pushing again.
hint: See the 'Note about fast-forwards' in 'git push --help' for details.
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$ git status
On branch readme-introdction
Your branch is ahead of 'origin/readme-introdction' by 1 commit.
  (use "git push" to publish your local commits)

nothing to commit, working tree clean
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$ git push
To gitlab.com:devops-test-group2675845/mmaron_test_project.git
 ! [rejected]        readme-introdction -> readme-introdction (fetch first)
error: failed to push some refs to 'gitlab.com:devops-test-group2675845/mmaron_test_project.git'
hint: Updates were rejected because the remote contains work that you do
hint: not have locally. This is usually caused by another repository pushing
hint: to the same ref. You may want to first integrate the remote changes
hint: (e.g., 'git pull ...') before pushing again.
hint: See the 'Note about fast-forwards' in 'git push --help' for details.
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$ git pull
remote: Enumerating objects: 1, done.
remote: Counting objects: 100% (1/1), done.
remote: Total 1 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
Unpacking objects: 100% (1/1), 250 bytes | 250.00 KiB/s, done.
From gitlab.com:devops-test-group2675845/mmaron_test_project
   4c19d0a..a892c9e  readme-introdction -> origin/readme-introdction
hint: You have divergent branches and need to specify how to reconcile them.
hint: You can do so by running one of the following commands sometime before
hint: your next pull:
hint:
hint:   git config pull.rebase false  # merge (the default strategy)
hint:   git config pull.rebase true   # rebase
hint:   git config pull.ff only       # fast-forward only
hint:
hint: You can replace "git config" with "git config --global" to set a default
hint: preference for all repositories. You can also pass --rebase, --no-rebase,
hint: or --ff-only on the command line to override the configured default per
hint: invocation.
fatal: Need to specify how to reconcile divergent branches.
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$ vim README.md
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$ git push
To gitlab.com:devops-test-group2675845/mmaron_test_project.git
 ! [rejected]        readme-introdction -> readme-introdction (non-fast-forward)
error: failed to push some refs to 'gitlab.com:devops-test-group2675845/mmaron_test_project.git'
hint: Updates were rejected because the tip of your current branch is behind
hint: its remote counterpart. Integrate the remote changes (e.g.
hint: 'git pull ...') before pushing again.
hint: See the 'Note about fast-forwards' in 'git push --help' for details.
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$ git pull
remote: Enumerating objects: 1, done.
remote: Counting objects: 100% (1/1), done.
remote: Total 1 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
Unpacking objects: 100% (1/1), 295 bytes | 295.00 KiB/s, done.
From gitlab.com:devops-test-group2675845/mmaron_test_project
   61579ad..afed511  main       -> origin/main
Your configuration specifies to merge with the ref 'refs/heads/readme-introdction'
from the remote, but no such ref was fetched.
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$ git checkout main
Switched to branch 'main'
Your branch is behind 'origin/main' by 3 commits, and can be fast-forwarded.
  (use "git pull" to update your local branch)
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$ git log
commit 61579ad4fa8dbffaa6a9e39450bd0a1009edc207 (HEAD -> main)
Author: MMaronC <matesz.maron12@gmail.com>
Date:   Sun Nov 10 21:19:06 2024 +0100

    edit README-init

commit 0530665d0ba386349a404484a6fdfca1cbc0c42f (origin/production)
Author: Mateusz Maron <273150@student.pwr.edu.pl>
Date:   Sat Nov 9 17:08:28 2024 +0000

    Initial commit
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$ git che
checkout      cherry        cherry-pick
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$ git che
checkout      cherry        cherry-pick
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$ git checkout
FETCH_HEAD                  origin/HEAD                 origin/readme-introdction
HEAD                        origin/main                 production
main                        origin/production           readme-introdction
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$ git branch -d
main                 readme-introdction
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$ git branch -d readme-introdction
error: The branch 'readme-introdction' is not fully merged.
If you are sure you want to delete it, run 'git branch -D readme-introdction'.
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$ git branch -D readme
-introdction
Deleted branch readme-introdction (was 11cb9cc).
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$ ls -l
total 8
-rw-r--r-- 1 mmaron mmaron 6246 Nov 10 21:42 README.md
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$ vim README.md
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$ git pull
Updating 61579ad..afed511
Fast-forward
 README.md | 3 +++
 1 file changed, 3 insertions(+)
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$ git status
On branch main
Your branch is up to date with 'origin/main'.

nothing to commit, working tree clean
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$ cat README.md
# MMaron_test_project

## Introduction

* Name: Mateusz
* Activities: squash, box

## Getting started

To make it easy for you to get started with GitLab, here's a list of recommended next steps.

Already a pro? Just edit this README.md and make it your own. Want to make it easy? [Use the template at the bottom](#editing-this-readme)!

## Add your files

- [ ] [Create](https://docs.gitlab.com/ee/user/project/repository/web_editor.html#create-a-file) or [upload](https://docs.gitlab.com/ee/user/project/repository/web_editor.html#upload-a-file) files
- [ ] [Add files using the command line](https://docs.gitlab.com/ee/gitlab-basics/add-file.html#add-a-file-using-the-command-line) or push an existing Git repository with the following command:

```
cd existing_repo
git remote add origin https://gitlab.com/devops-test-group2675845/mmaron_test_project.git
git branch -M main
git push -uf origin main
```

## Integrate with your tools

- [ ] [Set up project integrations](https://gitlab.com/devops-test-group2675845/mmaron_test_project/-/settings/integrations)

## Collaborate with your team

- [ ] [Invite team members and collaborators](https://docs.gitlab.com/ee/user/project/members/)
- [ ] [Create a new merge request](https://docs.gitlab.com/ee/user/project/merge_requests/creating_merge_requests.html)
- [ ] [Automatically close issues from merge requests](https://docs.gitlab.com/ee/user/project/issues/managing_issues.html#closing-issues-automatically)
- [ ] [Enable merge request approvals](https://docs.gitlab.com/ee/user/project/merge_requests/approvals/)
- [ ] [Set auto-merge](https://docs.gitlab.com/ee/user/project/merge_requests/merge_when_pipeline_succeeds.html)

## Test and Deploy

Use the built-in continuous integration in GitLab.

- [ ] [Get started with GitLab CI/CD](https://docs.gitlab.com/ee/ci/quick_start/index.html)
- [ ] [Analyze your code for known vulnerabilities with Static Application Security Testing(SAST)](https://docs.gitlab.com/ee/user/application_security/sast/)
- [ ] [Deploy to Kubernetes, Amazon EC2, or Amazon ECS using Auto Deploy](https://docs.gitlab.com/ee/topics/autodevops/requirements.html)
- [ ] [Use pull-based deployments for improved Kubernetes management](https://docs.gitlab.com/ee/user/clusters/agent/)
- [ ] [Set up protected environments](https://docs.gitlab.com/ee/ci/environments/protected_environments.html)

***

# Editing this README

When you're ready to make this README your own, just edit this file and use the handy template below (or feel free to structure it however you want - this is just a starting point!). Thanks to [makeareadme.com](https://www.makeareadme.com/) for this template.

## Suggestions for a good README

Every project is different, so consider which of these sections apply to yours. The sections used in the template are suggestions for most open source projects. Also keep in mind thatwhile a README can be too long and detailed, too long is better than too short. If you think your README is too long, consider utilizing another form of documentation rather than cutting out information.

## Name
Choose a self-explaining name for your project.

## Description
Let people know what your project can do specifically. Provide context and add a link to any reference visitors might be unfamiliar with. A list of Features or a Background subsectioncan also be added here. If there are alternatives to your project, this is a good place to list differentiating factors.

## Badges
On some READMEs, you may see small images that convey metadata, such as whether or not all the tests are passing for the project. You can use Shields to add some to your README. Many services also have instructions for adding a badge.

## Visuals
Depending on what you are making, it can be a good idea to include screenshots or even a video (you'll frequently see GIFs rather than actual videos). Tools like ttygif can help, but check out Asciinema for a more sophisticated method.

## Installation
Within a particular ecosystem, there may be a common way of installing things, such as using Yarn, NuGet, or Homebrew. However, consider the possibility that whoever is reading your README is a novice and would like more guidance. Listing specific steps helps remove ambiguity and gets people to using your project as quickly as possible. If it only runs in a specific context like a particular programming language version or operating system or has dependencies that have to be installed manually, also add a Requirements subsection.

## Usage
Use examples liberally, and show the expected output if you can. It's helpful to have inline the smallest example of usage that you can demonstrate, while providing links to more sophisticated examples if they are too long to reasonably include in the README.

## Support
Tell people where they can go to for help. It can be any combination of an issue tracker, achat room, an email address, etc.

## Roadmap
If you have ideas for releases in the future, it is a good idea to list them in the README.

## Contributing
State if you are open to contributions and what your requirements are for accepting them.

For people who want to make changes to your project, it's helpful to have some documentation on how to get started. Perhaps there is a script that they should run or some environment variables that they need to set. Make these steps explicit. These instructions could also beuseful to your future self.

You can also document commands to lint the code or run tests. These steps help to ensure high code quality and reduce the likelihood that the changes inadvertently break something. Having instructions for running tests is especially helpful if it requires external setup, such as starting a Selenium server for testing in a browser.

## Authors and acknowledgment
Show your appreciation to those who have contributed to the project.

## License
For open source projects, say how it is licensed.

## Project status
If you have run out of energy or time for your project, put a note at the top of the READMEsaying that development has slowed down or stopped completely. Someone may choose to fork your project or volunteer to step in as a maintainer or owner, allowing your project to keep going. You can also make an explicit request for maintainers.
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$ head README.md
# MMaron_test_project

## Introduction

* Name: Mateusz
* Activities: squash, box

## Getting started

To make it easy for you to get started with GitLab, here's a list of recommended next steps.
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$ git checkout -b readme-introduction
Switched to a new branch 'readme-introduction'
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$ git status
On branch readme-introduction
nothing to commit, working tree clean
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$ vim README.md
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$ git status
On branch readme-introduction
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   README.md

no changes added to commit (use "git add" and/or "git commit -a")
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$ git add README.md
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$ git commit -m "addin
g last name to README file"
[readme-introduction fd265e2] adding last name to README file
 1 file changed, 1 insertion(+)
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$ git status
On branch readme-introduction
nothing to commit, working tree clean
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$ git log
commit fd265e2b3b5a5b3c7b01339f601ef32ebfe8784f (HEAD -> readme-introduction)
Author: MMaronC <matesz.maron12@gmail.com>
Date:   Sun Nov 10 21:45:47 2024 +0100

    adding last name to README file

commit afed511984218159ef82941f2ba7e05164502de1 (origin/main, origin/HEAD, main)
Merge: 61579ad a892c9e
Author: Mateusz Maron <273150@student.pwr.edu.pl>
Date:   Sun Nov 10 20:41:38 2024 +0000

    Merge branch 'readme-introdction' into 'main'

    Updating project readme with introduction

    See merge request devops-test-group2675845/mmaron_test_project!1

commit a892c9eec98f0f8fec7b0d68e2e2e38fec9bbd7d (origin/readme-introdction)
Merge: 4c19d0a 61579ad
Author: Mateusz Maron <273150@student.pwr.edu.pl>
Date:   Sun Nov 10 20:30:49 2024 +0000

    Merge branch 'main' into 'readme-introdction'

    # Conflicts:
    #   README.md

commit 61579ad4fa8dbffaa6a9e39450bd0a1009edc207
Author: MMaronC <matesz.maron12@gmail.com>
Date:   Sun Nov 10 21:19:06 2024 +0100

    edit README-init

commit 4c19d0afa9b9e62e1582f3048908f3b4244c7f7e
Author: MMaron <matesz.maron12@gmail.com>
Date:   Sun Nov 10 21:10:41 2024 +0100

    Updating project readme with introduction

commit 0530665d0ba386349a404484a6fdfca1cbc0c42f (origin/production)
Author: Mateusz Maron <273150@student.pwr.edu.pl>
Date:   Sat Nov 9 17:08:28 2024 +0000

    Initial commit
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$ git push -u origin
FETCH_HEAD                  main                        origin/production
HEAD                        origin/HEAD                 origin/readme-introdction
ORIG_HEAD                   origin/main                 readme-introduction
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$ git che
checkout      cherry        cherry-pick
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$ git checkout origin/
production
Note: switching to 'origin/production'.

You are in 'detached HEAD' state. You can look around, make experimental
changes and commit them, and you can discard any commits you make in this
state without impacting any branches by switching back to a branch.

If you want to create a new branch to retain commits you create, you may
do so (now or later) by using -c with the switch command. Example:

  git switch -c <new-branch-name>

Or undo this operation with:

  git switch -

Turn off this advice by setting config variable advice.detachedHead to false

HEAD is now at 0530665 Initial commit
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$ git status
HEAD detached at origin/production
nothing to commit, working tree clean
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$ git che
checkout      cherry        cherry-pick
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$ git checkout main
Previous HEAD position was 0530665 Initial commit
Switched to branch 'main'
Your branch is up to date with 'origin/main'.
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$ git status
On branch main
Your branch is up to date with 'origin/main'.

nothing to commit, working tree clean
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$ git che
checkout      cherry        cherry-pick
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$ git checkout
FETCH_HEAD                  origin/HEAD                 production
HEAD                        origin/main                 readme-introdction
ORIG_HEAD                   origin/production           readme-introduction
main                        origin/readme-introdction
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$ git checkout
FETCH_HEAD                  origin/HEAD                 production
HEAD                        origin/main                 readme-introdction
ORIG_HEAD                   origin/production           readme-introduction
main                        origin/readme-introdction
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$ git checkout readme-introdction
Branch 'readme-introdction' set up to track remote branch 'readme-introdction' from 'origin'.
Switched to a new branch 'readme-introdction'
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$ head README.md
# MMaron_test_project

## Introduction

* Name: Mateusz
* Activities: squash, box

## Getting started

To make it easy for you to get started with GitLab, here's a list of recommended next steps.
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$ git checkout readme-introduction
Switched to branch 'readme-introduction'
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$ head README.md
# MMaron_test_project

## Introduction

* Name: Mateusz
* Activities: squash, box
* LastName: Maron

## Getting started

mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$ git log
commit fd265e2b3b5a5b3c7b01339f601ef32ebfe8784f (HEAD -> readme-introduction)
Author: MMaronC <matesz.maron12@gmail.com>
Date:   Sun Nov 10 21:45:47 2024 +0100

    adding last name to README file

commit afed511984218159ef82941f2ba7e05164502de1 (origin/main, origin/HEAD, main)
Merge: 61579ad a892c9e
Author: Mateusz Maron <273150@student.pwr.edu.pl>
Date:   Sun Nov 10 20:41:38 2024 +0000

    Merge branch 'readme-introdction' into 'main'

    Updating project readme with introduction

    See merge request devops-test-group2675845/mmaron_test_project!1

commit a892c9eec98f0f8fec7b0d68e2e2e38fec9bbd7d (origin/readme-introdction, readme-introdction)
Merge: 4c19d0a 61579ad
Author: Mateusz Maron <273150@student.pwr.edu.pl>
Date:   Sun Nov 10 20:30:49 2024 +0000

    Merge branch 'main' into 'readme-introdction'

    # Conflicts:
    #   README.md

commit 61579ad4fa8dbffaa6a9e39450bd0a1009edc207
Author: MMaronC <matesz.maron12@gmail.com>
Date:   Sun Nov 10 21:19:06 2024 +0100

    edit README-init

commit 4c19d0afa9b9e62e1582f3048908f3b4244c7f7e
Author: MMaron <matesz.maron12@gmail.com>
Date:   Sun Nov 10 21:10:41 2024 +0100

    Updating project readme with introduction

commit 0530665d0ba386349a404484a6fdfca1cbc0c42f (origin/production)
Author: Mateusz Maron <273150@student.pwr.edu.pl>
Date:   Sat Nov 9 17:08:28 2024 +0000

    Initial commit
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$ git status
On branch readme-introduction
nothing to commit, working tree clean
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$ git branch
FETCH_HEAD                  origin/HEAD                 readme-introdction
HEAD                        origin/main                 readme-introduction
ORIG_HEAD                   origin/production
main                        origin/readme-introdction
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$ git branch -D readme
-introdction readme-introduction
Deleted branch readme-introdction (was a892c9e).
Deleted branch readme-introduction (was fd265e2).
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$ git branch
FETCH_HEAD                  main                        origin/production
HEAD                        origin/HEAD                 origin/readme-introdction
ORIG_HEAD                   origin/main
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$ git pull
Already up to date.
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$ git fetch -p
From gitlab.com:devops-test-group2675845/mmaron_test_project
 - [deleted]         (none)     -> origin/readme-introdction
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$ git che
checkout      cherry        cherry-pick
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$ git checkout -b readme-introduction
Switched to a new branch 'readme-introduction'
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$ ls- l
Command 'ls-' not found, did you mean:
  command 'lsd' from snap lsd (0.16.0)
  command 'lsw' from deb suckless-tools (46-1)
  command 'ls' from deb coreutils (8.32-4.1ubuntu1.2)
  command 'lsm' from deb lsm (1.0.4-2)
  command 'lsh' from deb lsh-client (2.1-13)
  command 'lsc' from deb livescript (1.6.1+dfsg-2)
See 'snap info <snapname>' for additional versions.

mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$ ls -l
total 8
-rw-r--r-- 1 mmaron mmaron 6289 Nov 10 21:48 README.md
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$ head README.md
# MMaron_test_project

## Introduction

* Name: Mateusz
* Activities: squash, box

## Getting started

To make it easy for you to get started with GitLab, here's a list of recommended next steps.
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$ vim README.md
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$ git status
On branch readme-introduction
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   README.md

no changes added to commit (use "git add" and/or "git commit -a")
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$ git add README.md
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$ git commit -m "adding last name to README file"
[readme-introduction ff29502] adding last name to README file
 1 file changed, 1 insertion(+)
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$ git status
On branch readme-introduction
nothing to commit, working tree clean
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$ git push -u origin
FETCH_HEAD            ORIG_HEAD             origin/HEAD           origin/production
HEAD                  main                  origin/main           readme-introduction
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$ git push -u origin readme-introduction
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 16 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 312 bytes | 312.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0
remote:
remote: To create a merge request for readme-introduction, visit:
remote:   https://gitlab.com/devops-test-group2675845/mmaron_test_project/-/merge_requests/new?merge_request%5Bsource_branch%5D=readme-introduction
remote:
To gitlab.com:devops-test-group2675845/mmaron_test_project.git
 * [new branch]      readme-introduction -> readme-introduction
Branch 'readme-introduction' set up to track remote branch 'readme-introduction' from 'origin'.
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$ vim README.md
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$ git add README.md
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$ git commit -m "addin
g third activity to README project file"
[readme-introduction 8f7945c] adding third activity to README project file
 1 file changed, 1 insertion(+), 1 deletion(-)
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$ git status
On branch readme-introduction
Your branch is ahead of 'origin/readme-introduction' by 1 commit.
  (use "git push" to publish your local commits)

nothing to commit, working tree clean
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$ git push
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 16 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 316 bytes | 316.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0
remote:
remote: View merge request for readme-introduction:
remote:   https://gitlab.com/devops-test-group2675845/mmaron_test_project/-/merge_requests/
remote:
To gitlab.com:devops-test-group2675845/mmaron_test_project.git
   ff29502..8f7945c  readme-introduction -> readme-introduction
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$ git status
On branch readme-introduction
Your branch is up to date with 'origin/readme-introduction'.

nothing to commit, working tree clean
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$ git pull
remote: Enumerating objects: 3, done.
remote: Counting objects: 100% (2/2), done.
remote: Compressing objects: 100% (2/2), done.
remote: Total 3 (delta 0), reused 0 (delta 0), pack-reused 1 (from 1)
Unpacking objects: 100% (3/3), 725 bytes | 362.00 KiB/s, done.
From gitlab.com:devops-test-group2675845/mmaron_test_project
   afed511..4ac6163  main       -> origin/main
   0530665..4efc880  production -> origin/production
 * [new tag]         v1.0       -> v1.0
Updating afed511..4ac6163
Fast-forward
 README.md | 3 ++-
 1 file changed, 2 insertions(+), 1 deletion(-)
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$ git branch
FETCH_HEAD                   origin/HEAD                  readme-introduction
HEAD                         origin/main                  v1.0
ORIG_HEAD                    origin/production
main                         origin/readme-introduction
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$ git branch
* main
  readme-introduction
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$ git branch -d readme-introduction
Deleted branch readme-introduction (was 8f7945c).
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$ git branch
* main
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$ git branch
* main
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$ git branch
FETCH_HEAD                   main                         origin/production
HEAD                         origin/HEAD                  origin/readme-introduction
ORIG_HEAD                    origin/main                  v1.0
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$ git branch --all
* main
  remotes/origin/HEAD -> origin/main
  remotes/origin/main
  remotes/origin/production
  remotes/origin/readme-introduction
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$ git pull --prune
From gitlab.com:devops-test-group2675845/mmaron_test_project
 - [deleted]         (none)     -> origin/readme-introduction
Already up to date.
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$ git branch --all
* main
  remotes/origin/HEAD -> origin/main
  remotes/origin/main
  remotes/origin/production
mmaron@DESKTOP-AL3UD1R:~/DevOpsPath/GitLabProjects/mmaron_test_project$

[mmaron@DESKTOP-AL3UD1R ~DevOpsPathGitLabProjectsmmaron_test_project.md](https://github.com/user-attachments/files/17693128/mmaron%40DESKTOP-AL3UD1R.DevOpsPathGitLabProjectsmmaron_test_project.md)
