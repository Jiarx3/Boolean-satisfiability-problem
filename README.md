# Boolean-satisfiability-problem
A simple Boolean satisfiable problem (SAT) C++ solution code, is the sophomore data structure and algorithm course project.

1. Questions
Given m expressions involving n boolean variables, figure out how to assign values to these n variables so that all m boolean expressions are true at the same time. There is not always one answer to this question.

2. Program specific format and requirements
2.1. Enter the format.
(1) The first integer is the number of variables n.
(2) The following integer is the number of expressions m.
(3) Then it is m group of integers, each group is three integers, each integer represents the relevant variable and whether it is its non-value; The size of the value indicates the variable, and the positive and negative indicate whether the value is non-value.
2.2. Output format. Press x1,x2,... ,xn order, output the value of each variable, using 1 for true and 0 for false. Leave a space before each output.
2.3. Other relevant information and requirements.
• It can be assumed that any given test example has at least one set of solutions.
• Number of variables n≤300, expression number m≤1200.
• For any given test example, the solution must be given within 5 seconds.
