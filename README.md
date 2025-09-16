# LearningR_ForAnthroResearch

## How to use this repository:
1. Install git
2. Associate your git identity on your computer in Terminal (git config --global user.email [email address] and git config --global user.name [github username]
3. Make sure your IDE (coding environment, the software where you actually do the coding, e.g., RStudio) is connected to GitHub. If you are using RStudio, you will need to go to global options from the tools menu, select Git/SVN, create RSA key. Back in GitHub, create a personal access token for RStudio in the settings menu then down in developer settings. Generate a new token, name it RStudio in your note, set an expiration (optional), and set the scope (which should at least have repo editing privileges). This token is saying that RStudio can access your Github account and enact changes. Copy the token (and maybe store it somewhere secure) and then enter it into RStudio by using the following R code in the console:
   install.packages("gitcreds")
   library(gitcreds)
   gitcreds_set()
Then paste in your token as prompted in the console and hit enter.
If you're doing this in Positron (another IDE) you need to log into your github account in the bottom left hand corner, which usually it prompts you to do.
5. Once your IDE is integrated with git, you need to Fork the repository. Forking takes this repository at the state it is in when you fork it, and makes a version that belongs to you. You can rename it and add a description when you do this. Copy the default branch only
6. Clone the **forked** repo to your local files. This will take the remote repository and making it a directory (folder) on your own computer. In Github, go to the forked repo, then select <>Code (a green button). Copy the HTTPS link. If you're using RStudio you will open a NEW project and select from Git/version control and use the https link from github to create. Make sure you store it somewhere that makes sense in your computer and that you will remember (e.g., Documents, but not Desktop or Downloads).


## What's in this Repo?
Coming Soon!
How to use version control
Figuring out file paths
Data analysis templates
