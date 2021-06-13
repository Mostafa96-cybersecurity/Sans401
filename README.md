# **Sans401**

## Linux Part

### **1. Where is Linux Used ?**
 
 *Linux is a strong OS it has advantages and disadvantages. I mean disadvantages like it's not easy to use you must be familiar with it
 Linux used in big companies, google, youtube, and many companies 
 you can depend on it on the website's server such as apache service 
 the project of Linux comes from UNIX 
 Linux has many types, ubuntu,Redhat,Linux mint*
 
 # Basic commands
 
 # 1- echo
 
 **This command is used for print your input on screen**
   
   **Example**  *(  echo "Hello World" )*
   
   ![echo1](https://user-images.githubusercontent.com/84593266/121801974-f8196180-cbee-11eb-81d6-69ff7032fa1a.PNG)
   
   **note** if you want your input in the same line or your input will not be in newline add option "-n" .
   
   **Example**  *( echo -n "hello" )*
   
   ![echo2](https://user-images.githubusercontent.com/84593266/121803393-31090480-cbf6-11eb-9bc8-d01c0542965a.PNG)
    
   *there is no newline the output is on the same line .*
    
 # 2- man command 
   
   **This Command is used for help**
   
   **Example :** you want to know What does "echo" command or , how to use it . 
   
   **man command** displays the usege of the command you want to know and all option about it .
   
   **the command is three parts** 
     
     - command
     - option
     - argument
   
   **-command :** is the main such as "ls" , "echo" , "cd" , "cp" .
   
   **-option :** it's flag depend on your purpose such as *echo -n "hello World"* the flag here is "-n" you do not want to start a newline . 
   
   **-option part** *" optional not main part "*
   
   **argument** it comes after the command or both command and option for ***Example*** *" cp -r /home/Desktop/ / "*  paths here are arguments . 
   
   **Example** 
   
   ![command](https://user-images.githubusercontent.com/84593266/121805091-729dad80-cbfe-11eb-9603-124e8ece68b3.PNG)
   
   *man command let you know , what are flags and options and how to use the command*
   
   *in the bash shell write "man echo"*
   
   ![man](https://user-images.githubusercontent.com/84593266/121805270-5a7a5e00-cbff-11eb-8419-a6ac0cb251b1.PNG)
    
   *man command show you what does this command can do and the options of command "echo"* 
   
   **Notice :** *there are another way to get help about commands this way is built in command itself such as " -h " , " --help "*
   
   **Example :** *ls --help* 
   
   ![man2](https://user-images.githubusercontent.com/84593266/121805678-f22c7c00-cc00-11eb-974e-5affc453869b.PNG)
   
   **man command :** *show you more information about your command* 
   
   **--help :** *show you litle information*
   
 # 3- ls command 
   
   *this command is used to display the content of the directory*
   
   **Example :**  * write "ls *
     
   ![ls](https://user-images.githubusercontent.com/84593266/121805949-69aedb00-cc02-11eb-9795-2ac3048c7688.PNG)

   *the output show you this directory contain " file " as you see " ls " command make you see what the directory contain*
   
   **ls options :** *ls has many options but we will discuss the most important two option " -a " , " -l " .
   
   **-a :** *this option displays all files and directories even the hidden files .*
   
   **-l :** *this option displays long information about the files and directories such as " time , date , size , owner , permissions , the name of the file .*
   
   **Example -a , -l**
   
   ![ls -a](https://user-images.githubusercontent.com/84593266/121806348-57ce3780-cc04-11eb-90ba-98c952f6e7cd.PNG)

   *-a displays all files , the hidden files start with " . " or " .. " .*
   
   *-l displays more information about the files as you see in the Example .*
   
 # 4- cat command 
   
   *this command is used to display the content of files such as " file.txt "*
   
   **Example :** *i have a file contain "hello world" i want to read the contant of this file .*
   
   *Write " cat file.txt "*
   
   ![cat](https://user-images.githubusercontent.com/84593266/121809144-82be8880-cc10-11eb-8281-1aab6a121d1d.PNG)
   
   *cat command can accept options . for example we want to print the file content with lines .*
   
   *write " cat -n file.txt " > will print the file content with line numbers .*
   
   ![cat1](https://user-images.githubusercontent.com/84593266/121809445-adf5a780-cc11-11eb-908e-df266c7f2298.PNG) 
      
   *you noticed this*
  
   **note :** *the file you want to read not necessary be ended with .txt it could be " file " without .txt extension .*
   
 # 5- touch command 
 
   *this command is very simple it can be used to create files .*
   
  **Example :** *i want to create a file name " new.txt " .* 
  
  *write " touch new.txt ".* 
  
  ![touch](https://user-images.githubusercontent.com/84593266/121809909-915a6f00-cc13-11eb-9a63-284a54891c4b.PNG)

  *touch created the file " new.txt " as you see .*
  
  **note :** *there is more than one command to create files such as ( nano , gedit , vim , pico ) but touch is an easy command .*
    
  
   
    
   
   
                 
   
 
