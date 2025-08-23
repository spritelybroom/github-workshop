# Git and GitHub Basics

This repository provides an introduction to using Git and GitHub, covering essential concepts and commands to help you get started with version control and collaboration on software projects.

## What is Git?
**Git** is a distributed version control system used to track changes in files, allowing multiple people to collaborate on a project. Git enables you to revert back to previous versions, branch out for experimental features, and merge code seamlessly.

## What is GitHub?
**GitHub** is a platform that hosts Git repositories, enabling easier collaboration, issue tracking, code review, and version control. GitHub also provides social features, making it easier to collaborate, contribute, and share projects with a global community.

---

### Basic Git Commands

Below are some core Git commands for managing repositories, files, and branches:

- **Configure Git**  
  ```bash
  git config --global user.name "Your Name"
  git config --global user.email "you@example.com"
  ```
  Configures your name and email for all commits.

- **Initialize a Repository**  
  ```bash
  git init
  ```
  Initializes a new Git repository in the current directory.

- **Add Files**  
  ```bash
  git add <filename>
  git add .
  ```
  Stages a file (or all files) for commit.

- **Commit Changes**  
  ```bash
  git commit -m "Commit message"
  ```
  Records changes in the local repository.

- **Check Status**  
  ```bash
  git status
  ```
  Shows the status of your files in the repository.

- **View Commit History**  
  ```bash
  git log
  ```
  Displays a log of commits.

- **Create a Branch**  
  ```bash
  git branch <branch-name>
  ```
  Creates a new branch for development.

- **Switch Branch**  
  ```bash
  git checkout <branch-name>
  ```
  Switches to a specified branch.

---

### Basic GitHub Commands

Below are essential commands for collaborating using GitHub:

- **Push to GitHub**  
  ```bash
  git push origin <branch-name>
  ```
  Pushes changes to a branch on GitHub.

- **Pull Changes**  
  ```bash
  git pull origin <branch-name>
  ```
  Pulls the latest changes from a GitHub branch to your local repository.

- **Clone a Repository**  
  ```bash
  git clone <repository-url>
  ```
  Creates a local copy of a GitHub repository.

- **Fork a Repository**
  To fork, click on the "Fork" button on the repository page to create a copy in your GitHub account. You can then make changes and submit them back to the original repository.
