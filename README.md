# CSCI-460 PA0
The main goal of this assignment and in turn this Readme is to familiarize myself with some of the tools that will be used in CSCi 460. Such as using markdown to write this and the basics of commands in vagrant.
****
## Task #1
* Done!
****
## Task #2
 * The three repo Readmes that I have chosen are [Computer Vision Recipes](https://github.com/microsoft/computervision-recipes), [Github Readme Stats](https://github.com/anuraghazra/github-readme-stats), and [Piskel](https://github.com/piskelapp/piskel). 
 * These three repos have several things in common, the first one that is the most obvious, is a well written general overview of their repository. The second similarity is a section on how to implement/setup the application or code in the repo. Lastly there is a section on how to contribute to the project as well as licensing. I think that all of these features in a Readme are important and are something that I hope to implement myself going into the future.
 ****
## Task #3
Base on the image below it seems as though the command 'uname -a' is simply displaying the OS and architecture that vagrant is based on.
 
![Using the uname -a command](uname.png)
*****
## Task #4
### Initial inspection of the commands
#### Part 1.
##### Initial inspection of the commands
  - Well based on past experience I know that the 'cd ~' command brings you to the home directory, so if I was in another directory and used this command I would see that I am brought back to the home directory.
  - It would seem that 'pwd' is the command for displaying what the current directory path is.
  - The mkdir command seems to creates a new directories, so when you use 'mkdir -p /tmp/this/is/a/sub/directory' this command creates multiple directories.
  -  
  - 'ls -al' seems to print out all the files and directories in the current directory along with their permissions and when they were last modified.
  - 
  - 'curl -O https://raw.githubusercontent.com/traviswpeters/cs460-code/master/week02/info' seems as though it is doing an http request to the specified url and storing that file. 
  - 'cat info' is printing the contents of 'info' to the standard output of the command line. I have used this before so I am fairly confident in my assertion.
  - 
#### Commands after research
  - My initial intuition was correct as 'cd ~' does bring you to the home directory.
  - Initial inspection again was correct
  - &darr; &darr;
  - 
  - My initial observations were correct as the ls command prints all of the files and directories in the current directory. The '-al' means all files and use a long listing format.
  - 
#### Part 2.
Well based on the emphasis on manual, I am going to say that this is a reference to man pages or running 'man [command]' to learn more about a specific command in the terminal.
#### Part 3
I would say scapy is my favorite tool I don't know if it counts as it is not a native tool, but is fun to use as it allows you to manipulate/monitor packets. Such as capturing them, or tracing their path. For a more native tool I would say that cat is my favorite as it is very useful to be able to print out a file quickly without actually using a text editor like vim or emacs.
## Task #5


## Task #7
    '''ls
    ==1786== 
    ==1786== HEAP SUMMARY:
    ==1786==     in use at exit: 0 bytes in 0 blocks
    ==1786==   total heap usage: 102 allocs, 102 frees, 6,442 bytes allocated
    ==1786==
    ==1786== All heap blocks were freed -- no leaks are possible
    ==1786==
    ==1786== For counts of detected and suppressed errors, rerun with: -v
    ==1786== ERROR SUMMARY: 0 errors from 0 contexts (suppressed: 0 from 0)
    '''
