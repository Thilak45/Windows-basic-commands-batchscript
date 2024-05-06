# Windows-basic-commands-batchscript
Ex08-Windows-basic-commands-batchscript

# AIM:
To execute Windows basic commands and batch scripting

# DESIGN STEPS:

### Step 1:

Navigate to any Windows environment installed on the system or installed inside a virtual environment like virtual box/vmware 

### Step 2:

Write the Windows commands / batch file
Save each script in a file with a .bat extension.
Ensure you have the necessary permissions to perform the operations.
Adapt paths as needed based on your system configuration.
### Step 3:

Execute the necessary commands/batch file for the desired output. 




# WINDOWS COMMANDS:
## Exercise 1: Basic Directory and File Operations
Create a directory named "MyLab" on the desktop.


## COMMAND AND OUTPUT

Change to the "MyLab" directory and create an empty text file named "MyFile.txt" inside it.
%userprofile%\Desktop\MyLab

![image](https://github.com/Thilak45/Windows-basic-commands-batchscript/assets/138849161/b1701934-4ec1-4c0b-a986-3b2fd8c208e0)

## COMMAND AND OUTPUT

List the contents of the "MyLab" directory.
%userprofile%\Desktop\MyLab
![image](https://github.com/Thilak45/Windows-basic-commands-batchscript/assets/138849161/8f6bd397-d32b-4d60-af5e-bd217ffe7d91)
![image](https://github.com/Thilak45/Windows-basic-commands-batchscript/assets/138849161/5281058c-2c2a-4c8b-a97b-0ab9a799068b)

## COMMAND AND OUTPUT

Copy "MyFile.txt" to a new folder named "Backup" on the desktop.
%userprofile%\Desktop\MyLab
![image](https://github.com/Thilak45/Windows-basic-commands-batchscript/assets/138849161/159395c1-7520-451c-a090-e7ec794d8e41)

## COMMAND AND OUTPUT

Move the "MyLab" directory to the "Documents" folder.
%userprofile%\Desktop\Backup mkdir %userprofile%\Desktop\Backup
![image](https://github.com/Thilak45/Windows-basic-commands-batchscript/assets/138849161/bd1a0b57-c18c-4280-8299-6fd213b2753e)
![image](https://github.com/Thilak45/Windows-basic-commands-batchscript/assets/138849161/fe660d9d-06ea-4bbd-8776-c92ccd98d711)


## COMMAND AND OUTPUT
mv Myfile.txt %userprofile%\Documents
![image](https://github.com/Thilak45/Windows-basic-commands-batchscript/assets/138849161/30c011e2-ff7d-4052-896a-b8670db93edb)

## Exercise 2: Advanced Batch Scripting
Create a batch script named "BackupScript.bat" that creates a backup of files with the ".docx" extension from the "Documents" folder to a new folder named "DocBackup" on the desktop.

@echo off mkdir %userprofile%\Desktop\DocBackup copy %userprofile%\Documents*.docx %userprofile%\Desktop\DocBackup echo Backup completed successfully!
## OUTPUT
![image](https://github.com/Thilak45/Windows-basic-commands-batchscript/assets/138849161/b3ac02a5-526e-47fc-9bb6-16333d46fafb)

# RESULT:
The commands/batch files are executed successfully.

