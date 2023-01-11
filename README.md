# Linux Shell

It is a UNIX Shell which is present a command line where the user types in the commands and the command 
is proccesed by the calling the perticular file and gets the output.

The command executed are :
1. **Internal Commands:** 
Internal commands are those which are interpreted by the shell program itself, with-
out requiring a different program to handle the expected operations
  * cd
  * pwd 
  * echo
  * exit
  
2. **External Commands:**
External commands on the other hand relate to commands which are not handled directly
by the shell program but by an external program.
  * date
  * ls
  * cat
  * rm
  * mkdir
  
  
The shell made in C language. 
I have used fork to create a new process and execl family system calls to run the individual 
program. The parent program must also wait for the child program to
terminate using the wait() family of system calls.


To execulte the shell you have make a copy of the repository and then upload in your system by putting all the files in one folder and then run the make command in the command line of your linux system and the programs of the shell will start running. 

Some Screenshots showing the shell are below:

  
