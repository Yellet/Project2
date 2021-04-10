# list storage
ls
# show hidden 
ls -a 
# list details
ls -l

# where are we : full path
pwd

# change directory
cd 
> double tab when multiple completion possible/ 

# find things:
locate 

# find commands
which 
which cal
whatis
whatiscal
# look for commands about...
apropos
apropos time
apropos network

# list everything we typed in the past. 
history

# Manual of a command 
man rm

# make a directory
mkdir NameFolder

# create a file 
touch file1

# copy
cp source destination

# move or rename
mv

# delete stuff
rm 
rm -r 
> (for dirs)

rmdir 
>(for empty dirs)

# read text file
cat 
cat > file2 
> (creates/replace text in file, type and ctrl D when done)
cat >> file2
>(to quickly happend text file, type and ctrl D when done )

less file2

# edit text
nano
vim

# pipping | 
history | less
 ls -al / > lsout.txt

 # sudo
 sudo -s (to become root) 
>exit to go out

 su - cindy
 > going to cindy's account with her setting and her home folder. 

users
> see who is logged in. 

id
> info about you account


















## check and change shell 
cat /etc/shells
chsh