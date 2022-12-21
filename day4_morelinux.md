# Linux File hierarchy
- **linux UNIX** have a special file syste than windows.
- **file system** is a directory structure that the OS uses.
   
   - **windows** system files appear under the localdisk C:.
   - **linux** system files appear under the *rootdirectory*(/). 
  ## file structure in detail
  1) /(root)
       
     * every single files and directory start from the root directory.
     * use only root users
  
  1) bin-binary executables
    
     - Essentialcommand binaries that need to be available in single-user mode
  3) /boot-Boot loader files
     
     - kernelinited, vmlinux,grub files are locatedunder /boot.
  
  4) /dev- Essential Device Files
    
     - this include terminal device, usb or any device attached the system.
  5) /etc- et cetera
     
     - contains configration files required by all program.
     - this also contain start up and shutdown shell.
  6) /home -home directory
     
     - home directories for all users to store their personal files.
  7) /lib libraries for essential for the binaries in /bin/sbin
     
     - libraries filenames are either id or lib
  8) /media 
   
     - store the temproray file or mount file such as cdrom hard disk and etc
  9) /mnt 
    
     - temporarly mounted files like media.
     - temporarly mounte directory where system admins can mount filesystem.
  10) /opt optional appilication software pakage
   
       - contains add-on appilication from individual vendors.
       
    11) /sbin-Essential system binares
   
         - just like /bin, /sbin also contains binary executables.
         - the linux commands located under this directory are used typically by system administrator, for system maintenance purpose.
  12) /tmp-temporary files
   
      - directory that cintains temporary files ceated by system and uders.
      - fils under this directory are **delated** when sysetem is rebooted.
  13) /usr-user utilities
      
      - contains binaries, libraries , documentation and source-code for second level program.
      - /usr/bin contains binary fies for user programs.
  #                       Text Editors
  - programs that user for text processing.
  - linux command line tetxt editors
     
     - vim
     - Nano
     - Emacs
     - Neovim
     - ...
   - linux Graphical text editors
      
     -  sublime  
     -  vscode
     -  gedit
     -  plima
  - Before vi the primary editor used to on unix was the line editor
      
        - user was able to see/edit only one line of the text at atime
  - then vi editor importved and developed VIM.
  - the vim editor is:
     
     - a very power full
     - but at the same time it is cryptic
   - it have to modes
   
     - command mode -> where you can do commands
     - input mode -> where you can write
- opening vim
  
  - syntax
    
     - $ vim day4_morelinux.md
   - vim is by default on command mode when you open it.
   - to get on insert mode you have ti type 'i'.
    - inside commasnd mode you can
       
       -      save :w
       -      save & quit  :q
       -      force quit & save :wq!
       -      undo :undo or :u 
       -      execute bash commands :%!
  ## Nano
    
      - nano is user firendly
      - it is free and open source.
      - usually comes pre-installed in moder linux system.
  - starting Nano
    
    - nano filname
- ## linux user managemen
  - on computer system , person who uses the computer is called **user**.
  - every users have group.
  - on linux their is 2 kinds of users:
     
     - root id =0
     - normal user id =1-999
   - the root user have the power to do every thing on linux.
 - ## Creating Users
   - on linux to create users you can use the following commands.
   
     - useradd ->simple
     - adduser -> detailed
 - user command 
  
   - sudo su useradd user name
 - adduser
   
   - sudo su adduser user name        
  