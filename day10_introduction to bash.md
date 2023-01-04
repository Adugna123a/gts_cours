# **Introduction to BASH scripting**
## what is bash script
- it is a shell, that used to interarct whith your karnel.
- ## **what is script**
   - **script** is a file that contain shell commands.
- the original is sh - Bourne shell
## use of Bash
  - Script develop
  - simpliying tasks
  - simplyifing your linux ability
  - Developing hacking script
  ## starting with Bash
  - Bash file can have exetension ".sh" but you can use without ".sh".
  ## Displaying output
  - to start every bash scripts use **shebang**.
    -  #! /bin/bash
-  display in text editor
   -  echo "hellow adugna"
- to run project type this your terminal
  - /bin/bash file.sh
## Variables
- Bash variable is the some of python variables, with the same execption.
- sytaxt 
  - variable_name = value
  - name = adugna
  
 echo "your name is $name"
-
- bash variable is string by default.
- The set command can be used to assign values to positional parameters.
## System Variables 
- system variables is declared by the system.
  ## **Variables & Data Types**
  -  As we saw, the previous method they create strings only.
    - So to create other data types we use declare.
    - Arrays
  
        a) Arrays are lists or tuples on python.

        b) Syntax: 

            i) var=(“list1” “list2” “list3” “list4)
            ii) TO display echo 
                (1) ${var[0]}
            iii) To get all the elements 
                (1) ${var[@]}
            iv) To get the indexes 
                (1) ${!var[@]}
            v) To get the length 
                (1) ${#var[@]}
            vi) To add element to the array 
                (1) var[4]=”list5”
            vii) To remove from the array 
                (1) unset var[3]
## **Bash input**
- on bash we have two methods to accept the input.
  - Read function
  - Arguments
 ## **1) Bash Read**
read used to accept inputs while the script is running.

read -p "text"

read -sp "text" hidden display text file

read -a var for accept array
## **1) Arguments**
these helps to get input before the script starts.
echo "your name :$1"
echo "your father name is $2"
## **Bash sleep**
- Sleep used to make a good waiting on our script.
-Syntax: 
    - sleep 2s
  ## **Operation**
● To do mathematical operations you have to do $(( expression ))

● we will use let keyword for assigning variable

        A) Arithmetic Operations
                a) Addition $(( a + b ))
                b) Subtraction $(( a - b ))
                c) Multiplication $(( a * b ))
                d) Division $(( a / b ))
                e) Exponential $(( a ** b ))
                f) Modulo $(( a % b ))
        B) Assignment Operations 
                a) Increment “let a+= 3”
                b) Decrement “ let a-= 3”
                c) Multiply “ let a*= 3 “
                d) Divide “ let a/=3 “
        C) Comparison operation
Alphabetic comparison   ----------- -->Sign comparison
- Greater Than => -gt   --------->   ●  >
- Less Than => -lt--------------->● <
- Greater than and equals to => -ge----->●  >=
- Less than and equals too => -le------>● <=
- Equal => -eq-------------------------->● =
- Not equal => -ne--------------------->● !=

## **if else codition**
- on bash we dont use indentation but we closed by "fi"
  






