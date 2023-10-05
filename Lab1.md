
```
ls
lecture1
```
The working directory is home directory
I am getting this output because ls will list out files and directories this current director contains
The output is not an error

```
ls lecture1/
Hello.class  Hello.java  messages  README
```
The working directory is still home directory
I am getting this output because ls lists out files and directories within the lecture1 directory
The output is not an error

```
ls en-us.txt
en-us.txt
```
The working directory is /home/lecture1/messages
I am getting this ouput because ...
The output is not an error

```
cd
pwd
/home
```
The working directory is /home/lecture1/messages
The cd command brings me back to the home directory because I did not give it any argument
The output is not an error

```
cd lecture1/
pwd
/home/lecture1
```
The working directory is home directory
The cd command changes my directory to the lecture1 directory
the output is not an error

```
cd lecture1/messages/en-us.txt
bash: cd: lecture1/messages/en-us.txt: Not a directory
```
The working directory is home directory
The cd command tries to change my directory to a file but it cannot do it because it only works for changing directories not a specifc file
the output is not an error

