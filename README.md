# **EXPLANATION OF VERSION CONTROL, GIT AND GITHUB, THERE DIFFERENCES AND SOME OTHER TERMS.**
___
**WHAT IS VERSION CONTROL?**
*A version control system, or VCS, tracks the history of changes as people and teams collaborate on projects together. As developers make changes to the project, any earlier version of the project can be recovered at any time.You can use the versions property within a file's frontmatter to define which products an article will appear for.*
___  
# **DIFFERENT BETWEEN GIT AND GITHUB**  
|Git                                                              |Github                                                                                                 |  
|-----------------------------------------------------------------|-------------------------------------------------------------------------------------------------------|  
| Git is a distributed version control system for tracking changes in source code during software development. It is designed for coordinating work among programmers, but it can be used to track changes in any set of files. Its goals include speed, data integrity, and support for distributed, non-linear workflows.|GitHub is a web-based Git repository hosting service, which offers all of the distributed revision control and source code management (SCM) functionality of Git as well as adding its own features.|GitHub is a web-based Git repository hosting and it is a version control system to manage source code history. Service, which offers all of the distributed revision control and source code management (SCM) functionality of Git as well as adding its own features.
|Git is a software and a command tool which can be installed locally on a system. It focuses on version control and code sharing and it is a version control system to manage source code history.|GITHUB It is a service and graphical interface. Github is hosted on web and is maintained by microsoft. it focused on centralized source code hosting. GitHub is a hosting service for Git repositories.  

#**THREE OTHER GITHUB ALTERNATIVES ARE:**  
* BITBUCKET:Bitbucket is a Git-based source code repository hosting service owned by Atlassian.
* SOURCEFORGE:SourceForge is a web service that offers software consumers a centralized online location to control and manage open-source software projects and research business software
* APACHE ALLURA:Apache Allura is an open-source forge software for managing source code repositories, bug reports, discussions, wiki pages, blogs and more for any number of individual projects.




                                                          






##**DIFFERENCES BETWEEN GIT FETCH AND GIT PULL**
**GIT FETCH**: Git fetch basically imports the commits to local branches so as to keep up-to-date that what everybody is working on.The git fetch command downloads commits, files, and refs from a remote repository into your local repo. Fetching is what you do when you want to see what everybody else has been working on.
                                                         *WHILE*
**GIT PULL**:  Git Pull basically brings the local branch up-to-date with the remote copy that will also updates the other remote tracking branches.  The name “pull request” comes from the idea that you're requesting the project to “pull” changes from your forK.
##**WHAT IS GIT REBASE?**:
  *Rebase is one of two Git utilities designed to integrate changes from one branch onto another. Rebasing is the process of combining or moving a sequence of commits on top of a new base commit.*
  
##**GIT REBASE COMMAND**
| GIT BASE <rebase>     |Performs the standard rebase     |
|-----------------------|---------------------------------|
| git rebase -- x       |This executes a command line shell script for each marked commit during playback.
| git status            |Checks the rebase status.
| git rebase -- continue|Continue with the changes that you made.
| git rebase --skip     |Skips the changes
| git rebase -- d       |The commit gets discarded from the final combined commit block during playback.
| git rebase -- p       |This leaves the commit alone, not modifying the content or message, and keeping it as an individual commit in branches' history.  
## **WHAT IS GIT CHERRY-PICK?**
*Git cherry-pick is a powerful command that enables arbitrary Git commits to be picked by reference and appended to the current working HEAD. Cherry picking is the act of picking a commit from a branch and applying it to another.*
## **THE GIT CHEERY-PICK COMMAND**
* git cherry-pick <commit-hash> : This command takes the specified commit (identified by its has) and applies it to the currently checked-out branch.
* git cherry-pick <satrt-commit>: is the commit you want to start with.
* git cherry-pick branh name: This applies all new changes on the speified branch that are not on the current branch.
* git cherry-pick -e <commit-has>: This open an editor to modify the commit message during the cherry-pick process.
