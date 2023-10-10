
```
ls
lecture1
```
The working directory is home directory.
I am getting this output because ls will list out files and directories this current directory contains.
The output is not an error.

```
ls lecture1/
Hello.class  Hello.java  messages  README
```
The working directory is still home directory
I am getting this output because "ls lecture1/" lists out files and directories within the lecture1 directory
The output is not an error

```
ls en-us.txt
en-us.txt
```
The working directory is /home/lecture1/messages.
I am getting this ouput because ls command simply confirms that this file exits by displaying its name. 
The output is not an error

```
cd
pwd
/home
```
The working directory is /home/lecture1/messages.
The cd command brings me back to the home directory because I did not give it any argument
The output is not an error

```
cd lecture1/
pwd
/home/lecture1
```
The working directory is home directory.
The cd command changes my directory to the lecture1 directory
the output is not an error

```
cd lecture1/messages/en-us.txt
bash: cd: lecture1/messages/en-us.txt: Not a directory
```
The working directory is home directory.
The cd command tries to change my directory to a file but it cannot do it because it only works for changing directories not a specifc file
the output is not an error

```
cat
No output
```
The working directory is home directory. 
cat command is used to concatenate and display files' contents. When there is no argument, it does not have content to display.
It is not an error, the command requires input.

```
cat ./lecture1
cat: lecture1: Is a directory
```
The working directory is home directory.
cat command is used to display contents of files. Therefore, when the argument is a directory, cat cannot run properly
This is an error, cat only takes files as input to concatenate or display the contents

```
cat en-us.txt
Hello World!
```
The working directory is /home/lecture1/messages.
cat command is used to display contents of files so it shows the message within the en-us.txt file.
The output is not an error. 

![Image](meme1.jpg)

