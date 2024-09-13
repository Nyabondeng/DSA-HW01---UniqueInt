**Unique Integers Assignment**
Task Description
The goal of this assignment is to read a list of integers from an input file, identify the unique integers, and generate an output file containing these unique integers in sorted order.

**Instructions**
Input File: The input file contains one integer per line (positive or negative). Variations in input lines (whitespace, invalid lines) should be handled as specified.
Output File: The output file should contain a list of unique integers from the input, sorted in increasing order.


**Handling Variations:**
Skip lines with no inputs or white spaces.
Skip lines with two integers separated by white space.
Skip lines containing non-integer input (e.g., alphabets, punctuation marks, floating point numbers).


**Approach**
Create a data structure (e.g., a set) to store unique integers.
Read each line from the input file.
Parse the line to extract the integer.
Add the integer to the set if it’s valid (skip invalid lines).
After reading all lines, sort the unique integers.
Write the sorted integers to the output file.
**Usage**
Compile or run your code (e.g., UniqueInt.cpp).
Provide the input file path and output file path as arguments.
Verify that the output file contains the correct list of unique integers.
