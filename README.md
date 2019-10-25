# COMP110 Worksheet 4

Please edit this README.md file with your answers to the worksheet questions.

## Question 1

### a
A|B|C|A AND B|NOT C|(A AND B) AND (NOT C)
|-|:-:|:-:|:-------:|:----:|--------------------:|
0|0|0|	0|	1|	0
1|0|0|	0|	1|	0
0|1|0|	0|	1|	0
1|1|0|	1|	1|	1
0|0|1|	0|	0|	0
1|0|1|	0|	0|	0
0|1|1|	0|	0|  0
1|1|1|	1|	0|  0


### b
A	B	C	NOT C	B AND (NOT C)	NOT (B AND NOT C)	A AND (NOT B AND NOT C)
0	0	0	1	0	1	0
1	0	0	1	0	1	1
0	1	0	1	1	0	0
1	1	0	1	1	0	0
0	0	1	0	0	1	0
1	0	1	0	0	1	1
0	1	1	0	0	1	0
1	1	1	0	0	1	1


### c
A	B	C	NOT B	A OR (NOT B)	A OR C	(A OR NOT B) AND (A OR C)
0	0	0	1	1	0	0
1	0	0	1	1	1	1
0	1	0	0	0	0	0
1	1	0	0	1	1	1
0	0	1	1	1	1	1
1	0	1	1	1	1	1
0	1	1	0	0	1	0
1	1	1	0	1	1	1


### d
A	B	C	D	NOT C	B OR (NOT C)	NOT (B OR NOT C)	NOT A	D AND (NOT A)	(D AND NOT A) AND (NOT B OR NOT C)	(D AND (NOT A AND NOT B OR NOT C) AND A
0	0	0	0	1	1	0	1	0	0	0
1	0	0	0	1	1	0	0	0	0	0
0	1	0	0	1	1	0	1	0	0	0
1	1	0	0	1	1	0	0	0	0	0
0	0	1	0	0	0	1	1	0	0	0
1	0	1	0	0	0	1	0	0	0	0
0	1	1	0	0	1	0	1	0	0	0
1	1	1	0	0	1	0	0	0	0	0
0	0	0	1	1	1	0	1	1	0	0
1	0	0	1	1	1	0	0	0	0	0
0	1	0	1	1	1	0	1	1	0	0
1	1	0	1	1	1	0	0	0	0	0
0	0	1	1	0	0	1	1	1	1	0
1	0	1	1	0	0	1	0	0	0	0
0	1	1	1	0	1	0	1	1	0	0
1	1	1	1	0	1	0	0	0	0	0


## Question 2
All images for this question are in the microsoft word document called "worksheet 4"
### a

### b

### c

### d

## Question 3

### a
A	B	A OR B	NOT (A OR B)
0	0	0	1
1	0	1	0
0	1	1	0
1	1	1	0

A	B	NOT A	NOT B	(NOT A) AND (NOT B)
0	0	1	1	1
1	0	0	1	0
0	1	1	0	0
1	1	0	0	0

### b
A	B	A AND B	NOT (A AND B)
0	0	0	1
1	0	0	1
0	1	0	1
1	1	1	0

A	B	NOT A	NOT B	(NOT A) OR (NOT B)
0	0	1	1	1
1	0	0	1	1
0	1	1	0	1
1	1	0	0	0

### c
A	B	C	A AND B	A AND C	(A AND B) OR (A AND C)
0	0	0	0	0	0
1	0	0	0	0	0
0	1	0	0	0	0
1	1	0	1	0	1
0	0	1	0	0	0
1	0	1	0	1	1
0	1	1	0	0	0
1	1	1	1	1	1

A	B	C	B OR C	A AND (B OR C)
0	0	0	0	0
1	0	0	0	0
0	1	0	1	0
1	1	0	1	1
0	0	1	1	0
1	0	1	1	1
0	1	1	1	0
1	1	1	1	1

### d
A	B	C	A OR B	A OR C	(A OR B) AND (A OR C)
0	0	0	0	0	0
1	0	0	1	1	1
0	1	0	1	0	0
1	1	0	1	1	1
0	0	1	0	1	0
1	0	1	1	1	1
0	1	1	1	1	1
1	1	1	1	1	1

A	B	C	B AND C	A OR (B AND C)
0	0	0	0	0
1	0	0	0	1
0	1	0	0	0
1	1	0	0	1
0	0	1	0	0
1	0	1	0	1
0	1	1	1	1
1	1	1	1	1

## Question 4

### a
NOT (A AND B) = (NOT A) OR (NOT B)

A	B	A AND B	NOT (A AND B)
0	0	0	1
1	0	0	1
0	1	0	1
1	1	1	0

A	B	NOT A	NOT B	(NOT A) OR (NOT B)
0	0	1	1	1
1	0	0	1	1
0	1	1	0	1
1	1	0	0	0

### b
(A AND B) OR (C AND B) = (A OR C) AND B, where A is type(x) == int, B is x > 7 and C is type(x) == float

A	B	C	A AND B	C AND B	(A AND B) OR (C AND B)
0	0	0	0	0	0
1	0	0	0	0	0
0	1	0	0	0	0
1	1	0	1	0	1
0	0	1	0	0	0
1	0	1	0	0	0
0	1	1	0	1	1
1	1	1	1	1	1

A	B	C	A OR C	(A OR C) AND B
0	0	0	0	0
1	0	0	1	0
0	1	0	0	0
1	1	0	1	1
0	0	1	1	0
1	0	1	1	0
0	1	1	1	1
1	1	1	1	1

### c
For the first set of code the program checks to see if x and y are equal to 0,
if both are then the function “do_something” is activated, if x or y is not 0
then the program prints “Do nothing”. Where as in the second set of code the
program checks if x and y are not 0, if they are not then the program prints
“Do nothing”, if x and y are both 0 then the program actives the function
“do_something”. So both programs active the same task but they both go about
checking the conditions in different ways the first program checks for the
condition first by using an if statement while the second program checks for
the inverse of the condition by using an else statement.

### d
A OR (B AND C) = B AND (A OR C), where A is x>10, B is x>0 and C is y>0.

A	B	C	B AND C	A OR (B AND C)
0	0	0	0	0
1	0	0	0	1
0	1	0	0	0
1	1	0	0	1
0	0	1	0	0
1	0	1	0	1
0	1	1	1	1
1	1	1	1	1

A	B	C	A OR C	B AND (A OR C)
0	0	0	0	0
1	0	0	1	0
0	1	0	0	0
1	1	0	1	1
0	0	1	1	0
1	0	1	1	0
0	1	1	1	1
1	1	1	1	1

