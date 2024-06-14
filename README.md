
# What is Linux?
  It is a family of open-source Unix operating systems based on the Linux kernel.

# Basic commands in Linux
1. check IP address of server
   
    hostname -i
   
    ifconfig
   
    ip addr
   
    ip addr show


2. Know current working directory
   
     pwd

3.To display all the file with timestamp and who is owner of file, size, name of the file 

      ls -ltr 

4. To Create file

     touch <file name>
     
     vi <file name>
     
     vim <file name>

5. delete files
   
     $rm –f  filename 
     
6. delete directory
   
     rmdir filename

7.  print no of CPU in system
    
     nproc

8. show memory info
    
    lscpu

9. To know how much memory is free in computer
    
   free

10. To know disk size
    
    df

11. To display all the specification of computer
    
    top

12.To print active process on your machine 

     ps -ef

13.To print particular data in process. (grep)

     The grep filter searches a file for a particular pattern of characters and displays all lines that contain that pattern.

    ps -ef | grep “anything u want to print”

 note-> | -pipe command
 What ever output is giving in first command, its input to second command 






