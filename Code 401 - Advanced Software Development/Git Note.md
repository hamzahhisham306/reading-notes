1. What is the Command Line 
 > A text-based system interface known as a command line or terminal is used. Commands can be entered using the keyboard, and feedback is provided to you in a 
  text-like format.
  
2. How does it work?
  > Usually, the command line will give you a prompt. It will appear after the prompt as you type. You will primarily be giving orders
  
3.how do I get to one?
  > you can ues cmd windows or dowload terminal for Ubuntu or Linux

4. Basic Navigation 
   - pwd > it print on your screen (Print Working Directory)
   
5. What's in Our Current Location?
 - > we can use ls command to show the file in my directory.
 - > we can use some options with command ls 
 - > for example : ls -l it shows the  list the contents of the directory in a table format with columns
 - > ls /fileName  ls is instructed to list that directory's contents rather than our current directory.
 
6. path:
 - We have access to both absolute and relative paths. We use one of these paths whenever we talk about a file or directory. Both types of paths can be used to refer to a file or 
 - directory whenever necessary (either way, the system will still be directed to the same location).
 - Relative path > A file or directory location relative to where we currently are in the file system.
 - Absolute path > A file or directory location in relation to the root of the file system.
 - ~ (tilde) > This is a shortcut for your home directory. eg, if your home directory is /home/ryan then you could refer to the directory Documents with the path /home/ryan/Documents or ~/Documents
 - . (dot) > This is a reference to your current directory. eg in the example above we referred to Documents on line 4 with a relative path. It could also be written as ./Documents (Normally this extra bit is not required but in later sections we will see where it comes in handy)
 - .. (dotdot) > This is a reference to the parent directory. You can use this several times in a path to keep going up the hierarchy. eg if you were in the path /home/ryan you could run the command ls ../../ and this would do a listing of the root directory
7. Cd
- > if you want to change dir we can use cd path
8. More About Files
  - Linux is an Extensionless System
  - file.exe - an executable file, or program.
  - file.txt - a plain text file.
  - file.png, file.gif, file.jpg - an image.
  - Linux is Case Sensitive
  - Spaces in file and directory names are perfectly valid but we need to be a little careful  with them.

9. Manual Pages > The manual pages are a collection of pages that describe each command that is available on your system, including what they do, how to use them specifically, and what command line parameters they take. While some of them can be a little confusing at first, once you get the hang of them, they are generally consistent in their structure. You can access the manual pages by using the command.
  - for example : man <command> man ls, man pwd, man mkdir.
  - man -k <search term> Do a keyword search for all manual pages containing the given search term.
  - /<term> Within a manual page, perform a search for 'term'
  - n >After performing a search within a manual page, select the next found item.
 


 10. File Manipulation!
   - to make new dir you have to use mkdir nameDire.
   - mkdir -p   -p >  which tells mkdir to make parent directories as needed.
   -  -v which makes mkdir tell us what it is doing.
   - for removing a dir you have to use > rmdir  nameDir. 
   - to create new file > touch filename.
   - to copy file to file > cp source destination.
   - to moving a file > mv <source> <destination>
   - to remove a file > rm <fileName>
 
 11. [Cheat Sheet ](https://ryanstutorials.net/linuxtutorial/cheatsheet.php)











