# StudentDirectory
Contains Java files from a prior Java assignment from COP 3330C while attending Florida State College at Jacksonville (FSCJ). 

## Description
This is a small simple console application which represents a student directory.

## What it does?
The application builds an in-memory directory of students, where each student has a name and an age. 
Once students are added, the program can iterate over the entire directory and look up individual students by name. 
The `main()` runs a self-contained demonstration of all of this, so no input is required to see it work.

## The Classes
The `Student` class represents one student. It stores the student’s name and age.
The `StudentDirectory` class represents a list of students. It uses an ArrayList to store student objects.

## How the application works
The `main()` in `StudentDirectory` does the following:
Creates an empty `StudentDirectory`.
Adds three students: Alice (20), Bob (22), and Charlie (19).
Iterates over the directory and prints each student.
Searches for "Bob", who exists, and prints the found student.
Searches for "David", who does not exist, and prints a "not found" message.

## How to compile and run the program
Because the two files use the same package name: `package edu.fscj.cop3330c`, ensure both are stored in the same folder.
You can use any IDE of our choosing. Or you can use the command line terminal by changing the directory to same as the Java files, 
then by entering the following bash/shell commands:
`javac edu/fscj/cop3330c/Student.java edu/fscj/cop3330c/StudentDirectory.java` to compile
then
`java edu.fscj.cop3330c.StudentDirectory` to run the Student Directory application.

## Expected Output
```
Student List:
Student{name='Alice', age=20}
Student{name='Bob', age=22}
Student{name='Charlie', age=19}
Found student: Student{name='Bob', age=22}
Student with name David not found.
```
