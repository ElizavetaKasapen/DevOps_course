1. Examine the tree command. Master the technique of applying a template, for example, display all files that contain a character c, 
or files that contain a specific sequence of characters. List subdirectories of the root directory up to and including the second nesting level.  

![Screenshot](https://github.com/ElizavetaKasapen/DevOps_course/blob/Linux.Base/images/01.21.png)

tree -L 2

![Screenshot](https://github.com/ElizavetaKasapen/DevOps_course/blob/Linux.Base/images/01.22.png)

2.What command can be used to determine the type of file (for example, text or
binary)? Give an example.

![Screenshot](https://github.com/ElizavetaKasapen/DevOps_course/blob/Linux.Base/images/01.23.png)

3. Master the skills of navigating the file system using relative and absolute paths. 
How can you go back to your home directory from anywhere in the filesystem?

![Screenshot](https://github.com/ElizavetaKasapen/DevOps_course/blob/Linux.Base/images/01.24.png)
![Screenshot](https://github.com/ElizavetaKasapen/DevOps_course/blob/Linux.Base/images/01.25.png)
![Screenshot](https://github.com/ElizavetaKasapen/DevOps_course/blob/Linux.Base/images/01.26.png)

4. Become familiar with the various options for the ls command. Give examples of listing directories using different keys.

![Screenshot](https://github.com/ElizavetaKasapen/DevOps_course/blob/Linux.Base/images/01.27.png)

5.Perform the following sequence of operations:
- create a subdirectory in the home directory;
- in this subdirectory create a file containing information about directories
located in the root directory (using I/O redirection operations);

![Screenshot](https://github.com/ElizavetaKasapen/DevOps_course/blob/Linux.Base/images/01.28.png)

- view the created file;

![Screenshot](https://github.com/ElizavetaKasapen/DevOps_course/blob/Linux.Base/images/01.29.png)

- copy the created file to your home directory using relative and absolute
addressing.


![Screenshot](https://github.com/ElizavetaKasapen/DevOps_course/blob/Linux.Base/images/01.30.png)

- delete the previously created subdirectory with the file requesting removal;
- delete the file copied to the home directory.

![Screenshot](https://github.com/ElizavetaKasapen/DevOps_course/blob/Linux.Base/images/01.31.png)

6.Perform the following sequence of operations:
- create a subdirectory test in the home directory;
- copy the .bash_history file to this directory while changing its name to
labwork2;
- create a hard and soft link to the labwork2 file in the test subdirectory;

![Screenshot](https://github.com/ElizavetaKasapen/DevOps_course/blob/Linux.Base/images/01.32.png)

- rename the hard link file to hard_lnk_labwork2;
- rename the soft link file to symb_lnk_labwork2 file;

![Screenshot](https://github.com/ElizavetaKasapen/DevOps_course/blob/Linux.Base/images/01.33.png)

- then delete the labwork2. 

![Screenshot](https://github.com/ElizavetaKasapen/DevOps_course/blob/Linux.Base/images/01.34.png)

7.Using the locate utility, find all files that contain the squid and traceroute sequence.

![Screenshot](https://github.com/ElizavetaKasapen/DevOps_course/blob/Linux.Base/images/01.35.png)
![Screenshot](https://github.com/ElizavetaKasapen/DevOps_course/blob/Linux.Base/images/01.36.png)

8.Determine which partitions are mounted in the system, as well as the types of these partitions.

![Screenshot](https://github.com/ElizavetaKasapen/DevOps_course/blob/Linux.Base/images/01.37.png)

9.Count the number of lines containing a given sequence of characters in a given file.

![Screenshot](https://github.com/ElizavetaKasapen/DevOps_course/blob/Linux.Base/images/01.38.png)
![Screenshot](https://github.com/ElizavetaKasapen/DevOps_course/blob/Linux.Base/images/01.39.png)

10.Using the find command, find all files in the /etc directory containing the host character sequence.

![Screenshot](https://github.com/ElizavetaKasapen/DevOps_course/blob/Linux.Base/images/01.40.png)

11.List all objects in /etc that contain the ss character sequence. How can I duplicate a similar command using a bunch of grep?

 find /etc |grep ss
 
 ![Screenshot](https://github.com/ElizavetaKasapen/DevOps_course/blob/Linux.Base/images/01.41.png)

12.Organize a screen-by-screen print of the contents of the /etc directory. Hint: You must use stream redirection operations.

 ![Screenshot](https://github.com/ElizavetaKasapen/DevOps_course/blob/Linux.Base/images/01.42.png)
 
 13. You can view devices connected via the PCI bus using the lspci command

 ![Screenshot](https://github.com/ElizavetaKasapen/DevOps_course/blob/Linux.Base/images/01.43.png)
 
 View only equipment of a certain type
 
 ![Screenshot](https://github.com/ElizavetaKasapen/DevOps_course/blob/Linux.Base/images/01.44.png)
 
 15.* List the first 5 directory files that were recently accessed in the /etc directory.
 
 ![Screenshot](https://github.com/ElizavetaKasapen/DevOps_course/blob/Linux.Base/images/01.45.png)
 
