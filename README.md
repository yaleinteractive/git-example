# Readme!

Networks & Transactions lab from Feb 25, 2016 on how to use git

## To start Meteor

    meteor --port $IP:$PORT

## To create a new project from scratch, with a new repository

1. Create a public repository in GitHub. Don't initialize it with anything.

2. Create a new project in Cloud9. Give it the same name. Be sure you're logged 
into Cloud9 with your GitHub credentials.

3. In a Cloud9 terminal:

    git init
    git remote add origin git@github.com:yaleinteractive/git-example.git
    git status
    git add -A
    git status
    git commit -m "Initial commit"
    git push
      
Change the remote URL based on what it says in your GitHub repo.

`git init`: Initializes the local repository

`git remote add origin`: Connect your local repository to a remote repository called 'origin'.
Copy the remote URL from your GitHub repository. Use the SSH version of the remote URL for more convenience.

`git status`: See what the changed files are.

`git add -A`: Add all changed files to this commit.

`git commit -m "Your commit message here"`: Commit the changed files to your local repository

`git push`: Push commits from your local repository, to the remote repository (GitHub)

Repeat the last four commands whenever you add a feature or fix a bug. The commit message
describes the feature or bug fix.



