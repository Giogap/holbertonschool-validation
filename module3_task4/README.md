Learning Objectives
This project aims at showing use cases where a DevOps mindset is bringing value to a software project by automating it, which decreases the amount of manual work and increases the development speed. It focuses on why automation is useful and helps speeding a development lifecycle.

After this project, you should be able to:

Understand the value of automating tedious tasks
Define a development lifecycle
Automate shell-like tasks with Make, and/or shell script
Be aware of tools dependencies and the value of reproducing environment
Build static HTML website from Markdown code using Go-Hugo
Prerequisites
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
Tooling
This project needs the following tools / services:

An HTML5-compliant web browser (Firefox, Chrome, Opera, Safari, Edge, etc.)
A free account on GitHub, referenced as <GitHub Handle>
A shell terminal with bash, zsh or ksh, including the standard Unix toolset (ls, cd, etc.) with:
GNU Make in version 3.81+
Git (command line) in version 2+
Go Hugo v0.80+
The student needs to be able to spawn up a clean Ubuntu 18.04 system. Therefore Docker is recommended with NO prior knowledge.
A text editor or IDE (Integrated Development Editor) of your convenience (Visual Code, Notepad++, Vim, Emacs, IntelliJ, etc.)
Story
Congratulations!

It’s your first day at “Awesome Inc.” as a software engineer. This company is currently experiencing fast growth and hired you to work on their web services.

Your predecessor left to travel the world, and the expectations are high on your ability to help "Awesome Inc.” to grow a culture of collaboration with a technical mindset, while managing their existing web services. That’s exactly what DevOps is about!



Learning Objectives
This project aims at practicing with Continuous Integration (CI) / Delivery (CD) / Deployment to understand the differences, the goals and the value.

After this project, you should be able to:

Implement Continuous Integration workflows using GitHub Actions
Tell if a given GitHub Action’s workflow is about Continuous Integration (CI), or Continuous Delivery (CD) or Continuous Deployment (skill of context analysis)
Understand the challenges of build reproductibility, through management of build dependencies using APT packages, NPM, Python3’s pip, and direct binary downloads.
Build collaboratively a Software Delivery Pipeline and produce released artifacts, including documenting the changes and the usage
Continuously deploy a static web site to Netlify
Prerequisites
Concepts
You should have a basic knowledge of the following concepts:

What is and how to use git tags
Basics of what is and how to use a GitHub “Release”
What is and how to create/use a ZIP archive
Know how to write a valid YAML file
Tooling
This project needs the following tools / services:

The command lines
yq
shellcheck
Story
Continuing your journey as a Software Engineer at Awesome Inc., you want to provide early visibility on your work to your colleagues to allow you to iterate on the most important issues or improvements for the company.

By defining a Software Delivery Pipeline with automated tasks, you’ll ensure that the collaboration between teams is improved, and that your team grows in maturity while providing an efficient process to ensure that you can deliver the application often.