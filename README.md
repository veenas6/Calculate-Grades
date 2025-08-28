# Student Grades Management in C

## Overview
This C program allows users to input information for multiple students, including their names and marks for three subjects. It then calculates the total and average marks for each student and displays the results.

## Features
- Store student details using a `struct` (name, marks, total, average)
- Calculate total and average marks for each student
- Accept input for multiple students dynamically
- Display detailed student information with calculated grades

## How It Works
1. The program prompts for the number of students.
2. For each student:
   - Input their full name (including spaces).
   - Input marks for three subjects.
3. It calculates the total and average marks.
4. Displays the information for all students.

## Usage

### Compile
```bash
gcc -o student_grades student_grades.c
