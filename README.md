# IFocusDevOpsTraining

12/03/2025::
============

Introduction about the all tools 

<img width="846" alt="CI-CD" src="https://github.com/user-attachments/assets/1789ebfa-2809-465e-8dbc-01ad575eeba6" />


13/03/2025::
===============

Taken again 2nd demo of the all teh tools flow

<img width="846" alt="CI-CD" src="https://github.com/user-attachments/assets/cf86fc29-ece1-4fec-9579-dd2f1f61565f" />

What is Git?

Git is a free, open-source version control system (VCS) that helps developers manage their code. It's the most widely used tool VCS(version control system) Git is fast for committing, branching, merging, and comparing past versions Git is very high Performance and Flexibility,Security

Install Git in you local machine

https://git-scm.com/downloads/win

Please download the ---64-bit Git for Windows Setup.

Once download the git .exe file , double click and install the git on your machine

once installed right click on your local machine you can found Open Git batch here option, means git is installed successfully in your machine

![image](https://github.com/user-attachments/assets/e33acd91-3c58-4284-8e39-13f3f2b486d3)


GitHub account creation:: for creating github account EmailId is Required

go to link --https://github.com/signup?ref_cta=Sign+up&ref_loc=header+logged+out&ref_page=%2F&source=header-home

Enter Email & password ,Username click continue ---Account will create successfully image

![image](https://github.com/user-attachments/assets/f0e311c5-629f-4e53-bf3a-3edee944eeff)


Github::Github is a one of the SCM(Source code management) tool and store the Project code.

Repository: storage area of your source code. Create a Repository on GitHub

click Repositories

Enter Repository Name::

![image](https://github.com/user-attachments/assets/a6d6c3c8-8814-45b3-8c39-994e6546470d)

Public:: Anyone on the internet can see this repository.

Private:: You choose who can see and commit to this repository.

Click Create Repository

![image](https://github.com/user-attachments/assets/c592782f-e429-43bb-a064-fbbe24d30c41)

Repository Created SUccessfully with Default branch main

![image](https://github.com/user-attachments/assets/bb4deaf9-ff56-473a-b3e6-46ac0346883e)



14/03/2025::
============

Github Introduction::
===============

GitHub is a web-based platform for version control and collaboration, allowing developers to store and manage their code in repositories.

Version Control: ::
GitHub uses Git, a distributed version control system, to track changes in code. This allows multiple people to work on the same project without overwriting each other's contributions.

Repositories::: where you can store your project files and track the history of changes made to those files.Public and private repos can be created depending on accessibility needs.

Clone repository/Project from github to local machine steps::
=============================================

Fork::Fork means to make a copy of the repository into my own github account
A fork is a copy of a repository

![image](https://github.com/user-attachments/assets/9710696d-1991-4f8d-a66c-bc4ed70d44c3)

Fork done

![image](https://github.com/user-attachments/assets/9d7eeeeb-adb0-4aff-a5a4-78755e99d1c7)

Clone Project and Push Changes to Github Repository::

Go to Code and copy url

![image](https://github.com/user-attachments/assets/cfe0f9a6-e661-4a4c-871f-7a6d84c97f9a)

Go to Local Folder and right click and Open Git Bash here and it will navigate to gitbash

![image](https://github.com/user-attachments/assets/8622a586-526f-41c6-bb5c-3494372e0007)

navigate to gitbash

![image](https://github.com/user-attachments/assets/6a8aab98-73eb-4fc8-bfb2-607297064e75)

Copy Repository URL

![image](https://github.com/user-attachments/assets/19aedccf-571e-4034-b5fc-8d05d442f39d)

Git Commands::

>git clone <repo url>

>git clone https://github.com/parasa7358/spring-petclinic.git
>

>![image](https://github.com/user-attachments/assets/e8b7464b-069e-43ed-b372-86ddd7a730c4)


![image](https://github.com/user-attachments/assets/0590c587-3511-4a80-9de1-52536ec90cef)


>cd <reponame>

>git checkout <branchname>

>git status

>git add --all

>git status

>git commit -m "commit message"

>git push origin

All Steps::

HP@DESKTOP-E518Q66 MINGW64 ~/Desktop/Ifocus/AWS
$ git clone git@github.com:parasa7358/spring-petclinic.git
Cloning into 'spring-petclinic'...
The authenticity of host 'github.com (20.207.73.82)' can't be established.
ED25519 key fingerprint is SHA256:+DiY3wvvV6TuJJhbpZisF/zLDA0zPMSvHdkr4UvCOqU.
This key is not known by any other names.
Are you sure you want to continue connecting (yes/no/[fingerprint])? yes
Warning: Permanently added 'github.com' (ED25519) to the list of known hosts.
remote: Enumerating objects: 10425, done.
remote: Counting objects: 100% (2/2), done.
remote: Compressing objects: 100% (2/2), done.
remote: Total 10425 (delta 0), reused 0 (delta 0), pack-reused 10423 (from 2)
Receiving objects: 100% (10425/10425), 7.67 MiB | 706.00 KiB/s, done.
Resolving deltas: 100% (3935/3935), done.

HP@DESKTOP-E518Q66 MINGW64 ~/Desktop/Ifocus/AWS
$ cd spring-petclinic/

HP@DESKTOP-E518Q66 MINGW64 ~/Desktop/Ifocus/AWS/spring-petclinic (main)
$ git checkout feature/2025.02.24
branch 'feature/2025.02.24' set up to track 'origin/feature/2025.02.24'.
Switched to a new branch 'feature/2025.02.24'

HP@DESKTOP-E518Q66 MINGW64 ~/Desktop/Ifocus/AWS/spring-petclinic (feature/2025.02.24)
$ git status
On branch feature/2025.02.24
Your branch is up to date with 'origin/feature/2025.02.24'.

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   pom.xml

no changes added to commit (use "git add" and/or "git commit -a")

HP@DESKTOP-E518Q66 MINGW64 ~/Desktop/Ifocus/AWS/spring-petclinic (feature/2025.02.24)
$ git add --all

HP@DESKTOP-E518Q66 MINGW64 ~/Desktop/Ifocus/AWS/spring-petclinic (feature/2025.02.24)
$ git commit -m "This is first commit for this project and updated pom.xml"
[feature/2025.02.24 434fce4] This is first commit for this project and updated pom.xml
 1 file changed, 1 insertion(+)

HP@DESKTOP-E518Q66 MINGW64 ~/Desktop/Ifocus/AWS/spring-petclinic (feature/2025.02.24)
$ git push
ssh: Could not resolve hostname github.com: Name or service not known
fatal: Could not read from remote repository.

Please make sure you have the correct access rights
and the repository exists.

HP@DESKTOP-E518Q66 MINGW64 ~/Desktop/Ifocus/AWS/spring-petclinic (feature/2025.02.24)
$ git push origin
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 4 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 338 bytes | 338.00 KiB/s, done.
Total 3 (delta 2), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (2/2), completed with 2 local objects.
To github.com:parasa7358/spring-petclinic.git
   6c05fc9..434fce4  feature/2025.02.24 -> feature/2025.02.24

HP@DESKTOP-E518Q66 MINGW64 ~/Desktop/Ifocus/AWS/spring-petclinic (feature/2025.02.24)
$

Screenshot::

![image](https://github.com/user-attachments/assets/1e723036-90a9-4cee-8d31-2746f37f525b)


17/03/2025::
===========


Github branching strategy::
===========================

<img width="846" alt="Untitled" src="https://github.com/user-attachments/assets/406f212d-86de-4283-99f7-f8f823c99baf" />

A GitHub branching strategy is crucial for maintaining an organized workflow in version control. There are different strategies depending on the size of the project, the number of team members, and the desired workflow. Here are some common branching strategies used in GitHub:

main or master branch:: This is default branch and whenever we created the empty Repository by defauly main or master branche is created automatically.
main or master branch always stable and live code 

feature branch:: It could be a new feature, an improvement of existing features, bug fixes, or any other changes. A feature branch is a type of branch in Git typically used to develop new features for the software.feature branch will created from main or master OR feature branch created from latest release branch always based on the release cycle

formate:: feature/YYYY.MM.DD
 feature/2025.03.17

release branch:: Based on the release we have created release branch accourdingly and starts the next release cycle.
always release branch created from master only and master have stable and live code and post release we shold merged code changes to master branch only

release/2025.03.17

hotfix branch:: always created from main or master branch only for production fixes.once production fix done we should merged directly to main or master branch only.

always created this hotfix branch for production issues fixes

bugfix:: this branch is created from release branch to fix the LLE(lower level environemnt)/Pre-Prod/UAT/Non-Prod issues and once LLE issues fixed ,we should pushed their changes to release branch only.

cloning references::

![image](https://github.com/user-attachments/assets/87f6ed4a-095b-4faa-854a-7fcdc019f31f)


Generate SSHKeys::

syntax::ssh-keygen -t ed25519 -C "your_email@example.com"

Keys avaibale path and save the key (/c/Users/HP/.ssh/id_ed25519):
![image](https://github.com/user-attachments/assets/c1031abb-57bf-4585-88a9-e1fbb9358621)

![image](https://github.com/user-attachments/assets/ce78114d-1a3f-4adf-a677-c3f26736f6cc)


Please follow below links for more understanding 

https://docs.github.com/en/authentication/connecting-to-github-with-ssh

https://docs.github.com/en/authentication/connecting-to-github-with-ssh/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent

Once genearted the keys (public/private) and copy public key to Github Account

Go to -->settings

![image](https://github.com/user-attachments/assets/e6856f23-6d62-4e02-8fb2-05c720542ec3)

Click SSH and GPG Keys

![image](https://github.com/user-attachments/assets/906f1f68-79a8-4920-837f-38f165e5849e)

click New SSH Key

![image](https://github.com/user-attachments/assets/a461189f-f9e1-415c-b52e-c25f6cfaf1d2)

Add new SSH Key and click Add SSH Key

![image](https://github.com/user-attachments/assets/f62d4d90-f588-462b-bf04-54de51e566d8)

Clone Project code using SSH URL::
===============================

>git clone git@github.com:ifocusbatch2/spring-petclinic.git

![image](https://github.com/user-attachments/assets/1b704706-cfe5-4db1-8917-e7ca4c44e35f)

![image](https://github.com/user-attachments/assets/12f6150b-e9e9-4615-9864-4e3424a594dd)

![image](https://github.com/user-attachments/assets/03037e55-f77d-499e-b845-4e775b82afed)

![image](https://github.com/user-attachments/assets/8c5653a0-1427-4b26-968b-cda90c04cc48)


HP@DESKTOP-E518Q66 MINGW64 ~/Desktop/Ifocus/batch2_17
$ git clone git@github.com:ifocusbatch2/spring-petclinic.git
Cloning into 'spring-petclinic'...
The authenticity of host 'github.com (20.207.73.82)' can't be established.
ED25519 key fingerprint is SHA256:+DiY3wvvV6TuJJhbpZisF/zLDA0zPMSvHdkr4UvCOqU.
This key is not known by any other names.
Are you sure you want to continue connecting (yes/no/[fingerprint])? yes
Warning: Permanently added 'github.com' (ED25519) to the list of known hosts.
remote: Enumerating objects: 10430, done.
remote: Total 10430 (delta 0), reused 0 (delta 0), pack-reused 10430 (from 1)
Receiving objects: 100% (10430/10430), 7.67 MiB | 1.17 MiB/s, done.
Resolving deltas: 100% (3935/3935), done.

HP@DESKTOP-E518Q66 MINGW64 ~/Desktop/Ifocus/batch2_17
$ cd spring-petclinic/

HP@DESKTOP-E518Q66 MINGW64 ~/Desktop/Ifocus/batch2_17/spring-petclinic (main)
$ git status
On branch main
Your branch is up to date with 'origin/main'.

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   pom.xml

no changes added to commit (use "git add" and/or "git commit -a")

HP@DESKTOP-E518Q66 MINGW64 ~/Desktop/Ifocus/batch2_17/spring-petclinic (main)
$ git add --all

HP@DESKTOP-E518Q66 MINGW64 ~/Desktop/Ifocus/batch2_17/spring-petclinic (main)
$ git commit -m "updated pom.xml file"
[main b2e46bf] updated pom.xml file
 1 file changed, 1 insertion(+), 1 deletion(-)

HP@DESKTOP-E518Q66 MINGW64 ~/Desktop/Ifocus/batch2_17/spring-petclinic (main)
$ git push
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 4 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 340 bytes | 340.00 KiB/s, done.
Total 3 (delta 2), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (2/2), completed with 2 local objects.
To github.com:ifocusbatch2/spring-petclinic.git
   2aa53f9..b2e46bf  main -> main

HP@DESKTOP-E518Q66 MINGW64 ~/Desktop/Ifocus/batch2_17/spring-petclinic (main)
$ git checkout -b feature/2025.03.17
Switched to a new branch 'feature/2025.03.17'

HP@DESKTOP-E518Q66 MINGW64 ~/Desktop/Ifocus/batch2_17/spring-petclinic (feature/2025.03.17)
$ git status
On branch feature/2025.03.17
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   pom.xml

no changes added to commit (use "git add" and/or "git commit -a")

HP@DESKTOP-E518Q66 MINGW64 ~/Desktop/Ifocus/batch2_17/spring-petclinic (feature/2025.03.17)
$ git add --all

HP@DESKTOP-E518Q66 MINGW64 ~/Desktop/Ifocus/batch2_17/spring-petclinic (feature/2025.03.17)
$ git status
On branch feature/2025.03.17
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        modified:   pom.xml


HP@DESKTOP-E518Q66 MINGW64 ~/Desktop/Ifocus/batch2_17/spring-petclinic (feature/2025.03.17)
$ git commit -m "added branch"
[feature/2025.03.17 f393310] added branch
 1 file changed, 1 insertion(+), 1 deletion(-)

HP@DESKTOP-E518Q66 MINGW64 ~/Desktop/Ifocus/batch2_17/spring-petclinic (feature/2025.03.17)
$ git push
fatal: The current branch feature/2025.03.17 has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin feature/2025.03.17

To have this happen automatically for branches without a tracking
upstream, see 'push.autoSetupRemote' in 'git help config'.


HP@DESKTOP-E518Q66 MINGW64 ~/Desktop/Ifocus/batch2_17/spring-petclinic (feature/2025.03.17)
$ git push origin feature/2025.03.17
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 4 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 302 bytes | 302.00 KiB/s, done.
Total 3 (delta 2), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (2/2), completed with 2 local objects.
remote:
remote: Create a pull request for 'feature/2025.03.17' on GitHub by visiting:
remote:      https://github.com/ifocusbatch2/spring-petclinic/pull/new/feature/2025.03.17
remote:
To github.com:ifocusbatch2/spring-petclinic.git
 * [new branch]      feature/2025.03.17 -> feature/2025.03.17




18/03/2025::
=============

Raise PR (Pull Request) :: Merge the code from one branch to another branch that is called pull request

below are the steps to raise PR::

Go to -->Pull requests and click

![image](https://github.com/user-attachments/assets/5cfe4883-dd46-4643-a506-b54262c36202)

Click New Pull Request::

![image](https://github.com/user-attachments/assets/37020743-a2e9-4163-9afd-7680d58fc63a)

![image](https://github.com/user-attachments/assets/dad8eec2-b480-460f-8715-9d9c5fc3c12d)

please select base & compare branches so here base branch is release/2025.02.25 and compare branch is feature/2025.02.25

i'm going to merge code changes from feature branch to release branch 

![image](https://github.com/user-attachments/assets/185f0572-c51a-4ab2-884c-d2694522b268)

click create pull request

![image](https://github.com/user-attachments/assets/91068166-9d06-4b47-9d68-8c1251b0872f)

![image](https://github.com/user-attachments/assets/08a98671-c810-46fc-9024-17bae7538a61)


parasa7358 wants to merge 1 commit into release/2025.02.25 from feature/2025.02.25  

click merge request

![image](https://github.com/user-attachments/assets/44a4b84e-1aef-4b19-a93e-64e48b362b29)


confirm merge

![image](https://github.com/user-attachments/assets/cc12b687-b664-4497-bf91-0ab17f37bfa0)

Merged

![image](https://github.com/user-attachments/assets/9ee86d60-3e25-40a2-8d45-3bfe67668a2e)


Avoide conflicts in RealTime Scenarious::
=================

If multiple developers OR DevOps Engineers are working on same Project/MOdules, if they tried to commits thier code changes to Repository, it will faces the  conflicts issues and how to resolved those conflicts issues in real time projects 


![image](https://github.com/user-attachments/assets/8bc72ca5-a9fd-407b-9d37-48824e5375b7)

Avoide conflicts:: Before pushing the code changes to github repository, make sure, you should be run the command -->git pull

>git pull --->git pull command is use, copies changes from a remote repository directly into your working directory (local directory) and merged code changes from remote repository to local repository 
>git fetch ---->The git fetch command only fetch the changes into your local Git repo and it will not merged anything. just fetch the details

Please create A,B,C directories in your local machine and clone the project code separately 

![image](https://github.com/user-attachments/assets/7e786310-5092-4975-9eb9-7b18801353d8)

Editor steps for Resolved the conflicts::

editor::

1.press i from your keyboard, INCERT
2.press the esc from your keyboard at top left corner 
3.shift+: 
4.wq


Developer-A Activity::

 git checkout feature/2025.02.27
error: pathspec 'feature/2025.02.27' did not match any file(s) known to git

HP@DESKTOP-E518Q66 MINGW64 ~/Desktop/A/spring-petclinic (main)
$ git pull
From github.com:parasa7358/spring-petclinic
 * [new branch]      feature/2025.02.27 -> origin/feature/2025.02.27
Already up to date.

HP@DESKTOP-E518Q66 MINGW64 ~/Desktop/A/spring-petclinic (main)
$ git checkout feature/2025.02.27
branch 'feature/2025.02.27' set up to track 'origin/feature/2025.02.27'.
Switched to a new branch 'feature/2025.02.27'

HP@DESKTOP-E518Q66 MINGW64 ~/Desktop/A/spring-petclinic (feature/2025.02.27)
$ git status
On branch feature/2025.02.27
Your branch is up to date with 'origin/feature/2025.02.27'.

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        Jenkinsfile

nothing added to commit but untracked files present (use "git add" to track)

HP@DESKTOP-E518Q66 MINGW64 ~/Desktop/A/spring-petclinic (feature/2025.02.27)
$ git add --all
warning: in the working copy of 'Jenkinsfile', LF will be replaced by CRLF the next time Git touches it

HP@DESKTOP-E518Q66 MINGW64 ~/Desktop/A/spring-petclinic (feature/2025.02.27)
$ git status
On branch feature/2025.02.27
Your branch is up to date with 'origin/feature/2025.02.27'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   Jenkinsfile


HP@DESKTOP-E518Q66 MINGW64 ~/Desktop/A/spring-petclinic (feature/2025.02.27)
$ git commit -m "Added jenkins file for Feb Release"
[feature/2025.02.27 9ad4ee0] Added jenkins file for Feb Release
 1 file changed, 22 insertions(+)
 create mode 100644 Jenkinsfile

HP@DESKTOP-E518Q66 MINGW64 ~/Desktop/A/spring-petclinic (feature/2025.02.27)
$ git push
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 4 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 483 bytes | 241.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To github.com:parasa7358/spring-petclinic.git
   e4b9aa2..9ad4ee0  feature/2025.02.27 -> feature/2025.02.27

HP@DESKTOP-E518Q66 MINGW64 ~/Desktop/A/spring-petclinic (feature/2025.02.27)
$

Developer-B Activity::

HP@DESKTOP-E518Q66 MINGW64 ~/Desktop/B/spring-petclinic (feature/2025.02.27)
$ git pull
Already up to date.

HP@DESKTOP-E518Q66 MINGW64 ~/Desktop/B/spring-petclinic (feature/2025.02.27)
$ git status
On branch feature/2025.02.27
Your branch is ahead of 'origin/feature/2025.02.27' by 2 commits.
  (use "git push" to publish your local commits)

nothing to commit, working tree clean

HP@DESKTOP-E518Q66 MINGW64 ~/Desktop/B/spring-petclinic (feature/2025.02.27)
$ git push
Enumerating objects: 9, done.
Counting objects: 100% (8/8), done.
Delta compression using up to 4 threads
Compressing objects: 100% (5/5), done.
Writing objects: 100% (5/5), 586 bytes | 293.00 KiB/s, done.
Total 5 (delta 3), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (3/3), completed with 2 local objects.
To github.com:parasa7358/spring-petclinic.git
   9ad4ee0..ed57c5e  feature/2025.02.27 -> feature/2025.02.27


Developer-C Activity::

HP@DESKTOP-E518Q66 MINGW64 ~/Desktop/C/spring-petclinic (feature/2025.02.27)
$ git status
On branch feature/2025.02.27
Your branch is ahead of 'origin/feature/2025.02.27' by 2 commits.
  (use "git push" to publish your local commits)

nothing to commit, working tree clean

HP@DESKTOP-E518Q66 MINGW64 ~/Desktop/C/spring-petclinic (feature/2025.02.27)
$ git push
Enumerating objects: 33, done.
Counting objects: 100% (24/24), done.
Delta compression using up to 4 threads
Compressing objects: 100% (9/9), done.
Writing objects: 100% (13/13), 1.14 KiB | 233.00 KiB/s, done.
Total 13 (delta 5), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (5/5), completed with 5 local objects.
To github.com:parasa7358/spring-petclinic.git
   ed57c5e..80681f1  feature


   Please be practice above 3 users activity in real time bases 


   19/03/2025::
   ================

   Jenkins Introductiion::

Jenkins is a free and open source automation server/tool. It helps automate the parts of software development related to building, testing, and deploying, facilitating continuous integration and continuous delivery.


Jenkins is a Orchestration tool

Jenkins is a CI/CD tool

Jenkins is a Schedular

Jenkins is a crone job schedular 

LLE/Pre-prod/UAT  ---automatically ---contunutineus deployemt
LLE/Pre-prod/UAT  ---Manually ---contunutineus delivery

Continuous Integration(CI)::the practice of automating the integration of code changes from multiple Developers into a single software project. It's a primary DevOps best practice, allowing developers to frequently merge code changes into a central repository,after which automated builds and tests are run automatically.

developers frequently commit to a shared repository using a version control system such as Git,A continuous integration automatically builds and runs unit tests on the new code changes to immediately using jenkins Orchestration.

Continuous Delivery (CD)::Continuous Delivery is a software development practice in which code changes are automatically built, tested, and prepared for release to production in a consistent and reliable manner. The key distinction of continuous delivery is that the process of deploying the code to production is done manually by a human decision-maker.

![image](https://github.com/user-attachments/assets/a3be0abd-12cf-49a5-b1e5-e56d54ac1080)



Continuous Deployment(CD) :: Continuous Deployment is an extension of continuous delivery. With continuous deployment, every change that passes through the automated tests and builds is automatically deployed to production without any human intervention. The deployment process is fully automated.

![image](https://github.com/user-attachments/assets/03cd5335-7656-4b39-80c3-e7ba7a0234a9)


Roles And Responsibilities::

1)The devops engineer was responsibility to release the product to the market as soon as possible
2)release the product speed to the market
3)Devops engineer was give continues feedback to the developers
4) Devops engineer responsibility start from git and end with production

A) when your activity start from git and end with production environment(production servers)Continues deployment
when your activity start from git to LLE(lower level environment,testing environment,pre-prod…et) environment(pre-production servers)Continues delivery non-production environment

Download JDK 17 ::

https://www.oracle.com/java/technologies/javase/jdk17-archive-downloads.html

Windows x64 Installer	153.92 MB	
https://download.oracle.com/java/17/archive/jdk-17.0.12_windows-x64_bin.exe (sha256 )

OR

Windows x64 Compressed Archive	172.87 MB	
https://download.oracle.com/java/17/archive/jdk-17.0.12_windows-x64_bin.zip (sha256 )

Download Maven::

https://maven.apache.org/download.cgi

Source zip archive	apache-maven-3.9.9-src.zip


====================

JDK 17 Environment setup::

Go to Search box & type Edit the system environemnt variables and click


![image](https://github.com/user-attachments/assets/66f98991-dc2a-4bd5-a093-67b88997e851)

It will navigate to System properties 

![image](https://github.com/user-attachments/assets/2b14fcee-1b5d-4f00-ac6e-b0ee83932384)

Open Environemnt Variables

![image](https://github.com/user-attachments/assets/5c2b431e-caa8-4a64-86ed-71f379f57c7b)

![image](https://github.com/user-attachments/assets/b3e2a06a-27ec-46a2-b1ac-8579c5be9321)


User variables::
JAVA_HOME=C:\Users\HP\Downloads\jdk-17.0.12_windows-x64_bin\jdk-17.0.12
 
![image](https://github.com/user-attachments/assets/8ad54751-f25d-4a0c-9339-1e90caa81094)

System variable::

%JAVA_HOME%\bin
%MAVEN_HOME%\bin
 
![image](https://github.com/user-attachments/assets/00ace73f-2dad-442d-9404-7ade62e0ba70)

![image](https://github.com/user-attachments/assets/14ea70d3-2d24-4f7d-a752-c412d4fb704d)


Maven setup::
MAVEN_HOME=C:\Users\HP\Downloads\apache-maven-3.9.9-bin\apache-maven-3.9.9

![image](https://github.com/user-attachments/assets/8a0f15af-32c5-4624-af43-59959b02e8c8)

Download link
https://maven.apache.org/download.cgi


Make sure we should setup the path at system variable 

JAVA_HOME & MAVEN_HOME

![image](https://github.com/user-attachments/assets/07ddf2ff-a7f1-470b-b07c-66316e8b1d7e)


now verify the java version & maven version:: go to git bash and verify. below are refreenced screenshots

> java -version

![image](https://github.com/user-attachments/assets/4319ddcf-5a6a-4844-aa74-5e7e3b88d601)

> mvn -v

![image](https://github.com/user-attachments/assets/ff578d8a-5c15-4686-8fdf-d9c94240ee73)


once above setup is ready then we will proceed to installe jenkins 

================

Installed jenkins in Windows::
https://www.jenkins.io/download/

Go to google search -->download jenkins war file for windows

![image](https://github.com/user-attachments/assets/d5550fe2-9af0-4376-af1b-6d4056beafe8)

Click --->WAR file link


![image](https://github.com/user-attachments/assets/3504e05f-6c0d-47a8-9b51-dffbcd0f790f)

Please follow the below link steps to installed jenkins in your windows machines

https://www.jenkins.io/doc/book/installing/war-file/

Steps::

https://www.jenkins.io/download/
1. First download the jenkins.war file and right click -->open gitbash here
2. run the command  -->java -jar jenkins.war --httpPort=9090

![image](https://github.com/user-attachments/assets/1cf75767-d6d7-4dfb-9a75-ccb9365b5ffb)

Browse to http://localhost:9090 and wait until the Unlock Jenkins page appears

Installed the default suggested plugins

![image](https://github.com/user-attachments/assets/081c44fc-a6a3-46fa-82e3-7b34c2dc2dd6)

click on continue 

Need to create jenkins user profile 

USER Name--->admin (any name you can provide)
PASSWORD  -->admin  (any password as your wish but make sure you should remembered the these credentials)

![image](https://github.com/user-attachments/assets/f0458a88-da81-4d32-9f87-42458fd214a1)






20/03/2025::
==============

Create sample Freestyle project::
============================

Click New Item

![image](https://github.com/user-attachments/assets/d9e7f707-aa00-4c74-b9ca-30489ded6f55)


Configuration stages::

1.General

2.Source code management (SCM)

3.Triggres

4.Environment

5.Build Steps

6.Post Build Actions


![image](https://github.com/user-attachments/assets/b7b5caf1-3d81-4de0-aebc-c2dc5080f916)


General Section provide the Project/job description 


At SCM stage level select the Git and provide the github details

![image](https://github.com/user-attachments/assets/827c5b34-8a6e-41ad-b6e1-4899348730d6)

Branches to build

![image](https://github.com/user-attachments/assets/51cf678c-afbd-40bc-bbb5-fae55e4c5537)

Poll SCM:: i want triggered the jenkins job build every minute

![image](https://github.com/user-attachments/assets/7bab6e2d-7868-460e-bd42-b2697195f3fe)

Build steps::select the Invoke top-level Maven targets
Goals section
>mvn clean install

Maven goals::

>mvn test

>mvn install


>mvn clean install


>mvn clean


>mvn package

![image](https://github.com/user-attachments/assets/53d49170-9dfe-4cad-abc0-50bf268e96c7)


Job will be created

Click Build Now


Buils is Inprogress

![image](https://github.com/user-attachments/assets/c6e399ce-ac52-47de-94a3-b4d6d156dce5)


Automatically Discard Old Builds:::
==============================
To automate the process of discarding old builds, you can configure the job’s settings to automatically delete old builds based on criteria such as the number of builds to keep or the age of the builds.

Follow these steps:

Open the Jenkins job (project).
Click on Configure (on the left-hand side).
Scroll down to the Build Discarder section (usually under the Build Triggers section).
Check Discard old builds.
Specify the following options:
Max # of builds to keep: Set the maximum number of builds to keep.
Max days to keep builds: Set the maximum age for builds to keep.
Save the configuration by clicking Save.

Poll SCM ::Jenkins server ask git if there is any changes in git server or not, if changes there Jenkins server build/package the changes , every change build happened like 5 mints ,means every 5 minutes verify the Jenkins server to git if there is any changes 

![image](https://github.com/user-attachments/assets/6f436ad6-e92a-40e3-831a-23219c288217)

POLL SCM ----* * * * * --every minute when every commit 

Create one sample POLL SCM jenkins job::
===========================================
Go to jenkins Dashboard
click New Item

![image](https://github.com/user-attachments/assets/1c62657f-935b-4eed-b032-08842fb09a57)

Description

![image](https://github.com/user-attachments/assets/3a54ba69-b2aa-4443-ad9b-d18ab5fbde02)


Provide the Git URL

![image](https://github.com/user-attachments/assets/1fb7b83f-3bba-411b-aad9-a725f25d3e1c)


Branch buiild

![image](https://github.com/user-attachments/assets/71aec8f1-4783-4e97-97cb-232dd18811ae)

POLL SCM:: * * * * *

every minute build was trigger when new commits happend in github repository

![image](https://github.com/user-attachments/assets/d6ab7a34-156a-4430-9d40-31e362ad23b1)


Build Steps::

![image](https://github.com/user-attachments/assets/4aae78af-d217-41de-a1e6-16bfe2e34472)


Execute the Jobs in Parallel::
==============================


1.By Default execute the Jenkins build jobs are sequence way,one by one 

2.Don’t do 2 projects build parallel  this is real time scenario but we can do parallel builds as well one job

Jenkins build parallel setup
Go job ---> configure ----> Generall ---> Execute concurrent builds if necessary



![image](https://github.com/user-attachments/assets/909edd87-548d-4ded-a862-29cf850fac05)


Here 5 builds execute parallel ,I kept executor is 5 this is same machine 

![image](https://github.com/user-attachments/assets/a840a224-5cbb-43cc-92c1-d135db4ce00f)


Build Periodically:::	H/15 * * * *   ----this build happened every 5 minutes without commits ,if changes are commit or not but every 5 mints build happened in Jenkins 


