Class 7

# Programing with JavaScript #

Operators
	* Binary Operators -requires two operands, one before the operator and one after.
		operand1  operator  operand2
	* Unary Operators -requires a single operand, either before or after the operator
		operator operand 
		operand operator
	* Ternary Operator (Conditional Operator)

Operator Types
* Assignment Operator - assigns value to its left operand based on the value of its right operand. The simple assignment operator is equal (=), which assigns the value of its right operand to its left operand. That is, x = y assigns the value of y to x
* Compound Assignment Operators			https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Expressions_and_Operators#assignment_operators
   * Return Value and Chaining
  * Const z = (x = y); // or equivalently: const z = x = y;
  * console.log(z); // Log the return value of the assignment x = y
  * Chaining is evaluated right to left.
* Destructuring -extract data from arrays or objects using a syntax 
* Comparison Operator - compares its operands and returns a logical value based on whether the comparison is true. The operands can be numerical, string, logical, or object values.
* Arithmetic Operator - takes numerical values (either literals or variables) as their operands and returns a single numerical value. The standard arithmetic operators are addition (+), subtraction (-), multiplication (*), and division (/).

* Bitwise Operator -treats their operands as a set of 32 bits (zeros and ones), rather than as decimal, hexadecimal, or octal numbers. For example, the decimal number nine has a binary representation of 1001.
* Logical Operators - typically used with Boolean (logical) values; when they are, they return a Boolean value. However, the && and || operators actually return the value of one of the specified operands, so if these operators are used with non-Boolean values, they may return a non-Boolean value.
* String Operators -addition to the comparison operators, which can be used on string values, the concatenation operator (+) concatenates two string values together, returning another string that is the union of the two operand strings.
* Conditional (ternary) Operators - only JavaScript operator that takes three operands. The operator can have one of two values based on a condition.
* Unary Operators -operation with only one operand.
* Relational Operators -compares its operands and returns a Boolean value based on whether the comparison is true.

Operator Procedure -The precedence of operators determines the order they are applied when evaluating an expression. You can override operator precedence by using parentheses.

Expressions -any valid unit of code that resolves to a value.
  * Two Types
	   * With side effects -assign value to a variable  x = 7
	  * Evaluate and resolve to a value  3 + 4


Functions (declaration/statement)
* Contains a function keyword followed by the name of the function, list of parameters to the function enclosed in parentheses and separated by commas, and the JS statements that define the function enclosed by {} curly brackets.
* Can refer to and call itself (recursion or recursive function) by one of 3 ways.  Function name, in-scope variable that refers to the function, or arguments.callee
* JS has sever top-level, built-in functions

Control Flow -order in which the computer executes statement in a script.
* Code is run in order from the first line in the file to the last line, unless the computer runs across the (extremely frequent) structures that change the control flow, such as conditionals and loops.
