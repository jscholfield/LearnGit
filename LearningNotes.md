# Notes Scratch Pad for use studying Git

To keep it simple I'm using the following tools.

1. A terminal emulator, in this case Gnome terminal
  A. This is on Fedora and using the zsh shell
2. Atom text editor

I have a Projects directory in my home directory. In that directory I made a LearnGit directory. I used touch to create README.md and LearningNotes.md. I then used git init to initialize the directory in git.

I used git add . to add both files to git. Git status now shows both files staged but not yet committed.

I edited both files and saved them from Atom. Both showed staged as before but also showed as modified and not staged versions. I used git add . to stage both to be committed.

The tab for a modified file in Atom has a right side blue dot indicating that changes to the file are not yet saved. Ctrl/S saves the file and the blue dot is removed.
