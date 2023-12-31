# <p style="text-align: center;"><span style="color:blue">*Simple_Shell*</span></p>

### TABLE OF CONTENTS
- [DESCRIPTION](#description)
- [FLOWCHART](#flowchart)
- [REQUIREMENTS](#requirements)
- [COMPILATION CMD](#compilation-cmd)
- [RETURN VALUE](#return-value)
- [EXAMPLES](#examples)
- [MAN PAGE](#man-page)
- [CHECK MEMORY LEAKS](#check-memory-leaks)
- [AUTHORS](#authors)


### DESCRIPTION

The shell is a command-line interface enabling the user to interact with a computer's operating system. It acts as a layer of abstraction between the user and the operating system kernel, enabling the user to execute commands, launch programs, navigate directories, manage files and processes, and automate tasks using scripts.

The shell is a powerful tool for interacting with a command-line operating system, enabling users to execute commands, launch programs, navigate directories, manage files and processes, and automate tasks.



### FLOWCHART

![flowchart](https://github.com/Nadely/holbertonschool-simple_shell/blob/main/Flowchart_Simple_Shell.png)

### REQUIREMENTS
compiler, list of authorized functions)

_Compiler :_GNU

_List of authorized functions :_

  	all functions from string.h
	access (man 2 access)
	chdir (man 2 chdir)
	close (man 2 close)
	closedir (man 3 closedir)
	execve (man 2 execve)
	exit (man 3 exit)
	_exit (man 2 _exit)
	fflush (man 3 fflush)
	fork (man 2 fork)
	free (man 3 free)
	getcwd (man 3 getcwd)
	getline (man 3 getline)
	getpid (man 2 getpid)
	isatty (man 3 isatty)
	kill (man 2 kill)
	malloc (man 3 malloc)
	open (man 2 open)
	opendir (man 3 opendir)
	perror (man 3 perror)
	printf (man 3 printf)
	fprintf (man 3 fprintf)
	vfprintf (man 3 vfprintf)
	sprintf (man 3 sprintf)
	putchar (man 3 putchar)
	read (man 2 read)
	readdir (man 3 readdir)
	signal (man 2 signal)
	stat (__xstat) (man 2 stat)
	lstat (__lxstat) (man 2 lstat)
	fstat (__fxstat) (man 2 fstat)
	strtok (man 3 strtok)
	wait (man 2 wait)
	waitpid (man 2 waitpid)
	wait3 (man 2 wait3)
	wait4 (man 2 wait4)
	write (man 2 write)


### COMPILATION CMD
	gcc -Wall -Werror -Wextra -pedantic -std=gnu89 *.c -o simple_shell

### RETURN VALUE
	Return the status code : 0 (sucess), 127 or 2 (error).

### EXAMPLES

_Interactive :_

		./simple_shell
		$ ls

_Non-interactive :_

		echo "/bin/ls" | ./simple_shell

### MAN PAGE

the command to use the man page is :

	man ./man_1_simple_shell

### CHECK MEMORY LEAKS

	valgrind ./simple_shell

### AUTHORS

Erwan Rocal, Nadège Tettelin.
