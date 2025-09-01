# Ex-01-Linux-Commands


## Aim:

To study the execution of various Linux operating system commands.

## Linux:

Linux is an open-source operating system. The kernel is the heart of Linux OS which
 
helps the communication between hardware and software. The main advantage of Linux was that programmers can use Linux kernel to design their own custom OS.

Linux Commands:
All basic and advanced tasks can be done by executing commands. The commands are executed on Linux terminal. Linux commands are case sensitive.


## Commands:

### 1)	ls Command

The ls command is used to display a list of content of a directory.

 Syntax: ls

 <img width="945" height="207" alt="image" src="https://github.com/user-attachments/assets/7f43819f-2908-4066-a359-5f6d229d4eee" />



### 2)	pwd Command

The pwd command is used to display the location of the current working directory.

Syntax: pwd

<img width="937" height="68" alt="image" src="https://github.com/user-attachments/assets/fa5f168a-59f9-4297-ab47-6f78ea8d6d42" />


 
### 3)	mkdir Command

The mkdir command is used to create a new directory under any directory.

Syntax: mkdir <directory name>

<img width="942" height="61" alt="image" src="https://github.com/user-attachments/assets/1ac96d4d-9ca5-400a-888d-71d848ad9f8f" />



### 4)	rmdir Command

The rmdir command is used to delete a directory.

Syntax: rmdir <directory name>

<img width="940" height="63" alt="image" src="https://github.com/user-attachments/assets/5098b431-0b0a-4795-8b0c-74707c73f9da" />



### 5)	cd Command

The cd command is used to change the current directory.

Syntax: cd <directory name>

<img width="935" height="69" alt="image" src="https://github.com/user-attachments/assets/b1ddd190-aa47-4d8c-a17f-58064467ffa8" />



### 6)	cat Command

The cat command is a multi-purpose utility in the Linux system. It can be used to create a file, display content of the file, copy the content of one file to another file, and more.

Syntax: cat [OPTION]... [FILE]..

<img width="936" height="112" alt="image" src="https://github.com/user-attachments/assets/68f0be97-ba08-4ca5-86b6-a4cf5b6d2edd" />


 
### 7)	cp Command

The cp command is used to copy a file or directory.

Syntax: cp <existing file name> <new file name>

<img width="939" height="68" alt="image" src="https://github.com/user-attachments/assets/17fb2b16-2bd4-4058-b1ef-321589fd429c" />




### 8)	gedit Command

The gedit is a general-purpose text editor. It can be used to create and edit all kinds of text files.

Syntax: gedit file_name

<img width="939" height="30" alt="image" src="https://github.com/user-attachments/assets/aa582fe4-543d-4e03-9589-e8403e362d76" />



### 9)	su Command

The su command provides administrative access to another user. In other words, it allows access of the Linux shell to another user.

Syntax: su <user name>

<img width="943" height="102" alt="image" src="https://github.com/user-attachments/assets/ba14696a-9a8a-46ca-a8db-2d85e0222ff0" />



### 10)	mv Command

The mv command is used to move a file or a directory form one location to another location.

Syntax: mv <file name> <directory path>

<img width="931" height="33" alt="image" src="https://github.com/user-attachments/assets/48937285-0e77-4355-baf5-6ce2393baf8a" />


 
## 11)	rename Command

The rename command is used to rename files. It is useful for renaming a large group of files.

Syntax: rename 's/old-name/new-name/' files

<img width="940" height="229" alt="image" src="https://github.com/user-attachments/assets/226303bc-dfca-421f-854a-ac6e2e60da49" />



### 12)	head Command

The head command is used to display the content of a file. It displays the first 10 lines of a file.

Syntax: head <file name>

<img width="937" height="308" alt="image" src="https://github.com/user-attachments/assets/c07d8f9e-251d-450f-b06c-99e7b54924a8" />



### 13)	tail Command

The tail command is similar to the head command. The difference between both commands is that it displays the last ten lines of the file content. It is useful for reading the error message.

Syntax: tail <file name>

<img width="838" height="221" alt="image" src="https://github.com/user-attachments/assets/99f681c0-e09f-4b68-a143-4f968bab116b" />


 
### 14)	id Command

The id command is used to display the user ID (UID) and group ID (GID).

Syntax: id

<img width="941" height="101" alt="image" src="https://github.com/user-attachments/assets/0be0bcf2-cba9-4887-a3e2-e44f309e79ce" />


### 15)	grep Command

The grep is the most powerful and used filter in a Linux system. The 'grep' stands for "global regular expression print." It is useful for searching the content from a file. Generally, it is used with the pipe.

