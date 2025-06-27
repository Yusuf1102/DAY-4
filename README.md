📒 Java Notes App – File I/O Project
🧾 Project Overview
This is a simple text-based Notes App built using Java, which allows users to write and read notes using FileWriter, FileReader, and BufferedReader. It demonstrates how to perform basic file input/output operations in Java.

🎯 Objective
Learn how to persist data by writing to and reading from files.

Understand how to use Java I/O classes like FileWriter, FileReader, and BufferedReader.

Build a menu-driven console application using Scanner.

🛠️ Tools & Technologies
Java (JDK 8 or higher)

VS Code / IntelliJ / Any Java IDE

Command Line or Terminal

📂 File Structure
bash
Copy
Edit
NotesApp.java     # Main Java file
notes.txt         # Text file created automatically to store notes
🚀 How to Run
Clone or download this project.

Open the terminal and navigate to the project folder.

Compile the code:

nginx
Copy
Edit
javac NotesApp.java
Run the program:

nginx
Copy
Edit
java NotesApp
🧪 Features
✅ Add a note (appends to notes.txt)

✅ View all saved notes

✅ Handles file creation automatically

✅ Graceful error handling for file I/O

📘 Java Concepts Used
Feature	Description
FileWriter	To write notes into a file (append mode)
FileReader	To read notes character by character
BufferedReader	To read notes line by line (efficient)
Scanner	To get user input from the console
Exception Handling	To manage file errors like FileNotFound

🧠 Learnings & Outcome
Understand the basics of Java File I/O operations.

Learn how to persist data to a file.

Practice exception handling and user interaction in Java.

Build a menu-driven console app.

📌 Sample Notes File (notes.txt)
sql
Copy
Edit
Buy groceries
Finish homework
Call the dentist
