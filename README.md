# Bash_shell-commands
## Create,Copy, move,delete, and organize files from the bash shell
- #### How to create directory in Linux commands,We used<ins> mkdir</ins> command.
![image](https://user-images.githubusercontent.com/103019032/162363772-e377e93d-41fb-4e36-adbd-0af6578393a3.png)
- #### Create two files(new_file1,new_file2) inside new_folder.We use <ins>touch</ins> command.
![image](https://user-images.githubusercontent.com/103019032/162367280-c51b5937-5431-4819-ae83-3b2be28bad9f.png)
- #### Now copy files from new_folder to new_folder2.We uses <ins>cp</ins> command.
![image](https://user-images.githubusercontent.com/103019032/162368138-175d2fdc-aaa2-454e-ba05-b39ebef0d5da.png)
- #### Now move files from new_folder to new_folder2.We uses <ins> mv</ins> command.
 ![image](https://user-images.githubusercontent.com/103019032/162369203-f5a8cdf9-3fcd-474b-bf40-fde52e2b4364.png)
- #### Now delete files from new_folder.We use <ins>rm</ins> command.
![image](https://user-images.githubusercontent.com/103019032/162370109-ebf9e7f8-9ba9-4d54-805c-189206a8785d.png)
- #### Now remove directory using <ins>rmdir</ins> command
![image](https://user-images.githubusercontent.com/103019032/162370464-58d392a0-c9dc-478e-88c6-6002630215c5.png)
 ## *Create, view, and edit text files from command output or in an editor*
 - #### Create file using cat command,touch command, redirect command, nano command and vi
 ![image](https://user-images.githubusercontent.com/103019032/162372940-52bc8363-1c89-4dc2-9e9e-e15ddf87ee16.png)
- #### Using nano command we can edit text in nano editor
![image](https://user-images.githubusercontent.com/103019032/162373358-82b505a3-9e9d-49d3-b809-a0cefc1aac2b.png)
- #### If we write the nano command with file name and then enter in nano editor
![image](https://user-images.githubusercontent.com/103019032/162373449-70764526-d82a-4efa-bd9f-0309b67cad87.png)
- #### Using cat command we can view the content of file
![image](https://user-images.githubusercontent.com/103019032/162373848-25542b06-24c5-46a5-b757-274277cf91a9.png)
- #### Using vi command we can edit text in vi editor
![image](https://user-images.githubusercontent.com/103019032/162375536-4472ab44-989d-4c45-b254-ec92a1660d64.png)
- #### If we write the vi command with file name and then enter in vi editor
![image](https://user-images.githubusercontent.com/103019032/162376485-9cbc9645-e2cc-425b-b9ae-bda8b40216a9.png)
- #### Using cat command we can view the content of file
![image](https://user-images.githubusercontent.com/103019032/162376774-ea9ceb80-467b-46fe-a7c0-253aac63007f.png)
## *Manage local Linux users and groups*
- #### To list out all the users in Linux, use the awk command with -F option.
![image](https://user-images.githubusercontent.com/103019032/162377596-48b831ee-c8fb-4fcc-a313-f56633ee3772.png)
- #### Using id command, you can get the ID of any username.
![image](https://user-images.githubusercontent.com/103019032/162377904-88ef65c6-9626-4566-8ef0-4aea53ea2231.png)
- #### The command to add a user. useradd command adds a new user to the directory.
![image](https://user-images.githubusercontent.com/103019032/162378401-3c0919f3-c005-4b9e-9897-da1e1f3dc26a.png)
- #### Using passwd command to assign a password to a user.
![image](https://user-images.githubusercontent.com/103019032/162379207-79036a4e-cb2e-49d8-bb77-ce6a8495f967.png)
- #### Accessing a user configuration file.  
  username : x : user id : user group id : : /home/username : /bin/bash 
![image](https://user-images.githubusercontent.com/103019032/162379535-5a59042c-6230-4565-91c4-7c44e0d21351.png)
- #### The command to change the user ID for a user.  
![image](https://user-images.githubusercontent.com/103019032/162380530-ae6c31cd-9b57-47b5-9811-419bf8bdc4df.png)
 - #### The command to delete a user name. 
 ![image](https://user-images.githubusercontent.com/103019032/162381069-6e26d25c-e821-427f-9565-d5a7cf00780b.png)
## *Set Linux file system permissions on files*
- #### Using ls -l command we can see permission.
 ![image](https://user-images.githubusercontent.com/103019032/162384632-6e5ba402-d2b5-43c5-b794-d9a6f4a86c9b.png)
- #### Using chmod 777 command, give all the permission like read,write and execute.
![image](https://user-images.githubusercontent.com/103019032/162385099-2d8db6a5-0a12-4797-9d87-bd8ab66c41d3.png)
- #### Removing all permission  like read,write and execute from groupuser and other in newfile1
![image](https://user-images.githubusercontent.com/103019032/162385761-54a190a5-945b-4347-ac9f-07afedf1abcf.png)
- #### Giving all permission to user, read write permission to group ,and read permission to other to newfile.txt.
![image](https://user-images.githubusercontent.com/103019032/162386451-e19f29e9-9399-4871-b881-e56563e97e30.png)
## *Obtain information about the system*
- #### The ps command is used to display or view information related to the processes running in a Linux system.
![image](https://user-images.githubusercontent.com/103019032/162398815-895750cd-99c8-4075-a220-e8eaa92ce701.png)
#### The top (table of processes) command shows a real-time view of running processes in Linux 
![image](https://user-images.githubusercontent.com/103019032/162399204-252f6117-7d04-42fe-bba9-dbfcb83e7e60.png)
- #### *control processes running on it*
- ## Killing process using kill command
![image](https://user-images.githubusercontent.com/103019032/162401995-4e330aa4-9df0-4a36-8dcd-d418f88e0fe7.png)
- #### Sending Signals To Processes
![image](https://user-images.githubusercontent.com/103019032/162402524-14dcb6e3-a9c2-4eb8-9ca3-8ac872d0b129.png)
- #### To kill an application using its name, use pkill or killall
![image](https://user-images.githubusercontent.com/103019032/162403335-c6da3e36-eb4a-44e3-97b2-c4413da62547.png)
- #### How to transfer file from one machine to another using scp command
- #### Sending the file
![image](https://user-images.githubusercontent.com/103019032/162409856-7468dc61-05fa-47e6-a1c8-1bfd4630670b.png)
- #### Receiving the file
![image](https://user-images.githubusercontent.com/103019032/162410145-83d89fad-09a4-4307-9d1b-1e27a5c560a8.png)
- #### Installation of Apache2 using sudo apt install apache2 command
![image](https://user-images.githubusercontent.com/103019032/162412603-5785292c-0bc5-4266-a09a-7bf975c0ad49.png)
![image](https://user-images.githubusercontent.com/103019032/162413044-c0fc4eb4-c3ad-4e26-a4ff-e81a9ef31ae4.png)
- #### We can check it out by typing in our IP address for the web server.
![image](https://user-images.githubusercontent.com/103019032/162414520-5f9415d5-8a2e-4d4d-a6c7-da17c44644df.png)
- #### Installion of nginx using sudo apt install nginx command
![image](https://user-images.githubusercontent.com/103019032/162413516-0a18db20-7684-422b-948a-1b5fa6fbbd5d.png)
## ** File system in Linux
- #### df command reports file system disk space usage, to include the file system type on a particular disk partition, use the -T
![image](https://user-images.githubusercontent.com/103019032/162564733-3da75e66-04f7-4c1e-b3e3-264c5443eb19.png)
- #### fsck command is used to check and optionally repair Linux file systems, it can also print the file system type on specified disk partitions.
- #### The flag -N disables checking of file system for errors, it just shows what would be done.
![image](https://user-images.githubusercontent.com/103019032/162564968-7582a092-6582-4c2a-8d70-5e472d243af3.png)
- #### lsblk command displays block devices, when used with the -f option, it prints file system type on partitions as well
![image](https://user-images.githubusercontent.com/103019032/162565071-16463303-e90b-4be3-8ffd-3a5e7fab6ba9.png)
- #### mount command is used to mount a file system in Linux, it can also be used to mount an ISO image, mount remote Linux filesystem and so much more.
![image](https://user-images.githubusercontent.com/103019032/162565254-677f0b1e-479a-4bf9-9234-e23e7f4c7f68.png)
- #### blkid command is used to find or print block device properties
![image](https://user-images.githubusercontent.com/103019032/162565445-77f3cd1f-0026-47bb-beea-985711423d22.png)
- #### blkid command is used to find or print block device properties
![image](https://user-images.githubusercontent.com/103019032/162566087-edce69cd-82a0-4ccd-b83b-d590bd2632a3.png)
- #### file command identifies file type, the -s flag enables reading of block or character files and -L enables following of symlinks
![image](https://user-images.githubusercontent.com/103019032/162566234-67d7b25f-b6ed-4dc0-a027-bb3c8c5e6cf9.png)
- #### The /etc/fstab is a static file system info (such as mount point, file system type, mount options etc) file
![image](https://user-images.githubusercontent.com/103019032/162566531-bb5618c0-31b8-4e1c-a42e-9c89fd25dabe.png)
#### **Hugepages in Linux**
- #### grep Huge /proc/meminfo command to check current huge pages details.you can see the one-page size is 2MB Hugepagesize and a total of 0 pages on the system      HugePages_Total. This huge page size can be increased from 2MB to max 1GB.
![image](https://user-images.githubusercontent.com/103019032/162566792-427227f9-0e60-449d-b4af-0ac020ceb9aa.png)
## Swap in Linux
- #### cat command to see total and used swap size
![image](https://user-images.githubusercontent.com/103019032/162568338-dbe13db5-b117-4697-a873-019cd428beca.png)
- #### We can check the total size and free memory in swap using grep Swap /proc/meminfo
![image](https://user-images.githubusercontent.com/103019032/162568426-88131fcd-a0e5-4ca7-8e52-2b16203d35e3.png)
- #### Look for swap space in Linux using swapon command
![image](https://user-images.githubusercontent.com/103019032/162568650-2fe0b936-f4e3-463e-a8b5-03ea416d113d.png)
- #### Use free command to monitor swap space usage
![image](https://user-images.githubusercontent.com/103019032/162568701-e1817c3d-84f9-4638-8f42-255c9ac6ec56.png)
- #### See swap size in Linux using vmstat command
![image](https://user-images.githubusercontent.com/103019032/162568899-756f1b8e-d91c-4125-9dc4-6cb17ad8c901.png)
## grep command in linux
- #### Case insensitive search : The -i option enables to search for a string case insensitively in the given file. It matches the words like “UNIX”, “Unix”, “unix”. 
![image](https://user-images.githubusercontent.com/103019032/162569419-b6564a1b-ec5d-4f99-9ec5-c5facaf303f1.png)
- #### Displaying the count of number of matches : We can find the number of lines that matches the given string/pattern 
![image](https://user-images.githubusercontent.com/103019032/162569635-ff325978-12bf-4a17-a596-c2f1fc024786.png)
- #### Checking for the whole words in a file 
![image](https://user-images.githubusercontent.com/103019032/162569784-d473ca2d-afd3-48e9-85d9-1b6c7b604c33.png)
- #### Displaying only the matched pattern 
![image](https://user-images.githubusercontent.com/103019032/162569875-840564b4-dc0d-41ad-8f1b-064755bbc02a.png)
- #### Inverting the pattern match : You can display the lines that are not matched with the specified search string pattern using the -v option
![image](https://user-images.githubusercontent.com/103019032/162570566-3418c567-c65f-4c1a-a4e6-1ec522043dfe.png)
- #### Replacing all the occurrence of the pattern in a line
![image](https://user-images.githubusercontent.com/103019032/162572544-90186ff3-346d-4df3-b800-48089f563be9.png)











