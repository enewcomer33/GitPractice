###Git Cheatsheet
**Name:** enewcomer33
**Date:** January 17, 2017

###one-time configuration
 git config --global user.name "[name]

 git config --global user.email "[email address]
 
 git config --list
 
 ###for each new git repository
 
 git init #initialize new git repository
 
 git remote add origin [URL of your remote repo] #create new repository in github (same name as local repository/directory)- by clicking "+" sign in top right corner. then do this command with URL of new remote repository/directory/folder 

 git push -u origin master # to indicate it's a new origin/master 
 
 git remote -v #tells you where the fetch/push info is going

 git status # status of the file (in github or no)

 git log # shows all the versions of your docs

###to add new versions to existing repository (directory/folder)

 git add . #  "." means everything - all documents
 
 OR

 git add "filename.extension"

 git reset # will un-add (un-stage, un-add) everything

 git commit -m "[clear message describing the changes you made]" # committing all the changes I staged (in git add step) and with a message helpful for future you 

 git push origin master # push it to the origin/master doc copy

 # then check it's in your github
