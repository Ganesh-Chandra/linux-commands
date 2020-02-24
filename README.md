# CHAPTER - 1


# Facts
* shell is a program that takes cmds from keyboard and passes them to os to carry out those commands
* terminal with # at end means that it has super user privilages.
* prompt typically has username@machinename working dir $/#
* most of linux has bash which is a shell program.
* Most Linux distributions remember the last 1000 commands by default
* There will be multiple virtual terminals running behind the GUI curtain.
* To access virtual terminal we have to press Ctrl+Alt+F3.to return back Alt+F2.
* After going to virtual terminal it askes us to login from terminal.

# $date
* prints out day month date time year

# $cal
* shows the calendar of a month 

# $df
* prints amount of free space present in our disk drives

# $free
* displays amout of free space available

# $exit
* exits out and closes terminal




# CHAPTER - 2


# Facts
* the unix organizes files in hierarhical directory structure like a tree
* the first directory is called root and its root for all file systems no matter how many drives or devices connected.(unlike windows)
* GNOME == GNU network object model environment(desktop top gui) KDE == K desktop environment (used for cross platform apps)
* There are two types of path names absolute path names and releative path names.
* absolute path is the path from the root directory till the target with directoires separated by leading space.
* releative path is path from current working directory. "." refers to the current directory.".." refers to the parent directory. when refering to releative path it alsways starts with "./" by default.
* there are hidden files in the directories they all start with "." in the begining.
* files in linux are case sensitive.
* linux has no concept of file extension.although linux os dont use extensions to know contents and purpose of the files applications in linux use them.

# $pwd 
* Print name of current working directory

# $cd 
* Change directory


# $ls 
* List directory contents

# chapter3(exploring the system)
# Facts
* Computers, after all, only understand numbers and all data
is converted to numeric representation.one of such mapping is ascii.windows word and linux libre office has more complex structures but notepad works with plainly 
ascii values
* config files has system settings and are stored in ascii format In addition, some of the actual programs
that the system uses (called scripts) are stored in this format
* less is more! previously there was a cmd named more but with adding new features it was made as less.so less is more.
* a file permission thing starting with - is a file.staring with d is directory.if its l then its a symbolic link file.also known as softlink or symlink.
* these symbolic links are used to sole problems in versioning.
# file
* determines the file type
# ls 
* ls /path/fora/directory :this prints out contents of the directory in the given path
* ls ~/path/fora/directory :this prints out contents of the directory in the given path,along with componenets in current path
* ls -lt :prints files of dir in long format and sorted by Time modified
* ls -lt --reverse :prints files of dir in long format and sorted by Time modified in reverse order
# less
* used to read text in a file.arrows to navigate contents displayed by less.
* less /characters :Search forward to the next occurrence of characters
* less n :Search for the next occurrence of the previous search


