# Instruction for Candidates

Welcome, we look forward to getting to know you. 

As part of our job application process, we are asking candidates to modify an existing Web site so as to showcase themselves and their job skills. 

Please do the following:

1. Change your name and bio in the _config.toml_ file
2. Edit the About page (found in the content folder) to provide a more extensive bio,
3. Edit the pages in the Challenges folder to provide your test answers, and
4. Add blog posts to provide information about additional research and anything else you think we should know.

When you are done, please commit and push the changes.

Feel free to improve (with customisations or new features) the Hugo theme provided. Part of the exercise is for you to show us your technical skills.

[//]: # (This is directly from Regis's readme in the candidate-cx site update 1 = need to update all: https://github.com/project-cx/cx-candidates/blob/master/README.md)

# Install

## You need Git, Go and Hugo
* Install [Git](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git)
* Install [Go](https://golang.org/dl)
* Install [Hugo](https://gohugo.io/getting-started/installing/)

## GitHub
* [Signup](https://github.com/) for a GitHub account
* Signin to GitHub
* Generate or locate your [SSH Key](https://help.github.com/articles/adding-a-new-ssh-key-to-your-github-account/) and add them to your GitHub profile settings:
	profile > settings > SSH and GPG Keys

## Cloning the project
Open your favorite terminal app, and go to the directory where your `cx-candidates` project is going to live.
You can easily do this on MacOS by simply navigating to the directory with the finder, copy (cmd+c) the directory, and paste it in the terminal after having type `cd `.

It should look something like this:
```
$ cd /Users/whoever/projects/pbx
```

Once you are in there,

Clone the repo:
```
$ git clone git@github.com:project-cx/cx-candidates.git
```

Go to the newly created repo directory

```
$ cd cx-candidates
```

Init and update the submodule

```
$ git submodule update --init --recursive
```

## Serving Hugo
From there, you've got all the files ready to go and you can start your hugo server to preview the changes you'll make. Live reload will update your change in the browser as soon as you hit that `save` key.

```
$ hugo serve
```

The terminal will tell you at which address your hugo server lives, but it usually is at `http://localhost:1313`

## Editors
Several editors for better markdown editing
* [Sublime](https://www.sublimetext.com/3) has package called [MarkdownExtended](https://github.com/jonschlinkert/sublime-markdown-extended) that improves Markdown + Front Matter syntax highlighting
* [Atom](https://atom.io/) has a built in GitHub Markdown syntax highlighting
* [Visual Studio](https://www.visualstudio.com)
* [WebStorm](https://www.jetbrains.com/webstorm/)

## Git Clients
Git, using command lines can be a little bit confusing at first, those UI clients will help wrap your head around it.
[//]: # (there is a new to git article in draft from HarrieBickleTW - what level of handholding is needed here, if from basic up then include link once live)
* [GitHub Desktop](https://desktop.github.com/)
* [Source Tree](https://www.sourcetreeapp.com/)
* [Git Kraken](https://www.gitkraken.com/)
