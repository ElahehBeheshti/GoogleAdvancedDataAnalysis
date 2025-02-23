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

1. Programming Language Comparisons

Python, R, Java, and C++ are among the most commonly used languages for data analysis. They can be compared across several dimensions such as:

 ◉ Speed
	
 ◉ Accessibility

 ◉ Variable Management

 ◉ Data Science Focus

 ◉ Programming Paradigm

<img width="898" alt="image" src="https://github.com/user-attachments/assets/54e7afaa-41f2-4c20-bc66-f105f17e25f1" />

2. Object-Oriented Programming: Classes, Methods, and Attributes

Classes
	
 ◉ Definition:
		
 	 ◉ A class is a blueprint for creating objects. It bundles data (attributes) and functionality (methods) together.

 ◉ Core Python Classes:

  	◉ Primitive types: Integers, floats, strings, booleans
	
  	◉ Collections: Lists, dictionaries, tuples, sets, frozensets
	
  	◉ Others: Functions, ranges, and even None (which represents an empty value)
	
  	◉ Custom Classes: Many additional classes come with libraries and packages—and you can define your own.
  
Methods vs. Functions
	
 	◉ Method:
	
  		◉ A function that belongs to a class. Called on an object using dot notation (e.g., dog.bark()).
	
 	◉ Function:
		
  		◉ A standalone block of code that can be called anywhere without being attached to an object (e.g., def my_function(): ...).
	
 	◉ Attributes
	
  		◉ Definition:
		
  		◉ Values associated with an object or class that are accessed using dot notation (e.g., dataframe.columns).
		
  ◉ ◉ Note: Attributes do not use parentheses.

3. Basic Python Concepts

Variables and Naming
	
 	◉ Variables as Containers:
	
  		◉ Variables store values in computer memory. For example, student_name holds the name of a student.
	
 	◉ Naming Rules:
		
  		◉ No spaces allowed
		
  		◉ Can be a mix of upper and lower case
		
  		◉ Must not start with a number (but can contain numbers after the first character)
	
 	◉ Naming Conventions:
		
  		◉ Use snake_case for variable and function names (e.g., student_name is preferable to sn).
		
  		◉ Descriptive names help maintain readability.
	
 	◉ Keywords and Operators
	
  		Keywords:
			Special reserved words used for specific purposes (e.g., in, not, or, for, while, return).
		Operators:
		Symbols that perform operations on objects and values. Examples include:
			◉ + (Addition)
			◉ - (Subtraction)
			◉ * (Multiplication)
			◉ / (Division)
			◉ ** (Exponentiation)
			◉ % (Modulo: returns the remainder, e.g., 10 % 3 == 1)
			◉ // (Floor division: e.g., 5 // 2 == 2)
			◉ > (Greater than)
			◉ < (Less than)
			◉ == (Equality)
	◉ Expressions
		Definition:
		An expression is a combination of numbers, symbols, and variables that computes and returns a result.
			
   		Example:
			[1, 2, 3] + [2, 4, 6] concatenates two lists.

       
4. Data Types and Conversions

	Common Data Types
		◉ Strings (str):
			A sequence of characters. Immutable (cannot be changed in place).
		◉ Integers (int):
			Whole numbers without fractions.
		◉ Floats (float):
			Numbers with decimal points.
		◉ Booleans (bool):
			Represent only two values: True or False.
	Comparators and Logical Operators
		Comparators

	Compare two values and return a Boolean.
		Six main comparators:
			◉ > (Greater Than)
			◉ >= (Greater Than or Equal To)
			◉ < (Less Than)
			◉ <= (Less Than or Equal To)
			◉ == (Equal To)
			◉ != (Not Equal To)
   
	Comparison Rules & Examples:
		
		◉ Comparing incompatible types (e.g., integer with string) raises a TypeError.
		◉ Strings are compared alphabetically (e.g., 'z' > 'a' is True).
	Logical Operators

		◉ and: Returns True if both conditions are true.
		◉ or: Returns True if at least one condition is true.
		◉ not: Inverts the Boolean value (e.g., not True becomes False).
Examples:

		◉ "cat" == "dog" → False
		◉ ("yellow" > "cyan") and ("brown" > "magenta") → False (second comparison is false)
		◉ (25 > 50) or (1 != 2) → True (because 1 != 2 is true)
		◉ not (42 == "Answer") → True (inverts the false result of the comparison)
  
Comparators and logical operators empower you to write complex, decision-based code.

	Data Type Conversions (Casting)
		◉ Implicit Conversion:
			Automatic conversion when needed (e.g., 3 + 2.5 results in 5.5).
		◉ Explicit Conversion (Typecasting):
			Manually converting a value using functions like int(), float(), or str().
				Example: str(7), int("42")


   5. Control Flow: Branching and Loops

	◉ Branching (Conditional Statements)
		Branching lets your program choose different execution paths using:
		if: Executes code if a condition is true.
		elif: Checks another condition if the previous one is false.
		else: Executes code if all previous conditions are false.
			Example:
				number = -4
				if number > 0:
				    print('Number is positive.')
				elif number == 0:
				    print('Number is zero.')
				else:
				    print('Number is negative.')
