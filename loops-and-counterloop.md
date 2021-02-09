### JavaScript supports different kinds of  loops:

1. for - loops through a block of code a number of times.A for loop repeats until a specified condition evaluates to false. The JavaScript for loop is similar to the Java and C for loop.
A for statement looks as follows:
for ([initialExpression]; [conditionExpression]; [incrementExpression])
  statement

2. while - loops through a block of code while a specified condition is true
while statement
A while statement executes its statements as long as a specified condition evaluates to true. A while statement looks as follows:
while (condition)
  statement
If the condition becomes false, statement within the loop stops executing and control passes to the statement following the loop.
The condition test occurs before statement in the loop is executed. If the condition returns true, statement is executed and the condition is tested again. If the condition returns false, execution stops, and control is passed to the statement following while.
To execute multiple statements, use a block statement ({ ... }) to group those statements.

3. do/while - also loops through a block of code while a specified condition is true
A do...while statement looks as follows:
do
  statement
while (condition);
statement is always executed once before the condition is checked. (To execute multiple statements, use a block statement ({ ... }) to group those statements.)
If condition is true, the statement executes again. At the end of every execution, the condition is checked. When the condition is false, execution stops, and control passes to the statement following do...while.


## loop counters

In computer programming a loop counter is the variable that controls the iterations of a loop (a computer programming language construct).

1. initialization
The initialization expression initializes the loop. The initialization expression is executed only once when the loop starts. You typically use the initialization is to initialize a counter variable. If you use the var keyword to declare the counter variable, the variable will have either function or global scope. In other words, you can reference the counter variable after the loop ends. However, if you use the let keyword to declare the counter variable, the variable will have a blocked scope, which is only accessible inside the loop.

2. condition
The condition is an expression that is evaluated once before every iteration. The statement inside the loop is executed only when the condition evaluates to true. The loop is terminated if the condition evaluates to false. Note that the condition is optional. If you omit it, the for loop statement considers it as true.

3. The increment operator ( ++ ) increments (adds one to) its operand and returns a value.