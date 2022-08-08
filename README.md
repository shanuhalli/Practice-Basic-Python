# Python-Basics
for loop, while loop, if elif else

Loops
  There are two types of loops in Python, for and while.

The "for" loop:

  For loops can iterate over a sequence of numbers using the "range" and "xrange" functions. The difference between range and xrange is that the range function returns a new list with numbers of that specified range, whereas xrange returns an iterator, which is more efficient. (Python 3 uses the range function, which acts like xrange). Note that the range function is zero based.

"while" loops:

  While loops repeat as long as a certain boolean condition is met.

"break" and "continue" statements:

  break is used to exit a for loop or a while loop, whereas continue is used to skip the current block, and return to the "for" or "while" statement.

Can we use "else" clause for loops?

  When the loop condition of "for" or "while" statement fails then code part in "else" is executed. If a break statement is executed inside the for loop then the "else" part is skipped. Note that the "else" part is executed even if there is a continue statement.
