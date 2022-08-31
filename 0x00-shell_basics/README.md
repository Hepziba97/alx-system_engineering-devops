pwd - a script that prints the absolute path name of the current working directory.
ls - Display the contents list of your current directory.
cd - a script that changes the working directory to the user’s home directory.
ls -l - Display current directory contents in a long format
ls -al - Display current directory contents, including hidden files (starting with .). Use the long format.
ls -alF - Display current directory contents in long format with user and group IDs displayed numerically and hidden files (starting with .)
mkdir /tmp/my_first_directory/ - Create a script that creates a directory named my_first_directory in the /tmp/ directory.
mv betty my_first_directory - Move the file betty from /tmp/ to /tmp/my_first_directory.
mv /tmp/betty /tmp/my_first_directory  - to move the file to another .directory
rm /tmp/my_first_directory/betty - to  remove the file from a directory
rmdir /tmp/my_first_directory - Delete the directory my_first_directory that is in the /tmp directory.
cd - - a script that changes the working directory to the previous one.
ls -al . .. /boot - a script that lists all files (even ones with names beginning with a period character, which are normally hidden) in the current directory and the parent of the working directory and the /boot directory (in this order), in long format.
file /tmp/iamafile -  a script that prints the type of the file named iamafile
ln -s /bin/ls __ls__ - it Create a symbolic link to /bin/ls, named __ls__.
cp -nu *.html .. - a script that copies all the HTML files from the current working directory to the parent of the working directory, but only copy files that did not exist in the parent of the working directory or were newer than the versions in the parent of the working directory.
mv [[:upper:]]* /tmp/u - Create a script that moves all files beginning with an uppercase letter to the directory /tmp/u.
rm *~ - Create a script that deletes all files in the current working directory that end with the character ~.
mkdir -p welcome/to/school - Create a script that creates the directories welcome/, welcome/to/ and welcome/to/school in the current directory.
ls -pamv - a command that lists all the files and directories of the current directory, separated by commas (,).