Syntax: command | grep <search word>

<img width="942" height="62" alt="image" src="https://github.com/user-attachments/assets/b9546409-9cf1-43df-a685-b6c61cebcfbf" />



### 16)	tr Command

The tr command is used to translate the file content like from lower case to upper case.

Syntax: command | tr <'old'> <'new'>

<img width="938" height="170" alt="image" src="https://github.com/user-attachments/assets/a4c05462-aa85-473d-95bb-2619b543b202" />


### 17)	chmod Command

The chmod command is used to change the access mode of a file (i.e., read, write or execute)

Syntax: chmod<options><permissions><file_name>

<img width="601" height="24" alt="image" src="https://github.com/user-attachments/assets/22cf5dd6-5751-427e-b64f-389d68f093bb" />


### 18)	tar Command

The tar command is used for creating Archieve and extracting the archieve files.

Syntax: tar[options][archieve-file] [file to be archieved]
$ tar xvzf file.tar *.c

<img width="603" height="39" alt="image" src="https://github.com/user-attachments/assets/9a8995f2-260b-45d4-bc4d-d3af3366e964" />

 
### 19)	chown Command

The chown command is used to change ownership.

Syntax: chown owner_name file_name

<img width="631" height="23" alt="image" src="https://github.com/user-attachments/assets/0db2c9cf-d513-4650-ac5e-51cf440789c4" />


### 20)	make Command

The make command is used for building and maintaining group of program.

Syntax: make [-f makefile][options]…….[targets]….

<img width="634" height="40" alt="image" src="https://github.com/user-attachments/assets/b71fca94-96ae-42d4-8b1c-6e9019667f35" />



### 21)	ifconfig Command

The ifconfig command is used to configure kernel-resident network interface.

Syntax: ifconfig[options][interface]

<img width="693" height="491" alt="image" src="https://github.com/user-attachments/assets/796570d4-2d3d-45fe-aa73-cced14cd9155" />


### 22)	chmod 777 Command

The chmod 777 command gives read, write and execute permission to the owner, group and public.

Syntax: chmod 777 file_name
$chmod -R 777 /path/to/file/or/folder

<img width="603" height="39" alt="image" src="https://github.com/user-attachments/assets/19d0a5f9-2677-4471-8a22-1d51ca969449" />

 
### 23)	host Command

The host command is used to display the IP address for a given domain name and vice versa. It performs the DNS lookups for the DNS Query.

Syntax: host <domain name> or <ip address>

<img width="603" height="39" alt="image" src="https://github.com/user-attachments/assets/60067dff-54d8-46c5-86b6-187fa9463910" />



### 24)	gzip Command

The gzip command is used to truncate the file size. It is a compressing tool. It replaces the original file by the compressed file having '.gz' extension.

Syntax: gzip <file1> <file2> <file3>..

<img width="589" height="22" alt="image" src="https://github.com/user-attachments/assets/8b2da491-8708-4179-bc61-a7395b619906" />



### 25)	sort Command

The sort command is used to sort files in alphabetical order.

Syntax:sort <file name>

<img width="594" height="256" alt="image" src="https://github.com/user-attachments/assets/3097ec65-9878-4f4a-b883-662c390477a2" />


 
### 26)	cal Command

The cal command is used to display the current month's calendar with the current date highlighted.

Syntax: cal


### 27)	clear Command

Linux clear command is used to clear the terminal screen.

Syntax: clear

<img width="570" height="169" alt="image" src="https://github.com/user-attachments/assets/5f406040-5b55-45dc-a0c7-eb98b583f4a2" />


### 28)	mail Command

The mail command is used to send emails from the command line.

Syntax: mail -s "Subject" <recipient address>
<img width="731" height="87" alt="image" src="https://github.com/user-attachments/assets/72a53143-a395-41b2-a59d-d4ff51a9fe19" />

 
### 29)	df Command

The df command is used to display the disk space used in the file system. It displays the output as in the number of used blocks, available blocks, and the mounted directory.

Syntax: df

<img width="734" height="209" alt="image" src="https://github.com/user-attachments/assets/ceb76d4d-cbeb-4d7e-bd58-f4d4f023ecd5" />


### 30)	find Command

The find command is used to find a particular file within a directory.

Syntax: find.-name”*.pdf”

<img width="707" height="47" alt="image" src="https://github.com/user-attachments/assets/1bdceb94-adb8-4e93-a387-11b33b7ba6ff" />





















## Result:

Thus, the execution of various Linux commands is executed successfully using Ubuntu OS.
