# Code 401 - Pre-work - Practice with the Terminal

## What is Command Line?

**The Command Line**: Also known as the terminal, is a 'text based interface to the system'. You can enter commands in the terminal and feedback is returned to you. To open the Terminal in a Mac, go to Applications -> Utilities and look for the Terminal.

The **Shell** is located inside the terminal. The shell deals with how the terminal looks and behaves after you are done executing specific commands. Various types of shells but the most common is called Bash.

If you have a Mac, you already have access to the terminal on your computer. Alternatively, you can use **Linux**. **Ubuntu** is a recommended distro to use but there are others like OpenSuSe.

## Basic Navigation

**Basic Navigation**: In order to use the terminal efficiently, it is important to know how to navigate to different spots in the system.

**pwd** : Print Working Directory tells you what your current or present working directory is.

**ls** : ls stands for List and list tells you what is located in your current directory. Ls allows you to run optional arguments- ls -l : Prints a longer list of the current directory with more info like whether it is a normal file or a directory, the owner of the directory, etc.

**path**: refers to the way to access/get to a particular directory or file that is located. There are absolute paths and relative paths. You can use an absolute or relative path to access a file or directory, they both direct you to the same location in the system.

**absolute path**: Specifies a location that is in relation to the root directory. These always begin with a forward slash (/).

**relative path**:  Specifies a location that is in relation to where you are currently located in the system. These don't begin with a forward slash.

**cd**: Also known as change directory, it allows you to move to different directories in the terminal

## More About FILES

More About Files: Remember that in linux is that everything is essentially a file. Linux is also an extensionless system, meaning it doesn't include extensions like .exe, .txt, .png, etc. I didn't know that you can use quotes in the command line to access files that have a space between them (ex. cd 'Holiday Photos'). Or you can use escape characters (\) in the command line too (ex. cd Holiday\ Photos) You can use a . to hide files in the command line too. Also cool that the ls command doesn't show hidden files as well.

**file**: Helps you determine what type of file a file in the command line. This is important because the command line doesn't use extensions.

**ls -a**: list the contents of the current directory that also includes the hidden files. the -a does that.

## Manual Pages

**Manual Pages**: Explains every single command that is available on your system and what they do. 

This is a great resource since remembering all the different commands would be difficult/unnecessary. It is also interested that you can use the shorthand or long hand version of commands like -a or --all. Long hand commands begin with -- and short hand commands begin with -.

**man**: Allows you to invoke the manual pages which tells you all the different commands available in your system.

**man k**: Allows you to do a keyword search through the manual pages.

## File Manipulation

**mkdir**: Make Directory helps you make a new directory in the command line. You can also add a relative or absolute path after the mkdir to establish where the new directory will exist.

**p**: Also known as Parent this can be added after mkdir to make this specific directory a parent directory.

**rmdir**: Also known as Remove Directory, removes a directory. You can also utilize -v and -p for Remove Directory.

**touch**: creates a blank file. Also used to modify access and the modification times of a particular file.

**cp**: Also known as Copy, this makes a copy of directory of file. You can use absolute or relative paths with this command.

**mv**: Also known as Move, this allows you to move a file or directory. You can also use Move to rename a file directory while your movie it.

**rm**: Also known as Remove, removes a file. It is similar to rmdir but for files.

## References

1. [Ryans Tutorials](https://ryanstutorials.net/linuxtutorial/)
