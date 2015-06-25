#GET GIT GOT

####What You Need
* Install [Git](http://git-scm.com/download)
* Create a [GitHub Account](https://github.com/)

##What is the Command Line?

Do you recall the days of DOS? When you turned on the desktop and the screen was not a high resolution lavender nebula but just black & the text was "ugh i've been slimed!" green? That was the terminal. It's still there, hiding behind your flip clock screensaver & your desktop widgets. 

["The command line is an interface that allows you to talk directly to your computer using words called commands."](http://www.freesoftwaremagazine.com/articles/command_line_intro) 

Commands are formatted without spaces. i.e. `command` Some commands can be modified. Modifications are made through options, commands that come after the command. Options are preceded by a dash. i.e. `command -option`

Option `--help` will spell out the details of the command you precede it with.

* Windows --> cmd.exe
* Mac --> Terminal

Quick Tip: A directory is just another name for a folder.

##Basic Commands for the Command Line

| Command 			|	Use 										|
|-------------------|-----------------------------------------------|
| `whatis`			|	a look up command i.e. `whatis cd`			|
| `cd`				|	change directory 							|
| `cd ..` 			| 	go back one directory 						|
| `cd - `			| 	go back to previous working directory 		|
| `ls`				|	list (files in directory) 					|
| Tab				|	completing arguments 						|
| CTRL-P/CMMD-P		|	recalls the previous command  (up arrow) 	|
| CTRL-R/CMMD-R 	|	search command history 						|
| CTRL-W/CMMD-W 	|	deletes the last word						|
| CTRL-U/CMMD-U 	|	deletes the whole line 						|
| CTRL-L/CMMD-L		|	clear screen 								|

For more info, check out [The Art of the Command Line](https://github.com/jlevy/the-art-of-command-line)

##What is Git?
Distributed Version Control System - DVCS makes it possible to track the changes various authors make to a file or set of files & smoothes out the process of combining their files while preserving old versions. Makes for easier collaboration & effective combining of changes. 

Just like with the Command Line, commands are formatted without spaces and can be followed by an option. However, all Git commands begin with the word `git`. 

Why learn Git? With applications like the GitHub software, there doesn't seem to be a use for using the terminal, except the software can be problematic. Learning the basics of git is honestly faster, just as easy & prepares you to better understand what you're doing. 

##What is GitHub?
Allows you to make changes to your version without affecting the shared project. Changes you make can be cleanly housed within your branch and then merged to the master branch when ready

Repository - a directory that is enabled to interact with Git & GitHub. Abbreviation: repo. 

Within each Repo there are three trees...
1. Working Directory - houses the files (what you see in your folder)
2. Index - the staging area
3. HEAD - the last commit

Commit - a snapshot of the file at a specific state. 
Branch - a seperate work area. A version of the repository that authors can change without affecting the master branch but can later merge with the master branch to make a big change all at once. 
Staged - files ready to be committed.
Unstaged - files that have been changed and not ready to commit
Untracked - files that git doesn't track, ususally new.
Deleted - a file you have removed from a folder but is waiting to be removed from the repo via git.

##Setting up your Terminal
Log into GitHub via your terminal

1. `git config --global user.name "John Doe"`
2. `git config --global user.email johndoe@example.com`
3. z

##Interacting with GitHub one-on-one

https://try.github.io/

###Commit & Push
`git status`
`git add filename.py`
`git status`
`git commit -m "adding filename"`
`git status`
`git push origin branchname`



git push -u origin branchname (-u will make git remember the parameters you entered so that next time you can just type in git push.)

###Branches

###Tracking Changes

##Interacting with GitHub as a team

###Cloning

###Pull

###Merge

###Conflicts

##Interacting with other people's GitHub

###Forking

##Resources

###Walkthroughs
* [Try Git](https://try.github.io/)
* [Git Immersion](http://gitimmersion.com/)
* [Roger Dudler's Git Guide](http://rogerdudler.github.io/git-guide/)
* [Think Like a Git](http://think-like-a-git.net/)
* [A Visual Git Guide](http://marklodato.github.io/visual-git-guide/index-en.html)
* [Git Tower](http://www.git-tower.com/learn/)
* [Git & The Terminal](https://18f.gsa.gov/2015/03/03/how-to-use-github-and-the-terminal-a-guide/)

###Self Directed
* [Pro Git](http://git-scm.com/book/en/v2)
* [First Aid Git](http://firstaidgit.io/#/)
* [Understanding GitHub](http://readwrite.com/2013/09/30/understanding-github-a-journey-for-beginners-part-1#awesm=~oGqRd1nOhtuidI%3F_escaped_fragment_=)
* [Git Youtube Videos](https://www.youtube.com/playlist?list=PLg7s6cbtAD165JTRsXh8ofwRw0PqUnkVH)
* [Git Dev Docs](http://devdocs.io/git/git)
* [Git Cheat Sheet](http://overapi.com/git/)
