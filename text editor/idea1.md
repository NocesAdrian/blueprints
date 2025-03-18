# Text Editor
This is my idea for making a text editor

# Goals
1. open a file
2. edit the file content
3. save the file
4. display all names of the files that exist that has been created or modified

# scope and limitation
1. will not make a functional file manager
2. will not include renaming a file
3. will not include advance features

# data flow
-> fileName input -> request to get the fileName input value -> save to a variable -> sanitize the file name -> check if it has extension -> if not add .txt as extension 
-> if fileName input is empty -> rrequire a fileName if not it wont be save.
-> content input -> request to get the fileName input value -> save to a variable -> put content into the file 
-> default display content and file name