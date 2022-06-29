D​istributed Version Control Systems (DVCS) have become critical tools in software development, and key enablers for social and collaborative coding. 

* Software Engineers and DevOps professionals 
* Data Scientists and Data Engineers

* useful anywhere tracking changes/versions and/or collaboration between multiple users is required
* usecases in technical documentation, legal document management, and even collaborative development of recipes, books, etc

# Getting Started with Git and Git Hub

# Module 1: Overview of Version Control, git, github
## Overview of Version Control, Git, Github
### Git
* Free and open source software
* Distributed version control system
* Accessible anywhere in the world
* One of the most commom version control systems available
* Can also version control images, documents, etc.

Applications:
* Git + GitHub (web host services)
* Gitlab
* Bithucket
* beanstalk

SHORT Glossary of terms:
* SSH protocal - method to secure remote log in
* Repo - folder of your project
* Fork - a copy of repository
* Pull Request - the process you use the request that someone reviews and approves your changes before they become final
* Working directory - directory on your file system

Basic git commands:
* git init
* git add
* git status
* git commit
* git reset
* git log
* git branch
* git checkout
* git merge

## Introduction to Github
### Git
* Git is a distributed version control system
    * Track changes to contents
    *  Provides a central point for collaboration
* Git allows for centralized administration
    * Teams have controlled access scope
    * Main branch should ways correspond to deployable code

### GitHub
* Gibhub is online hosting service for git repos


## Github Repo

## GitHub Workflows with Branches and Commands
### Github Branches and Pull Requests
Push, pull and fetch data to share work
* Git push: local repo to remote repo
* Git fetch: remote repo to local repo
* Git Pull: get fetch and git merge

* Upstream or origin
    * Origin refer to your fork
    * Upstream refer to the original work

### Cloning and Forking Github projects
* Forking:
    * Takes a copy of a GitHub Repo and use it as the base for a new project
    * Submit changes back to the original repository
    * Independently make changes to a project
        * Submit a pull request to the original project owner    
        * Owner decides whether to accept your changes

### Managing GitHub Projects
* Developer communicate with other using:
    * git clone from the upstream to prime the local repo
    * git pull and git fetch origin to keep up to date with the upstream
    * git push to share repo
    * git format patch to prepare email submission
    * git send email to send your email submission without corruption by you MUA
    * git request pull to create a summary of changes for your upstream  to pull
* An integrator
    * receives changes made by others
    * Reviews and responds to pull requests
    * Publishes the result for others to use
* Investigators use the following commands:
    * git am to apply patches to emailed in from your contributors
    * git pull to merge from your trusted lieutenants
    * git format patch to prepare and send suggested alternative to contributors
    * git rever to undo bothched commits
    * git push to publish the bleeding edges
* A repo administrator sets up and maintains access to the repository by developers
    * git deamon to allow anonymous download from repo
    * git shell can be used as a restricted login shell for shared central repo users
    * git http backend provides a server side implementation of git over http allowing both fetch and push services
    * gitweb provides a web front end to git repo, which can be set up using the git-instaweb script

Module Summary
In this module, you learned that:

Branches are used to isolate changes to code. When the changes are complete, they can be merged back into the main branch.

Repositories can be cloned to make it possible to work locally, then sync changes back to the original.

Repositories can be forked to be used as a base for a new project, or so that the developer can work independently.

A​ Pull Request (PR) can be submitted to have your changes reviewed and merged.

Large projects include people working in different roles:

Developer – creates code

Integrator – manages changes made by developers

Repository Administrator – configures and maintains access to the repository
