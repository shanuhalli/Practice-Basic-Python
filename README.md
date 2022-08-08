# Python-Basics
for loop, while loop, if elif else

Loops: There are two types of loops in Python, for and while.

1. "for" loop: For loops can iterate over a sequence of numbers using the "range" and "xrange" functions. The difference between range and xrange is that the range function returns a new list with numbers of that specified range, whereas xrange returns an iterator, which is more efficient. (Python 3 uses the range function, which acts like xrange). Note that the range function is zero based.

2. "while" loops: While loops repeat as long as a certain boolean condition is met.

3. "break" and "continue" statements: break is used to exit a for loop or a while loop, whereas continue is used to skip the current block, and return to the "for" or "while" statement.

Can we use "else" clause for loops? When the loop condition of "for" or "while" statement fails then code part in "else" is executed. If a break statement is executed inside the for loop then the "else" part is skipped. Note that the "else" part is executed even if there is a continue statement.

Conditional Statements in Python: Decision-making in a programming language is automated using conditional statements, in which Python evaluates the code to see if it meets the specified conditions.

The conditions are evaluated and processed as true or false. If this is found to be true, the program is run as needed. If the condition is found to be false, the statement following the If condition is executed.

Python has six conditional statements that are used in decision-making:

1. If Statement:
The If statement is the most fundamental decision-making statement, in which the code is executed based on whether it meets the specified condition. It has a code body that only executes if the condition in the if statement is true. The statement can be a single line or a block of code.

2. If Else Statement:
This statement is used when both the true and false parts of a given condition are specified to be executed. When the condition is true, the statement inside the if block is executed; if the condition is false, the statement outside the if block is executed.

3. If…Elif..else Statement:
In this case, the If condition is evaluated first. If it is false, the Elif statement will be executed; if it also comes false, the Else statement will be executed.

4. Nested IF Statement:
A Nested IF statement is one in which an If statement is nestled inside another If statement. This is used when a variable must be processed more than once. If, If-else, and If…elif…else statements can be used in the program. In Nested If statements, the indentation (whitespace at the beginning) to determine the scope of each statement should take precedence.

5. Nested IF Statement:
A Nested IF statement is one in which an If statement is nestled inside another If statement. This is used when a variable must be processed more than once. If, If-else, and If…elif…else statements can be used in the program. In Nested If statements, the indentation (whitespace at the beginning) to determine the scope of each statement should take precedence.

6. Short Hand if-else statement:
It is used to mention If-else statements in one line in which there is only one statement to execute in both if and else blocks. In simple words, If you have only one statement to execute, one for if, and one for else, you can put it all on the same line.
