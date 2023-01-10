Go-Hugo Website

2. Empathy as Code: Inline Help, Comment and Documentation 

Requirements

    Same requirements as the previous task:
        A Valid Go-Hugo website is provided
        There are no Git Submodules
        The theme ananke is installed
        No directory dist/ committed
        Makefile present

    Add comments in the Makefile to describe what each target is expected to do.
        These comments should be written on the same line as the targets
        Each comment should start with two characters #

## Prerequisites

Concepts

You should have a basic knowledge of the following concepts:

    Shell terminal basics, using command lines:
        Navigating in a Unix file-system
        Understanding how stdin/stdout redirection and piping
        Showing and searching the content of a text files
        Defining and using Environment Variables
        Adding command lines to your terminal using the apt-get package manager and/or with the PATH variable
        Writing and executing a shell script

    Git with the command line (and also a graphical interface)
        Retrieving or creating a repository
        Manipulating changes locally with Git’s 3 steps process (workspace, staging, history)
        Distributing changes history with remotes repositories

    Make/Makefile usage:
        Executing tasks through make targets
        Default target and PHONY target
        Makefile’s variables and macro syntax


## Lifecycle

lifecycle is generally staying the same. In this project, you will start to define this lifecycle via the following steps::

    build: Build: Generate the website from the markdown and configuration files in the directory dist/

    clean: Cleanup the content of the directory dist/

    post: Post: Create a new blog post whose filename and title come from the environment variables POST_TITLE and

    help: prints out the list of targets and their usage.
