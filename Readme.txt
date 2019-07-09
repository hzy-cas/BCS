-----------Zhenyu Huang, July 2019--------------------------------

This is a windows version of the BCS implementation.

1. Double click BCS.exe to execute the program.

2. You should input the name of the file which contains the input polynomial system.

Note that the input file and BCS.exe should be in the same folder.
For example:  input present.txt by keyboard


3. The input polynomial should be written as the following form:

a) variables are written as x1, x3, x100, x999; (the index of the variable should be less than 99999) 

b) x1x2 or x1*x2 both can represent "x1 times x2";

c) brackets "(" and ")" can be used;

d) each polynomial should be ended by "," or ";" ;

e) the last polynomial should be ended by ".";

f) some examples can be found in the folder benchmarks


4. The first step of the solving process is pre-elimination, 
that is eliminating the leading variables of the input linear polynomials by substitution until no new linear polynomials generated
After pre-elimination, the number of non-linear polynomials is presented by "Num of Polynomials"


5. After solving, the result will be output in "result.txt", the result is represented by monic triangular sets, and different triangular sets are separated by "**********"


6. the timing result and some other information is stored in "time.txt"

