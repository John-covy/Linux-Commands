# Linux-Commands
COMMANDS

pwd -> prints the current working directory path

cd -> used to change the working directory

ls -> lists the directory contents

mkdir <dir name> -> create folders

rmdir <dir name> -> deletes a folder

rm <file/dir name> -> used to delete a file or a folder

mv <current_path> <new_path> -> used to move  a file

cp <parent file> <child file> -> used to copy a file to another

open <filename> used to open a file

touch <filename> creates a n empty file

find -> used to find a file of folders that follow a particullar seach pattern

ln <original><link> -> used to create links of a linux file system

gzip <filename> -> used to compress a file using gzip compression protocal

gunzip -> somehow similar to gzip but the -d is always enabled by default

tar -> creates an archive, grouping multiple files into one file

cat <file> -> used to add content to a file

less <filename> -> shows the content stored inside a file

tail <filename> -> It opens the file at the end, and watches for file changes

wc < filename> -> gives useful information about a file or input it receives via pipes

uniq <filename> -> used to sort lines of text

echo "text" >> <filename> -> prints into the file the arguments passed

chown <owner> <file> -> changes the owner of a file

du -> calculates the size of a directory

df -> get the disk usage information

basename <filepath> -> returns the basename of a file

dirname <path> -> returns the directory path

ps -> prints out the processes being carried out by the computer

top -> lists the processes that are running in real time

kill -> used to stop a running processes

killall < name> -> send signals to many processes to stop the all at once

type -> shows how the command will be interpreted which is either an executable, a shell built-in program, a shell function or an alias

which <command> -> returns the path to the specified command

nohup <command> to let the process continue working even after you log out

xargs -> convert input from standard input into arguments to a command

vim -> opens vim which is a text editor

nano -> opens nano which is also a text editor

whoami -> prints the name of the usename currently logged in

who -> displays which users are logged in

su <username> -> switches to the specified user

passwd -> used to change the password for the currently logged in user

ping <host> -> sends request to a server and the server returns a respond

clear -> used to clear the current terminal

history -> shows the history of the terminal

export -> used to export variables to a child process

env -> used to pass environment variables without setting them on the outer environment

printenv -> prints  the values of environment variables


SUDO COMMANDS

sudo [command] - runs the command as the root

sudo apt update - to update to s/w
sudo apt upgrade - to upgrade the s/w
sudo apt install - used to install new s/w
sudo bash - used to start a BASH shell with root privileges
sudo passwd root - Set the root password
sudo su - Become root temporarily


-h        Displays help information and exits.
-V        Displays version information and exits.
-v        Updates the user's timestamp without running a command.
-k        Invalidates the user's timestamp, forcing the user to re-enter their password the next time sudo is used.
-K        Removes the user's timestamp entirely, similar to -k.
-b        Runs the given command in the background.
-n        Non-interactive mode; if a password is required, sudo shows an error.
-H        Sets the HOME environment variable to the target user's home directory.
-i        Simulates an initial login session, running the shell as a login shell.
-e        Edits files safely with elevated privileges.
-s        Starts a shell with root privileges.
-u        Runs the command as a specified user.
-g        Runs the command as a specified group.
-l        Lists the user's allowed and forbidden commands.
-A        Uses an alternate method for password authentication.
-E        Preserves the user's environment when running a command.
--        Indicates the end of sudo options
