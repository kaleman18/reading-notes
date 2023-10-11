# Dynamic web pages with JavaScript

## What are variables in JavaScript?

Containers for storing data. All JavaScript variables must be identified with unique names. These unique names are called **identifiers**.

## What does it mean to declare a variable?

Creating a variable in JavaScript is called "declaring" a variable.

You declare a JavaScript variable with the var or the let keyword:

*var carName;*

or:

*let carName;*

After the declaration, the variable has no value (technically it is undefined).

To assign a value to the variable, use the equal sign:

*carName = "Volvo";*

You can also assign a value to the variable when you declare it:

*let carName = "Volvo";*

**It's a good programming practice to declare all variables at the beginning of a script.**

## What is an “assignment” operator, and what does it do?

In JavaScript, the equal sign (=) is an "assignment" operator.

x = x + 5

= means

it assigns the value of x + 5 **to** x

## What is information received from the user called?



## When to Use var, let, or const?

1. Always declare variables

2. Always use const if the value should not be changed

3. Always use const if the type should not be changed (Arrays and Objects)

4. Only use let if you can't use const

5. Only use var if you MUST support old browsers.