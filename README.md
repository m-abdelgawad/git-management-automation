# Git Management Automation

## Project Overview

A Bash script that scans all Git repositories in my local directory; then outputs a summary
of all my projects, and lists repositories that need to be committed, pushed, or pulled.

## Project Structure
I have 3 main directories in the same path:
* `Git-management-automation`: Which contains this project.
* `Public`: Which contains all Git repositories that I am hosting publicly on Github.
* `Private`: Which contains all Git repositories that I am hosting privately on Github.

<img src="imgs/1.PNG">

> Note that `public` and `private` repositories are separated as I often duplicate a private repository then host it publicly after removing all sensitive data.

## Main Features
* Scans all repositories directories in both the `Public` and `Private` directories.

* Run `Git status` in each repository.

* Generates a full summary report including:

    * Count of public repositories.
    * Count of private repositories.
    * Total count of all existing repositories.
    * Count of repositories that have changes need to be committed.
    * Count of repositories that have commits needs to be pushed.
    * Count of repositories that have pull requests need to be made.
    * Count of repositories that don't have any commits yet.
    * Count of repositories that don't have any remotes configured.
    * Count of clean repositories that need no actions.  
      
* Lists the absolute paths of repositories only in the following cases:
    * Have changes that need to be committed.
    * Have commits that need to be pushed.
    * Have pull requests that need to be made.
    * Don't have any commits yet.
    * Don't have any remotes configured.
    * Not Git repositories

## What Software Did I Need?

* Bash Scripting:  
    * Bash variables
    * Numeric variables in Bash
    * Arrays in Bash
    * If statements
    * FOR loops
    * Functions in Bash
* A text editor: VS Code
* Version Control with Git

## Screenshots

<img src="imgs/2.PNG">
<img src="imgs/check_clean_repos.png">
<img src="imgs/check_commit_repos.png">
<img src="imgs/check_pull_repos.png">
<img src="imgs/check_push_repos.png">
<img src="imgs/check_repos_no_commits_yet.png">
<img src="imgs/list_repos.png">
<img src="imgs/print_array.png">
<img src="imgs/print_summary.png">
<img src="imgs/repos_with_no_remote.png">

## About The Author

* Author: Mohamed Abdel-Gawad Ibrahim
* Contact: muhammadabdelgawwad@gmail.com
* Phone: +201069052620 | +201147821232
