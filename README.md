# UbuntuCommands
Basic Ubuntu Commands

Command 1: pwd >> Print the current working directory. 

Command 2: ls  >> Print all the available directories and files in the present working directory.
				
			 ls -a >> Include hidden files and directory also.
			 ls -l >> Get detail info about files and directory.
			 ls -al >> Include hidden files and directory with detail info.
			 ls -R >> Get subdirectories and files of a directory.

Command 3: cd  >> Most used commands of Ubuntu. There are multiple use of this command.
			 cd /  >> Change directory to root.
			 cd    >> Change the present directory to the home directory.
			 cd Desktop >> Change the pwd to Desktop.
			 				cd directoryName

Command 4: mkdir >> Create a new directory.
				
				mkdir directoryName
				rmdir directoryName >> Remove od Delete directory.
				mv old_directory_name new_directory_name >> Rename a directory.
				rmdir directory_name >> Remove empty directory.
				rm -r directory_name >> Delete directories and their contents, including all files and 	subdirectories.
				rm -rf directory_name >> Force delete.
				cp -r source_directory destination_directory >> Copy a directory and its contant.
				cp -r source_directory . >> Copy a directory and its contant same directory(creating a duplicate).

Command 5: touch fileName.extention >> Create an empty file.
					vim/nano fileName.extention >> Text editors for editing files.
					cat fileName.extention >> Display the contents of a file.
					rm filename.extention >> Delete files.
					cp source_file destination >> Copy a file using cp command.

Command for System Information:
		
		> uname -a : Display system Information 
		> free -h  : Display free and used memory.
		> df -h    : Display disk space usage. 

Command user and permissions:
		
		> whoami: Display the current username.
		> sudo: Execute a command with superuser.
			>>
		> chmod: Change file permissions.
			>>chmod options permissionsfileName.extention
				>>>chmod 700 private_file.txt : Give full permition to the owner and no permissions to others.
		> chown: Change file owner.
			>> chown newuser file.txt



File Permission

mkdir -m 777 dirname
Chmod 777 file name

D rwx-rwx-rwx
0 > no permission > - - -
1> execution > - - x
2 > write > - w -
3> ex: + write > - wx
4 > read > r - -
5 > read + ex: > r - x
6 > read + write > rw -
7 >read+write+ex: > rwx


