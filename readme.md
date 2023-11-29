
# Local Setup Only

From a local folder, within terminal, type git init
Then you can type git status

# Commands

git init
git status
git add -A          #after you have added files/made changes
git commit -m  "made change 1"
git status
create a remote repo thru github website
git remote add origin https://github.com/jomoglobal/github-test.git
git branch -M main
git push -u origin main


git config --global user.name “[firstname lastname]”	set a name that is identiﬁable for credit when review version history
git config --global user.email “[valid-email]”	set an email address that will be associated with each history marker
git config --global color.ui auto	set automatic command line coloring for Git for easy reviewing

Installation & GUIS
With platform speciﬁc installers for Git, GitHub also provides the ease of staying up-to-date with the latest releases of the command line tool while providing a graphical user interface for day-to-day interaction, review, and repository synchronization
Machine OS	Description
GitHub for Windows	https://windows.github.com
GitHub for Mac	https://mac.github.com
For Linux and Solaris platforms	the latest release is available on the oﬃcial Git web site
Git for All Platforms	http://git-scm.com

# Git Reference
https://git-scm.com/docs
# Git Documentation
https://git-scm.com/docs/git

Git is the free and open source distributed version control system that's responsible for everything GitHub related that happens locally on your computer.
Git aliases are stored in .bash_profile, here is a sample: https://github.com/joshnh/bash_profile/blob/master/.bash_profile

Starting / Getting / Creating Projects
Conﬁguring user information, initializing and cloning repositories
Command	Description
git init	Initialize an existing directory as a Git repository. Initialize a local Git repository
git clone ssh://git@github.com/[username]/[repository-name].git	Create a local copy of a remote repository. Retrieve an entire repository from a hosted location via URL.

https://git-scm.com/book/en/v2