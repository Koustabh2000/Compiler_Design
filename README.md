# Project Details
Basic line wise interpreter made with Python

##### Operations Inplemented
* Evaluating Expression
* Variables
* Condition Check
* While and For Looping statements
* Functions with parameters
* Basic Error Checking and giving feeedback
<br><br>

# Prerequisites
- Python should be installed
- Environment Variable should be set
- Recommended Python Version > 3.7+
- Download compatible Python version from below links
>[Windows](https://www.python.org/downloads/windows/)
<br>[Linux/UNIX](https://www.python.org/downloads/source/)
<br>[macOS](https://www.python.org/downloads/macos/)
<br>[Others](https://www.python.org/download/other/)
- Please install Python on your own 😉
<br><br>

# Steps to be followed to run the project
1. Fetch the latest code from repository
2. compile the python files in following order<br>
&emsp;- **strings_with_arrows.py** (Logic to point the error or show result)<br>
&emsp;- **basic.py** (compiler logic & classes)<br>
&emsp;- **shell.py** (taking the input from CLI)<br>
3. Give inputs
<br><br>

# Input Format / Grammer to be followed
#### Evaluating expression with operators<br><br>
**Supported number format**
- Integer
- Floating number<br>

**Suppoted Operators**
<br>arithmatic -> "+", "-", "*", "/", "^"
<br>relational -> "=", "==", "!=", "<", ">", "<=", ">="
<br>logical -> "AND", "OR", "NOT"

**sample arithmatic operations**
- num + num
- num - num
- num * num
- num / num

**sample operations using braces**
- (num operator num)operator num
- num operator(num operator num)
- (num operator(num operator num))<br>

##### Declaring Variables
VAR variable_name = value

##### Sample Conditional statement
IF expr THEN expr
&emsp;ELIF expr THEN expr
&emsp;&emsp;ELSE expr

##### Sample Looping example
VAR result = 1
FOR i = 1 TO 6 THEN VAR result = result * i
(result would be 120)<br><br>

VAR i = 0
WHILE i < 1000 THEN VAR i = i + 1
(end result of i would be 1000)

##### Sample Function
function declaration
FUN name(parameters) -> operations
**FUN add(a,b) -> a+b**

function calling
name(parameters)
**add(5,6)**

# ENJOY 👍
