What is an expression in JavaScript?
an expression is a valid unit of code that resolves to a value. There are two types of expressions: those that have side effects (such as assigning values) and those that purely evaluate.

The expression x = 7 is an example of the first type. This expression uses the = operator to assign the value seven to the variable x. The expression itself evaluates to 7.

The expression 3 + 4 is an example of the second type. This expression uses the + operator to add 3 and 4 together and produces a value, 7. However, if it's not eventually part of a bigger construct (for example, a variable declaration like const z = 3 + 4), its result will be immediately discarded — this is usually a programmer mistake because the evaluation doesn't produce any effects.

Why would we use a loop in our code?
Loops are used in JavaScript to perform repeated tasks based on a condition. Conditions typically return true or false . A loop will continue running until the defined condition returns false .
here are many different kinds of loops, but they all essentially do the same thing: they repeat an action some number of times. (Note that it's possible that number could be zero!)

When does a (for) loop stop executing?
A for loop repeats until a specified condition evaluates to false. The JavaScript for loop is similar to the Java and C for loop.



How many times will a while loop execute?
While loop =I need to run a loopwhile a condition is true
=Do while
The following while loop iterates as long as n is less than 3:

JS
Copy to Clipboard
let n = 0;
let x = 0;
while (n < 3) {
  n++;
  x += n;
}
