# PyTNote
## PyTNote (Python Terminal Notes) is a simple note manager for your terminal.

PyTNote (Python Terminal Notes) is a simple note manager for your terminal.
It allows you to quickly and easily create and manage notes without ever leaving your terminal workflow.

Creating a new note is as simple as typing "note Remember to update readme".

![alt tag](http://img4.imagetitan.com/img4/ciO0bPFjaHN23TR/14/14_screenshot2016-11-28at14.00.16.png)

Stay on top of your productivity with PyTNote!

This software has no license, so do whatever you want to with it. I'd prefer it if you didn't sell it though.

## Getting started
#### Arguments
You can use the following arguments when running the script:

no arguments          - lists all your notes and their times of creation
string of text        - creates a new note consisting of all arguments joined

-c [note no.]         - copies the contents of the note to the clipboard
-cl				            - clears all notes (asks you to confirm before doing so)
-d [note no.]	        - deletes note with corresponding id
-e [note no.]	        - edits note with corresponding id
-h				            - lists this help menu

#### Dependencies
PyTNote requires the following modules to work:
* appdirs (finds the correct place to store the notes depending on your OS)
* pyperclip (allows you to copy the note to clipboard)

If you have pip installed, both of the modules will automatically be installed upon running the script.

### macOS and Linux
Installing PyTNote on macOS and Linux distributions is as simple as running the following one-liner in your terminal:

`curl -o note https://raw.githubusercontent.com/simonklitjohnson/PyTNote/master/note.py && chmod +x note && mv note /usr/local/bin`

### Windows
I do not have a Windows machine, but I suppose you can pretty easily find a guide on how to make a python file executable in cmd on Windows somewhere.
