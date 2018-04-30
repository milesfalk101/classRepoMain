Welcome to the class repository! Below I have attached account details and instructions for cloneing, committing and pushing to the shared account.

INSTRUCTIONS:
//I have included a brief guide to the command line below :)

1. Open the proper terminal (cmd/powershell on windows & Terminal on mac)
2. Go to the desktop from within the terminal
3. Create new directory to clone the repository into
4. Go into that new directory
5. Use thi bellow commands to clone the specified git repo

COMMAND LINE COMMANDS:
//Replace all instances of 'name' with the correct name you wish to use.
//Replace all instances of '/source/' & '/destination/' with appropriot destinations and sources
//This turorial is for unix based commandlines ie powershell and terminal. If possible refrain from using CMD but I can also explain commands for cmd if need be

1. Change directory: cd 'name'
2. Make new directory: mkdir 'name'
3. Create new filen: touch 'name'
4. View all files in a current directory: ls
5. View all files & hidden files in current directory: ls -la
6. Delete a file: rm 'name'
7. Delete a directory: rm -rf 'name'
8. Copy file from one directory to another: cp 'name' '/destination/'
9. Move a file from one directory to another: mv '/source/' '/destination/'

CLONE A GIT REPO:
//This is how you retrieve the specific git repo. Replace 'url' with the appropriet git url

git clone 'url'

ADD FILES TO BE PUSHED:
//You can specify each file by name or you . to specify all files

git add name

COMMIT A REPO:
//Leave a descriptive comment about the days work. DOUBLE QOUTES ARE IMPORTANT

git commit -m ""

PUSH A REPO:
//You may be prompted to specify the account username and password. You will be able to see the text you type when entering the username, however this is disallowed when typing passwords. 

git push origin master


//NOTES:

I have set up a repository for each class group:

Miles & Deepika:
https://github.com/milesfalk101/milesDeepika.git

Gabbrial&Shristi:
https://github.com/milesfalk101/gabbyShristi.git

Ms Blitz and Yennet:
https://github.com/milesfalk101/blitzYennet.git

