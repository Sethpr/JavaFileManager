# File Manager

a Java file manager - Meant to be read and thought about.

You can fork this repo, and clone it down onto your computer.
The `main()` function is in `class FileManager`.
You should be able to run that function. 

## What is does

This is a very simple file management _shell_, it shows how to manipulate files using java standard library calls.
Available commands:
- `list` a folder
- `info` on on a file
- `mkdir` make a new folder 
- `rename` a file
- `copy`, `move`, `delete` files
- `quit` the file manager shell

There are three classes in this app: *FileManager*, *FileOperator* and *Console*.
Each class a different reason for being.
There is a simple file hierarchy for manual testing in the _test_ folder.
You can use the _test_ folder for doing simple file manipulations.


Why are the manipulation commands, the things that affect files and folders, in a different class than
the _file manager_ itself?

Why is all the input and output factored out into a separate class?

Why is Copy/Move in the same method?

What would you have to do to:

- add the idea of a _current folder_?
- how would you add a _change folder_ command?
- how would you add a command to display the contents of a file?
- how would you change _list_ to show the difference between files and folders?
- how could you clean up some of the code by using an _enum_ instead of strings for the commands?
- how would you use the _FileOperator_ class to test the _FileOperator_ class?

How would you test this code? 
How are the testing methods different for each class? 
Which class cannot be easily tested wit unit tests?

Does the code, as is, have any obvious bugs?
How would find out?

Why is the Console passed as a parameter to the two constructors?