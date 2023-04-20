A brief repo to store the git commands and their respective functionalities
#1 How to install git in your computer.

 

STEPS:
1. DOWNLOAD GIT FROM GIT WEBSITE.
2. FOLLOW THE PROCESS
	2.A SELECT GIT FOR COMMAND PROMPT
3. SELECT ALL THE DEFAULT CSELECTIONS. 

AFTER SUCCESSFUL COMPLETION OF THE INSTALLATION
1. OPEN GITHUB.COM
2. CREATE A REPOSITORY THERE
3. CREATE A FOLDER 'GIT' INSIDE C DRIVE
4. OPEN GIT BASH
5. THOUGH GIT BASH NAVIGATE TO GIT C:/GIT ( CD GIT )    **LS COMMAND TO SEE THE LIST OF DIRECTORIES INSIDE A FOLDER
6. NOW CONFIGURE YOUR GIT ACCOUNT
	6.A. GIT GONFIG --GLOBAL USER.NAME "GITHUB USER NAME"
	6.B. GIT CONGIF --GLOBAL USER.EMAIL "EMAILID"
7. NOW DOWNLOAD THE GITHUB REPOSITORY 
	7.A. GIT CLONE "GITHUB REPOSITORY URL" (A FOLDER GETS CREATED ie THE GIT HUB REPOSITORY)
	7.B. NAVIGATE INTO THE FOLDER
8. CREATE A TEXT FILE FOR EXAMPLE AND SAVE IT
9. TO UPLOAD THE FILE/FILES USE COMMAND ( GIT ADD 'file name'/ GIT ADD * |THIS COMMAND ADDS ALL THE FILE FOR UPLOAD|)
10. TO FINALIZE THE ADDINGS USE COMMAND GIT COMMIT -M "ANY MESSAGE REGARDING THE FILE" FILE_NAME / *
11. TO UPLOAD IT TO GITHUB USE GIT PUSH -U ORIGIN MASTER ( THIS UPLOADS THE FILE FOR THAT SPECFIC USER AND TO MASTER BRANCH)


#2 Basic command in GIT:

git init 					initialize  local git repository
git add <file/*>				add file to index
git status 					working status of a working tree
git commit					commit changes				
git push 					push file into the remote repository
git pull					pulls latest files from repository
git clone 					download the complete repository into the local system
touch .gitignore				all the files listed in this folder will be ignored for upload		
git branch 'branch_name'			adds branch to the repository
git checkout 'branch_name'  			changes to the new working branch

