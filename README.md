# Quine McCluskey Algorithm Implementation using C++
Team Members Info: Iman Attia - 900192510, Rawan Hamad - 900192388

This C++ code automates Quine McCluskey algorithm and finds the following:

The code reads in and evaluates a boolean function  using its minterms and don’t care terms as decimal numbers.
Th inputs are provided by a text file which has 3 lines: 
The first line : number of variables 
The second line: the minterms separated by commas (‘,’) 
The third line : the don’t care terms separated by commas (‘,’)

If the input file cannot open an error message is shown
If a number is used for both minterms and don't care, the program prints an error and and it requires you to correct the file and run it again.
If a number exceeds the range of combinations (2^n) variables
The code outputs the columns of the implication table, the prime implicants, the esstential prime implicants, and the minterms that are not covered by the essential PIs.

To build and use the code:
Put the text file with the correct format with the source file and then run the program 
