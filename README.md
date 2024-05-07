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
```
mkdir %userprofile%\Desktop\MyLab
```

![image](https://github.com/SAIDARSHINI27072005/Windows-basic-commands-batchscript/assets/147474227/ead4844f-0893-44ff-b14b-b42927527be5)



## COMMAND AND OUTPUT

List the contents of the "MyLab" directory.
```
%userprofile%\Desktop\MyLab
```

![image](https://github.com/SAIDARSHINI27072005/Windows-basic-commands-batchscript/assets/147474227/58398f59-deda-4113-b053-910ecb4b8166)
![image](https://github.com/SAIDARSHINI27072005/Windows-basic-commands-batchscript/assets/147474227/048b21ad-2940-4f6e-8ea6-5282c55d1eb3)



## COMMAND AND OUTPUT

Copy "MyFile.txt" to a new folder named "Backup" on the desktop.
```
%userprofile%\Desktop\MyLab
```

![image](https://github.com/SAIDARSHINI27072005/Windows-basic-commands-batchscript/assets/147474227/2465ae8f-4bb9-4488-9a4c-fbdc1b050417)


## COMMAND AND OUTPUT

Move the "MyLab" directory to the "Documents" folder.
```
mkdir %userprofile%\Desktop\Backup mkdir %userprofile%\Desktop\Backup
```

![image](https://github.com/SAIDARSHINI27072005/Windows-basic-commands-batchscript/assets/147474227/c98ca4b7-65e0-405e-abb8-9ab12fa5f404)

![image](https://github.com/SAIDARSHINI27072005/Windows-basic-commands-batchscript/assets/147474227/a4aa8243-5ccc-49f9-ae83-3ec5a5ea5eee)


## COMMAND AND OUTPUT
```
mv Myfile.txt %userprofile%\Documents
```
![image](https://github.com/SAIDARSHINI27072005/Windows-basic-commands-batchscript/assets/147474227/13c88d1e-bbf8-4071-8ccd-04600efc8723)


## Exercise 2: Advanced Batch Scripting
Create a batch script named "BackupScript.bat" that creates a backup of files with the ".docx" extension from the "Documents" folder to a new folder named "DocBackup" on the desktop.


```
@echo off mkdir %userprofile%\Desktop\DocBackup copy %userprofile%\Documents*.docx
%userprofile%\Desktop\DocBackup echo Backup completed successfully!

```

## OUTPUT

![image](https://github.com/SAIDARSHINI27072005/Windows-basic-commands-batchscript/assets/147474227/56619f03-f7b0-4cae-aaa7-ac0a4e6e5ec1)




# RESULT:
The commands/batch files are executed successfully.

