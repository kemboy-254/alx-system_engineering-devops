# SHELL PERMISSIONS TASKS  
### 0. My name is betty  
		 su betty - Switches the current user to the user betty  

### 1. Who am I  
		 id -un - Prints the effective username of the current user.  

### 2. Groups  
		 id -Gn - Prints all the groups the current user is part of.  

### 3. New owner  
		 chown betty hello - Changes the owner of the file hello to the user betty.  

### 4. Empty  
		 touch hello - creates an empty file called hello.  

### 5. Execute  
		 chmod u+x hello - adds execute permission to the owner of the file hello.  

### 6. Multiple permissions  
		 chmod ug+x,o+r hello - adds execute permission to the owner and the group owner, and read permission to other users, to the file hello.  

### 7. Everybody  
		 chmod a+x hello - adds execution permission to the owner, the group owner and the other users, to the file hello  

### 8. James Bond  
		 chmod 007 hello - sets the permission to the file hello as follows:  

			 Owner: no permission at all  
			 Group: no permission at all  
			 Other users: all the permissions   

### 9. John Doe  
		 chmod 753 hello - sets the mode of the file hello to this:  

			 -rwxr-x-wx 1 julien julien 23 Sep 20 14:25 hello  

### 10. Look in the mirror  
		 chmod --reference=olleh hello - sets the mode of the file hello the same as olleh’s mode.  

### 11. Directories  
		  chmod -R ugo+X . - adds execute permission to all subdirectories of the current directory for the owner, the group owner and all other users while not changing regular files.  

### 2. More Directories  
		 mkdir -m 751 my_dir - creates a directory called my_dir with permissions 751 in the working directory.  

### 13. Change group  
		 chgrp school hello - changes the group owner to school for the file hello  

### 14. Owner and group  
		 chown vincent:staff * - changes the owner to vincent and the group owner to staff for all the files and directories in the working directory.  

### 15. Symbolic links  
		  chown -h vincent:staff _hello - changes the owner and the group owner of _hello to vincent and staff respectively.  

### 16. If only  
		 chown --from=guillaume betty hello - changes the owner of the file hello to betty only if it is owned by the user guillaume.  

### 17. Star Wars  
		 telnet towel.blinkenlights.nl - a script that will play the StarWars IV episode in the terminal.