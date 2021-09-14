# **Programming with JavaScript**

1. **Expressions and Operator**
        - **Operators**
            - Assignment Operators
            - Comparison Operators
            - Arithmetic Operators
            - Bitwise Operators
            - Logical Operators
            - String Operators
            - Conditional (ternary) Operator
            - Comma Operator
            - Unary Operators
            - Relational Operators
        - **Expressions**
            - Primary Expressions
2. **Functions**
            - **Function Declarations**

            A function definition (also called a function declaration, or function statement) consists of the function keyword, followed by:

                    The name of the function.
                    A list of parameters to the function, enclosed in parentheses and separated by commas.
                    The JavaScript statements that define the function, enclosed in curly brackets, {...}.

            - Function Expression
            
            Function expressions are convenient when passing a function as an argument to another function. The following example shows a map function that should receive a function as first argument and an array as second argument:

            - Calling Function

            Calling the function actually performs the specified actions with the indicated parameters.

            - Scope and the function stack

            (Recursion) - A function can refer to and call itself. There are three ways for a function to refer to itself:

                        The function's name
                        arguments.callee
                        An in-scope variable that refers to the function
            
            - Nested functions and closures
            You may nest a function within another function. The nested (inner) function is private to its containing (outer) function.

            - Preservation of value
            - Multiply-nested functions
            - Name conflicts

            - CLosures
            Closures are one of the most powerful features of JavaScript. JavaScript allows for the nesting of functions and grants the inner function full access to all the variables and functions defined inside the outer function (and all other variables and functions that the outer function has access to).

            - Using the argument object
            The arguments of a function are maintained in an array-like object. Within a function, you can address the arguments passed to it as follows:

            - Function parameters
            
                - Default Parameter
                - Rest Parameter

            - Arrow functions
            An arrow function expression (previously, and now incorrectly known as fat arrow function) has a shorter syntax compared to function expressions and does not have its own this, arguments, super, or new.target.

            - Shorter functions
3. **Control flow**
            - The control flow is the order in which the computer executes statements in a script.
            - Code is run in order from the first line in the file to the last line, unless the computer runs across the (extremely frequent) structures that change the control flow, such as conditionals and loops.
4. **[JavaScript Functions](https://www.w3schools.com/js/js_functions.asp)**
5. **[JavaScript Operators](https://www.w3schools.com/js/js_operators.asp)**
