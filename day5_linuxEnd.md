# Advanced Linux User!
### same advancedd user commands
- to change password of user
  
  - sudo passwd username
- to change user id

  - sudo usemod -u new-id username
-  to dselete user
    
    - sudo userdel -r username
  - to change mount
  
     - sudo newuser:newgroup file name
    ## sudoers file
 - the sudoers file is afile linux and unix administration use to allocate system rights to system users
 - the user you created doesn't have power to use sudo as the original one.
 - to access this file
  
   - sudo visudo  
  ## linux file permission
 - every file have their own 
  
   - owner
   - permission
 - there is 5 main parts on the listing
   
   - permission
   - owners
   - date
   - size
   - filename
 ## Ownership
 - Ownership is the owner of the file 
 - this have 2 kinds 
     
     - user
     - group
 - to change the owner  of file you can use the command
  
   - chmown user:group filename
  ## permission
  - there are 3 types of permissions
   
     - read(r)
     - write(w)
     - execute(x)
   - the folders and files are differ with the 'd; and '-' on the beginning of the permkission.
- there still the permission have three parts.
 
   - user-group-other
 - **user**(u)=>power of user defined on the owership
 - **Group**(g)=>power of group defined on the ownership
 - **other**(o)=>power of other users.
 - **All**=>power of all which can be found in the 3 above owners
 - command to change permission of file
  
   - chmod < option > filename
  ## chmod command
  - this command helps to change file permission.
  - those file permission are read, write and execute.
  - each of the permission have a number representations
    
    - Read -> 4-r
    - Wrie ->2-w
    - execute ->1-r
  - syntax
  - chmod parameter filname
  ## package installation on linux
  - on linux to install  software you use package managers.
  - we will use debian package manager.
  - on debian the package manager i called 'apt' also there id called 'dpkg'
  - package managers are a free-software user interface that work with an online server to handle the installatrion and debian-based linux distributions.
  ## the repository
  this is the site/server kali use to upload the package.
  ## Advanced package tool/apt/
  - apt is free-software user interface that work with an online server to handle the installation and removal of software on debian and debian-based linux distribution.used for online and offline purpose.
  - the old 'apt' used as 'apt-get'
  - systax
    
    - sudo apt update
    - sudo apt search software
    - sudo apt install software
    - sudo upgrade
    - sudo apt purge software
    ## package dependecies
- a software can be built based on another program called 'modules'
## Dpkg/ Debian package manager/
- dpkg is an offline package mnaging program
- packages on debian have an extension".deb"
- 

