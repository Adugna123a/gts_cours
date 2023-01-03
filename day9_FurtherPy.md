# Further on Python
## Functions
● A function is a block of code that performs a specific
task.

● Suppose, you need to create a program to create a
circle and color it. You can create two functions to solve
this problem:

     ○ create a circle function
     ○ create a color function
● Dividing a complex problem into smaller chunks makes
our program easy to understand and reuse.
## Types of function
● There are two types of function in Python programming:

     ○ Standard library functions - These are built-in functions in Python that are available to use.
    ■ Almost all keywords are functions
        ○ User-defined functions - We can create our own functions based on our requirements.
## Creating FUnctions
Syntax: It have body like if else statements also have
body.
Example:

● Functions have to be called to word. Thing functions like some skilled person, plumbers
can do water pipe problems, their specific task is fixing broken pipes. So, if i need to fix my
plumber what do i do? I just call them right! | => SO python functions also have to be
called.
## Return statement
● A Python function may or may not return a value.

● If we want our function to return some value to a function call, we use
the return statement. 
## Recursion
● Recursion is process of defining something in terms of itself.

● In Python, we know that a function can call other functions. It is even possible for the
function to call itself. These types of construct are termed as recursive functions.
## Advantages of Recursion
1. Recursive functions make the code look clean and elegant.
 
3. A complex task can be broken down into simpler sub-problems using
recursion.

1. Sequence generation is easier with recursion than using some nested
iteration.
## Disadvantages of Recursion
1. Sometimes the logic behind recursion is hard to follow through.
2. Recursive calls are expensive (inefficient) as they take up a lot of memory and time.
3. Recursive functions are hard to debug.
## Anonymous / lambda Function
● If function doesnt have name it is called lambda function / Anonymous

● If you have 1 line code to return you dont need to def a function,

● a lambda function is a special type of function without the function name.

● We use lambda keyword instead of def
## Filter Function
● Filters are used to filter or search some function from sequences.
## Map function
● Used to do some operations on Sequences
## Append
● Append used to add some value to a list.
## Object-Oriented Programming / OOP
● Python is an object oriented programming. This means mores things on python are
objects.

● Objects are anythings which can have action and name.

● Objects have attributes(properties) and methods(action or functions) 
## Creating Objects
● You can Create many Objects based on 1 class. | Here we created Object
called Nathan_Computer

● Syntax:

    ○ Var = classname()
    ○ Var.attribute = “value”
## Python Constructors
● Earlier we assigned a default value to a class attribute,
However, we can also initialize values using the constructors.
Here, __init__() is the constructor function that is called whenever
a new object of that class is instantiated.
The constructor above initializes the value of the name attribute. We
have used the self.name to refer to the name attribute of the bike1
object.
## Python Inheritance
● Is a way of creating new class with
some properties of existing class.

● Syntax:

    ○ class newclass(oldclass):