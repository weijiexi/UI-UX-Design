# Submit assignments
- 1.Create your own version of this repo using the fork button at the top right of the repository

        fork button - fork
- 2.Clone this repo by clicking the green Code button, then copy pasting the SSH URL: 

        Copy a SSH key url  
        cd 
        git clone git@github.com:YOUR-GITHUB-USERNAME/Git-for-Web-Development-Project.git

- 3.Create a branch: 

    git checkout -b 'FIRSTNAME-LASTNAME'

    code .

- 4.Edit in the mac.md or pc.md file.
- 5.Follow the steps for adding, committing, and pushing your work from your local computer to GitHub: 

        git add .
        Git status
        git commit -m 'WRITE A MESSAGE TO DESCRIBE YOUR CHANGES HERE' 
        git push -u origin FIRSTNAME-LASTNAME

- 6.Create a Pull Request to submit your work. 
- 7.Make sure that your repository's main branch is listed on the left side of the screen and your repository's FIRSTNAME-LASTNA

    ME branch is listed on the right side. This is telling GitHub that you want to compare the work you did in your FIRSTNAME-LASTNAME branch to the work in your main branch. Make sure that you don't click the "merge" button!

### git push -u origin BRANCH_NAME
### git push
### git fetch && git reset --hard
### git fetch && git reset --hard origin/main
### git fetch && git reset --hard ef67b8188bf1f8059880b47acbb7958f76408a24

The command git fetch && git reset --hard is a combination of two Git commands, git fetch and git reset --hard, used together to update your local repository to match the remote repository. Here’s a breakdown of what each part does:
### 1. git fetch
- Purpose:
git fetch downloads commits, files, and references from a remote repository into your local repository. However, it does not merge or modify your working directory or current branch.
It updates your remote-tracking branches (like origin/main), allowing you to see what changes have been made on the remote without altering your local working directory.
- Use Case:
Use git fetch when you want to see what has been updated in the remote repository before deciding to merge those changes into your local branch.
It’s a safe operation since it doesn’t modify your working files or branches.
### 2. git reset --hard
- Purpose:
git reset --hard is a powerful command that resets your current branch (e.g., main) to a specific state. It changes the HEAD to a specified commit (or to the current state of the branch if no commit is specified) and updates the index and working directory to match that state.
This means all changes in your working directory and index that haven’t been committed will be discarded, and your branch will look exactly like the specified commit or reference.
- Use Case:
Use git reset --hard when you want to completely discard all local changes and uncommitted work, effectively reverting your working directory and branch to a specific state.
### 3. Combined Command: git fetch && git reset --hard
When combined, git fetch && git reset --hard is typically used to force your local branch to match the remote branch exactly. Here’s how it works:
- Step 1: git fetch:
Fetches the latest changes from the remote repository but doesn’t change your local working branch yet.
- Step 2: git reset --hard origin/<branch>:
Resets your current branch to match the fetched remote branch exactly. For example, git reset --hard origin/main would reset your current branch to match origin/main exactly.
This operation will discard any local changes that haven’t been committed, ensuring your branch is identical to the remote branch.
- Warning:
git reset --hard is a destructive command. It will remove any local changes that are not committed, so use it with caution. Always make sure you don’t have any work you want to keep before running this command.
- Example:
If you are on the main branch and you want to force it to match the remote origin/main, you would run:

git fetch && git reset --hard origin/main

This will:
Fetch the latest changes from the remote repository.
Discard all local changes and reset the main branch to match origin/main exactly.

### git switch xxxxxxxxx
### git fetch && git reset --hard origin/xxxxxx



