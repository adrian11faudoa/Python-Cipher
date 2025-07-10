Subject:

Variables are an essential part of Python and any programming language. A variable is a name that references or points to an object. You can declare a variable by writing the variable name on the left side of the assignment operator = and specifying the value to assign to that variable on the right side of the assignment operator:

Example Code:
```
    variable_name = value
```


Variables can store values of different data types. You just assigned an integer value, but if you want to represent some text, you need to assign a string. Strings are sequences of characters enclosed by single or double quotes, but you cannot start a string with a single quote and end it with a double quote or vice versa:

Example Code:
```
    string_1 = "I am a string"
    string_2 = 'I am also a string'
    string_3 = 'This is not valid"
```


Functions are reusable code blocks that you can call, or invoke, to run their code when you need them. 
To call a function, you just need to write a pair of parentheses next to its name. 


An argument is an object or an expression passed to a function — added between the opening and closing parentheses — when it is called:

Example Code:
```
    greet = 'Hello!'
    print(greet)
```


Each character of a string can be accessed by using bracket notation. 
You need to write the variable name followed by square brackets and add the index of the character between the brackets:

Example Code:
```
    text = 'Hello World'
    r = text[8]
```


Key aspects of variable naming in Python are:

Some words are reserved keywords (e.g. for, while, True). They have a special meaning in Python, so you cannot use them for variable names.
Variable names cannot start with a number, and they can only contain alpha-numeric characters or underscores.
Variable names are case sensitive, i.e. my_var is different from my_Var and MY_VAR.
Finally, it is a common convention to write variable names using snake_case, where each space is replaced by an underscore character and the words are written in lowercase letters.


A loop allows you to systematically go through a sequence of elements and execute actions on each one.

In this case, you'll employ a for loop. Here's how you can iterate over text:

Example Code:
```
    for i in text:
```


addition assignment operator:

Example Code:
```
    a += b
```


Comparison operators allow you to compare two objects based on their values. 
You can use a comparison operator by placing it between the objects you want to compare. 
They return a Boolean value — namely True or False — depending on the truthfulness of the expression.

Python has the following comparison operators:

Operator	Meaning
==	        Equal
!=	        Not equal
>	        Greater than
<	        Less than
>=	        Greater than or equal to
<=	        Less than or equal to


a conditional if statement is composed of the if keyword, a condition, and a colon :.

Example Code:
```
    if x != 0:
        print(x)
```

A conditional statement can also have an else clause. 
This clause can be added to the end of an if statement to execute alternative code if the condition of the if statement is false:

Example Code:
```
    if x != 0:
        print(x)
    else:
        print('x = 0')
```


 the modulo operator (%) can be used to return the remainder of the division between two numbers


A function is essentially a reusable block of code. 
You have already met some built-in functions, like print(), find() and len(). 
But you can also define custom functions like this:

Example Code:
```
    def function_name():
        <code>
```

A function declaration starts with the def keyword followed by the function name — a valid variable name — and a pair of parentheses. The declaration ends with a colon.


In Python, the scope of a variable determines where that variable can be accessed:

Variables defined outside a function have a global scope and they can be accessed from any part of your code.

Variables defined inside a function are local to that function and cannot be accessed outside of it.


To execute, a function needs to be called (or invoked) by appending a pair of parentheses after its name, like this:

Example Code:
```
    function_name()
```


functions can be declared with parameters to introduce versatility and customization:

Example Code:
```
    def function_name(param_1, param_2):
        <code>
```

Parameters are variables that you can use inside your function. A function can be declared with different number of parameters. In the example above, param_1 and param_2 are parameters.


In Python, you can write a comment using a #. Anything that comes after the # won't be executed.


to use a return statement:

Example Code:
```
    def foo():
        return 'spam'
```

You need to write return followed by a space and the value that the function should return. 
Once the return statement is found, that value is returned and the execution of the function stops, proceeding to the next line of code after the function call. 
In the example above, the foo function returns the string 'spam'.


The multiplication operator in Python is *


Functions can be called with default arguments. 
A default argument indicates the value that the function should take if the argument is not passed. 
For example, the function below accepts three arguments but you can call it passing two arguments. The third one will assume the specified value by default:

Example Code:
```
    def foo(a, b, c=value):
        <code>
```


The .isalpha() method returns True if all of the characters of the string on which it is called are letters. For example, the code below returns True:

Example Code:
```
    'freeCodeCamp'.isalpha()
    # True
```


The not operator is used to negate an expression. When placed before a truthy value — a value that evaluates to True — it returns False and vice versa.


The pass keyword can be used as a placeholder for future code. 
It does not have any effect in your code but it can save you from errors you would get in case of incomplete code:

Example Code:
```
    def foo():
        pass
```


In Python, there's a way to easily format strings. f-strings enable you to interpolate values in your strings.

Interpolation means writing placeholders that will be replaced by the specified values when the program runs. 
For example, you can get the same result of 'Encrypted text: ' + text with f'Encrypted text: {text}'. 
You need to put an f before the quotes to create the f-string and write the variables or expressions you want to interpolate between curly braces.


The newline character \n is a special sequence used to represent a new line. 
You can write a backslash \ followed by an n as a normal sequence of characters in a string and it will be replaced by a new line in the output when the program runs.


