### Introduction
The fundamental UNIX commands necessary for development
- The command line is a tool for interacting with a computer using only text (also known as a text interface) rather than other methods like clicking and scrolling.
- If you press the Tab key while entering a file name or folder name, the rest of the name gets auto-completed. 
- The directory that you're currently in, is called the current directory. 
- In the file structure of a computer, there is a root directory at the very top. The root directory is represented by /.

#### Commands

##### File and Directory Structures
+ touch file_name.extension => Create new file
    ```sh
    $ touch begin.txt
    ```
+ cat file_name => Displays the content of a file 
    ```sh
    $ cat begin.txt
    ```    
    ` [` If you specify a file that does not exist using the cat command, you will get an error, as the command is invalid `]`
+ mkdir directory_name => Creates a new directory
    ```sh
    $ mkdir code
    ```   
+ cd directory_name => Moves to specified directory
    ```sh
    $ cd html
    ```
     ` [` You'll get an error if you specify a directory that does not exist `] `    
     
+ pwd (print working directory) => To know the directory you are currently working in 
    ```sh
    $ pwd
    ```
    
+ ls (Listing files) => Displays the directories and files that are direct children of the current directory
    ```sh
    $ ls
    ```
+ `..` => Moves to the parent directory
    ```sh
    $ cd ..
    ```
    ` [ ` If you execute cd without specifying a directory, you can move to what is called a home directory (represented by ~) `] `
    
##### Working with Files and Directories
+ mv directories/file_to_move/ destination_directory => Moves to directories/file
    ```sh
    $ mv begin.txt html
    ```    
+ mv old_file_name new_file_name => Renames a file
    ```sh
    $ mv begin.txt end.txt
    ```
+ cp file_to_copy new_file_name. => To copy files
    ```sh
    $ cp begin.txt copy.txt
    ```    
+ cp -r  directory_to_copy new_directory_name => Copy a directory ( r - Recursive copy) 
    ```sh
    $ cp -r code html 
    ```
    ` [ ` If you try to copy a directory without adding the -r option, you will get an error `]`
+ rm file_to_remove => Removes a file
    ```sh
    $ rm begin.txt
    ```   
+ rm -r directory_to_remove => Removes a directory
    ```sh
    $ rm -r code
    ```  
#### Other Important Commands
+ man => Opens reference manual of a Linux operating system (help document)
    ```sh
    $ man
    ```  
+ history  =>  Shows all the commands that you have used in the past for the current terminal session
    ```sh
    $ history
    ``` 
+ clear =>  Clears the terminal
    ```sh
    $ man
    ```      
 + lp Filename =>  Prints a file
    ```sh
    $ lp begin.txt
    ```      
#### Reference Links

* [Progate]
* [Guru99]


[Progate]: https://progate.com/languages/commandline
[Guru99]: https://www.guru99.com/must-know-linux-commands.html

**if you want to contribute to the project,create a pull request**
