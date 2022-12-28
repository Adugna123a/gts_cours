## **Finishing for Linux!**
## Script installation
● Some hacking tools are developed by some peoples and those peoples make it

open-source, that means we can get those scripts/programs from github.

● So we can download and use it. For this purpose git have a feature called ‘clone’
● Syntax

    ○ git clone <link_of_the_script_from_github>
## **Script modules**
● Scripts are made with scripting languages(programming) like
 { python,bash,go,ruby,...}
 ## **Errors you may encounter**
● Don’t close apt while installation

● Repository errors, if this happened you can fix it using

   
      ○ sudo apt edit-sources

● And more…

➔ For those kinds of errors what you have to do is
google/youtube { detail we will see this while we
learn Footprinting }
## **Linux Processes & Services**
● As we interact with Linux, we create numbered
instances of running programs called
“processes”

● To get the processes:

○ ps [options]

● More commands

    ○ ps -> for process running on my shell
    ○ ps -A -> view all running process
    ○ ps -u username -> view users process
● PID - Process ID
● To stop process

    ○ Kill [options] [PID]
● More on kill

     ○ kill -19 PID -> to stop the process

    ○ kill -18 PID -> to resume the process we stopped

    ○ kill -9 PID -> to Stop a process immediately
    ○ … there are 31 options.
   ## **Null device**
● /dev/null - Redirects output to nowhere.

● If you want to ignore output, you can send it to the null device, /dev/null. 
The null
device is a special file that throws away whatever is fed to it. You may hear people refer
to it as the bit bucket. 
If you do not want to see errors on your screen and you do not
want to save them to a file, you can redirect them to /dev/null

● On shell output there are 2 things.

    ○ STDERR = 2
    ○ STDOUT = 1

● To redirect the errors from a command result we do
○ command 2> filename => here if you check the file you saved on it have errors only

● To redirect the error-FREE output

    ○ command 1>filename

● So if we redirect our commands output to /dev/null we will get error free result

○ command 2> /dev/null
## **alias**
● Used to give a name to some bunch of
commands.

● Example: if i wanted to name ls -la ‘rex so
any time i want to get output of ls -la i just
type rex

    ○ alias rex=’ls -la’
## **Tmux - Terminal Multiplexer**
● Tmux is used to classify our terminal work.

● You can install it using apt. On kali it is built-in

● Then to start it just type ‘tmux’\

● To Create config file type

    ○ nano .tmux.conf
    ○ Type this
- unbind C-b
- unbind l
- set -g prefix C-a
- unbind %
- bind e split-window -h
- bind o split-window -v
- set -g base-index 1
- setw -g pane-base-index 1
 
        ○ Save it | exit tmux and open again
● To split horizontally
    ○ ^A then o

● To split vertically
    ○ ^A then e

● To exit

    ○ ^A then x or
    ○ just type ‘exit’
● To create tab
    ○ ^A then c
● To rename the tab

    ○ ^A then ,(comma)
● To switch tabs

    ○ ^A then <numbers>
    ○ TO switch partitions
- ^A then <arrow>
  
● … for more you can google but be aware of our super key is ^A
## **Wget**
● Is a tool used to download files from websites/servers

● Syntax

○ wget [options] [link]

● wget https://tldp.org/LDP/intro-linux/intro-linux.pdf