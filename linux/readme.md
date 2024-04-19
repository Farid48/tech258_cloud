# Linux Commands

## Check the current shell we are using

```
-ps -p $$ # OR 1330 - these 2 are interchangeable 
```
**ps** - all the processes that are currently running

**p** - Select a specific process (which is the next argument)

**$$** - short form for 1330, which will allow you to check your shell

## Check History

```
history # to check history
history -c # Clear history
```

![alt text](linux_images/image-1.png)

## List all the shells in the system

```
cat /etc/shells # outputs all the shells that are installed
```
![alt text](linux_images/image.png)

## Download a file

```
curl "ENTER YOU URL" --output "FILENAME".jpg 
```

## Move and Rename a file
```
mv cat.jpg cat # Will rename cat.jpg to cat, but linux will still remember that it is still a jpg

mv cat funny_jokes/funny_images # Ths will move the cat file to the funny_image directory

file cat # checks the file type of the file called "cat"

```
![alt text](linux_images/image-2.png)

Example of moving a file:

![alt text](linux_images/image-12.png)

How to move a file back to the current directory (in this case back to the home):

![alt text](linux_images/image-13.png)


## Copy and Remove Files
```
cp cat cat.jpg # will copy the cat file and name it as cat.jpg

rm cat # will remove the cat file

rm -r funny_jokes # will remove the directory of the folder (-r means recursive, so it deletes everything inside)

rf # means recursive force, this will forcefully remove all the files, however, if there are no arguments after it, it will delete all the files on linux.
```
![alt text](linux_images/image-4.png)

![alt text](linux_images/image-5.png)


linux is case sensitive 

### Task 1

print top 2 lines of the file:

![alt text](linux_images/image-8.png)

print bottom 2 lines of the file:

![alt text](linux_images/image-9.png)

number the lines:

![alt text](linux_images/image-10.png)

find all the lines where chicken was ued:

![alt text](linux_images/image-11.png)


### Creating a script


`#!/bin/bash` - This is the shell we want to use, so we have to state what shell we have to use in the nano 

#### Example Script
```
sudo apt update -y  # Ensure this is saved inside a file with any name with the extension . sh
```

You can run this script by typing `./FILENAME.sh

![alt text](image.png)

```chmod 777 provision.sh```


first is current user, second is groups of users, and the last one is everyone else

```RWXRWXRWX``` - long form

read = +4 <br>
write = +2     ------> CHMOD short form <br>
execute = +1  

[chmod calc](https://chmod-calculator.com/)