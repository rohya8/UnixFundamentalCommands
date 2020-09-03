The fundamental UNIX commands necessary for development
The command line is a tool for interacting with a computer using only text (also known as a text interface) rather than other methods like clicking and scrolling.
if you press the Tab key while entering a file name or folder name, the rest of the name gets auto-completed. 

touch file_name.extension => create new file  
eg. touch begin.txt

cat file_name => display the content of a file 
eg. cat begin.txt [If you specify a file that does not exist using the cat command, you will get an error, as the command is invalid.]

mkdir directory_name => create a new directory
eg. mkdir code

cd directory_name => to move to specified directory
eg. cd html [You'll get an error if you specify a directory that does not exist] 

pwd =>  to know the directory you are currently working in (print working directory)

The directory that you're currently in is called the current directory. 
In the file structure of a computer, there is a root directory at the very top. The root directory is represented by /

ls => to display the directories and files that are direct children of the current directory

.. => to move to the parent directory
eg. cd ..

If you execute cd without specifying a directory, you can move to what is called a home directory (represented by ~)


Working with Files and Directories
mv directories/file_to_move/ destination_directory => to move a directories/file
eg. mv begin.txt html

mv old_file_name new_file_name => rename a file
eg. mv begin.txt end.txt

cp file_to_copy new_file_name. => to copy files
eg. cp begin.txt copy.txt

cp -r directory_to_copy new_directory_name => copy a directory ( r - Recursive copy) 
eg. cp -r code html [If you try to copy a directory without adding the -r option, you will get an error ]

rm file_to_remove => to remove a file
eg. rm begin.txt

rm -r directory_to_remove => remove a directory
eg. rm -r code


