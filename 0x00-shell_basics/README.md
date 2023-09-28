file: functionality

0-current_working_directory:	prints the absolute path name of the current working directory
1-listit:			displays current directory contents
2-bring_me_home:		changes the working directory to the user’s home directory
3-listfiles:			displays current directory contents in a long format
4-listmorefiles:		displays current directory contents in a long format including hidden files
5-listfilesdigitonly:		displays current directory contents in a long format including hidden files
				with user and group ids displayed numerically
6-firstdirectory:		creates a directory named "my_first_directory" in /tmp
7-movethatfile:			moves the file "betty" from /tmp to /tmp/my_first_directory
8-firstdelete:			deletes the file "betty"
9-firstdirdeletion:		deletes the directory "my_first_directory" in /tmp
10-back:			changes the working directory to the previous one
11-lists:			list all files in the current directory, the parent, and /boot respectively
				in a long format including hidden files
12-file_type:			prints the type of the file "iamafile" in /tmp
13-symbolic_link:		Creates a symbolic link "__ls__" to /bin/ls in the current working directory
14-copy_html:			copies all the HTML files from the current working directory to the parent
				that did not exits or are newer
