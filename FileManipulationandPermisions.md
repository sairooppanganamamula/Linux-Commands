# File Manipulation
## Making a directory 
Creating a directory is pretty easy. It can be done using the following command. 
•	mkdir test 
test is the name of the directory we want to create. 
It also has two options which are -p which tells mkdir to create parent directories and -v which makes mkdir tell us what it is doing.
•	mkdir -p linuxtutorial/foo/bar
•	mkdir -pv linuxtutorial/foo/bar
## Removing a directory
To remove a directory we use rmdir.
•	rmdir linuxtutorial/foo/bar
## Creating a blank file 
We can create a blank file using the command touch.
•	touch filename 
If we touch a file and it does not exist then it will be automatically created for us.
## Copying Files
The content of one file is copied to another file using the command cp.
•	cp example1 file1
By default, cp copies only a file. We may copy directories using -r which stands for recursive.
## Removing Files
•	rm filename
This removes the file with specified name.
## Removing non-empty directories
•	rm -r directoryname




# File Permissions
Linux permissions dictate 3 things you may do with a file, read, write and execute. They are referred to in Linux by a single letter each.
•	 *read* - you may view the contents of the file.
•	 *write* - you may change the contents of the file.
•	 *execute* - you may execute or run the file if it is a program or script.
For every file, we define 3 sets of people for whom we may specify permissions.
•	*owner* – single person who owns the file.
•	*group* - every file belongs to a group.
•	*others* - everyone else who is not in the group.
## View Permissions
To view permissions for a file, we can use long listing.
•	*ls -l filename*
## Change Permissions
To change permissions, we use chmod. 
•	*chmod [permissions] [path]* 
Permission arguments are made of 3 arguments as follows.
•	Who are we changing the permissions to? (user, group, others or all)
•	Are we granting or revoking permissions? (+, -)
•	Which permission are we setting? (r, w or x)
Let us take a look at a few examples. 
*chmod u-x filename* - Removes execute access to the user.
*chmod g+rw filename* - Provides read and write access to the group.
*chmod o+rwx filename* - Provides read, write and execute access to others.
## Change directory permissions
*ls -ld testdir*  
