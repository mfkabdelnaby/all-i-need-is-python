# Command Line Tutorial, Part I — Navigating Directories

After installing Git, open Git Bash.

Useful Commands to use in Git Bash:

`pwd`: "print working directory"
it will print the current path on the computer; by default,
we’ll be starting in our computer’s Home directory
***
`ls`: "list"
To see the contents of a directory

**Note**: If you want to see all files in a directory (including hidden ones), you can add a flag  `ls -a` to list “all” of the contents present. Hidden files will appear with a `.` preceding their names.
***
`start`: If you want to open a file or a directory
type `start`, followed by a space, followed by the name of the file or directory you wish to open

**Note**: To be efficient, you can use the `TAB`  key on your keyboard to autocomplete file and directory names that reside in your current (or “working”) directory

To open current (working) directory:
`start .`
***
`cd`: “change directory” command

Ex: `cd Desktop`
The command above will move you from the `Home` directory into the Desktop directory.

`cd ..`: to move back into previous directory

**Note**: Typing `cd` without a directory will take you back to `Home` directory

# Command Line Tutorial, Part II — Creating and Removing Directories and Files

#### The `mkdir` Command

`mkdir`: make-dir; is used to make a new directory with the name that we provide

Ex: if you are in `Desktop` and you want to create `animals` that is in `photos` inside `Desktop`

 * use `cd` to move into `photos`, then type `mkdir animals`
 * simply run the command `mkdir photos/animals` from your current directory.

###### Creating multiple directories
Provide a list of directory names separated by spaces

**Note:** avoid using spaces in files names

#### The `touch` command
`touch`: to create files in your current directory

**Note:** including file types is crucial here. Ex: `touch MyFile.txt`

###### Creating a file in a directory other than the working directory
If you are in `Desktop` and you want to creat `cat.txt` in `animals` folder, you can use the following code:
`touch photos/animals/cat.txt` from your current directory

###### Creating multiple files
Provide a list of file names separated by spaces.
You can also provide list of full directories separated by a space. This can create multiple files in multiple locations

#### Delete Files and Directories
* `rm`: used to delete file
* `rmdir`: to delete empty Directories
* `rm -r`: to delete directories, including those with content

**Note:** if you want to be asked a confirmation message for your deletion add `-i` to your command
