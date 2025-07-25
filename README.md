## to use github repo on local device use the folllowing steps

### use terminal for performing git commands..

-  make a local folder

-  use ```git clone``` command by ```git clone "URL"```

-  then after cloning use ```git init``` to initialize the git repository

- then after git init command use command ``` git remote [Name] URL .git ``` to add a remote user for the repo, add .git after the URL link 

- after the above steps make files or paste files which you want to push in the github repository

- then after pasting or creating the file use ```git status``` command to check if the changes are made or not , if the changes are not made in the github repo it'll show the file name in red font , else the fike name will be highlighted in green font.

- if the file name is highlighted in red font , then use ```git commimt -m "Message"``` command to make a commit message to the new files..

- after using commit command , use ``` git push [Name] [branch name] ``` to make changes in the github repository..

# Making new branch

- want to make ne wbranch ? Here's Ho wyou can make new branch in an existing repo .

- use command ```git branch <branch_name>``` to make new branch .

- to use the new branch use ```git checkout <branch_name>``` ..

- to check what branches are available in your repo use ```git branch``` command to list all the branches.
