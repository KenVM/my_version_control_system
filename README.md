# my_version_control_system

In this project we are creating our own version control system using C. We'll perform this project in 7 stages:

**1. Initialize the .git directory**
git init initializes a git repository by creating a .git directory. This directory contains:

.git
├── config
├── HEAD
├── hooks
│   └── prepare-commit-msg.msample
├── objects
│   ├── info
│   └── pack
└── refs
    ├── heads
    └── tags

- config      is a text file that contains your git configuration for the current repo. It contains basic settings for your repo like the author, filemode, etc.
- HEAD        contains the current head of the repo. This is pointing to the refs/heads folder
- hooks       contain any scripts that can be run before/after git does anything, in our project, we will not be adding this folder
- objects     contain the git objects, that is, the data bout the files, commits, etc. 
- refs        these store references (pointers) to branches and tags


**2. Read a blob object**


**3. Create a blob object**


**4. Read a tree object**


**5. Write a tree object**


**6. Create a commit**


**7. Clone a repository**


