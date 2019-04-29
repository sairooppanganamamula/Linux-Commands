# Linux – Basic Navigation and File Commands
## Print Working Directory – Prints the current working directory
•	*pwd*
## Short Listing – To list files in our directory
•	*ls*
## Long Listing 
•	*ls -l*
### long listing has the following:
•	First character indicates whether it is a normal file (-) or directory (d).
•	Next 9 characters are permissions for the file.
•	The next field is the number of blocks.
•	The next field is the owner of the file.
•	Then comes the group which the file belongs to.
•	Next is the modification time.
•	Finally we have the actual name of the file.
### List contents of a specific directoy
•	*ls /etc* 
## Absolute and Relative Paths
### Absolute Path
They specify a location in relation to the root directory. They can be easily identified as they begin with a forward slash (/).
•	*/home/john*
### Relative Path
They specify a location in relation to where we currently are in the system.
•	*ls Documents*
### More on Paths
•	*~(tilde)*: This is a shortcut for our home directory.
•	*.(dot)*: This is a reference to current directory.
•	*..(dotdot)*: This is a reference to parent directory.


## Change Directory
In order to move around in the system we use a command called cd which stands for change directory.
•	*cd [location]*
If the command is run with no arguments, it takes us to our home directory.
# More About Files
In Linux, everything is a file. For example, a text file is a file, a directory is a file, monitor is a file etc. Linux is also an extensionless system which ignores the extension and looks inside it to determine what type of file it is. It can sometimes be hard to know what type of a file a particular file is. We have a command called file which is used to find this out. 
•	*file [path]*
## Spaces in Names
Spaces in names is valid and a space on the command line is how we separate the items. 
•	*cd Holiday Photos* 
This will not work because it takes Holidays and Photos as separate items. If we want to move into it then we can do so by using quotes as follows.
•	*cd ‘Holiday Photos’*
## Hidden Files and Directories
If a file or directory name begins with a .(full stop), then it is considered to be hidden. Hidden files can be listed using the following command.
•	*ls -a* 
