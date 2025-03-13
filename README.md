# Student Management System

## Overview
This C++ program implements a simple Student Management System that allows users to:
1. Enter student details (name, roll number, age)
2. Record marks for 5 subjects
3. Calculate and display the total marks and percentage

## Features
- Student information management
- Test score tracking
- Result calculation
- Formatted console output with color coding

## Class Structure
The program consists of three main classes:
- **Student**: Stores basic student information
- **Test**: Manages test scores and contains a Student object
- **Result**: Calculates the final results based on Test data

## How to Use
1. Compile the code using a C++ compiler:
   ```
   g++ FriendlyStudent.cpp -o student_management
   ```

2. Run the executable:
   ```
   ./student_management
   ```

3. Follow the prompts to enter:
   - Student details (name, roll number, age)
   - Marks for 5 subjects

4. The program will display:
   - Student details
   - Marks for each subject
   - Total marks (out of 500)
   - Percentage score

## Example Output
```
 |------------------------------|
 |        STUDENT INPUT         |  <-input started...
 |------------------------------|
 | Name      : Rudra
 |
 | Roll No   : 21051079
 |
 | Age       : 21
 |------------------------------|
 |------------------------------|
 |          MARKS INPUT         |
 |------------------------------|
 | Mark[0]      : 89
 |
 | Mark[1]      : 85
 |
 | Mark[2]      : 90
 |
 | Mark[3]      : 95
 |
 | Mark[4]      : 99
 |------------------------------|  <-input terminated...


 |------------------------------|
 |           TEST INFO          |  <-output
 |------------------------------|
 |           STUDENT            |
 |------------------------------|
 | Name      : Rudra
 |
 | Roll No   : 21051079
 |
 | Age       : 21
 |------------------------------|
 |------------------------------|
 |             MARKS            |
 |------------------------------|
 | Mark[0]      : 89
 |
 | Mark[1]      : 85
 |
 | Mark[2]      : 90
 |
 | Mark[3]      : 95
 |
 | Mark[4]      : 99
 |------------------------------|
 |------------------------------|
 |            RESULT            |
 |------------------------------|
 | Total Marks      : 458/500
 |
 | Percentage       : 91%
 |------------------------------|
```

## Technical Notes
- The program uses friend classes to demonstrate object-oriented principles
- Console output is formatted with ASCII box characters
- Color coding is used for different sections (green for input, yellow for output)
- The program initializes the total marks to 0 but doesn't explicitly initialize percentage

## Requirements
- C++ compiler with support for STL (Standard Template Library)
- Terminal that supports ANSI color codes for optimal display