Loops, Break, and Continue
	While Loops

	◉ Definition:
	   Repeats a block of code as long as a condition remains True.
	◉ Example:
		x = 1
		while x < 100:
		    print(x)
		    x = x * 2
Using break & continue:

	◉ break:
	Exits the loop immediately.
	◉ continue:
	Skips to the next iteration of the loop.
	◉ Example with break:
		x = 1
		i = 0
		while x < 100:
		    if i == 5:
		        break
		    print(i, x)
		    x = x * 2
		    i += 1
Here, the loop stops when i equals 5.
	◉ Example with continue:
		i = 0
		while i < 10:
		    if i % 3 != 0:
		        print(i)
		        i += 1
		        continue
		    i += 1
This loop prints numbers from 0 to 9 that are not divisible by 3.


6. String Indexing and Slicing

String Indexing
	◉ Every character in a string has a position (index) starting at 0.
		◉ For "Hello", H is at index 0, e at index 1, etc.
	◉ Negative indices count from the end (-1 is the last character).
String Slicing
	◉ Slicing syntax: string[start:end]
		◉ The start index is included; the end index is not.
	◉ You can add a step: string[start:end:step].
	◉ Example:
		"Hello"[1:4] returns "ell".
String Methods
	A concise list of Python string methods with a brief explanation:
	
	◉ capitalize():
	Converts the first character to uppercase and the rest to lowercase.
	◉ casefold():
	Converts the string to a lower-case version, more aggressive than lower().
	◉ center(width[, fillchar]):
	Centers the string within a specified width, padding with an optional fill character.
	◉ count(sub[, start[, end]]):
	Returns the number of times a substring appears.
	◉ encode(encoding='utf-8', errors='strict'):
	Encodes the string into bytes.
	◉ endswith(suffix[, start[, end]]):
	Checks if the string ends with a specified suffix.
	◉ expandtabs(tabsize=8):
	Replaces tab characters with spaces.
	◉ find(sub[, start[, end]]):
	Returns the lowest index of a substring or -1 if not found.
	◉ **format(*args, kwargs):
	Formats the string using positional and keyword arguments.
	◉ format_map(mapping):
	Formats the string using a dictionary.
	◉ index(sub[, start[, end]]):
	Like find(), but raises an error if the substring isn’t found.
	◉ isalnum():
	Returns True if all characters are alphanumeric.
	◉ isalpha():
	Returns True if all characters are alphabetic.
	◉ isascii():
	Returns True if all characters are ASCII.
	◉ isdecimal():
	Returns True if the string contains only decimal characters.
	◉ isdigit():
	Returns True if the string contains only digits.
	◉ isidentifier():
	Returns True if the string is a valid Python identifier.
	◉ islower():
	Returns True if all cased characters are lowercase.
	◉ isnumeric():
	Returns True if the string contains only numeric characters.
	◉ isprintable():
	Returns True if all characters are printable.
	◉ isspace():
	Returns True if the string contains only whitespace.
	◉ istitle():
	Returns True if the string is titlecased.
	◉ isupper():
	Returns True if all cased characters are uppercase.
	◉ join(iterable):
	Concatenates an iterable of strings, using the original string as a separator.
	◉ ljust(width[, fillchar]):
	Left-justifies the string in a given width.
	◉ lower():
	Converts all characters to lowercase.
	◉ lstrip([chars]):
	Removes leading whitespace or specified characters.
	◉ maketrans(x, y=None, z=None):
	Creates a translation table for use with translate().
	◉ partition(sep):
	Splits the string at the first occurrence of a separator.
	◉ replace(old, new[, count]):
	Replaces occurrences of a substring with another substring.
	◉ rfind(sub[, start[, end]]):
	Returns the highest index where the substring is found, or -1.
	◉ rindex(sub[, start[, end]]):
	Like rfind(), but raises an error if not found.
	◉ rjust(width[, fillchar]):
	Right-justifies the string in a given width.
	◉ rpartition(sep):
	Splits the string at the last occurrence of a separator.
	◉ rsplit(sep=None, maxsplit=-1):
	Splits the string from the right.
	◉ rstrip([chars]):
	Removes trailing whitespace or specified characters.
	◉ split(sep=None, maxsplit=-1):
	Splits the string into a list of substrings.
	◉ splitlines(keepends=False):
	Splits the string at line breaks.
	◉ startswith(prefix[, start[, end]]):
	Returns True if the string starts with the specified prefix.
	◉ strip([chars]):
	Removes both leading and trailing whitespace or specified characters.
	◉ swapcase():
	Swaps the case of each character.
	◉ title():
	Converts the string to title case.
	◉ translate(table):
	Translates the string using a translation table.
	◉ upper():
	Converts all characters to uppercase.
	◉ zfill(width):
	Pads the string on the left with zeros until it reaches the specified width.

7. Debugging and Best Practices

◉ Debugging:
	Finding and fixing errors in your code is essential. Even experienced programmers use online resources and community forums.
◉ Clean Code:
	Writing well-documented, modular, and self-explanatory code makes it easier to maintain and collaborate.
◉ Comments and Docstrings:
	Use comments to outline your thought process and steps in complex functions.
	Docstrings (triple-quoted strings at the start of functions) explain the function’s purpose, parameters, and return values.
 

----------------------------------------------------
----------------------------------------------------

#3.Translate Data into Insights
#4.
