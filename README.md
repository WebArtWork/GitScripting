# What is git
Git is a free and open source distributed version control system designed to handle everything from small to very large projects with speed and efficiency. Basically this tool will solve the team work on an software project.

# Installation
[In this link](https://git-scm.com) you can download soft which will allow you to use git. Also it provide you an nice terminal which will let you use git in a better way.

# Commands in bin folder
Git has commands like `git pull origin master` which is not small commands to type from terminal, and for that reasson we made this repo, to use small commands. Description of each you can find below, or you can simply open each file and google for it's content. To make those commands work, you have to drop folder bin inside your user folder. If for some reason commands will not work, you will have to check your PATH variable, if it's linking your user folder.

## add
Adds all modified and new files in the current directory and all subdirectories to the staging area.

## commit
Makes something like checkpoints (saving all your working files). Commit can be local and on the server side. When you do push, you make your local commits to be written in the server.

## d
Switch you into dev branch.
## m
Switch you into master branch.

## fetch
Reset all files to working saved versions to the `dev` branch in server.
## f
Same with `fetch` command, just it require also branch as second parament. ex: `f master` which will fetch to branch master.

## fmfd
Fetching master branch from dev branch. Useful when you want to update your master branch from your dev branch.

## gap
This command is used to start up application for the PhoneGap app.
## run
This command is used to start up web server application by nodemon
## go
This command start a npm project (npm run start).
## publish
Publish will publish your npm repo into [npm public access. ](https://www.npmjs.com)

## gkey
This command is made to generate ssh key, is require email as second parameter and after it will ask few questions about the key you want to generate. Not providing any answers will generate the default key.
## key
This command will print in terminal your ssh key, if you have one.

## init
Initialize git repository with dev branch. Require as second parameter repo link. ex: `init git@github.com:WebArtWork/GitScripting.git`
## minit
Initialize git repository with master branch. Require as second parameter repo link. ex: `minit git@github.com:WebArtWork/GitScripting.git`

## pa
This command unite the update group of commands, require as second parameter the message for commit and updating the dev branch. ex: `pa 'Updating readme file'`<br>
At start it do `add`, then `commit Message_Provided`, then pull and after that push. If merge has appeared on pull command, push will not work.
## p
This is same command with pa, with the difference that we can pass on which branch we want to do the update. ex `p 'UPdating readme file' master`

## pull
This comand downloads the code from dev branch.
## pul
Same with `pull` command, with difference that we can specify the branch we want to download the code the code. ex `pul master`

## push
This command pushing all your local commits to the dev branch in the server.
## pus
This is same command with push with difference that we can specify the branch. ex `pus master`
