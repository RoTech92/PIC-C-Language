C LANGUAGE - CH-1 ASSIGNMENT - TURBO C++ EDITION
====================================================

This folder has 10 separate .txt files, one per program from your
Ch-1 Assignment, formatted to run in the old Turbo C++ (DOS/Borland)
IDE. Saved as .txt so every file opens directly in Notepad.

WHAT WAS CHECKED / CHANGED
----------------------------
Most of your original programs (1-8) were already written in proper
Turbo C++ style (void main(), conio.h, clrscr(), getch(), no return
statement) - nothing needed to change there.

Only 2 programs used "int main()" instead of "void main()":
  - Program 9: Swap Two Numbers Without a Third Variable
  - Program 10: Convert Fahrenheit to Celsius
These were changed to "void main()" to match Turbo C++ style and
keep every file consistent. No "return" statement is used anywhere
since void main() does not return a value.

Nothing about the actual logic (formulas, arithmetic, swapping,
etc.) was changed - only this main()/void consistency fix.

HOW TO USE THESE FILES
------------------------
1. Open any .txt file here in Notepad, select all (Ctrl+A), copy (Ctrl+C).
2. In Turbo C++: File > New, paste the code (Ctrl+V).
3. Save the file with a .c or .cpp extension (Turbo C++ needs this,
   not .txt, to compile).
4. Compile: Alt+F9      Run: Ctrl+F9      View output: Alt+F5

FILE LIST
---------
01_print_name.txt                  - Print your complete name
02_arithmetic_operations.txt       - Sum, difference, product, quotient, remainder
03_simple_interest.txt             - Simple interest calculation
04_area_of_circle.txt              - Area of a circle
05_area_of_rectangle.txt           - Area of a rectangle
06_total_percentage_5_subjects.txt - Total & percentage of 5 subjects
07_square_cube.txt                 - Square and cube of a number
08_swap_using_third_variable.txt   - Swap two numbers (with a third variable)
09_swap_without_third_variable.txt - Swap two numbers (without a third variable)
10_fahrenheit_to_celsius.txt       - Convert Fahrenheit to Celsius
