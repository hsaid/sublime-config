###What is this?
My Sublime Text 2 configuration. It primarily contains [C++ and Python snippets](https://github.com/ryanwersal/sublime-config/tree/master/Packages/User/Snippets) of use to me in my day-to-day job. A few things of note for others would be the minimization of the tab size and [the Emacs style key bindings](https://github.com/ryanwersal/sublime-config/blob/master/Packages/User/Default%20%28Windows%29.sublime-keymap).

###Initial "Installation" Steps
1. Open the Command Palette and create a new Rope Project ("Rope: New Project")
2. Create the new project in the "python" directory of the working copy.
3. Open config.py in the newly crated .ropeproject directory to modify troublesome settings.
4. Update the ignored patterns with *.h, *.cpp, and *.sql just to be completely safe (those better not exist in there!)
5. Add the ztoolkit python path under "source_folders" prefs.
6. Add whatever-python-you're-currently-using folder to the "python_path" prefs.
7. Save and restart. Test. Did it work? Good!

###Goals/Todo
* ~~Get SublimeRope working performantly.~~
* Get SublimeClang working performantly.
