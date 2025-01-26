#### # Variables are containers used to store, manipulate & display information within a program
#### # Has a unique name and a value that can be of different types.
1. Numbers:
Types of Numbers
int = Whole Numbers ex: a = 1/-1/0
float = Real Numbers  ex: a = 1.2, 3.4 
2. String:
Char - A single character (ex: 1, %, l, a….)
String(str) - consists of multiple **char**s.
To initialize a string value in a variable, enclose it within **single or double quotation marks:** 
3. Boolean:
A bool (Boolean) type has only 2 possible values: True or False
Booleans are the building blocks for creating logic in the programs we write. We have a whole chapter about logic and conditions.
4. Recap:
#### # Type your code below

#### # Don't change the line below
print(f"k = {k}")
print(f"PI = {PI}")
print(f"name = {name}")

##### # Mistakes to learn:
##### 1. String Formatting Issue:
#####  In Python, you need to use an f before the string to enable formatting (e.g., f"k = {k}").
##### 2.  Missing Objects
##### # To include the value of k, you need to write f"{k}" in the print statement. If you're missing the curly braces {} inside the f-string then code will not run.  
eg: This example doesn't work unless you use the curly braces
##### # Type your code below
k = 88
##### # Don't change the line below
print(f"k")
