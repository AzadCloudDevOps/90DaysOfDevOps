## Task4 of #90daysofdevops

Hello 👋 there

Here are some learnings about shell scripting with tasks.

So let's begin,

### 1. What is Kernel?

A kernel is a core and the heart of an OS, which manages the operations of the hardware and the computer. A kernel acts as a bridge between any user and the various resources offered by a system.

### 2. What is Shell?

Shell is a command-line interpreter. Shell is a computer program that acts as an interface between the user and the kernel. Users can communicate with the kernel by writing programs, commands, and scripts on the shell. It accepts human-readable commands and converts them into kernel-understandable language.

### 3. What is Linux Shell Scripting for DevOps?

A shell script is a computer program designed to be run by a Linux shell, a command-line interpreter. The shell script is a list of commands executed by the shell. Typical operations performed by shell scripts include file manipulation, program execution, and printing text. It combines lengthy command sequences into one simple script that can be stored and executed anytime automatically which reduces programming efforts and errors.

### 4. What is #!/bin/bash*?* and can we write #!/bin/sh as well?

```#!``` is nothing but shebang or hashbang.

```#``` is used for comments in shell scripts but here it has a special meaning.

Adding shebang plays an important role in shell scripting, especially while dealing with different types of shells to run the commands in the script.

which shell is the command to find the shell type in our system

```#!/bin/bash``` is a shebang line used in the script to set the bash present in the /bin directory, as the default shell to execute the commands present in the file.

There are different shebang lines for each different shell.

```#!/bin/bash``` --> the script should always be run with bash, rather than another shell.

```#!/bin/sh``` --> the interpreter should be a Bourne shell, not Bash.

```#!/bin/csh``` --> interpreter here is a C shell.

```#!/bin/ksh``` --> interpreter is Korn shell.

So we can use any shell type in our script as per the use case and availability of the type of shell in our system.

### 5. Write a Shell Script that prints I will complete the #90DaysOofDevOps challenge.
```
$ vim script.sh
#!/bin/bash
echo "I will complete the #90DaysofDevOps challenge"
:wq
$ chmod 777 script.sh
$ ls -l
$ ./script.sh
```
### 6. Write a Shell Script to take user input, input from arguments and print the variables.
~~~
$ nano msg_text.sh
#!/bin/bash
name=Bhuvan
echo "Hello ${name}, where do you live now"
read place
echo "I live in ${place} city"
echo "Sub: Hi, myself $1 here"
ctrl+x, Yes then enter
$ chmod 777 msg_text.sh
$ ./msg_text.sh Mahesh
~~~
~~~
output:-
Hello Bhuvan, where do you live now
#type Pune here
I live in Pune city.
Sub: Hi, myself Mahesh here
~~~
### 7. Write an Example of If else in Shell Scripting by comparing 2 numbers.
~~~
$ nano if_test.sh
#!/bin/bash
echo "enter the first number"
read a
echo "enter the second number"
read b
if [ "$a" = "$b" ]
then
    echo "Both numbers are same"
else
    echo "Both numbers are different"
fi
ctrl+x, Yes then enter
$ chmod 777 if_test.sh
$ bash if_test.sh
~~~


Checkout article link: [Basic Linux Shell Scripting ](https://akash-zade.hashnode.dev/basic-linux-shell-scripting-for-devops-engineers)
