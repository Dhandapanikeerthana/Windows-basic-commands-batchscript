# Windows-basic-commands-batchscript
Ex08-Windows-basic-commands-batchscript

# AIM:
To execute Windows basic commands and batch scripting

# DESIGN STEPS:

### Step 1:

Navigate to any Windows environment installed on the system or installed inside a virtual environment like virtual box/vmware 

### Step 2:

Write the Windows commands / batch file . Save each script in a file with a .bat extension. Ensure you have the necessary permissions to perform the operations. Adapt paths as needed based on your system configuration.
### Step 3:

Execute the necessary commands/batch file for the desired output. 




# WINDOWS COMMANDS:
## Exercise 1: Basic Directory and File Operations
Create a directory named "my-folder"

```
mkdir %userprofile%\Desktop\MyLab
```
![Screenshot 2025-05-22 233114](https://github.com/user-attachments/assets/a3f71764-5d7e-412e-99c7-55bede8ebf79)


## COMMAND AND OUTPUT
List the contents of the "MyLab" directory.
```
cd %userprofile%\Desktop\MyLab

```
![Screenshot 2025-05-22 234139](https://github.com/user-attachments/assets/8fb8de03-b106-45b4-a2e0-c8bb116b582e)

![Screenshot 2025-05-22 234542](https://github.com/user-attachments/assets/f4cd8b19-251a-44b5-9da8-5deb623c49dd)



## COMMAND AND OUTPUT
Copy "MyFile.txt" to a new folder named "Backup" on the desktop.

```
dir %userprofile%\Desktop\MyLab
```
![Screenshot 2025-05-22 235011](https://github.com/user-attachments/assets/0f5f9249-4d3e-4b9c-8a0f-b85a42d69a9f)




## COMMAND AND OUTPUT
copy MyFile.txt %userprofile%\Desktop\Backup
```
mkdir %userprofile%\Desktop\Backup
```
![Screenshot 2025-05-22 235228](https://github.com/user-attachments/assets/a36dc1cb-e45e-4c75-8daf-0e7eb33d18e4)

![Screenshot 2025-05-22 235245](https://github.com/user-attachments/assets/0af36eb4-2f95-4552-b29f-6023d1736da0)



## COMMAND AND OUTPUT
Remove the file hello1.txt

```
mv Myfile.txt %userprofile%\Documents
```

![Screenshot 2025-05-22 235605](https://github.com/user-attachments/assets/d99f324b-1859-4a7d-aa14-bfaa6ead32f9)



## Exercise 2: Advanced Batch Scripting
Create a batch file named on the desktop. The batch file need to have a variable assigned with a desired name for ex. name="John" and display as "Hello, John".

```
@echo off
mkdir %userprofile%\Desktop\DocBackup
copy %userprofile%\Documents\*.docx %userprofile%\Desktop\DocBackup
echo Backup completed successfully!
```




## OUTPUT
![Screenshot 2025-05-22 235715](https://github.com/user-attachments/assets/055c44ee-57f3-4117-b751-6a78ff525fac)




Create a batch file  on the desktop that checks whether a user-input number is odd or not. The script should:
Prompt the user to enter a number.
Calculate the remainder when the number is divided by 2.
Display whether the number is odd or not.
Ask the user if they want to check another number.
Repeat the process if the user enters Y, and exit with a thank-you message if the user enters N.
Handle invalid inputs for the continuation prompt (Y/N) gracefully.



## OUTPUT




Write a batch file that uses a FOR loop to iterate over a sequence of numbers (1 to 5) and displays each number with the label Number:. The output should pause at the end.




## OUTPUT




Write a batch script to check whether a file named sample.txt exists in the current directory. If the file exists, display the message sample.txt exists. Otherwise, display sample.txt does not exist. Pause the script at the end to view the result.

Instructions:
Use the IF EXIST conditional statement.
Make sure the script works for files located in the same directory as the batch file.
Use pause to keep the command window open after displaying the message.
Expected Output (if the file exists):

## OUTPUT


Write a batch script that displays a simple menu with three options:
Say Hello – Displays the message Hello, World!
Create a File – Creates a file named newfile.txt with the content This is a new file
Exit – Exits the script with a goodbye message
The script should repeatedly display the menu until the user chooses to exit. Use goto statements to handle menu navigation.


## OUTPUT



# RESULT:
The commands/batch files are executed successfully.

