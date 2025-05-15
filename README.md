#﻿# Intro-to-git-lab
This repository is for the version control lab assignment

My name is Adam Spataro and i do not currently have a favourite programming language as i haven't had to program very much if at all, but i am interested in learning python. 

## Project Overview
This lab helped me learn Git and GitHub basics including cloning, branching, and collaboration.

## Key Concepts
- Importance of version control
- Features of Git: distributed system, branching, collaboration, cloning and others.

## How to Run This Project
1. Create a github user name and email:
git config --global user.name "Your Name"
git config --global user.email "your.email@example.com"
*Change inside "" with you Name and Email

2. Creating a repository:
Login to your github account, click on the + symbol or there will be a pulldown arrow next to it that says create a repository. Choose an owner, then add a name, add a README file and you're good to go.

3. Clone the repo:   
git clone https://github.com/your-username/intro-to-git-lab.git
*Where is says your-username change it with your actual git username

4. Creating a file and adding changes:
Use the touch command to add a file. Then use whatever editor you want to add your contents to the file. Use git add to stage file changes, git commit -m to add a description and finally git push to send the changes through to github.

5. Branching and Merging:
To achieve this for the lab we created a new branch using git checkout -b. On github a banner will appear saying "Feature-branch had recent pushes. Compare & pull request". Click "Compare & pull request".
*Make sure you go to the pull request page and click on the "Merge pull request" green button.

6. To Add a Reviewer:
There should be a category on the right-hand side showing Reviewers. Click on the gear icon and search for the person you want to add.

## Commands Used for this Lab

|Command         | Syntax                                       | Description                               |
|----------------|----------------------------------------------|-------------------------------------------|
| Clone          | `git clone <URL>`                            | Clones a repo to your local machine.      |
| Add            | `git add <filename>`                         | Stages file changes.                      |
| Commit         | `git commit -m "message"`                    | Commits staged changes.                   |
| Push           | `git push origin <branch>`                   | Pushes commits to remote.                 |
| Checkout       | `git checkout <branch>`                      | Switches branches.                        |
| Branch         | `git branch <branch-name>`                   | Creates a new branch.                     |
| Config         | `git config --global user.name "Your name"`  | Set and manage Git configuration settings |
| Init           | `git init`                                   | Initialize a Repository                   |
            


   
   

