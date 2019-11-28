# exercise
Do anything on this for exercise

Just to test git commands.

# commands may be used

    git add 
    git commit -m "message"
    git status
    
    git push
    git pull
    git pull --rebase
    git fetch



# normal work process

1. get newest files
exec git pull to get newest change

    git pull --rebase

2. open editor( such as vscode) edit files

3. add changes

for each changed files exec.

    git add file

4. commit changes
every time finished a semall work, such like fix a bug, you should exec
    message should be the message what you did.

    git commit -m "message"

5. push local changes to remote
every time before pushing changes,you should get newest changes first

    git pull --rebase
    git push


# note:

every time you can exec 

    git status

to check what happened

