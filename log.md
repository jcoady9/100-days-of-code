# 100 Days Of Code - Log

### Day 28 February 18, 2017

**Today's Progress**: Finished up the code for creating the database (except for adding date datatypes) and added code for populating the new database with data from the spreadsheet.

**Thoughts:** After doing a little code cleanup I should probably work on some functionality for inserting/updating already existing databases.

### Day 27 February 17, 2017

**Today's Progress**: Did a little code for creating the database.

**Thoughts:** Nasty headache tonight so there won't be much work done tonight mostly added a little code for selecting a datatype for each column.

### Day 26 February 16, 2017

**Today's Progress**: Started work on a python program for transfering data from an xlsx file to a sqlite database.

**Thoughts:** Using openpyxl so it should be a pretty straightforward.

### Day 25 February 15, 2017

**Today's Progress**: Experimented with the Wagtail CMS framework.

**Thoughts:** Tried out a CMS framework to see what it could be used for.

### Day 24: February 14, 2017

**Today's Progress**: Implemented a simple worksheet object to simplify working with excel spreadsheet data.

**Thoughts:** This'll be a quick and easy project, it will simplify the work I do with spreadsheet where the number and position of columns often changes. 

### Day 23: February 13, 2017

**Today's Progress**: Finished implementing the decoder ring in rust.

**Thoughts:** After spending three days on a Rust program, I've come to the conclusion that it is pretty serious about type safety, you just need to really know what's going on with your data types or you'll have an excruciatingly hard time figuring out how to get your code to compile.

### Day 22: February 12, 2017

**Today's Progress**: Tried to get a little further with the decoder ring in rust. 

**Thoughts:** The learning curve for Rust seems to be a little steep compared to other languages like Python or Java. I keep having trouble casting variables to other data types.

### Day 21: February 11, 2017

**Today's Progress**: Started working on te Decoder Ring challenge. 

**Thoughts:** Decided to try learning a little Rust and tried out my new skills on some old challenges from that programming competition I entered in college. Overall the language is a little cleaner than C/C++.

### Day 20: February 10, 2017

**Today's Progress**: Fixed the issue with converting filenames to unicode that contained a right single quote character.

**Thoughts:** Took awhile to research this issue, ended up using the 'mbcs' encoding for windows which handled the issue automatically.

**Link to work:** [django-simpleaudiofield](https://github.com/jcoady9/files-to-xlsx)

### Day 19: February 9, 2017

**Today's Progress**: Started a simple script to write filenames from a directory to an excel spreadsheet. 

**Thoughts:** Got a little sidetracked today and tried writing a simple script to write some file info to an excel spreadsheet. Having a little difficutly between encoding and decoding UTF-8 strings. Need to figure out how to work with it using the openpyxl module.

**Link to work:** [django-simpleaudiofield](https://github.com/jcoady9/files-to-xlsx)

### Day 18: February 8, 2017

**Today's Progress**: Created the views and templates to browse tracks and albums. 

**Thoughts:** This seemed pretty straight forward. It was pretty easy to create the templates and views, if I want to make the templates a little more interactive I might have to figure out how to use Javascript.

**Link to work:** [django-simpleaudiofield](https://github.com/jcoady9/project-jukebox)

### Day 17: February 7, 2017

**Today's Progress**: Started on Project-Jukebox, began implementing the model and admin classes. 

**Thoughts:** I had started this project awhile ago but decided to start from scratch for this challenge.

**Link to work:** [django-simpleaudiofield](https://github.com/jcoady9/project-jukebox)

### Day 16: February 6, 2017

**Today's Progress**: Fixed the issue, looks like the bug was caused when validating the file extension in the formfield.

**Thoughts:** Ok, now I think I have it working....

**Link to work:** [django-simpleaudiofield](https://github.com/jcoady9/project-jukebox)

### Day 15: February 5, 2017

**Today's Progress**: Found another bug, looks like I'm not doing something right when I try to validate the file extension is whitelisted.

**Thoughts:** Looks like the unit tests did not cover everything, I'm going to do a little reading up on Django's validation process.

**Link to work:** [django-simpleaudiofield](https://github.com/jcoady9/django-simpleaudiofield)

### Day 14: February 4, 2017

**Today's Progress**: Fixed the unit tests, looks like the assertion was intended to be used with form fields not model fields. Added a custom form field the the SimpleAudioField.

**Thoughts:** Needed to read the documentation a little more, looks like the assertion I was using was for form fields. I created a custom form field for audio today anyways so not a complete waste. I think I'll give this django app a try with a test project tomorrow and see what happens. 

**Link to work:** [django-simpleaudiofield](https://github.com/jcoady9/django-simpleaudiofield)

### Day 13: February 3, 2017

**Today's Progress**: Tried working on fixing the SimpleAudioField to pass the unit test. Still having an issue with an underfined keyword 'required' that gets passed through **kwargs.

**Thoughts:** Still haven't figured out how to fix the issue with the 'required' keyword, I'll have to take another look tomorrow.

**Link to work:** [django-simpleaudiofield](https://github.com/jcoady9/django-simpleaudiofield)

### Day 12: February 2, 2017

**Today's Progress**: Attempted to write unit tests today for the SimpleAudioField. 

**Thoughts:** Didn't get very far with writing unit tests, I still need to get a better idea on how Django works to understand how fields and the unit tests will work.

**Link to work:** [django-simpleaudiofield](https://github.com/jcoady9/django-simpleaudiofield)

### Day 11: February 1, 2017

**Today's Progress**: Restarted the audiofield project again this time to start it from scratch. Started the basic code for the audio field itself.

**Thoughts:** Decided it would be much easier to just write a new custom field from scratch and borrow code that would still fit my needs than gutting someone else's project. This'll give me a little more in-depth experience with Django and should help me out in the long run.

**Link to work:** [django-simpleaudiofield](https://github.com/jcoady9/django-simpleaudiofield)

### Day 10: January 31, 2017

**Today's Progress**: When making a branch for my changes and pushing it to github caused all the files I worked on to get corrupted. I had to redo all the work I did yesterday...

**Thoughts:** At least I was only a day into this project, could have been much worse.

**Link to work:** [django-audiofield](https://github.com/jcoady9/django-audiofield)

### Day 9: January 30, 2017

**Today's Progress**: Started work on a Simplified version of [areski's django-audiofield](https://github.com/areski/django-audiofield). Mostly just gutted some of the code that is used to convert audio files and did a little refactoring since some of the code was gutte.

**Thoughts:** I liked the idea of an audiofield for my Django projects but want something relatively simple. The django-audiofield project looked like the simplest so I decided I would remove the audio conversion functionality to have something more basic. Not sure where I'm going to take this but it'll be fun to see where it goes.

**Link to work:** [django-audiofield](https://github.com/jcoady9/django-audiofield)

### Day 8: January 29, 2017

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
