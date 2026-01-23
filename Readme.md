\# Learning git


Integration with Oracle possible GUI

PyCharm integrates when coding with python

Install Git Bash or equiv for GitHub for command line interface

Migration  - Folders and sub directories
GitHub’s web-based importer is the best choice for standard repositories because it brings over your commit history and branches automatically.
https://gemini.google.com/app/85e1b2ff44aadc06

  * Clone bitbucket repo e.g git clone https://kdp508@bitbucket.org/university-of-york/biu-degree-outcomes.git
  * Log in to GitHub and click the + icon in the top right, then select Import repository.
  * Name your new GitHub repository and set the privacy (Public or Private).
  * When prompted, enter your Bitbucket credentials (use the App Password here).
  * Click Begin import. GitHub will notify you via email once it’s finished.
  * Error importing this way
  * 
git clone git@bitbucket.org:university-of-york/biu-degree-outcomes.git
attach git to existing Bitbucket repos in directories. It will reproduce directory structure.

Need to initialise by adding Readme file to repository
And also to commit uploaded files. 
 
 echo "# SIA_TEST_DegreeOutcomesMigration" >> README.md
 git init
 git add README.md
 git commit -m "first commit"
 git branch -M main
 git remote add origin https://github.com/KP1York/SIA_TEST_DegreeOutcomesMigration.git
 git push -u origin main

Use **pull** request on published GitHub to merge - various gateway operation can be done here. 

Then Fetch origin and Pull into local - desktop


Collaborators across project groups - meeting to discuss changes every 3 weeks or more...

Using Pull/merge functionality as good practice within the team. 

todo - Forks to be done later - see Slides

Following slide deck from GitHub training - see Slack channel - Research Coding Club

Using cmd line interface - Git Bash. Open up from Windows Explorer as usual. Git Add *.*, Git Commit, Git Push.  


