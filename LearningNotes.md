# Notes Scratch Pad for use studying Git

## Day 1

To keep it simple I'm using the following tools.

1. A terminal emulator, in this case Gnome terminal
  A. This is on Fedora and using the zsh shell
2. Atom text editor

I have a Projects directory in my home directory. In that directory I made a LearnGit directory. I used touch to create README.md and LearningNotes.md. I then used git init to initialize the directory in git.

I used git add . to add both files to git. Git status now shows both files staged but not yet committed.

I edited both files and saved them from Atom. Both showed staged as before but also showed as modified and not staged versions. I used git add . to stage both to be committed.

The tab for a modified file in Atom has a right side blue dot indicating that changes to the file are not yet saved. Ctrl/S saves the file and the blue dot is removed.

I used git commit . -m "initial commit" to commit the files and found I must put quotes around the message (following the -m ). I got an error if not including the message in the command when it tried to access Atom to write the message. I'll worry about that rabbit hole later. Git knows of Atom as my editor of choice. I decided to change my default editor in git to nano using the command git config --global core.editor "nano"

The video I am watching on this is Git & GitHub Crash Course For Beginners. Brad Traversy went into using .gitignore at this stage but that isn't of interest to me right now.

## Day 2

Tonight I listening to a different tutorial video called Git Tutorial for Beginners - Git and GitHub Fundamentals for Beginners. I'd like to get as far as pushing my project to GitHub tonight. 
