### Command line basics

## Tasks
1. Create a new directory in your home directory with the name test.
2. Navigate to the test directory.
3. Create a new file called test.txt. Hint: use the touch or echo command.
4. Open your newly created file in VSCode and make some changes, save the file, and close it.
5. Navigate back out of the test directory.
6. Delete the test directory.

## Solution:
```
odin@odin-VirtualBox:~/Documents/TheOdinProject/assignments/commandlinebasics$ mkdir ~/test
odin@odin-VirtualBox:~/Documents/TheOdinProject/assignments/commandlinebasics$ cd ~/test/
odin@odin-VirtualBox:~/test$ touch test.txt
odin@odin-VirtualBox:~/test$ code test.txt 
odin@odin-VirtualBox:~/test$ cd ..
odin@odin-VirtualBox:~$ rm -rf test/
```
## Knowledge Check

1. What is the command line?
The command line is a tool with various commands to complete diferent operations on an OS without using a GUI.
3. How do you open the command line on your computer?
You can open it with the GUI by searching for terminal or by opening it with the shortcut ctrl + alt +t.
5. How can you navigate to a particular directory?
cd <target directory>
7. Where will cd on its own navigate you to?
 to the home folder of the current user
8. Where will cd .. navigate you to?
  it will navigate one step back in the folder path from your current position
9. How do you display the name of the directory you are currently in?
  ``` pwd ```
10. How do you display the contents of the directory you are currently in?
  ls
11. How do you create a new directory?
  ```mkdir newfolder```
12. How do you create a new file?
 ``` touch newfile ```
13. How do you destroy a directory or file?
  ```
  rm file
  rmdir directory ( if empty )
  rm -r directory ( with content )
  ```
14. How do you rename a directory or file?
  ``` mv folder newfoldername ```
