# Student Management System

## Overview
A Java console application designed to manage student records. The system utilizes memory-based data structures to store and manipulate student data during runtime. 

## Features
* Add Student: Inputs a new student record into the system. Includes strict format validation for IDs, names, and email addresses to prevent invalid data entry.
* List Students: Outputs all currently stored student records.
* Search Student: Queries the system for a specific student using their unique ID and outputs the corresponding record if found.
* Remove Student: Deletes a specific student record from the system based on their unique ID.
* Exit: Terminates the application loop.

## Technical Details
* Language: Java
* Storage: java.util.ArrayList
* Input Handling: java.util.Scanner
* Validation Rules (java.util.regex.Pattern):
    * ID: Must match the pattern ^NUM\d{3}$ (e.g., NUM123).
    * Name: Must contain only letters and spaces, matching the pattern ^[A-Za-z ]{3,30}$.
    * Email: Must match the standard email address pattern ^[A-Za-z0-9._%+-]+@[A-Za-z0-9.-]+\.[A-Za-z]{2,}$.

## Usage
1. Compile the Main.java source file using a Java compiler.
2. Execute the compiled Main class.
3. Navigate the system by entering the integer corresponding to the desired menu option (1-5).
4. Provide string or integer inputs as prompted by the console for subsequent operations.
