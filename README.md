# tryhackme-learning
All my TryHackMe notes, Linux commands , networking basics , writeups , and learning progress
This repository contains my structured, detailed, and well-documented notes from TryHackMe Linux Fundamentals and other rooms.

It includes:

|Essential Linux Commands|
|Linux Operators|

---
2. Linux Commands

Navigation

|Command	|   Description |
|--------|---------------|
| pwd | Prints current working directory. |
 |ls	|       List files & directories.|
 |ls -l	 |  Long format listing.|
 |ls -a	   |Show hidden files. |
 |cd <path> |Change directory.|
 |cd ..	   |Go back one directory.|
 |cd ~	   |  Home directory.|



---

File & Directory Management

|Command	 |       Description|
|-----------|----------|
|mkdir <dir>	     | Create directory.|
|rmdir <dir>	    |  Remove empty directory.|
|touch <file>	   | Create empty file.|
|cp <src> <dst>	  |Copy files.|
|cp -r <src> <dst>|	Copy directories.|
|mv <src> <dst>	  |Move/rename.|
|rm <file>	     |   Delete file.|
|rm -r <dir>	|      Delete directory recursively.|



---

Viewing Files

|Command	 |       Description|
|------------ |------------------------|
|cat <file>	   | Print file content.|
|less <file>	|    View file interactively.|
|head <file>	 |   First 10 lines.|
|tail <file>	  |  Last 10 lines.|
|tail -f <file>	|Live updates from file.|



---

Searching & Finding

Command	                   Description

grep "text" file   	       Search text.
grep -r "text" dir      	 Recursive search.
grep -i	                   Case insensitive search.
find /path -name file.txt	 Find files.



---

Permissions & Ownership

Command	               Description

chmod 755 file	       Change permissions.
chmod +x file	         Add execute permission.
chown user:group file	 Change owner.



---

System Information

Command	  Description

whoami	 Shows current user.
uname    -a	System/kernel info.
top	     Process monitor.
ps aux	 Running processes.
df -h	   Disk usage.
du -h	   Folder/file size.
free -h	 Memory usage.



---

Networking

Command	    Description

ip           a	Network interfaces.
ifconfig	   Legacy interface tool.
ping host	  Check connectivity.
ss -tulnp	  Show active ports.
ssh user@ip	 SSH login.



---

Compression

Command	             Description

tar -xf file.tar	   Extract tar.
zip -r file.zip dir	 Create zip.
unzip file.zip	     Extract zip.



---

Useful Utilities

Command	 Description

history	 Command history.
clear	   Clear terminal.
date	   Show date/time.



---

3. Linux Operators


---

Redirection

Operator	Description

  > 	    Outputoverwrite.
  >>	    Output append.
  <	      Input from file.
  2>	    Error output. 
  &>	    Both stdout + stderr.




---

Chaining

Operator	Description

  ;	      Run sequentially.
  &&	    Run if previous succeeds.
	



---

Arithmetic

Operator	Example

 +	      $((5 + 2))
 -	      $((6 - 3)) 
 *	      $((4 * 2))
 /	      $((8 / 2))
 % 	      $((10 % 3))
 


---

Comparison

Operator	Meaning

-eq	      Equal
-ne	      Not equal
-gt	      Greater
-lt	      Less
-ge	      >=
-le	      <=



---

📄 File Test Operators

Test	Meaning

-f	File exists
-d	Directory exists
-e	Exists
-r	Readable
-w	Writable
-x	Executable



---

🧵 Wildcards

Pattern	Meaning

*	Any characters
?	Single character
[a-z]	Range match
