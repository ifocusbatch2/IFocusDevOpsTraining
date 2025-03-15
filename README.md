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



