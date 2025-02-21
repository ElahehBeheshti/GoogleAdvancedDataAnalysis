# GoogleAdvancedDataAnalysis
Google Certificate on Coursera Platform

<img width="882" alt="image" src="https://github.com/user-attachments/assets/d857e785-a9ca-4e64-ac3b-9c86cac73325" />


----------------------------------------------------
----------------------------------------------------
✔️1.Foundations of Data Science
What is data science vs. data analytics 
The following table presents a side-by-side comparison:
Data science	Data analytics
• Produces broad insights that concentrate on which questions should be asked about data	• Emphasizes discovering answers to questions being asked 
• Confronts what is unknown by using advanced techniques to make predictions about the future 	• Determines actionable insights that can be applied immediately based on existing queries
![image](https://github.com/user-attachments/assets/ebedc396-512a-440d-81a6-7f03b359e9c9)

The connections between data science and data analytics: both discover insights that can be used to lead an organization to improve and grow. 

📊📈the Common Types of Data Visualizations
	• Bar Chart: Compare quantities across categories.
	• Line Chart: Show trends over time or continuous data.
	• Histogram: Show the distribution of numerical data across ranges.
	• Pie Chart: Represent proportions or percentages.
	• Scatter Plot: Show relationships or correlations between two variables.
	• Heat Map: Highlight values using colors (e.g., intensity, frequency).
	• Tree Map: Show proportions hierarchically.
	• Box Plot: Show data distribution and identify outliers.
  •Bubble Chart: Show three variables using x-axis, y-axis, and bubble size.

----------------------------------------------------
----------------------------------------------------

✔️2.Python For Data Analysis:

    📍how to convert data types in Python
    📍fundamental data types such as integer, float, and string
    📍Interpret the naming conventions and restrictions for variables in Python
    📍Describe the purpose and procedure of assigning variables
    📍Define fundamental concepts of object-oriented programming such as object, class, method, and attribute
    📍Recognize the uses and benefits of Jupyter Notebook for data work
    📍Identify the basic features and capabilities of the Python programming language
    📍Explain how to import modules in Python scripts using import
    📍Perform arithmetic operations
    📍Use built-in functions and keywords to explore data
    📍Understand packages and interpreter options for Python
    📍Identify the concept of algorithms in python
    📍Identify the value of Python competency for data careers

Programming language comparisons

Python, R, Java and C++ are four of the most commonly used programming languages for data analysis. The following chart compares them using  five considerations: speed, accessibility, variable, data science focus, and programming paradigm. 

<img width="898" alt="image" src="https://github.com/user-attachments/assets/54e7afaa-41f2-4c20-bc66-f105f17e25f1" />

The most important concept in object-oriented programming is the class. A class is an object's data type that bundles data and functionality together.

A method is a function that belongs to a class and typically performs an action or operation. They use parentheses.

The core classes of Python are: Integers, floats, strings, booleans, lists, dictionaries, tuples, sets, frozensets, functions, ranges, and none, which is a data type that returns an empty value. There are also many additional custom-defined classes that come with libraries and packages, and you can even make your own. 

Attributes are values associated with an object or class which are referenced by name using dot notation. They don't use parentheses. Attributes are especially important for custom-built classes and more complex data structures, like dataframes.

some of the basics:

Variables: Represent data stored as strings, tuples, dictionaries, lists, and objects (note: future readings explain these categories)

Example: student_name

Keywords: Special words that are reserved for specific purposes and that can only be used for those purposes

Examples:

in
not
or
for 
while
return
Operators: Symbols that perform operations on objects and values

Examples:

+     Addition

-     Subtraction

*     Multiplication

/     Division

**   Exponentiation 

%     Modulo (returns the remainder after a division). Example: 10 % 3 = 1

//   Floor division (divides the first operand by the second operand and rounds the result down to the nearest integer. Example: 5 // 2 = 2

>     Greater than (returns a Boolean of whether the left operand is greater than the right operand)

<     Less than (returns a Boolean of whether the left operand is less than the right operand)

==   Equality (returns a Boolean of whether the left operand is equal to the right operand)

Expressions: A combination of numbers, symbols, and variables to compute and return a result upon evaluation
Example: [1, 2, 3] + [2, 4, 6]
Functions: A group of related statements to perform a task and return a value

Example: 
def to_celsius(x):
   '''Convert Fahrenheit to Celsius'''
   return (x-32) * 5/9

to_celsius(75)

Conditional statements: Sections of code that direct program execution based on specified conditions
Example: 
number = -4

if number > 0:
   print('Number is positive.')
elif number == 0:
   print('Number is zero.')
else:
   print('Number is negative.')

Naming rules and conventions

When assigning names to objects, programmers adhere to a set of rules and conventions which help to standardize code and make it more accessible to everyone. Here are some naming rules and conventions that you should know:

Names cannot contain spaces.

Names may be a mixture of upper and lower case characters.

Names can’t start with a number but may contain numbers after the first character.

Variable names and function names should be written in snake_case, which means that all letters are lowercase and words are separated using an underscore. 

Descriptive names are better than cryptic abbreviations because they help other programmers (and you) read and interpret your code. For example, student_name is better than sn. It may feel excessive when you write it, but when you return to your code you’ll find it much easier to understand.

Variables as Containers:

	Variables are like “containers” that point to values stored in computer memory.
	Proper naming and understanding what values your variables hold is essential.
 
Common Data Types in Python
	Strings (str): A sequence of characters, instantiated with quotes or the str() function.
	Immutable: Once created, strings cannot be altered in place.
	Integers (int): Whole numbers without fractions (e.g., 7, 42).
	Floats (float): Numbers with decimal points (e.g., 3.14, 2.0).
 
Mixing Data Types & Errors
	Adding or combining incompatible data types (e.g., int + str) leads to a TypeError.
	Always check error messages for clues about what went wrong.
 
Identifying Data Types
	Use the type() function to see the data type (or “class”) of a value or variable:
 		type("Hello")  # str
		type(10)       # int
		type(3.14)     # float
  
Data Type Conversions (Casting)
	Implicit Conversion: Python automatically converts types when it makes sense (e.g., int + float → float).
	Explicit Conversion (Typecasting): You manually convert from one type to another, often using int(), float(), or str().
		Example: str(7), int("42")
Debugging & Online Resources
	Debugging (finding and fixing errors) is an essential skill for data professionals.
	Even experienced coders use online resources and community forums to find quick solutions or explanations.



 
Implicit Conversion
	What it is: This happens automatically when Python converts one data type to another behind the scenes, without you having to do anything.
		Example: Adding an integer and a float (3 + 2.5) results in 5.5—Python automatically turns the integer 3 into a float 3.0 first.
Explicit Conversion
	What it is: You, the programmer, tell Python exactly when to convert one data type to another.
		Example: Converting a number to a string by using str(7), or converting a string "42" to an integer via int("42").
Mutable
	What it means: Something that can be changed after it’s created. In Python, this typically applies to objects like lists or dictionaries. For instance, you can add or 	remove items from a list without creating a new list.
		Example: A list [1, 2, 3] is mutable: you can do my_list.append(4) and it becomes [1, 2, 3, 4].
Immutable
	What it means: Something that cannot be changed after it’s created. If you want a new value, you have to create a whole new object.
		Example: A string "Hello" is immutable: if you try to “change” a character, Python actually creates a new string in the background.
Note: “Mutable conversion” or “Immutable conversion” aren’t standard Python phrases—usually, we just talk about whether an object itself is mutable or immutable, and whether a type conversion is implicit or explicit.

Functions in python:
	Functions are reusable blocks of code that perform specific tasks.
	Python has many built-in functions (e.g., print(), type(), str()), but you can define your own for custom tasks.

 Defining a Function
	Use the def keyword, followed by the function name and parentheses for parameters (also known as arguments).
		Example:
			def greeting(name):
			    print("Welcome,", name)
			    print("You are part of the team.")
       
**Indentation in Python denotes code hierarchy. All lines in a function’s body must be indented to the same level.

Calling a Function:

	After defining a function, call it by its name and pass in the required arguments.
		Example:
			greeting("Rebecca")

Returning Values:

	The return keyword specifies the value a function produces, allowing you to save that result for later use, rather than just printing it.
		Example:
			def triangle_area(base, height):
			    return (base * height) / 2
       
Reusability and Power of return:

	By returning values, functions can be combined with other operations without re-writing logic.
		Example using two triangles:
			area1 = triangle_area(5, 10)
			area2 = triangle_area(3, 4)
			total_area = area1 + area2
   
**Reusing code saves time and makes your programs more efficient.

Practical Example: Converting Time to Seconds:

	def get_seconds(hours, minutes, seconds):
	    total_seconds = hours * 3600 + minutes * 60 + seconds
	    return total_seconds

# Usage
result = get_seconds(16, 45, 20)  # 16 hours, 45 minutes, 20 seconds
This calculates the total number of seconds in the given inputs.

Function syntax 
	def my_function(parameters):
	    '''
	    Docstring.
	    Summarize the function's behavior and explain its arguments and return values.
	    '''
	    code block
	
	    return value
The docstring should summarize the function’s behavior and explain its arguments and return values.

return vs. print:
	With the return statement, you have some potatoes to cook. With the print statement, you just know what potatoes are available, but you don’t have any potatoes.
 Functions vs. methods:
 	Function: A piece of code you can call from anywhere in your program, and it doesn’t “belong” to anything. Think of it like a free tool you can pick up and use 	anytime you want.
	Method: A piece of code that is attached to an object (like a part of a toy or gadget). You can only use that piece of code by asking the object to do it. For 		example, if you have a dog object, it might have a method called bark(), so you say dog.bark()—that’s a method.

 Boolean Data
	Represents only two possible values: True or False.

Comparators
	Compare two values and return a Boolean (True or False).
		Six main comparators in Python:
			> (Greater Than)
			>= (Greater Than or Equal To)
			< (Less Than)
			<= (Less Than or Equal To)
			== (Equal To)
			!= (Not Equal To)
   Comparison Rules & Examples
	Different Data Types: Comparing incompatible types (like an integer and a string) raises a TypeError.
		Strings: Compared alphabetically based on their letters, e.g. 'z' > 'a' is True.
	Logical Operators
		and: Returns True only if both conditions are True; otherwise False.
		or: Returns True if at least one of the conditions is True; only False if both are False.
		not: Inverts the Boolean value of the following expression (True becomes False, and vice versa).

		Examples
			String Comparison: "cat" == "dog" → False.
			Using and: ("yellow" > "cyan") and ("brown" > "magenta") → False, because the second comparison is not true.
			Using or: (25 > 50) or (1 != 2) → True, because 1 != 2 is true.
			Using not: not (42 == "Answer") → True, because the expression (42 == "Answer") is False, and not False becomes True.
Comparators and logical operators let data professionals write more complex code, make decisions based on data conditions, and control the flow of programs in powerful ways.

Branching:
	allows a program to choose different paths of execution (if, elif, and else statements.)
 		if condition1:
    			# code if condition1 is True
		elif condition2:
   		 	# code if condition2 is True (and condition1 was False)
		else:
   			# code if neither condition1 nor condition2 is True

----------------------------------------------------
----------------------------------------------------

#3.Translate Data into Insights
#4.
