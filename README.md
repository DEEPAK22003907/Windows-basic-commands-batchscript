# EX 08: Windows-basic-commands-batchscript

## AIM:
To execute Windows basic commands and batch scripting

## DESIGN STEPS:

### Step 1:

Navigate to any Windows environment installed on the system or installed inside a virtual environment like virtual box/vmware 

### Step 2:

Write the Windows commands / batch file
Save each script in a file with a .bat extension.
Ensure you have the necessary permissions to perform the operations.
Adapt paths as needed based on your system configuration.
### Step 3:

Execute the necessary commands/batch file for the desired output. 

### Name : DEEPAK S
### Register Number : 212222040032

## WINDOWS COMMANDS:

## Exercise 1: Basic Directory and File Operations

Create a directory named "MyLab" on the desktop.

## COMMAND AND OUTPUT

Change to the "MyLab" directory and create an empty text file named "MyFile.txt" inside it.

```
mkdir %userprofile%\Desktop\MyLab

```

![Screenshot 2024-05-10 182232](https://github.com/DEEPAK22003907/Windows-basic-commands-batchscript/assets/119404520/9a91c595-66c8-4c5a-92cb-cda54f5eeb15)



```
cd %userprofile%\Desktop\MyLab
```

![Screenshot 2024-05-10 182546](https://github.com/DEEPAK22003907/Windows-basic-commands-batchscript/assets/119404520/41bb2236-25b9-4764-b828-78e950cebf08)



```
type nul > MyFile.txt

```
![Screenshot 2024-05-10 182624](https://github.com/DEEPAK22003907/Windows-basic-commands-batchscript/assets/119404520/cbadd6b0-5d17-4f8c-a933-af4db538b463)


## COMMAND AND OUTPUT

List the contents of the "MyLab" directory.
```
dir %userprofile%\Desktop\MyLab
```

![Screenshot 2024-05-10 182651](https://github.com/DEEPAK22003907/Windows-basic-commands-batchscript/assets/119404520/b7162182-c6a8-4597-a9ac-2974ac5b95af)


## COMMAND AND OUTPUT

Copy "MyFile.txt" to a new folder named "Backup" on the desktop.

```
mkdir %userprofile%\Desktop\Backup

```
![Screenshot 2024-05-10 182722](https://github.com/DEEPAK22003907/Windows-basic-commands-batchscript/assets/119404520/6ae62023-d76c-4054-a833-63f1156c2e65)


```
copy MyFile.txt %userprofile%\Desktop\Backup
```

![Screenshot 2024-05-10 182815](https://github.com/DEEPAK22003907/Windows-basic-commands-batchscript/assets/119404520/64737946-0942-48bf-a501-b6dde8808308)



## COMMAND AND OUTPUT

Move the "MyLab" directory to the "Documents" folder.

```
mkdir %userprofile%\Desktop\Documents
```

```
move MyLab Documents
```
![Screenshot 2024-05-10 182848](https://github.com/DEEPAK22003907/Windows-basic-commands-batchscript/assets/119404520/e60ac51e-fddc-4141-a478-a9796b7b403b)


## Exercise 2: Advanced Batch Scripting
Create a batch script named "BackupScript.bat" that creates a backup of files with the ".docx" extension from the "Documents" folder to a new folder named "DocBackup" on the desktop.

```
@echo off
mkdir %userprofile%\Desktop\DocBackup
copy %userprofile%\Documents\*.docx %userprofile%\Desktop\DocBackup
echo Backup completed successfully!

```

## OUTPUT

![Screenshot 2024-05-10 182912](https://github.com/DEEPAK22003907/Windows-basic-commands-batchscript/assets/119404520/a992aa64-b587-4a31-9f68-93102ec20e62)



# RESULT:
The commands/batch files are executed successfully.
