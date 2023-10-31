1.1 Listing files and directories (ls)
When you first login, your current working directory is your home directory. Your home 
directory has the same name as your user-name, for example, nye1, and it is where 
your personal files and subdirectories are saved.
To find out what is in your home directory type
ls
The ls command lists the contents of your current working directory.
However, it does not cause all the files in your home directory to be listed, but only 
those ones whose name does not begin with a dot (.) Files beginning with a dot (.) are
known as hidden files and usually contain important program configuration 
information. They are hidden because you should not change them unless you are 
familiar with Linux.
To list all files in your home directory including those whose names begin with a dot, 
type
ls -a
ls is an example of a command which can take options: -a is an example of an option. 
The options change the behaviour of the command. There are online manual pages 
that tell you what options a particular command can take, and how each option 
modifies the behaviour of the command. The online manual command is covered in 
tutorial 4.3.
ls -l
ls -lt
ls -lS
ls -lrS
ls -lrt
1.2 Making Directories (mkdir)
We will now make a subdirectory in your home directory to hold the files you will be 
creating and using in the course of this tutorial. To make a subdirectory called unixstuff 
in your current working directory type
mkdir unixstuff
University of Leicester | Tutorial One 3
To see the directory yo
