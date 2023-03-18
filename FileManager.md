# FileManager
### Basic function

#### list

`list` prints out all the files in the directory it is provided.
You can enter `.` to have it print the current directory.
This prints out all files in the directory, even those considered hidden files.

Sample output:
```agsl
bin
foo
lib
bar
```

#### info

`info` prints out information about the given directory.
It includes name, paths, size, and created/last modified dates.

Sample output:
```agsl

Name: test
Absolute path: /Users/Name/Documents/dev/JavaFileManager/test
Relative path: test
Size: 192
Created: 17. March 2023. 15:34:35
Last Modified: 17. March 2023. 15:34:35
```

#### mkdir

`mkdir` makes a new directory at the specified location.


Sample output:
```agsl
Created a folder called salad
```

#### rename

`rename` changes the name of a specified file or folder.

Sample output:
```
Rename succesful.
```

#### copy

`copy` makes a copy of the specified file at the target location.

Sample output:
```agsl
Copying is successfuly finished.
```

#### move
`move` moves a specified file to a different location.

Sample output:
```agsl
Moving is successfuly finished.
```

#### delete
`delete` deletes a file or folder at any location.
there is no are you sure prompt so use this command with caution.

Sample output:
```agsl
Folder successfully deleted!
```

### quit

`quit` ends the file manager.

Sample output:
```agsl
You're exiting File Manager.
```