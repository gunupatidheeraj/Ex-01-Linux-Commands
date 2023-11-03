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


![image](https://github.com/gunupatidheeraj/Ex-01-Linux-Commands/assets/146909163/57b94132-8d51-424f-912e-3f37df648c79)


### 2)	pwd Command

The pwd command is used to display the location of the current working directory.

Syntax: pwd

 
 ![image](https://github.com/gunupatidheeraj/Ex-01-Linux-Commands/assets/146909163/bf7f200d-44c9-49de-ab8d-ea70e547c23c)

### 3)	mkdir Command

The mkdir command is used to create a new directory under any directory.

Syntax: mkdir <directory name>


![image](https://github.com/gunupatidheeraj/Ex-01-Linux-Commands/assets/146909163/03ad6b12-310b-40ce-9842-f95eac46a49d)


### 4)	rmdir Command

The rmdir command is used to delete a directory.

Syntax: rmdir <directory name>



![image](https://github.com/gunupatidheeraj/Ex-01-Linux-Commands/assets/146909163/0f63e740-0f83-4cf5-9d07-593658150198)

### 5)	cd Command

The cd command is used to change the current directory.

Syntax: cd <directory name>


![image](https://github.com/gunupatidheeraj/Ex-01-Linux-Commands/assets/146909163/cbe92cf3-313a-4d6b-9de9-852d4a72e4a7)

### 6)	cat Command

The cat command is a multi-purpose utility in the Linux system. It can be used to create a file, display content of the file, copy the content of one file to another file, and more.

Syntax: cat [OPTION]... [FILE]..


![image](https://github.com/gunupatidheeraj/Ex-01-Linux-Commands/assets/146909163/c55978c8-4966-4bd3-9c8e-03b2d9fb6b46)

 
### 7)	cp Command

The cp command is used to copy a file or directory.

Syntax: cp <existing file name> <new file name>


![image](https://github.com/gunupatidheeraj/Ex-01-Linux-Commands/assets/146909163/8f6b3c66-6063-4d9f-958c-b103e5a5ed7e)



### 8)	gedit Command

The gedit is a general-purpose text editor. It can be used to create and edit all kinds of text files.

Syntax: gedit file_name


![image](https://github.com/gunupatidheeraj/Ex-01-Linux-Commands/assets/146909163/3b0024de-ecb2-4c05-8193-ccdb3bfdf049)

### 9)	su Command

The su command provides administrative access to another user. In other words, it allows access of the Linux shell to another user.

Syntax: su <user name>


![image](https://github.com/gunupatidheeraj/Ex-01-Linux-Commands/assets/146909163/93f0a678-5a42-48c4-a252-f19adb484db9)


### 10)	mv Command

The mv command is used to move a file or a directory form one location to another location.

Syntax: mv <file name> <directory path>


 ![image](https://github.com/gunupatidheeraj/Ex-01-Linux-Commands/assets/146909163/5bee089e-b819-4942-8a44-027f03db7a61)

## 11)	rename Command

The rename command is used to rename files. It is useful for renaming a large group of files.

Syntax: rename 's/old-name/new-name/' files


![image](https://github.com/gunupatidheeraj/Ex-01-Linux-Commands/assets/146909163/2e260235-06ce-4ee3-b2ae-b2d70c3fa95e)


### 12)	head Command

The head command is used to display the content of a file. It displays the first 10 lines of a file.

Syntax: head <file name>


![image](https://github.com/gunupatidheeraj/Ex-01-Linux-Commands/assets/146909163/7228acf7-bbf4-4fca-9fa7-b921ba86e05e)


### 13)	tail Command

The tail command is similar to the head command. The difference between both commands is that it displays the last ten lines of the file content. It is useful for reading the error message.

Syntax: tail <file name>


 ![image](https://github.com/gunupatidheeraj/Ex-01-Linux-Commands/assets/146909163/b63a5beb-71ba-4487-bdbe-d472482bf429)

### 14)	id Command

The id command is used to display the user ID (UID) and group ID (GID).

Syntax: id



![image](https://github.com/gunupatidheeraj/Ex-01-Linux-Commands/assets/146909163/e73e6d93-4b75-4426-b4c3-de86affd5796)

### 15)	grep Command

The grep is the most powerful and used filter in a Linux system. The 'grep' stands for "global regular expression print." It is useful for searching the content from a file. Generally, it is used with the pipe.

Syntax: command | grep <search word>


![image](https://github.com/gunupatidheeraj/Ex-01-Linux-Commands/assets/146909163/2169848d-3e8d-4fa8-8c3f-d43505b87d73)


### 16)	tr Command

The tr command is used to translate the file content like from lower case to upper case.

Syntax: command | tr <'old'> <'new'>


![image](https://github.com/gunupatidheeraj/Ex-01-Linux-Commands/assets/146909163/f6415fd8-50d1-4fee-9f79-4a2c0f51d7df)

### 17)	chmod Command

The chmod command is used to change the access mode of a file (i.e., read, write or execute)

Syntax: chmod<options><permissions><file_name>

### 18)	tar Command

The tar command is used for creating Archieve and extracting the archieve files.

Syntax: tar[options][archieve-file] [file to be archieved]
$ tar xvzf file.tar *.c
 
### 19)	chown Command

The chown command is used to change ownership.

Syntax: chown owner_name file_name


![image](https://github.com/gunupatidheeraj/Ex-01-Linux-Commands/assets/146909163/4c83aa30-7e08-4e5d-8179-3acde7f86e88)

### 20)	make Command

The make command is used for building and maintaining group of program.

Syntax: make [-f makefile][options]…….[targets]….

![image](https://github.com/gunupatidheeraj/Ex-01-Linux-Commands/assets/146909163/fb2f58a1-eba0-40a0-9531-2e70923e1193)

### 21)	ifconfig Command

The ifconfig command is used to configure kernel-resident network interface.

Syntax: ifconfig[options][interface]

![image](https://github.com/gunupatidheeraj/Ex-01-Linux-Commands/assets/146909163/a97af344-cc9d-40ee-8771-6eba93d808c4)

### 22)	chmod 777 Command

The chmod 777 command gives read, write and execute permission to the owner, group and public.

Syntax: chmod 777 file_name
$chmod -R 777 /path/to/file/or/folder


![image](https://github.com/gunupatidheeraj/Ex-01-Linux-Commands/assets/146909163/a97af344-cc9d-40ee-8771-6eba93d808c4)
 
### 23)	host Command

The host command is used to display the IP address for a given domain name and vice versa. It performs the DNS lookups for the DNS Query.

Syntax: host <domain name> or <ip address>


![image](https://github.com/gunupatidheeraj/Ex-01-Linux-Commands/assets/146909163/6d15a7c3-6c0d-41b0-a8b9-04851823cff6)


### 24)	gzip Command

The gzip command is used to truncate the file size. It is a compressing tool. It replaces the original file by the compressed file having '.gz' extension.

Syntax: gzip <file1> <file2> <file3>..
![image](https://github.com/gunupatidheeraj/Ex-01-Linux-Commands/assets/146909163/6eaa8c2b-a92a-4337-9dcf-e9f7511863c0)


### 25)	sort Command

The sort command is used to sort files in alphabetical order.

Syntax:sort <file name>
![image](https://github.com/gunupatidheeraj/Ex-01-Linux-Commands/assets/146909163/dac4eadf-c538-412e-a87f-ba812e2b0bf1)

 
### 26)	cal Command

The cal command is used to display the current month's calendar with the current date highlighted.

Syntax: cal
![image](https://github.com/gunupatidheeraj/Ex-01-Linux-Commands/assets/146909163/215f885a-2ea4-4157-9e4a-8c06b4ee009c)


### 27)	clear Command

Linux clear command is used to clear the terminal screen.

Syntax: clear
![image](https://github.com/gunupatidheeraj/Ex-01-Linux-Commands/assets/146909163/c664b159-4faa-4247-9a8b-9c1093c1ee35)


### 28)	mail Command

The mail command is used to send emails from the command line.

Syntax: mail -s "Subject" <recipient address>
![image](https://github.com/gunupatidheeraj/Ex-01-Linux-Commands/assets/146909163/0f4823f3-9cfc-453a-a1a7-fcecc771ad6a)

 
### 29)	df Command

The df command is used to display the disk space used in the file system. It displays the output as in the number of used blocks, available blocks, and the mounted directory.

Syntax: df


![Uploading image.png…]()

### 30)	find Command

The find command is used to find a particular file within a directory.

Syntax: find.-name”*.pdf”





















## Result:

Thus, the execution of various Linux commands is executed successfully using Ubuntu OS.
