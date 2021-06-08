# AO3
Step 1: create an account on https://github.com/ and create a repository
Step 2: Download and install Git from https://git-scm.com/
Step 3: Launch Git, and type the following commands to register your GITHUB credentials from the account you just registered
        $ git config --global user.name "github username"
        $ git config --global user.email "github registered email address"
Step 4: using git, navigate to the desired directory on your local machine with the files you want to commit, and type the following commands:
      $ git init
      $ git add .
this will add all of the files in that directory to be ready to be uploaded to github
Step 5: stage your commit with the command:
      $ git commit -m 'message goes here'
Step 6: on GitHub, go to your repository and copy the https link under quick setup
Step 7: Type the following command, and insert the link you just copied within the quotation marks
      $ git remote add origin 'https url'
Step 8: type the fllowing command to push your staged files. you will then be asked for your github password
      $ git push -u origin master
Step 9: Your files will now be uploaded into your repository





================================================================================================================================================================================

Branch - Allow you to create multipl work in progress versions of a project, so you can backtrack to previous versions if features break in another branch
Clone - Allows you to copy a branch or repository to you local machine
Commit - Allows you to finalize changes and submit them to your github repository
Fetch - Retrieves the latest meta data from your repository, but doesn't retrieve any files
Git - A software used to track changes in any set of files
Github - a hosting service for version control for developers using git
Merge - allows you to combine your local copy of a branch with the version hosted on your version control provider
Merge Conflict - occurs when there are errors in regards to the local version of your files, and the files hosted on your version control provider
Push - allows you to stage files to be transfered from your local machine to your version control provider
Pull - allows you to request files from your version control provider and download them to you local machine
Remote - allows you to view your remote connections
Repository - where all of your projects files and revision history reside 
