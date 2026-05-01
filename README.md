#  project -expression  Checker

##  Project Overview
The  is my " expression checker " Java-based mini project that simulates a feature of modern IDEs. It checks whether an expression has properly balanced parentheses, braces, and brackets using a Stack (LIFO) data structure.


## Objective
To validate the correctness of bracket usage in expressions and detect syntax errors such as:

* Missing brackets
* Mismatched brackets
* Incorrect nesting


##  Technologies Used

* **Language:** Java
* **Concepts:** Stack, Data Structures
* **Tools:** VS Code  / Command Prompt


##  How It Works

* Traverse the expression character by character
* Push opening brackets `(` `{` `[` into the stack
* Pop and match when closing brackets `)` `}` `]` appear
* If mismatch or stack not empty → expression is invalid


## Algorithm

1. Create an empty stack
2. Read the input expression
3. For each character:
   a. If opening bracket → push to stack
   b. If closing bracket:
       - If stack empty → Unbalanced
       - Pop and check matching
4. If stack is empty → Balanced
5. Else → Unbalanced


##  Program Output

### Balanced Expression
====================================
   CODE QUALITY GUARD (IDE SYSTEM)  
====================================
NAME   : Sherlin S
REG.NO : 711525BCS157
DEPT   : CSE_A
------------------------------------
Enter Expression: (a+b)^2 = a^2+b^2
 Balanced Expression

###  Unbalanced Expression
====================================
   CODE QUALITY GUARD (IDE SYSTEM)  
====================================
NAME   : Sherlin S
REG.NO : 711525BCS157
DEPT   : CSE_A
------------------------------------
Enter Expression: (a+b]*c
Unbalanced Expression


## How to Run

### Step 1: Compile
javac miniproject.java


### Step 2: Run
java miniproject


## Project Structure
sherlin/
│── miniproject.java


## Applications
* Code editors (VS Code)
* Compilers and interpreters
* Syntax validation tools
* Expression evaluation systems


##  Future Enhancements

* GUI-based IDE simulation
* Real-time error detection
* Auto-correction suggestions
* Integration with code editors



##  Author

Sherlin S
Reg No: 711525BCS157
Department: CSE_A

## ⭐ Acknowledgment

This project is developed as part of a Data Structures mini project to demonstrate real-world application of stacks.
