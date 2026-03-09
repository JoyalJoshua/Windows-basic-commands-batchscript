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
<img width="402" height="94" alt="Screenshot 2026-03-09 135214" src="https://github.com/user-attachments/assets/179fbe20-18f3-4fb7-9239-0f13406c4eaf" />

Remove the directory "my-folder"

## COMMAND AND OUTPUT
<img width="377" height="78" alt="Screenshot 2026-03-09 135242" src="https://github.com/user-attachments/assets/f98d49ee-681c-4e48-9bea-eca29e92f576" />


Create the file Rose.txt

## COMMAND AND OUTPUT
<img width="447" height="129" alt="Screenshot 2026-03-09 135300" src="https://github.com/user-attachments/assets/fc095be8-6d57-4380-a381-53d97c54ec98" />


Create the file hello.txt using echo and redirection

## COMMAND AND OUTPUT
<img width="531" height="114" alt="Screenshot 2026-03-09 135318" src="https://github.com/user-attachments/assets/afc80a75-2633-49d0-b59c-0853b14b468c" />

Copy the file hello.txt into the file hello1.txt

## COMMAND AND OUTPUT
<img width="503" height="142" alt="Screenshot 2026-03-09 135338" src="https://github.com/user-attachments/assets/3d91d5ae-3404-4a05-a34d-6a5dc2826091" />

Remove the file hello1.txt

## COMMAND AND OUTPUT
<img width="460" height="123" alt="Screenshot 2026-03-09 135353" src="https://github.com/user-attachments/assets/6edb48c7-b431-44c7-bd67-ca60ef50aec0" />

List out the file hello1.txt in the current directory

## COMMAND AND OUTPUT
<img width="483" height="227" alt="Screenshot 2026-03-09 135421" src="https://github.com/user-attachments/assets/0d997339-e347-4619-980b-3e4da0d146bd" />

List out all the associated file extensions 

## COMMAND AND OUTPUT
<img width="564" height="891" alt="Screenshot 2026-03-09 135534" src="https://github.com/user-attachments/assets/cb59db60-2b03-4351-a950-fc379c43bc1a" />


Compare the file hello.txt and rose.txt

## COMMAND AND OUTPUT
<img width="537" height="249" alt="Screenshot 2026-03-09 135552" src="https://github.com/user-attachments/assets/f115dbbd-e36e-4a13-8008-629c2722d6ba" />

## Exercise 2: Advanced Batch Scripting
Create a batch file named on the desktop. The batch file need to have a variable assigned with a desired name for ex. name="John" and display as "Hello, John".





## OUTPUT

<img width="488" height="109" alt="Screenshot 2026-03-09 141224" src="https://github.com/user-attachments/assets/530b0b10-da46-4dd5-9fc3-d17e51cf553b" />


Create a batch file  on the desktop that checks whether a user-input number is odd or not. The script should:
Prompt the user to enter a number.
Calculate the remainder when the number is divided by 2.
Display whether the number is odd or not.
Ask the user if they want to check another number.
Repeat the process if the user enters Y, and exit with a thank-you message if the user enters N.
Handle invalid inputs for the continuation prompt (Y/N) gracefully.



## OUTPUT
<img width="722" height="534" alt="Screenshot 2026-03-09 141844" src="https://github.com/user-attachments/assets/fc360621-3397-4982-9e90-b3e92b336684" />




Write a batch file that uses a FOR loop to iterate over a sequence of numbers (1 to 5) and displays each number with the label Number:. The output should pause at the end.




## OUTPUT
<img width="461" height="199" alt="Screenshot 2026-03-09 142147" src="https://github.com/user-attachments/assets/abc6c859-ace0-4f4e-80ab-b7a33a5c4a33" />




Write a batch script to check whether a file named sample.txt exists in the current directory. If the file exists, display the message sample.txt exists. Otherwise, display sample.txt does not exist. Pause the script at the end to view the result.

Instructions:
Use the IF EXIST conditional statement.
Make sure the script works for files located in the same directory as the batch file.
Use pause to keep the command window open after displaying the message.
Expected Output (if the file exists):

## OUTPUT

<img width="499" height="84" alt="Screenshot 2026-03-09 142437" src="https://github.com/user-attachments/assets/7287db8e-0d1c-46d2-a67e-3e05fe845ed1" />

Write a batch script that displays a simple menu with three options:
Say Hello – Displays the message Hello, World!
Create a File – Creates a file named newfile.txt with the content This is a new file
Exit – Exits the script with a goodbye message
The script should repeatedly display the menu until the user chooses to exit. Use goto statements to handle menu navigation.


## OUTPUT
<img width="452" height="394" alt="Screenshot 2026-03-09 142801" src="https://github.com/user-attachments/assets/f3dcfd61-afa8-4afc-9e78-88f5c57d0a11" />



# RESULT:
The commands/batch files are executed successfully.

