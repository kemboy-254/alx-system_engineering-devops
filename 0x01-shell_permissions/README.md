**SHELL PERMISSIONS TASKS**
0. My name is betty  
	 Switches the current user to the user betty  

1. Who am I  
	 Prints the effective username of the current user.  

2. Groups  
	 Prints all the groups the current user is part of.  

3. New owner  
	 Changes the owner of the file hello to the user betty.  

4. Empty  
	 creates an empty file called hello.  

5. Execute  
	 adds execute permission to the owner of the file hello.  

6. Multiple permissions  
	 adds execute permission to the owner and the group owner, and read permission to other users, to the file hello.  

7. Everybody  
	 adds execution permission to the owner, the group owner and the other users, to the file hello  

8. James Bond  
	 sets the permission to the file hello as follows:  

		 Owner: no permission at all  
		 Group: no permission at all  
		 Other users: all the permissions   

9. John Doe  
	 sets the mode of the file hello to this:  

		 -rwxr-x-wx 1 julien julien 23 Sep 20 14:25 hello  

10. Look in the mirror  
	 sets the mode of the file hello the same as olleh’s mode.  

11. Directories  
	  adds execute permission to all subdirectories of the current directory for the owner, the group owner and all other users while not changing regular files.  

12. More Directories  
	 creates a directory called my_dir with permissions 751 in the working directory.  

13. Change group  
	 changes the group owner to school for the file hello  