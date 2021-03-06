+++
title = "Week 2 Example commands"
date = 2021-04-05
+++

```
# More in the cheatsheet: https://ss64.com/bash/
# Just prints the contents of the following command
echo $SHELL

# Prints out the process working directory (folder)
pwd

# Prints out the logged in user
whoami

# Changes the directory
cd 

# cd's into /home/$USER directory
cd ~/

# . is the current directory
cd ./

# .. is the directory up the tree
cd ../
 
cd /home/$USER/Downloads

# cd's into the root directory
cd /

# Lists the contents of the current directory
ls 

# Lists the contents of the directory up the tree
ls ../

# Lists the contents of the directory two times up the tree
ls ../../

# Lists the contents of the root directory
ls /

# Lists the contents of the current directory, formatted as a list with additional info
ls -l

# Also includes the hidden files (starting with .)
ls -a

# Combines -l and -a options
ls -la

# Prints the directory name, not their contents
ls -d

# Creates a directory called try
mkdir try

# Creates all the directories included in path provided
mkdir -p try/try2/try3

# Creates the file, or updates its 'modified date'
touch file_try

# Opens the file in vim
vim file_nvim_try

echo Hello

# Redirects the output to file helloworld, rewriting the contents
echo Hello > helloworld

echo world > helloworld

# Appends the output to the file
echo hello_world >> helloworld

# Prints out the contents of the file
cat helloworld
```