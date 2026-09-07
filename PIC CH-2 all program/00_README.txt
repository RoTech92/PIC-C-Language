C LANGUAGE FUNDAMENTAL PROGRAMS - TURBO C++ EDITION (TXT FORMAT)
====================================================================

This folder has 30 separate .txt files, one per program from your PDF,
each rewritten to run in the old Turbo C++ (DOS/Borland) IDE. They are
saved as plain .txt so they open directly in Notepad on any system.

WHAT WAS CHANGED IN EVERY FILE (vs. the Standard C version in your PDF)
------------------------------------------------------------------------
1. Added:      #include<conio.h>
   Needed for clrscr() and getch(), which are Turbo C++ specific
   (they don't exist in standard/modern C compilers).

2. Changed:    int main()   ->   void main()
   Turbo C++ programs are traditionally written with void main().

3. Added:      clrscr();
   Placed right after the variable declarations. Clears the black
   output screen before new output is printed.

4. Added:      getch();
   Placed at the end, just before the closing brace. This is
   important in Turbo C++ / DOS: without it, the output window can
   flash and close before you get to read it.

5. Removed:    return 0;
   Not needed since void main() does not return a value.

Nothing about the actual logic (if-else, loops, switch, etc.) was
changed - only these Turbo C++ specific additions.

HOW TO USE THESE FILES
------------------------
1. Open any .txt file here in Notepad, select all (Ctrl+A), copy (Ctrl+C).
2. In Turbo C++: File > New, paste the code (Ctrl+V).
3. Save the file with a .c or .cpp extension (Turbo C++ needs this,
   not .txt, to compile).
4. Compile: Alt+F9      Run: Ctrl+F9      View output: Alt+F5

FILE LIST
---------
01_max_of_two.txt              - Find maximum of 2 numbers
02_voting_eligibility.txt      - Check voting eligibility (age >= 18)
03_even_odd.txt                - Check even or odd
04_positive_negative.txt       - Check positive or negative
05_discount_final_payment.txt  - Price x Qty with discount slab
06_leap_year.txt                - Check leap year
07_divisibility_check.txt      - Check divisibility of two numbers
08_max_of_three.txt            - Find maximum of 3 numbers
09_marks_grade_result.txt      - Marks -> total, percentage, result, grade
10_day_name_switch.txt         - Day number -> day name (switch-case)
11_positive_negative_zero.txt  - Check positive, negative, or zero
12_print_1_to_n.txt            - Print 1 to N
13_print_cubes.txt             - Print cubes 1..N
14_print_odd_numbers.txt       - Print first N odd numbers
15_left_triangle_symbol.txt    - Left-aligned triangle of a symbol
16_right_align_triangle.txt    - Right-aligned number triangle
17_diamond_shape.txt           - Diamond pattern of a symbol
18_multiplication_table.txt    - Multiplication table of a number
19_fibonacci_series.txt        - Fibonacci series, N terms
20_square_cube_table.txt       - 1-10 with square and cube
21_sum_of_10_numbers.txt       - Sum of 10 user-entered numbers
22_power_xy.txt                 - x raised to the power y
23_sum_of_digits.txt           - Sum of digits of a number
24_reverse_number.txt          - Reverse a number
25_palindrome_check.txt        - Check palindrome number
26_armstrong_check.txt         - Check Armstrong number
27_prime_check.txt             - Check prime number
28_primes_upto_n.txt           - All primes up to N
29_armstrong_upto_n.txt        - All Armstrong numbers up to N
30_factorial.txt                - Factorial of a number
