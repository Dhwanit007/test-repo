## To use github repo on local device use the folllowing steps

### Use terminal for performing git commands..

-  Make a local folder

-  Use ```git clone``` command by ```git clone "URL"```

-  Then after cloning use ```git init``` to initialize the git repository

-  Then after git init command use command ``` git remote [Name] URL .git ``` to add a remote user for the repo, add .git after the URL link 

- After the above steps make files or paste files which you want to push in the github repository

- Then after pasting or creating the file use ```git status``` command to check if the changes are made or not , if the changes are not made in the github repo it'll show the file name in red font , else the fike name will be highlighted in green font.

- If the file name is highlighted in red font , then use ```git commimt -m "Message"``` command to make a commit message to the new files..

- After using commit command , use ``` git push [Name] [branch name] ``` to make changes in the github repository..

# Making new branch

- Want to make new branch ? Here's How you can make new branch in an existing repo .

- Use command ```git branch <branch_name>``` to make new branch .

- To use the new branch use ```git checkout <branch_name>``` ..

- To check what branches are available in your repo use ```git branch``` command to list all the branches.
