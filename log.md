# 100 Days Of Code - Log

### Day 8: January 30, 2017

**Today's Progress**: Finished v1.0 of the virtualenv-manager. Refactored the application into a module that is called by a script. Also wrote the setup.py script to make installation a little easier and updated the README file for the github repository. 

**Thoughts:** Got this project done in a little over a week, not too bad. Figuring out how to package this project so it could be easily installed was a little tricky, had to modify the structure of the project to get it to work. Right now it can only be installed via github download but I've been reading that it is a simple process to create a package for the PyPi repo; I think I'll try putting the project on there to give it a little more exposure.

**Link to work:** [virtualenv-manager](https://github.com/jcoady9/virtualenv-manager)

### Day 7: January 28, 2017

**Today's Progress**: Finally able to start a new terminal with an environment. I had to change the SQL queries to use the name of the environment instead of the ROWID, it did not occur to me that once a row is deleted from the table that the ROWIDs would realign to the remaining rows.  

**Thoughts:** Looks like all I need to do is do a little code clean up and write the README for the project's github page and this project will be done.

**Link to work:** [virtualenv-manager](https://github.com/jcoady9/virtualenv-manager)

### Day 6: January 27, 2017

**Today's Progress**: Added an event handler for when user double-clicks an item in the listbox. Double-clicking an item will open a new command-line terminal. Also fixed a minor bug for the STDIN when opening a child process. 

**Thoughts:** Figuring out how to open a new terminal with the subprocess module was easy, the difficulty was being able to run a command in that new terminal. I did figure it out, its mostly just added commands sent to the terminal, but I didn't make it start the virtual environment. I'll focus on getting that portion implemented tomorrow.

**Link to work:** [virtualenv-manager](https://github.com/jcoady9/virtualenv-manager)

### Day 5: January 26, 2017

**Today's Progress**: Did a little bit of clean up on the gui portion of the code. I combined the buttons and text entry widgets into their own frame for better organization. Also fixed a minor bug with the delete_environment method where it would delete the directory with the virtual environment but delete the wrong row in the database. It was a quick fix with a +1 to the position used with the method. 

**Thoughts:** Originally meant to get to the point where I could start a terminal with a virtualenv but ran out of time, instead I put a little work into the gui but should go back to focusing on functionality tomorrow. Hopefully it will be good enough to share later this weekend.... Come to think of it I should probably write some unit tests for this project as well.

**Link to work:** [virtualenv-manager](https://github.com/jcoady9/virtualenv-manager)

### Day 4: January 25, 2017

**Today's Progress**: Added functionality to the GUI. It can now create and delete the environments with the buttons and it can also list the environments in the listbox.  

**Thoughts:** Not a lot done today due to a migraine, I'll put a little more time into it tomorrow to make up for it.

**Link to work:** [virtualenv-manager](https://github.com/jcoady9/virtualenv-manager)

### Day 3: January 24, 2017

**Today's Progress**: Started implementing the GUI portion of the application using Tkinter. It's not going to look that pretty but it'll get the job done. 

**Thoughts:** Have the basic look of the application down but need to think of the best approach when creating a new virtual environment (i.e just using a text box and a button as opposed to a dialog window where I can enter the new info for the new environment).

**Link to work:** [virtualenv-manager](https://github.com/jcoady9/virtualenv-manager)

### Day 2: January 23, 2017

**Today's Progress**: Implemented a method to to delete that deletes the directory of the virtual environment and finished implementing a method for listing all the environments in the database. Also did a little refactoring for exception handling when starting subprocesses

**Thoughts:** Should be done with the actual functionality in the next day or two. I need to figure out how to create the GUI. I'll probably go with Tkinter since its already built in to the standard library.

**Link to work:** [virtualenv-manager](https://github.com/jcoady9/virtualenv-manager)

### Day 1: January 22, 2017

**Today's Progress**: Got started on a GUI application for managing all the virtual environments I've created recently. Decided to make a class for handling the actual managing of the virtual environments. Also implemented a method for creating new virtual environments.

**Thoughts:** Overall this is looking to be a simple project, had to refresh my memory a bit with using sqlite and python but otherwise no real issues.

**Link to work:** [virtualenv-manager](https://github.com/jcoady9/virtualenv-manager)
