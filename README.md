 Task 1: Read a File and Handle Errors
Objective:
This task demonstrates how to read the contents of a file and handle potential errors if the file does not exist.

How it works:

The program attempts to open a file named sample.txt in read mode.

If the file exists, it reads and prints each line one by one.

If the file does not exist, it catches the FileNotFoundError and prints a user-friendly error message.


Task 2: Write and Append Data to a File
Objective:
This task shows how to write user input to a file, append more data, and finally read and display the complete file content.

How it works:

Takes input from the user and writes it to a new file output.txt using write ('w') mode.

Prompts the user for additional input and appends it to the same file using append ('a') mode.

Reads the updated file and prints its content line by line.
