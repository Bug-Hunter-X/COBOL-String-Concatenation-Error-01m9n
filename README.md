# COBOL String Concatenation Bug
This repository demonstrates a common error in COBOL related to string concatenation and shows how to solve it.

The bug involves attempting to directly concatenate a numeric variable with a string literal. This is not directly supported in COBOL and will lead to errors or incorrect output.

The solution shows how to correctly convert the numeric value to a string before performing the concatenation using the `MOVE` verb and appropriate data types.

## How to run
1. Compile the COBOL code in `bug.cob` using a COBOL compiler (e.g., GnuCOBOL). 
2. Run the compiled executable.
3. Observe the incorrect or unexpected output. 
4. Compile the COBOL code in `bugSolution.cob`.
5. Run the compiled executable.  Note the correct output. 