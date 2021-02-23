A table represents information in a grid format.
Examples of tables include financial reports, TV
schedules, and sports results.

The table element is used
to create a table. The contents
of the table are written out row
by row.
tr
You indicate the start of each
row using the opening tr>tag.
(The tr stands for table row.)
It is followed by one or more
td elements (one for each cell
in that row).
At the end of the row you use a
closing /tr tag.
td
Each cell of a table is
represented using a td
element. (The td stands for
table data.)

The colspan attribute can be
used on a th or td element
and indicates how many columns
that cell should run across.

The headings of the table should
sit inside the thead element.

The body should sit inside the
tbody element.

The footer belongs inside the
tfoot element.

The bgcolor attribute was used
to indicate background colors
of either the entire table or
individual table cells. The value
is usually a hex code

LITERAL NOTATION
A colon separates the key/value pairs.
There is a comma between each key/value pair.

OBJECT CONSTRUCTOR NOTATION
The function can be used to create multiple objects.
The this keyword is used instead of the object name.

The keyword this is commonly used inside functions and objects.
Where the function is declared alters what this means. It always refers
to one object, usually the object in which the function operates.

GLOBAL VARIABLES
All global variables also become properties of the
window object. so when a function is in the global
context, you can access global variables using the
window object, as well as its other properties.

When a function is defined inside an object, it
becomes a method. In a method, this refers to the
containing object.

If a named function has been defined in global
scope, and it is then used as a method of an object,
this refers to the object it is contained within.

In JavaScript, data is represented using name/value pairs.
To organize your data, you can use an array or object to group a set of
related values. In arrays and objects the name is also known as a key.

Arrays can store multiple pieces of information.
Each piece of information is separated by a comma.
The order of the values is important because items
in an array are assigned a number (called an index).

Objects store sets of name/value pairs. They can be
properties (variables) or methods (functions).
The order of them is not important (unlike the array).
You access each piece of data by its key.

built-in objects that represent things like the
browser window and the current web page shown in that window. These
built-in objects act like a toolkit for creating interactive web pages.

An object model is a group of objects, each of
which represent related things from the real world.
Together they form a model of something larger.

JavaScript has five simple (or primitive) data types:
1. String
2. Number
3. Boolean
4. Undefined (a variable that has been declared, but
no value has been assigned to it yet)
5. Null (a variable with no value - it may have had
one at some point, but no longer has a value)

6.0bject
arrays and functions are considered
types of objects.

The Math object has properties and methods
for mathematical constants and functions.