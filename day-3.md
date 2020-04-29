
**Day-3** 

Note ...
- We can host our website using S3, only static pages can be uploaded.
- If you want to use dynamic pages, then need to use react js plain javascript won't work here.
- Charges for hosting depends on the size of file uploaded

### Url description of website hosted using S3 :

Example :

 https://100-bucket.s3-amazonaws.com/website/index.html
  
 1. *https://*                      -   protocol prefix ('s' represents secured)
 2. *100-bucket*                    -   Bucket Name 
 3. *.s3-amazonaws.com/*            -   Domain  
 4. *website/index.html*            -   Path of file        
  
---  

***Command for Remote login***

General command
       
       ssh username@ip-address   
- After this enter and provide password, you can login.
         
- But this method of username-password pair increases the chances of **Brute Forcce Attack** (anyone can pass all possible combinations     of password and can hack the system).
- So,Linux uses the combination of private and public key arrived, while windows still use user-passwrd pair for authentication.
- This **public key is on AWS instance** in our case it is on ec2. 
- And **Pricate Key is nothing but the .pem** that is generated.

1. For windows  we are using Mobaxterm

- But, mobaxterm also uses the above shell command in backend, it is just that we cannot see it because we are using direct UI.

2. For Linux
       
       ssh -i <.pem>username@ip-address

---

## Linux Commands 

Conventions : 

 /# - Represents root
 
 ~  - Home directory of current user
 
 /  - Root directory 
 
 vi - Tool/program used in linux to create file

 **Command** | **Description** |
 --- | --- |
 cd<dir_name>| change directory |
 cd /|Takes to root|
 cd ~|Takes to root|
 pwd|print working diorectory|
 ls|lists the directory/file|
 mkdir <dir_name>|Make directory|
 clear|clears terminal|
 exit|Exit from current shell|
 vi <file_name>|create a file and enters in insert mode|
 esc|exit from current mode|
 :w|Write and save file|
 :q|Quit,exit file|
 :wq|Save and Exit|
 :wq!|Write and Quit Forcefully|
 cat <file_name>|Display file content|
 
---

## PATH

**Absolute Pathname**|**Relative Pathname**|
Begins with the root directory and follows the tree branch till desired dir/file|Begins with current directory and goes till root.|
Always starts with **/**| **.** represents current working dir. and **..** represents parent directory of workking directory.|
Example: /home/user|Example: ../data/demo.txt| 

*Q. Which one should we use?*

-> It depends on the situation, in some we have to use absolute pathname while in others we nay need to use relative pathname.

---

## Service 3: Database as Service		

*RDS - Relational Database Service*

- We can create database using differet engine options :
  1. MySQL
  2. SQL server
  3. Oracle
  4. PostgreSql
  5. Aurora
- We can connect to this database from our local machine.
- Security groups can be created differently.
- Can stop the instance whenever not in use thus by saving credits.


