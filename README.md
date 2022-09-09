# Using Gitlab on Windows
## Install
Install and Authorize via Browser: https://git-scm.com/download/win

## Clone Repository
After Gitlab is installed on your system, to clone a repostory to your local machine open 'Git Bash' via Windows-Key.
Now input the following commands to create a Git folder and clone the repostory into this folder
1) mkdir Git
2) cd Git
3) git clone https://github.com/niklaas-0rbit/Iron-Hideout-Competition.git
(this only works if you authorize the machine via webbrowser authentication, this should be prompted during the process)

## Gitlab Desktop for Syncing
https://desktop.github.com/

Once installed launch the application and open the already cloned repository via: 'File / Add local repository / Choose...' select the repository folder and click 'Add Repository'. Changes within the repository folders should be shown in the application and can be easily synced via the 'Commit' button. A brief summary text so people know what happened in a commit is recommended but not necessary.

After Commiting the changes need to be pushed with the appropriate button in the application, this actually saves your changes on the remote Gitlab server and makes those changes available to everyone.


# Iron-Hideout-Competition Repository Content
Various template files for the Path of Exile Iron Hideout Competition series.

possible converter MD <=> BBCode: http://feralhosting.github.io/b2m/index.html

Fork project and adjust some replacements: https://github.com/JonDum/BBCode-To-Markdown-Converter, particularly replace [hr] with --- to create horizontal lines
