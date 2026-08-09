# student-management-system
add, delete,update,search,display,records,data permently
The Student Management System is a menu-driven C program designed to manage student records.

The program uses structures and file handling to store student information permanently in a file. It allows the user to add, display, search, update, and delete student records.

✨ Features

The program provides the following features:

Add Student – Add a new student record.
Display Students – Display all stored student records.
Search Student – Search for a student using their roll number.
Update Student – Update the name and marks of an existing student.
Delete Student – Delete a student record using the roll number.
Exit – Exit the program.
📝 Student Information

Each student record contains:

Roll Number
Name
Marks

A struct Student is used to store this information.

🛠️ Technologies Used
Programming Language: C
Concepts Used:
Structures
Functions
File Handling
Binary Files
fread() and fwrite()
fseek()
remove()
rename()
Switch Case
Loops
Conditional Statements
📂 Files Used

The program uses the following files:

students.dat
temp.dat
students.dat

This file is used to permanently store student records.

temp.dat

This temporary file is used during the deletion process to create a new file without the deleted student record.

📋 Program Menu
===== STUDENT MANAGEMENT SYSTEM =====
1. Add Student
2. Display Students
3. Search Student
4. Update Student
5. Delete Student
6. Exit
Enter your choice:
🔧 Functions Used

The program is divided into separate functions:

addStudent()
displayStudents()
searchStudent()
updateStudent()
deleteStudent()
addStudent()

Accepts the student's roll number, name, and marks and stores the record in students.dat.

displayStudents()

Reads all student records from the file and displays them.

searchStudent()

Searches for a student using their roll number.

updateStudent()

Finds a student by roll number and updates their name and marks.

deleteStudent()

Deletes a student record by copying all other records into a temporary file and replacing the original file.

▶️ How to Run
Step 1: Compile the program

Using GCC:

gcc student.c -o student
Step 2: Run the program

On Windows:

student.exe

On Linux/macOS:

./student
🎯 Learning Objectives

This project helps in understanding:

How to use structures in C
How to create menu-driven programs
How to work with files in C
How to read and write binary files
How to search and modify records
How to delete records using temporary files
How to organize a program using functions
⚠️ Important Notes
Student records are stored in students.dat.
If no records exist, the program displays "No Records Found!"
A student's roll number is used to search, update, and delete records.
The program continues running until the user selects Exit.
👨‍💻 Author

Muskan Sarai

📄 Purpose

This project is created for educational purposes to practice structures, functions, file handling, and menu-driven programming in C.
