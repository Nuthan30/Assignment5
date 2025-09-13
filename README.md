# Assignment5
Task 1:

A basic Python script that demonstrates how to write, append, and read content in a text file named Output.txt. 
This project is a useful, hands-on example for understanding the different file modes in Python.

Usage
To run this script, you will need Python 3.
Make sure the write_append.py file is in your desired directory.
Open a terminal or command prompt in that directory.
Execute the script with the following command:
  Bash
  python write_append.py
The program will then guide you through the process by asking for text input for both writing and appending.

Script Breakdown
The script first opens Output.txt in write mode ('w'). 
This action overwrites any existing content in the file with the new text you provide.
Next, it opens the same file in append mode ('a').
This adds new data to the end of the file without erasing the previous content.
Finally, it opens the file in read mode ('r') to display the final, combined content of the file.
This simple script provides a clear demonstration of how these three common file modes function and affect a file's content.


Task 2:

This project features a simple Python script (dict.py) that demonstrates how to effectively use a dictionary for data storage and retrieval.
It allows a user to look up a student's marks by name and handles cases where the name is not found, making it an excellent example for beginners learning about dictionaries and conditional logic.

How to Use
To run the script, you'll need Python 3.
Clone the repository:
  Bash
  git clone https://github.com/your-username/your-repository-name.git
  cd your-repository-name
Run the script from your terminal:
  Bash
  python dict.py
The program will prompt you to enter a student's name, then display their marks or a "not found" message.

What the Code Does
The dict.py script performs three main actions:
Creates a Dictionary: It initializes a dictionary called student_marks where keys are student names and values are their corresponding marks.
Handles User Input: It prompts the user to enter a name and stores the input in a variable.
Performs a Search: Using an if...else statement, it checks if the entered name exists as a key in the student_marks dictionary.
If found, it retrieves and prints the marks associated with that key.
If not found, it prints a "Student not found" message.
This script is a clear, practical illustration of using dictionaries for efficient data lookups and shows how to include basic error handling in your programs.

