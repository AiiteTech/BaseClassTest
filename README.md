# BaseClassTest
GIT HUB:
GitHub is at heart a Git repository hosting 
service, i.e. a cloud-based source code 
management or version control system.
How to down load GITHUB
https://desktop.github.com/
after download open any folder 
and do right click and check the git 
logo with the name git GUI and git 
bash option will be present in the right 
click menu.

To push a code from local to cloud first 
time:
Step1. Create an account in git hub 
cloud 
step2. Create a repository(project) by 
login to that account
Step3 if u want to add a code to that 
repository
we need to push a code into 
that repository 
from local to cloud:
1. Select the code in local 
we want to push it to repository and 
move inside that project in local
2. Right click on the 
project and select git bash
3. Use “git int” click on 
enter
4. Git status - to check 
anything is present
5. Start adding the file into 
the .git folder “git add filename”
5.1. To add all file in one 
short “git add .”
6. To delete the file added 
to .git folder “git rm --cached filename
”
7. Tell the git who u r with u 
r email and username and were to 
push the code in cloud.
7.1 “git config --
global user.name “username””
7.2 “git config --
global user.email “email id”
7.3 u have config the 
cloud repository url
“git remote add 
origin cloudurl”
8. Commit the code 
using “git commit -m “message””
9. Push the code 
after updating the username 
email and repository (user name 
and email are one time config)
10. Depends on the 
project we work the repository url 
will be change so use the 
command “git remote add origin 
cloudurl”
To clone a code from cloud to 
local and resent the code to cloud 
after making the changes:
1. Locate a place in local to 
clone the project from cloud.
2. Get in to the folder and 
right click select gitbash
3. To clone a project “git clone 
repository url”
4. Create a new branch (don’t 
work in master branch)
a) via cloud - create 
branch by click on 
masterdropdown
after creating 
cloud switch the local pointed 
master branch to newly created 
branch and start the changes as 
per story. “git checkout -b 
branch-name”
when the git bash 
says no branch found in the give 
name “git fetch” after that give 
checkout command.
b) now via local: to 
create branch “git checkout -b 
branch-name” - if we do this the 
branch name will reflect only after 
pushing the code to cloud.
5. Make the change in the 
code and add the code to local 
master folder(.git) and commit the 
code and push the code and 
check the same is reflected in 
cloud. Follow the below steps
3. Use “git int” click on 
enter
4. Git status - to check 
anything is present
5. Start adding the file into 
the .git folder “git add filename”
5.1. To add all file in one 
short “git add .”
6. To delete the file added 
to .git folder “git rm --cached filename
”
7. Tell the git who u r with u 
r email and username and were to 
push the code in cloud.
7.1 “git config --
global user.name “username””
7.2 “git config --
global user.email “email id”
7.3 u have config the 
cloud repository url
“git remote add 
origin cloudurl”
8. Commit the code 
using “git commit -m “message””
9. Push the code 
after updating the username 
email and repository (user name 
and email are one time config)
10. Depends on the 
project we work the repository url 
will be change so use the 
command “git remote add origin 
cloudurl”
When we find conflict what we 
need to do:
1. we need to pull the 
code from master.
2. Open the git bash from 
were u have pushed the code
“git pull origin 
master”
after removing the 
conflict change
follow the steps dd 
commit and push and check in 
cloud.
Scenario:
For a single story two person 
works in same branch:
master code will be downloaded 
for both..
master caode has 150 line
person1 - 150 will start the code 
from 151 - u have finished first 
and pushing the code to a branch 
(150+100)= 250
person2-150 will start the code 
from 151 - u have finshed second 
and pushing the code to same 
branch were person1 already 
pushed the code.(here occurs 
conflit)(50+150=200 internal 
sysytem)
but in cloud the branch has 250 
line code sinnce personone 
pushed his code
“git pull origin branchname”
