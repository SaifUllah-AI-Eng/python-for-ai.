# **Lecture 01 – Introduction to Python Programming**

1. What You Will Learn in This Lecture

In this lecture, you will learn:

What Python is, who created it, and its release history

Why Python is the most popular language for AI

How to set up your Python environment

Basic Python syntax

Writing your first Python program

Variables and detailed data types 


# 2. Introduction to Python

## 2.1 What is Python?

Python is a high-level, interpreted, general-purpose programming language designed for simplicity and productivity. It is used in:

Web development

Artificial Intelligence

Machine Learning

Data Science

Automation

Scientific computing

Cybersecurity

Software development

Python’s simple English-like syntax makes it ideal for both beginners and professionals.

## 2.2 Who Discovered Python? When Was It Released?

**Creator**: Guido van Rossum

**Country**: Netherlands

**Started Development**: 1989

**First Release**: February 20, 1991

**Current Major Version**: Python 3 (initially released in 2008)


### Python was designed to be:

Easy to read

Easy to write

Highly productive

Today it is the most popular language in AI and machine learning.

# 2.3 Why Python?

🔥 Easy to Learn

Readable syntax → faster learning.

💡 **Versatile**

Used in almost all modern tech fields.

📚 **Rich Libraries**

TensorFlow, PyTorch, NumPy, Pandas, and many more.

🌍 **Huge Community**

Millions of developers contribute tools and support.

⚡ **Quick Development**

Write less, achieve more.

# 3. Key Features of Python Programming
🐍 **Interpreted Language**

Executes code line by line.

🧠 **Dynamically Typed**

No need to declare data types.

🧩 **Extensive Libraries**

Thousands of built-in modules.

💻 **Cross-Platform Support**

Runs on Windows, macOS, Linux.

📦 **Object-Oriented + Functional**

Supports both paradigms.



# 4. **Setting Up the Python Environment**

   
## 4.1 Installing Python Using Anaconda


Anaconda includes:

Python

Jupyter Notebook

Data science libraries

Conda package manager

Steps:

Download Anaconda

Install with default settings

Open Anaconda Navigator

Launch Jupyter Notebook

4.2 Using Jupyter Notebook
How to Start

Open Anaconda Navigator

Launch Jupyter Notebook

Create a new Python 3 notebook


📌 **Code vs Markdown**

**Code Cells**: Write Python code

**Markdown Cells**: Notes, headings, documentation

Run code using Shift + Enter.

## 4.3 Using VS Code for Python & Notebooks

Install VS Code

Install Jupyter extension

Open your project folder

Select Python kernel

Open terminal using Ctrl + Shift + `

VS Code is ideal for large AI projects.


# 5. Basic Python Syntax

## 5.1 Indentation

Python uses indentation instead of braces.

if x > 10:
    print("x is greater")

## 5.2 Case Sensitivity

Age and age are different identifiers.

## 5.3 Comments
# This is a comment

## 5.4 Variables
name = "Saif"
age = 21

# 6. Writing Your First Python Program
print("Hello, World!")

#  print() function:
The print() function displays output on the screen.

# 7. **Python Variables and Data Types**

Python provides several built-in data types that are essential for programming.

## 7.1 Integer (int) 🔢
Definition

Whole numbers: positive, negative, or zero.

**Examples**

x = 10

y = -5

z = 0

Uses

Counting

Indexing

Arithmetic

Operations

a = 5 + 3

b = 10 - 2

c = 4 * 3

d = 20 / 4

e = 10 % 3      # remainder

f = 2 ** 3      # exponent


## 7.2 Float (float) 💧

Definition

Numbers with decimals.

**Examples**

pi = 3.14

price = 19.99

Scientific Notation

value = 1.23e3   # 1230.0

## 7.3 String (str) ✨

Definition

A sequence of characters.

**Examples**

name = "Python"

message = 'Hello'


## String Operations

1. **Concatenation**
   
first = "Hello"

second = "World"

result = first + " " + second


3.**Repetition**

text = "Hi! " * 3

4. **Indexing**
   
name = "Python"

print(name[0])    # P

print(name[-1])   # n


5. **Slicing**
   
lang = "Python"

print(lang[0:3])  # Pyt

6. **Length**
   
len("Hello")

7. **Useful String Methods**
    
"hello".upper()

"HELLO".lower()

"python".capitalize()

"apple,banana".split(",")

"  hi  ".strip()



# 7.4 Boolean (bool) ✔️❌

Definition

Represents two values:

True

False

**Examples**

is_active = True

is_tired = False

Booleans from comparisons

5 > 3      # True

10 == 5    # False


# 7.5 List (list) 📋

Definition

An ordered, mutable collection.

**Example**

fruits = ["apple", "banana", "cherry"]

## List Operations

1. **Access**
   
fruits[0]


2. **Modify**
   
fruits[1] = "mango"


3. **Append**
   
fruits.append("orange")


4. **Remove**
   
fruits.remove("apple")


5. **Slicing**
   
fruits[0:2]


7. **Length**
   
len(fruits)


# 7.6 Tuple (tuple) 📌

Definition

Ordered, immutable collection.

**Example**

point = (10, 20)

Unpacking

x, y = point


Used for fixed-size data and mathematical operations.



# 7.7 Dictionary (dict) 🗂️

Definition

Stores data in key-value pairs.

**Example**

student = {"name": "Alice", "age": 22}


## Dictionary Operations

**Access**

student["name"]


**Add New Key**

student["grade"] = "A"


**Delete Key**

del student["age"]


Dictionaries are perfect for structured JSON-like data.


# 8. How to Find the Data Type in Python

Python provides a built-in function called type() to check the data type of any value or variable.

# 8.1 Using type() Function

**Syntax**

type(value)


**Example with Variables**

x = 10

y = 3.14

name = "Saif"

is_active = True

fruits = ["apple", "banana"]

point = (10, 20)

student = {"name": "Ali", "age": 22}


print(type(x))

print(type(y))

print(type(name))

print(type(is_active))

print(type(fruits))

print(type(point))

print(type(student))


**Output**

<class 'int'>

<class 'float'>

<class 'str'>

<class 'bool'>

<class 'list'>

<class 'tuple'>

<class 'dict'>


## 8.2 Why type() is Important?

Helps understand the nature of data you're working with

Helps avoid errors in operations

Essential for debugging

Useful during AI/ML programming when data types matter

Helps convert data types using casting functions like int(), float(), str(), etc.


# 8. Summary of Lecture 1

You learned:

Who created Python and its history

Why Python is used in AI

How to set up Anaconda, Jupyter, and VS Code

Basic syntax, indentation, variables

Your first Python program

Detailed data types with operations



