# What is git
Git is a free and open source distributed version control system designed to handle everything from small to very large projects with speed and efficiency. Basically this tool will solve the team work on an software project.

# Installation
[In this link](https://git-scm.com) you can download soft which will allow you to use git. Also it provide you an nice terminal which will let you use git in a better way.

# Commands in bin folder
Git has commands like `git pull origin master` which is not small command to type from terminal and for that reasson we made this repo, to use small commands. Description of each you can find below, or you can simply open each file and google for it's content. To make those commands work, you have to drop folder bin inside your user folder. If for some reason commands will not work, you will have to check your PATH variable, if it's linking your user folder.

## add
Add all modified and new files in the current directory and all subdirectories to the staging area.

## build
Run command `npm run build` which in most frameworks making build of the project

## d
Switch you into dev branch.

## m
Switch you into master branch.

## s
Switch you into stage branch.

## f :branch
Reset all files to working saved versions to the :branch branch in server. Ex: `f stage` which will fetch to branch stage.

## go
This command start a npm project (npm run start).

## publish
Publish will publish your npm repo into [npm public access. ](https://www.npmjs.com)

## gkey
This command is made to generate ssh key, is require email as second parameter and after it will ask few questions about the key you want to generate. Not providing any answers will generate the default key.

## key
This command will print in terminal your ssh key, if you have one.

## i :repo :branch
Initialize git repository with selected branch. Require as second parameter repo link. ex: `i git@github.com:WebArtWork/GitScripting.git stage`

## pa
This command unite the update group of commands, require as second parameter the message for commit and updating the currne branch. ex: `pa 'Updating readme file'`<br>
At start it do `add Message_Provided` then pull and after that push. If merge has appeared on pull command, push will not work.

## pull
This comand downloads the code from current branch.

## pul
Same with `pull` command, with difference that we can specify the branch we want to download the code the code. ex `pul master`

## push
This command pushing all your local commits to the current branch in the server.