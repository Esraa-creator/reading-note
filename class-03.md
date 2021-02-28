The ordered list is created with
the ol element.

Each item in the list is placed
between an opening li tag
and a closing /li tag.

The unordered list is created
with the ul element.

The definition list is created with
the dl element

 dt This is used to contain the term
being defined 

dd This is used to contain the
definition

Lists can be nested inside one another.

The overflow property tells the
browser what to do if the content
contained within a box is larger
than the box itself

hidden
This property simply hides any
extra content that does not fit in
the box.
scroll
This property adds a scrollbar to
the box so that users can scroll
to see the missing content.

Loops
Loops check a condition. If it returns true, a code block will run, and so on will repeat until the condition returns fslse.
Types of Loops:
For, used to run code a specific numbers of times.

While, if you don’t know how many times the code should run.

Do While, similar to the while loops, but it will always run the statements inside the curly braces at least once, even the condition evalutes to fslse.

For Loop uses a counter as a condution, and this tell the code to run a specified numbers of times.

Statements of For Loop:
Initialization var i= 0;
Condition i < 9;
Update i++

SWITCH STATEMENTS
A switch statement starts with a variable called the switch value. Each case indicates a possible value for this variable and the code that should run if the variable matches that value.

IF ELSE VS IF SWITCH :
IF ELSE
There is no need to provide an else option. (You can just use an if statement.)
With a series of if statements, they are all checked even if a match has been found (so it performs more slowly than switch).
SWITCH
You have a default option that is run if none of the cases match.
If a match is found, that code is run; then the break statement stops the rest of the switch statement running (providing better performance than multiple if statements).
While Loop will continue to run for as long as the condition in parentheses is true

ARRAYS : (Links to an external site.)
Is a special type of variable. It doesn’t just store one value; it stores a list of values

var colors;

colors = [‘white’, ‘black’, ‘ custom ‘];

VALUES IN ARRAYS : (Links to an external site.)
Values in an array are accessed as if they are in a numbered list. It is important to know that the numbering of this list starts at zero (not one).

INDEX VALUE 0 ‘white’ 1 ‘black’ 2 ‘custom’
ACCESSING & CHANGING VALUES IN AN ARRAY : (Links to an external site.)
Create the array var colors = [‘white’, ‘black’ , ‘custom’];

Update the third item in the array
colors[2] = ‘beige ‘ ;

Get the element with an id of colors var el = document .getElementByid(‘ colors’) ;

Replace with third item from the array
el .textContent = colors[2];