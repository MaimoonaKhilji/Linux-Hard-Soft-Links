# Linux-Hard-Soft-Links

1.	Create a directory CS_link_test in /home
2.	Cd CS_link_test
3.	In CS_link_test folder create 3 files as File_A, File_B & File_C as:
-	echo Banana > File_A 
-	echo Apple > File_B 
-	echo Orange > File_C 
What happens when above commands are executed
Output:  three files are created with respective text.

4.	In CS_link_test create a new directory named as dirA
5.	Mv File_C into dirA
6.	See the inode numbers of individual files as
-	ls -i File_A
-	ls –i File_B
-	ls –i File_C
7.	Now create hardlink  named as hl_FileA for File_A in and check the inode number for created hardlink. Is it same as inode number of File_A? if yes why?
8.	What is the file type and permissions of created hard link?
9.	Now create softlink for File_B named as sl_fileb  and check the inode number for created softlink. Is it same as inode number of File_B? if yes why? If no why?
10.	What is the file type and permissions of created soft link?
11.	Append content of  hl_FileA as “new Banana”. Does it affect content of File_A? If yes why ?
12.	Append content of  sl_FileB as “new Apple”. Does it affect content of File_B? If yes why ? 
13.	Unlink FileA from hl_FileA? what happened?
14.	Similarly delete softlink sl_File_B from File_b.

