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

## COMMAND AND OUTPUT
<img width="227" height="29" alt="image" src="https://github.com/user-attachments/assets/6c099af0-dd11-40fd-a64d-fcff545a6d7a" />

Remove the directory "my-folder"

## COMMAND AND OUTPUT
<img width="215" height="31" alt="image" src="https://github.com/user-attachments/assets/2958a3a1-6030-4436-a339-595b9178fb48" />


Create the file Rose.txt

## COMMAND AND OUTPUT
<img width="353" height="228" alt="image" src="https://github.com/user-attachments/assets/e05a8f52-b0f8-463f-9250-a83115b52a7c" />


Create the file hello.txt using echo and redirection

## COMMAND AND OUTPUT
<img width="323" height="106" alt="image" src="https://github.com/user-attachments/assets/d6b30bbb-fc41-484e-8106-39e37671666d" />

Copy the file hello.txt into the file hello1.txt

## COMMAND AND OUTPUT
<img width="235" height="56" alt="image" src="https://github.com/user-attachments/assets/dbf659f1-8cb6-4946-b6a7-9839e627dc6a" />

Remove the file hello1.txt

## COMMAND AND OUTPUT
<img width="265" height="104" alt="image" src="https://github.com/user-attachments/assets/b2665cb1-2063-40d3-a78d-1f63bbf03e1a" />

List out the file hello1.txt in the current directory

## COMMAND AND OUTPUT
<img width="397" height="446" alt="image" src="https://github.com/user-attachments/assets/4c478ca9-c4ed-4646-84a2-ad8dd4e2ce76" />

List out all the associated file extensions 

## COMMAND AND OUTPUT
<img width="300" height="129" alt="image" src="https://github.com/user-attachments/assets/d700c408-4ab7-4ea3-812b-6e7c379323d0" />


Compare the file hello.txt and rose.txt

## COMMAND AND OUTPUT

## Exercise 2: Advanced Batch Scripting
Create a batch file named on the desktop. The batch file need to have a variable assigned with a desired name for ex. name="John" and display as "Hello, John".





## OUTPUT
<img width="227" height="53" alt="image" src="https://github.com/user-attachments/assets/7cde5fd3-9620-4ead-ba6f-6850979678f9" />



Create a batch file  on the desktop that checks whether a user-input number is odd or not. The script should:
Prompt the user to enter a number.
Calculate the remainder when the number is divided by 2.
Display whether the number is odd or not.
Ask the user if they want to check another number.
Repeat the process if the user enters Y, and exit with a thank-you message if the user enters N.
Handle invalid inputs for the continuation prompt (Y/N) gracefully.



## OUTPUT

<img width="318" height="127" alt="image" src="https://github.com/user-attachments/assets/25f0fcca-4cc0-41f9-833f-f31322e80c9f" />




Write a batch file that uses a FOR loop to iterate over a sequence of numbers (1 to 5) and displays each number with the label Number:. The output should pause at the end.




## OUTPUT

<img width="243" height="100" alt="image" src="https://github.com/user-attachments/assets/87bdaea7-0214-48cf-9a84-c83ea566ec3e" />




Write a batch script to check whether a file named sample.txt exists in the current directory. If the file exists, display the message sample.txt exists. Otherwise, display sample.txt does not exist. Pause the script at the end to view the result.

Instructions:
Use the IF EXIST conditional statement.
Make sure the script works for files located in the same directory as the batch file.
Use pause to keep the command window open after displaying the message.
Expected Output (if the file exists):

## OUTPUT
<img width="392" height="127" alt="image" src="https://github.com/user-attachments/assets/0cba2430-4e75-46b6-8458-e1eddf6cd380" />


Write a batch script that displays a simple menu with three options:
Say Hello – Displays the message Hello, World!
Create a File – Creates a file named newfile.txt with the content This is a new file
Exit – Exits the script with a goodbye message
The script should repeatedly display the menu until the user chooses to exit. Use goto statements to handle menu navigation.


## OUTPUT
<img width="242" height="229" alt="image" src="https://github.com/user-attachments/assets/43da2ca2-0b25-440f-bde0-b373ac279c74" />



# RESULT:
The commands/batch files are executed successfully.

