# bash commands:

date - displays the current date and time
echo - displays anything after it, these are called arguments

argument parsing in bash is splitting the input into words based on whitespace,and each separated word is called an argument, and the first argument is the command itself
to use arguments with whitespace, you can use quotes to group them together

man - short for manual, followed by a command name will display the arguments for that command and a description of what it does
an alternative is to use the --help or -h argument after a command which displays a slightly shorter than the man page

cd - change directory, changes where the user is in the file system
/ means the root directory, which is the top level of the file system
~ means the user is in the home directory

cd /name_of_directory - moves user into that directory
cd / - moves user to the root directory
cd name_of_directory - moves user into a directory that is in the current directory
cd . - stays in the current directory
cd .. - moves user up one directory level
cd bin/../bin/././../bin - moves user to bin directory

which - displays the path to the executable file for a command, if it exists
it searches through each directory in the PATH environment variable, which is a list of directories separated by colons, and returns the first match it finds
which which - displays the path to the which command itself
whcih -a - displays all the available programs with the same name, not just the first one found
$PATH - an environment variable that contains a list of directories where the shell looks for executable files

ls - lists the contents of a directory, by default it lists the current directory
cat - short for concatenate, displays the contents of a file
head - displays the first 10 lines of a file by default, but you can specify a different number of lines with the -n[NUMBER] argument
tail - displays the last 10 lines of a file by default, but you can specify a different number of lines with the -n[NUMBER] argument
 
grep - a file searching, doesnt search for files but rather searches in files, and it searches for things that match a pattern
find - used to find things but has a lot of argument options so its a bit hard to use, might learn more about this later

