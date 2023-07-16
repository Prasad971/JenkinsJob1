# JenkinsJob1
MyjobGithub0: Pull commands from GitHub and execute the job


Note: In Jenkins choose to configure-->branches---> "main" instead of "master" (Github branch's default name has been changed from "master" to "main")
you have to set "main" as the branch name instead of "master"




Output
Started by user unknown or anonymous
Running as SYSTEM
Building in workspace /var/lib/jenkins/workspace/myjobgithub01
The recommended git tool is: NONE
No credentials specified
 > git rev-parse --resolve-git-dir /var/lib/jenkins/workspace/myjobgithub01/.git # timeout=10
Fetching changes from the remote Git repository
 > git config remote.origin.url https://github.com/Prasad971/JenkinsJob1.git # timeout=10
Fetching upstream changes from https://github.com/Prasad971/JenkinsJob1.git
 > git --version # timeout=10
 > git --version # 'git version 2.40.1'
 > git fetch --tags --force --progress -- https://github.com/Prasad971/JenkinsJob1.git +refs/heads/*:refs/remotes/origin/* # timeout=10
 > git rev-parse refs/remotes/origin/main^{commit} # timeout=10
Checking out Revision 79ccc5b741a5e1966bc852a00c44cd944d6980 (refs/remotes/origin/main)
 > git config core.sparsecheckout # timeout=10
 > git checkout -f 79ccc5b741a5f6e1966bc852a00c44cd944d6980 # timeout=10
Commit message: "Update README.md"
 > git rev-list --no-walk 79ccc5b741a5e1966bc852a00c44cd944d6980 # timeout=10
[myjobgithub01] $ /bin/sh -xe /tmp/jenkins14073551908071786212.sh
+ bash mytest.sh
hello this is Jenkins Job
      July 2023     
Su Mo Tu We Th Fr Sa
                   1 
 2  3  4  5  6  7  8 
 9 10 11 12 13 14 15 
16 17 18 19 20 21 22 
23 24 25 26 27 28 29 
30 31                
ec2-user
bye
Finished: SUCCESS
