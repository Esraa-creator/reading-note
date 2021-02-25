## execution contexts.
The JavaScript interpreter uses the concept of execution contexts.
There is one global execution context; plus, each function creates a new
new execution context. They correspond to variable scope.

Each time a script enters a new execution context, there are two phases
of activity:
* PREPARE
The new scope is created
 Variables, functions, and arguments are created
 The value of the this keyword is determined

* EXECUTE
 Now it can assign values to variables
 Reference functions and run their code
 Execute statements

 In the interpreter, each execution context has its own va ri ables object.
It holds the variables, functions, and parameters available within it.
Each execution context can also access its parent's v a ri ables object.

If a JavaScript statement generates an error, then it throws an **exception**.
At that point, the interpreter stops and looks for exception-handling code.

# Now that you know what an error is and how the browser treats them,
# there are two things you can do with the errors.

# 1: DEBUG THE SCRIPT TO FIX ERRORS
If you come across an error while writing a script
(or when someone reports a bug), you will need to
debug the code, track down the source of the error,
and fix it.

# 2: HANDLE ERRORS GRACEFULLY
You can handle errors gracefully using try, catch,
throw, and f i na 1 ly statement s.

* Debugging is about deduction:
eliminating potential causes of an error.

The console will show you when there is an
error in your JavaScript. It also displays the line
where it became a problem for the interpreter.

You can also just type code into the console
and it will show you a result.

Browsers that have a console have a console object, which has several
methods that your script can use to display data in the console.
The object is documented in the Console API.

## BREAKPOINTS
You can pause the execution of a script on any
line using breakpoints. Then you can check the
va lues stored in variables at that point in time.

## THROWING ERRORS
If you know something might cause a problem for your script, you can
generate your own errors before the interpreter creates them.

Debugging is the process of finding errors. It involves a
process of deduction.

The console helps narrow down the area in which the
error is located, so you can try to find the exact error.

JavaScript has 7 different types of errors. Each creates
its own error object, which can tell you its line number
and gives a description of the error.

If you know that you may get an error, you can handle
it gracefully using the try, catch, finally statements.
Use them to give your users helpful feedback.