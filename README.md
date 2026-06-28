# Overview & Fundamental of Python

---

# 🚀 Python for Beginners: From Zero to Hero (Complete Guide)

Welcome to the ultimate Python guide! Ye structured tutorial series aapko bilkul basic se lekar advanced level tak asani se guide karegi. Agar aap coding mein naye hain, toh fikar mat kijiye—Python ko sikhna bohot hi simple hai!

---

##### *Pre Tip* 

- *Agar Introvert Ho to Mere Jaise Codes me Apna Name Dalne Ka Try krna Jaldi Samjh aayega*


---

## 📚 Table of Contents

1. [Your First Python Program](#1-your-first-python-program)
2. [Variables and Data Types](#2-variables-and-data-types)
3. [Basic Arithmetic](#3-basic-arithmetic-python-as-a-calculator)
4. [Making Decisions](#4-making-decisions-if--else-statements)
5. [Loops](#5-loops-repeating-tasks)
6. [Functions](#6-functions-reusable-code)
7. [Lists](#7-lists-the-ultimate-collection-box)
8. [Tuples](#8-tuples-the-unchangeable-list)
9. [Dictionaries](#9-dictionaries-key-value-pairs)
10. [Advanced Loop Operations](#10-advanced-loop-operations)
11. [Sets](#11-sets-only-unique-items)
12. [File Handling](#12-file-handling-reading-and-writing-files)
13. [Handling Errors](#13-handling-errors-try--except)
14. [Modules and Libraries](#14-modules-and-libraries-importing-code)
15. [OOPs Basics](#15-object-oriented-programming-oops---basics)
16. [Advanced OOPs](#16-advanced-oops-inheritance--polymorphism)
17. [Lambda Functions](#17-lambda-functions-anonymous-functions)
18. [Map, Filter, and Reduce](#18-map-filter-and-reduce)
19. [Decorators](#19-decorators-modifying-function-behavior)
20. [Comprehensions](#20-list-dictionary-and-set-comprehensions-pro-shortcut)
21. [PIP and Package Management](#21-pip-and-package-management)
22. [Generators](#22-generators-memory-efficient-iteration)
23. [Context Managers](#23-context-managers-custom-with-statements)
24. [Virtual Environments](#24-virtual-environments-project-isolation)
25. [Type Hints](#25-type-hints-code-documentation)
26. [F-Strings](#26-f-strings-modern-string-formatting)
27. [Regular Expressions](#27-regular-expressions-pattern-matching)
28. [Working with APIs](#28-working-with-apis)
29. [Data Classes](#29-data-classes-modern-way)
30. [Async/Await](#30-asyncawait-concurrent-programming)
31. [Testing](#31-testing-writing-tests)
32. [Best Practices](#32-best-practices--pep-8)
33. [Walrus Operator](#33-walrus-operator--assignment-expressions)
34. [Match-Case Statements](#34-match-case-statements-structural-pattern-matching)
35. [Logging Module](#35-logging-professional-debugging)
36. [Pathlib Module](#36-pathlib-modern-file-handling)
37. [Collections Module](#37-collections-module-supercharged-data-structures)
38. [Itertools Module](#38-itertools-efficient-looping)
39. [JSON Handling](#39-json-handling-data-interchange)
40. [SQLite Database](#40-sqlite-database-built-in-sql)
41. [Environment Variables](#41-environment-variables-security-best-practice)
42. [Git & GitHub Basics](#42-git--github-basics-version-control)

### 🌐 Web Development & APIs
43. [Flask Basics](#43-flask-basics-micro-web-framework)
44. [FastAPI Introduction](#44-fastapi-introduction-modern-high-performance)
45. [REST API Principles](#45-rest-api-principles)
46. [HTTP Methods (GET/POST)](#46-http-methods-getpostputdelete)
47. [Jinja2 Templating](#47-jinja2-templating-html-rendering)
48. [SQLAlchemy (ORM)](#48-sqlalchemy-orm-object-relational-mapping)
49. [Pydantic Models](#49-pydantic-models-data-validation)
50. [Authentication (JWT)](#50-authentication-jwt-json-web-tokens)

### 📊 Data Science & Analysis
51. [NumPy Basics](#51-numpy-basics-numerical-python)
52. [Pandas DataFrames](#52-pandas-dataframes-data-manipulation)
53. [Data Cleaning](#53-data-cleaning-handling-missing-values)
54. [Matplotlib Plotting](#54-matplotlib-plotting-basic-visualization)
55. [Seaborn Visualizations](#55-seaborn-visualizations-statistical-plots)
56. [Exploratory Data Analysis (EDA)](#56-exploratory-data-analysis-eda)

### 🤖 Machine Learning & AI
57. [Scikit-Learn Intro](#57-scikit-learn-intro-ml-library)
58. [Linear Regression](#58-linear-regression-predictive-modeling)
59. [Classification Models](#59-classification-models)
60. [Train/Test Split](#60-traintest-split-evaluation)
61. [TensorFlow/Keras Basics](#61-tensorflowkeras-basics-deep-learning)
62. [Neural Networks Intro](#62-neural-networks-intro)
63. [OpenCV for Computer Vision](#63-opencv-for-computer-vision)
64. [NLP with NLTK/Spacy](#64-nlp-with-nltkspacy-text-processing)
65. [Hugging Face Transformers](#65-hugging-face-transformers-llms)

### ⚡ Performance & Optimization66. [Time Complexity (Big O)](#66-time-complexity-big-o-notation)
67. [Profiling Code (cProfile)](#67-profiling-code-cprofile)
68. [Multiprocessing](#68-multiprocessing-true-parallelism)
69. [Threading vs Asyncio](#69-threading-vs-asyncio-concurrency)
70. [Caching (functools.lru_cache)](#70-caching-functoolslru_cache)
71. [Memory Management](#71-memory-management-garbage-collection)

### 🛠️ Testing & Quality Assurance
72. [Unit Testing (unittest)](#72-unit-testing-unittest)
73. [Pytest Framework](#73-pytest-framework-modern-testing)
74. [Mocking & Patching](#74-mocking--patching-isolating-dependencies)
75. [Test Driven Development (TDD)](#75-test-driven-development-tdd)
76. [Code Coverage](#76-code-coverage-measuring-tests)

### 🏗️ Software Architecture & Design Patterns
77. [SOLID Principles](#77-solid-principles-clean-code)
78. [Singleton Pattern](#78-singleton-pattern)
79. [Factory Pattern](#79-factory-pattern)
80. [Observer Pattern](#80-observer-pattern)
81. [Dependency Injection](#81-dependency-injection)
82. [MVC Architecture](#82-mvc-architecture-model-view-controller)

### 🐳 DevOps & Deployment
83. [Docker Basics](#83-docker-basics-containerization)
84. [Dockerfile for Python](#84-dockerfile-for-python)
85. [CI/CD with GitHub Actions](#85-cicd-with-github-actions)
86. [Cloud Deployment (AWS/Heroku)](#86-cloud-deployment-awsheroku)
87. [Gunicorn & Nginx](#87-gunicorn--nginx-production-server)

### 🔒 Security & Best Practices
88. [Hashing Passwords (bcrypt)](#88-hashing-passwords-bcrypt)
89. [SQL Injection Prevention](#89-sql-injection-prevention)
90. [XSS Protection](#90-xss-protection)
91. [Rate Limiting](#91-rate-limiting)
92. [Secrets Management](#92-secrets-management)

### 🧠 Advanced Concepts & Internals
93. [Metaclasses](#93-metaclasses-class-of-a-class)
94. [Descriptors](#94-descriptors-managing-attributes)
95. [Context Managers (Advanced)](#95-context-managers-advanced)
96. [Coroutines Deep Dive](#96-coroutines-deep-dive)
97. [Bytecode & Disassembly](#97-bytecode--disassembly-under-the-hood)


---

## 1. Your First Python Program

Python mein screen par kuch bhi display karne ke liye hum **print()** function ka use karte hain.

```python
# Displaying text on the screen
print("Hello, World!")
```

---

## 2. Variables and Data Types

Variables ko aap ek **box (dabbe)** ki tarah samajh sakte hain jismein aap alag-alag tarah ka data store karte hain. Python ki sabse achhi baat ye hai ki aapko pehle se batana nahi padta ki box mein kis type ka data jayega; Python ise apne aap samajh leta hai.

```python
# Storing different types of data in variables
name = "Shrijan"          # String: Text data (hamesha quotes "" mein hota hai)
age = 17                  # Integer: Whole numbers (bina decimal ke)
wallet_balance = 99.50    # Float: Decimal waale numbers
is_learning = True        # Boolean: Sirf True ya False value

# Using variables
print(name)
print(age)
```

---

## 3. Basic Arithmetic (Python as a Calculator)

Python out-of-the-box ek powerful calculator ki tarah kaam kar sakta hai:

```python
addition = 5 + 3        # Output: 8
subtraction = 10 - 4    # Output: 6
multiplication = 3 * 4  # Output: 12
division = 20 / 5       # Output: 4.0 (Note: Python mein division hamesha float return karta hai)
```

---

## 4. Making Decisions (If / Else Statements)

Jab aapko decision lena ho ki code kis raste par chalega, tab hum if-elif-else ka use karte hain.

> **NOTE - (Indentation):** Python mein braces {} nahi hote. Code ka hissa dikhane ke liye hum **indentation (tabs ya spaces)** ka use karte hain.

```python
score = 85

if score >= 90:
    print("Excellent! You got an A.")
elif score >= 75:
    print("Good job! You passed.")
else:
    print("Keep practicing!")
```

---

## 5. Loops (Repeating Tasks)

Agar aapko ek hi code baar-baar run karna ho, toh loops ka use kiya jata hai.

### 5.1 For Loop

Jab aapko pata ho ki code ko kitni baar run karna hai, tab for loop best hai:

```python
# This will print numbers from 0 to 4
for i in range(5):
    print("Counting:", i)
```

### 5.2 While Loop

Ye loop tab tak chalta rehta hai jab tak di gayi condition **True** rehti hai:

```python
countdown = 3

while countdown > 0:
    print(countdown)
    countdown = countdown - 1  # Har baar value 1 se kam hogi

print("Blast off!")
```

---

## 6. Functions (Reusable Code)

Functions code ke wo blocks hote hain jinhe aap ek baar banate hain aur poore program mein **baar-baar reuse** kar sakte hain. Isse `def` keyword se banaya jata hai.

```python
# Defining a function
def greet_user(username):
    print("Welcome back, " + username + "!")

# Calling the function to execute it
greet_user("Shrijan")
```

---

## 7. Lists (The Ultimate Collection Box)

Ab tak hum variables mein sirf ek value store kar pa rahe the. Lekin agar aapko ek sath bohot saari cheezein ek hi jagah rakhni hon (jaise shopping list ya programming languages ke naam), toh hum **List** ka use karte hain. Ise square brackets `[]` se banaya jata hai.

```python
# Creating a list of programming languages
languages = ["Python", "Java", "C++", "JavaScript"]

# 1. Accessing items (Python mein counting hamesha 0 se shuru hoti hai!)
print(languages[0])    # Output: Python
print(languages[2])    # Output: C++

# 2. Adding a new item to the end of the list
languages.append("Go")
print(languages)       # Output: ['Python', 'Java', 'C++', 'JavaScript', 'Go']

# 3. Changing an item
languages[1] = "Kotlin" 
print(languages)       # Output: ['Python', 'Kotlin', 'C++', 'JavaScript', 'Go']
```

---

## 8. Tuples (The Unchangeable List)

Tuple bilkul list ki tarah hota hai, lekin ye **Immutable** hota hai—yaani ek baar banane ke baad aap iski values ko badal (change) nahi kar sakte. Ise round brackets `()` se banaya jata hai.

```python
# Fixed numbers ya coordinates ke liye best hai
coordinates = (40.7128, -74.0060)

print(coordinates[0])  # Output: 40.7128

# Agar aap ise change karne ki koshish karenge, toh Python error dega:
# coordinates[0] = 50.0  --> TypeError (Python iski permission nahi deta)
```

---

## 9. Dictionaries (Key-Value Pairs)

Dictionary real-life phonebook ya words dictionary ki tarah kaam karti hai. Ismein har data ka ek unique **Key (Naam)** hota hai aur uski ek **Value** hoti hai. Ise curly braces `{}` se banaya jata hai.

```python
# Storing user information
user_profile = {
    "username": "skt_ai_developer",
    "role": "AI Architect",
    "experience_years": 2
}

# Accessing values using their keys
print(user_profile["username"])    # Output: skt_ai_developer
print(user_profile["role"])        # Output: AI Architect

# Updating or adding a new key-value pair
user_profile["location"] = "India"
print(user_profile)
```

---

## 10. Advanced Loop Operations

Ab seekhte hain ki in Lists aur Dictionaries ke upar Loops ko thoda aur smart tareeqe se kaise chalate hain.

### 10.1 Looping Directly Through a List

Aapko `range()` ki zaroorat nahi hai, aap direct list ke items par loop chala sakte hain:

```python
fruits = ["Apple", "Banana", "Mango"]

for fruit in fruits:
    print("I love eating", fruit)
```

### 10.2 List Comprehension (The Pro Shortcut)

Python ka ek super-feature jisse aap nayi lists sirf ek single line mein bana sakte hain:

```python
# Traditional Way (Lamba tarika):
# numbers = [1, 2, 3, 4]
# squares = []
# for x in numbers:
#     squares.append(x**2)

# Pro Way (List Comprehension Shortcut):
numbers = [1, 2, 3, 4]
squares = [x**2 for x in numbers]  # Output: [1, 4, 9, 16]
print(squares)
```

---

## 11. Sets (Only Unique Items)

Agar aapko duplicate values hatani hon aur sirf unique items chahiye hon, toh **Set** ka use hota hai. Ismein koi bhi item repeat nahi ho sakta aur iska koi fixed order nahi hota.

```python
# Notice duplicate numbers here
raw_data = [1, 2, 2, 3, 4, 4, 4, 5]

unique_set = set(raw_data)
print(unique_set)  # Output: {1, 2, 3, 4, 5} (Duplicates automatically gayab!)
```

---

## 12. File Handling (Reading and Writing Files)

Real-world programs mein data ko files (jaise `.txt` ya `.csv`) mein save karna aur wahan se read karna padta hai. Python mein ye kaam `open()` function aur `with` statement ke sath bohot asani se hota hai.

```python
# 1. File mein write karna (Nayi file banna ya overwriting)
with open("notes.txt", "w") as file:
    file.write("Python is awesome!\n")
    file.write("Learning with Shrijan Tiwari.")

# 2. File se data read karna
with open("notes.txt", "r") as file:
    content = file.read()
    print(content)
```

> 💡 **Why use `with`?** `with` keyword ka fayda ye hai ki kaam khatam hote hi Python file ko apne aap close kar deta hai, jisse memory waste nahi hoti.

---

## 13. Handling Errors (Try / Except)

Agar aapke code mein koi aisi galti ho jaye jisse program crash ho sakta hai (jaise kisi number ko 0 se divide karna ya aisi file open karna jo exist hi nahi karti), toh program ko crash hone se bachane ke liye hum **Exception Handling** use karte hain.

```python
try:
    # Aisa code jisme error aa sakta hai
    number = 10
    result = number / 0
except ZeroDivisionError:
    # Agar ZeroDivisionError aaya, toh ye code chalega
    print("Oops! Aap kisi bhi number ko 0 se divide nahi kar sakte.")
except Exception as e:
    # Kisi bhi doosre error ke liye
    print("Kuch gadbad hui:", e)
finally:
    # Ye block hamesha chalega, chahe error aaye ya na aaye
    print("Execution complete.")
```

---

## 14. Modules and Libraries (Importing Code)

Python ki sabse badi taqat uski libraries hain. Kisi aur ka likha hua achha code ya Python ke inbuilt tools ko apne program mein use karne ke liye hum **import** ka istemal karte hain.

```python
import math    # Python ka inbuilt math module
import random  # Random numbers generate karne ke liye

# Math module ka use
print("Square root of 16 is:", math.sqrt(16))  # Output: 4.0

# Random module ka use (Dice roll game ki tarah)
dice_roll = random.randint(1, 6)
print("You rolled a:", dice_roll)
```

---

## 15. Object-Oriented Programming (OOPs) - Basics

Jab aapka code bohot bada ho jata hai, tab real-world entities ko code mein lane ke liye OOPs ka use hota hai. Ismein do cheezein hoti hain: **Class** (Ek blueprint/template) aur **Object** (Us blueprint se bani real cheez).

```python
# Creating a Class (Blueprint)
class Car:
    def __init__(self, brand, model):
        self.brand = brand  # Attribute
        self.model = model  # Attribute

    def start_engine(self):  # Method (Function inside class)
        print(self.brand + " " + self.model + " ka engine start ho gaya! Vroom Vroom!")

# Creating Objects (Real instances)
car1 = Car("Tesla", "Model S")
car2 = Car("Tata", "Safari")

# Accessing attributes and methods
print(car1.brand)       # Output: Tesla
car2.start_engine()     # Output: Tata Safari ka engine start ho gaya
```

---

## 16. Advanced OOPs (Inheritance & Polymorphism)

Jab ek nayi Class purani Class ki properties aur methods ko automatic copy kar leti hai, toh use **Inheritance** kehte hain. Aur jab wahi methods alag-alag tarike se kaam karte hain, toh use **Polymorphism** kehte hain.

```python
# Base Class (Parent)
class Animal:
    def __init__(self, name):
        self.name = name
    
    def speak(self):
        pass  # Dummy method jo child class override karegi

# Derived Class (Child 1) - Inheriting Animal
class Dog(Animal):
    def speak(self):
        return self.name + " says Woof!"

# Derived Class (Child 2) - Inheriting Animal
class Cat(Animal):
    def speak(self):
        return self.name + " says Meow!"

# Polymorphism in action
pets = [Dog("Sheru"), Cat("Lucy")]

for pet in pets:
    print(pet.speak())  # Output: Sheru says Woof! aur Lucy says Meow!
```

---

## 17. Lambda Functions (Anonymous Functions)

Python mein bina naam ke chote aur single-line functions banane ke liye `lambda` keyword ka use hota hai. Ye tab kaam aate hain jab aapko koi chota operation turant karna ho.

```python
# Normal Function:
# def square(x):
#     return x * x

# Lambda Way (Shortcut):
square = lambda x: x * x
print(square(5))  # Output: 25

# Multi-argument lambda
multiply = lambda a, b: a * b
print(multiply(4, 5))  # Output: 20
```

---

## 18. Map, Filter, and Reduce

Ye built-in functions aapko kisi list ya collection par loop chalaye bina complex operations karne ki power dete hain.

```python
from functools import reduce

numbers = [1, 2, 3, 4, 5]

# 1. Map: Har item par operation chalana (Double the numbers)
doubled = list(map(lambda x: x * 2, numbers))  # [2, 4, 6, 8, 10]

# 2. Filter: Condition ke basis par items nikalna (Only Even numbers)
evens = list(filter(lambda x: x % 2 == 0, numbers))  # [2, 4]

# 3. Reduce: Poori list ko single value mein convert karna (Sum of all)
total_sum = reduce(lambda x, y: x + y, numbers)  # 15

print("Doubled:", doubled)
print("Evens:", evens)
print("Sum:", total_sum)
```

---

## 19. Decorators (Modifying Function Behavior)

Decorators Python ka ek super-advanced feature hain. Inka use kisi existing function ke code ko bina badle, uski functionality ko badhane ya modify karne ke liye kiya jata hai.

```python
# Creating a decorator
def my_decorator(func):
    def wrapper():
        print("--- Function chalne se PEHLE ka kaam ---")
        func()
        print("--- Function chalne se BAAD ka kaam ---")
    return wrapper

# Applying decorator using '@' symbol
@my_decorator
def say_hello():
    print("Hello Shrijan!")

say_hello()
# Output:
# --- Function chalne se PEHLE ka kaam ---
# Hello Shrijan!
# --- Function chalne se BAAD ka kaam ---
```

---

## 20. List, Dictionary, and Set Comprehensions (Pro Shortcut)

Jaise humne point 10 mein List Comprehension dekha, waise hi hum loops ko hatane ke liye single line mein Dictionaries aur Sets bhi bana sakte hain.

```python
# 1. Dictionary Comprehension
# Kisi list se key-value pair banana
names = ["Shrijan", "Amit", "Rahul"]
name_lengths = {name: len(name) for name in names}
print(name_lengths)  # Output: {'Shrijan': 7, 'Amit': 4, 'Rahul': 5}

# 2. Set Comprehension
# Unique values nikalna single line mein
nums = [1, 2, 2, 3, 4, 4]
unique_squares = {x**2 for x in nums}
print(unique_squares)  # Output: {1, 4, 9, 16}
```

---

## 21. PIP and Package Management

Jab aapko professional development karni hoti hai, toh aapko bahar ki libraries (jaise Data Science ke liye **Pandas**, Web Development ke liye **Django**, AI ke liye **OpenAI/TensorFlow**) ki zaroorat padti hai. Unhe install karne ke liye hum Terminal/Command Prompt mein `pip` tool ka use karte hain.

```bash
# Terminal mein run karne ke liye commands:

# 1. Kisi library ko install karna
pip install requests

# 2. Installed libraries ki list dekhna
pip list

# 3. Library ko uninstall karna
pip uninstall requests

# 4. Specific version install karna
pip install pandas==1.5.0

# 5. Requirements file se install karna
pip install -r requirements.txt
```

---

## 22. Generators (Memory Efficient Iteration)

Jab aapke paas bohot bada data ho (jaise millions of records), toh puri list memory mein load karna system ko slow kar sakta hai. **Generators** data ko ek-ek karke generate karte hain jab zaroorat hoti hai, na ki pehle se sab store karte hain. Ise `yield` keyword se banaya jata hai.

```python
# Normal Function (Sab kuch memory mein load karta hai)
def get_squares_normal(n):
    result = []
    for i in range(n):
        result.append(i * i)
    return result

# Generator Function (Ek baar mein ek value deta hai - Memory Saver!)
def get_squares_generator(n):
    for i in range(n):
        yield i * i

# Usage
gen = get_squares_generator(5)
for num in gen:
    print(num)  # Output: 0, 1, 4, 9, 16
```

---

## 23. Context Managers (Custom 'with' Statements)

Humne Point 12 mein file handling ke liye `with` statement dekha tha. Aap apna khud ka custom context manager bana sakte hain taaki resources (jaise database connections ya network locks) automatically manage ho sakein.

```python
import time

class Timer:
    def __enter__(self):
        self.start = time.time()
        return self

    def __exit__(self, exc_type, exc_val, exc_tb):
        self.end = time.time()
        print(f"Time taken: {self.end - self.start:.4f} seconds")

# Iska use karna bilkul 'with open(...)' jaisa hi easy hai
with Timer():
    # Ye code kitna time leta hai check karne ke liye
    sum([i**2 for i in range(100000)])
```

---

## 24. Virtual Environments (Project Isolation)

Har project ki alag-alag library requirements hoti hain. Ek project mein `Django 3.0` chahiye ho sakta hai aur doosre mein `Django 4.0`. Agar aap globally install karenge toh conflict hoga. Isliye hum **Virtual Environment** use karte hain.

```bash
# Terminal Commands:

# 1. Naya virtual environment banana
python -m venv my_project_env

# 2. Environment ko activate karna (Windows)
my_project_env\Scripts\activate

# 3. Environment ko activate karna (Mac/Linux)
source my_project_env/bin/activate

# 4. Environment ko deactivate karna
deactivate

# 5. Installed packages ki list save karna
pip freeze > requirements.txt
```

---

## 25. Type Hints (Code Documentation)

Type hints se aap apne code ko aur readable bana sakte hain. Ye batate hain ki function ko kis type ka input chahiye aur kis type ka output dega. Ye runtime par enforce nahi hote, lekin IDEs aur linters ko code samajhne mein madad karte hain.

```python
# Without type hints
def calculate_area(length, width):
    return length * width

# With type hints (Much clearer!)
def calculate_area_typed(length: float, width: float) -> float:
    return length * width

# Complex type hints
from typing import List, Dict, Optional

def process_users(users: List[Dict[str, str]]) -> Optional[str]:
    if users:
        return users[0].get("name")
    return None

# Usage
area = calculate_area_typed(5.5, 3.2)
print(f"Area: {area}")
```

---

## 26. F-Strings (Modern String Formatting)

F-strings (formatted string literals) Python 3.6+ mein introduce hue the. Ye strings ko format karne ka sabse modern aur readable tarika hai.

```python
name = "Shrijan"
age = 17
balance = 99.50

# Old way (concatenation)
message_old = "Name: " + name + ", Age: " + str(age)

# Better way (.format())
message_format = "Name: {}, Age: {}".format(name, age)

# Best way (F-Strings)
message_fstring = f"Name: {name}, Age: {age}, Balance: ${balance:.2f}"
print(message_fstring)

# Expressions inside f-strings
print(f"Next year I'll be {age + 1}")
print(f"Name in uppercase: {name.upper()}")
```

---

## 27. Regular Expressions (Pattern Matching)

Regular expressions (regex) powerful pattern matching tools hain. Ye text mein specific patterns dhundhne, validate karne, ya extract karne ke liye use hote hain (jaise email validation, phone numbers, etc.).

```python
import re

text = "Contact us at support@example.com or sales@company.org"

# 1. Pattern find karna
email_pattern = r'\b[A-Za-z0-9._%+-]+@[A-Za-z0-9.-]+\.[A-Z|a-z]{2,}\b'
emails = re.findall(email_pattern, text)
print("Emails found:", emails)

# 2. Pattern match karna (start se)
if re.match(r'^Hello', 'Hello World'):
    print("Starts with Hello!")

# 3. Pattern search karna (kahin bhi)
if re.search(r'\d{3}-\d{4}', 'Call me at 555-1234'):
    print("Phone number found!")

# 4. Pattern replace karna
cleaned = re.sub(r'\d+', '#', 'Order 12345 is ready')
print(cleaned)  # Output: Order ##### is ready
```

---

## 28. Working with APIs

APIs (Application Programming Interfaces) se aap doosre applications se data le sakte hain. `requests` library se ye kaam bohot asaan ho jata hai.

```python
import requests

# 1. GET Request - Data fetch karna
response = requests.get('https://jsonplaceholder.typicode.com/posts/1')

if response.status_code == 200:
    data = response.json()  # JSON ko Python dictionary mein convert
    print("Title:", data['title'])
else:
    print("Error:", response.status_code)

# 2. POST Request - Data send karna
new_post = {
    'title': 'My New Post',
    'body': 'This is awesome!',
    'userId': 1
}

response = requests.post(
    'https://jsonplaceholder.typicode.com/posts',
    json=new_post
)

print("Created:", response.json())

# 3. Headers add karna (Authentication ke liye)
headers = {'Authorization': 'Bearer YOUR_TOKEN'}
response = requests.get('https://api.example.com/data', headers=headers)
```

---

## 29. Data Classes (Modern Way)

Data classes (Python 3.7+) automatically `__init__`, `__repr__`, aur `__eq__` methods generate karti hain. Ye classes banane ka modern aur clean tarika hai jab aapko sirf data store karna ho.

```python
from dataclasses import dataclass
from datetime import datetime

# Traditional way (bohot code likhna padta hai)
class User:
    def __init__(self, name, email, age):
        self.name = name
        self.email = email
        self.age = age
    
    def __repr__(self):
        return f"User(name={self.name}, email={self.email}, age={self.age})"

# Modern way with @dataclass (Automatic!)
@dataclass
class User:
    name: str
    email: str
    age: int
    created_at: datetime = datetime.now()  # Default value

# Usage
user1 = User("Shrijan", "shrijan@example.com", 17)
user2 = User("Shrijan", "shrijan@example.com", 17)

print(user1)  # Output: User(name='Shrijan', email='shrijan@example.com', age=17, created_at=...)
print(user1 == user2)  # Output: True (Automatic equality check!)
```

---

## 30. Async/Await (Concurrent Programming)

Async programming se aap multiple tasks ko ek sath run kar sakte hain bina wait kiye. Ye I/O-bound tasks (jaise API calls, file operations, database queries) ke liye perfect hai.

```python
import asyncio
import time

# Synchronous way (Ek ke baad ek - Slow)
def fetch_data_sync(task_id):
    time.sleep(2)  # Simulating network delay
    return f"Task {task_id} completed"

# Asynchronous way (Parallel - Fast!)
async def fetch_data_async(task_id):
    await asyncio.sleep(2)  # Non-blocking sleep
    return f"Task {task_id} completed"

# Running async functions
async def main():
    start = time.time()
    
    # Multiple tasks ko parallel run karna
    tasks = [
        fetch_data_async(1),
        fetch_data_async(2),
        fetch_data_async(3)
    ]
    
    results = await asyncio.gather(*tasks)
    
    for result in results:
        print(result)
    
    print(f"Total time: {time.time() - start:.2f} seconds")

# Run the async program
asyncio.run(main())
```

---

## 31. Testing (Writing Tests)

Testing se aap ensure kar sakte hain ki aapka code sahi kaam kar raha hai. `unittest` Python ka built-in testing framework hai.

```python
import unittest

# Function to test
def add(a, b):
    return a + b

def is_even(n):
    return n % 2 == 0

# Test cases
class TestMathFunctions(unittest.TestCase):
    
    def test_add(self):
        self.assertEqual(add(2, 3), 5)
        self.assertEqual(add(-1, 1), 0)
        self.assertEqual(add(0, 0), 0)
    
    def test_is_even(self):
        self.assertTrue(is_even(4))
        self.assertTrue(is_even(0))
        self.assertFalse(is_even(3))
        self.assertFalse(is_even(-1))

# Run tests
if __name__ == '__main__':
    unittest.main()
```

```bash
# Test run karne ke liye terminal mein:
python test_file.py

# Ya pytest use karke (more powerful):
pip install pytest
pytest test_file.py -v
```

---

## 32. Best Practices & PEP 8

PEP 8 Python ka official style guide hai. Ye follow karne se aapka code clean, readable, aur professional dikhta hai.

### Key Guidelines:

```python
# ✅ DO:

# 1. Naming conventions
user_name = "Shrijan"          # Variables: snake_case
MAX_CONNECTIONS = 100          # Constants: UPPER_CASE
class UserProfile:             # Classes: PascalCase
    pass

def calculate_total_price():   # Functions: snake_case
    pass

# 2. Line length (79 characters max)
long_variable_name = some_function(
    argument1, argument2, argument3,
    argument4, argument5
)

# 3. Imports (Top of file, alphabetically)
import os
import sys
from datetime import datetime

# 4. Docstrings for functions
def calculate_area(length: float, width: float) -> float:
    """
    Calculate the area of a rectangle.
    
    Args:
        length (float): Length of rectangle
        width (float): Width of rectangle
    
    Returns:
        float: Area of rectangle
    """
    return length * width

# 5. Use type hints
def greet(name: str) -> str:
    return f"Hello, {name}!"

# ❌ DON'T:

# Wildcard imports
from module import *  # Bad!

# Single letter variables (except loop counters)
x = "Shrijan"  # Bad! Use descriptive names

# Long lines
result = function1(param1) + function2(param2) + function3(param3) + function4(param4)  # Too long!
```

### Tools for Code Quality:

```bash
# Code formatter
pip install black
black your_file.py

# Linter (finds errors)
pip install flake8
flake8 your_file.py

# Type checker
pip install mypy
mypy your_file.py
```


---

## 33. Walrus Operator (`:=`) - Assignment Expressions
Python 3.8 mein introduce hua ye operator aapko variable assign karte waqt uski value check karne ki power deta hai. Isse code chota aur clean hota hai.

```python
# ❌ Old Way (Do lines)
data = input("Enter name: ")
if data:
    print(f"Hello, {data}")

# ✅ New Way (Walrus Operator - Ek line!)
if (data := input("Enter name: ")):
    print(f"Hello, {data}")
```

---

## 34. Match-Case Statements (Structural Pattern Matching)

Python 3.10+ mein `switch-case` jaisa feature aa gaya hai, lekin ye usse kaafi zyada powerful hai.

```python
def http_status(code):
    match code:
        case 200:
            return "OK"
        case 404:
            return "Not Found"
        case 500 | 502 | 503:  # Multiple values match
            return "Server Error"
        case _:  # Default case
            return "Unknown Status"
```

---

## 35. Logging (Professional Debugging)

`print()` ki jagah `logging` use karein production code mein.

```python
import logging

logging.basicConfig(level=logging.INFO, format='%(asctime)s - %(levelname)s - %(message)s')
logger = logging.getLogger(__name__)

logger.info("Application started")
logger.error("Something went wrong!")
```

---
## 36. Pathlib (Modern File Handling)

`os.path` ki jagah `pathlib` use karein. Ye Object-Oriented hai.

```python
from pathlib import Path

file_path = Path("documents") / "notes.txt"
if file_path.exists():
    print(file_path.read_text())
```

---

## 37. Collections Module (Supercharged Data Structures)

### Counter
```python
from collections import Counter
counts = Counter(["apple", "banana", "apple"])
print(counts['apple']) # 2
```

### defaultdict
```python
from collections import defaultdict
d = defaultdict(list)
d['key'].append(1) # No KeyError!
```

---

## 38. Itertools (Efficient Looping)

```python
import itertools

# Combinations
pairs = list(itertools.combinations([1, 2, 3], 2))
# Chain
combined = list(itertools.chain([1, 2], [3, 4]))
```

---

## 39. JSON Handling (Data Interchange)

```python
import json
# Dict to JSON
json_str = json.dumps({"name": "Shrijan"}, indent=4)

# JSON to Dict
data = json.loads(json_str)
```

---

## 40. SQLite Database (Built-in SQL)

```python
import sqlite3

conn = sqlite3.connect('test.db')
cursor = conn.cursor()
cursor.execute("CREATE TABLE IF NOT EXISTS users (id INT, name TEXT)")
cursor.execute("INSERT INTO users VALUES (1, 'Shrijan')")
conn.commit()
conn.close()
```

---

## 41. Environment Variables (Security Best Practice)

Kabhi bhi secrets code mein hardcode na karein.

```python
import os
from dotenv import load_dotenv

load_dotenv()
api_key = os.getenv("API_KEY")
```

---

## 42. Git & GitHub Basics (Version Control)

```bash
git init
git add .
git commit -m "Initial commit"
git push origin main
```

---

## 43. Flask Basics (Micro Web Framework)
Simple web server banane ke liye best start.

```python
from flask import Flask
app = Flask(__name__)

@app.route('/')
def home():
    return "Hello World!"

if __name__ == '__main__':
    app.run(debug=True)
```

---

## 44. FastAPI Introduction (Modern High-Performance)

Async support aur automatic docs ke sath modern framework.

```python
from fastapi import FastAPI
app = FastAPI()

@app.get("/items/{item_id}")
def read_item(item_id: int):
    return {"item_id": item_id}
```

---

## 45. REST API Principles

- **Stateless:** Server client state save nahi karta.
- **Resources:** URLs resources ko represent karte hain (/users, /posts).
- **Methods:** GET (Read), POST (Create), PUT (Update), DELETE (Remove).

---

## 46. HTTP Methods (GET/POST/PUT/DELETE)

```python
# Flask Example
@app.route('/user', methods=['POST'])
def create_user():
    data = request.json
    # Save to DB
    return {"message": "User created"}, 201
```
---

## 47. Jinja2 Templating (HTML Rendering)

Dynamic HTML pages generate karne ke liye.

```html
<!-- template.html -->
<h1>Hello {{ name }}</h1>
<ul>
{% for item in items %}
    <li>{{ item }}</li>
{% endfor %}
</ul>
```

---

## 48. SQLAlchemy (ORM)

Database ko Python objects ki tarah treat karein.

```python
from sqlalchemy import create_engine, Column, Integer, String
from sqlalchemy.ext.declarative import declarative_base

Base = declarative_base()

class User(Base):
    __tablename__ = 'users'
    id = Column(Integer, primary_key=True)
    name = Column(String)
```

---

## 49. Pydantic Models (Data Validation)

FastAPI aur data validation ke liye standard.

```python
from pydantic import BaseModel

class Item(BaseModel):
    name: str
    price: float
    is_offer: bool = False
```
---

## 50. Authentication (JWT)

Secure login systems ke liye JSON Web Tokens.

```python
import jwt
token = jwt.encode({"user_id": 1}, "secret_key", algorithm="HS256")
payload = jwt.decode(token, "secret_key", algorithms=["HS256"])
```

---

## 51. NumPy Basics (Numerical Python)

High-performance arrays aur mathematical operations.

```python
import numpy as np
arr = np.array([1, 2, 3, 4])
print(arr * 2) # [2, 4, 6, 8] - Vectorized operation (Fast!)
```

---

## 52. Pandas DataFrames (Data Manipulation)

Excel/CSV data handle karne ke liye best library.

```python
import pandas as pd
df = pd.read_csv('data.csv')
print(df.head())
print(df.describe())
```

---

## 53. Data Cleaning (Handling Missing Values)

```python
# Drop rows with missing values
df.dropna(inplace=True)

# Fill missing values with mean
df['age'].fillna(df['age'].mean(), inplace=True)
```

---
## 54. Matplotlib Plotting (Basic Visualization)

```python
import matplotlib.pyplot as plt
plt.plot([1, 2, 3], [4, 5, 6])
plt.title("My Graph")
plt.show()
```

---

## 55. Seaborn Visualizations (Statistical Plots)

Matplotlib se sundar aur statistical graphs.

```python
import seaborn as sns
sns.histplot(data=df, x="age")
plt.show()
```

---

## 56. Exploratory Data Analysis (EDA)

Data ko samajhne ki process:
1. Shape check karein (`df.shape`)
2. Null values check karein (`df.isnull().sum()`)
3. Correlation matrix dekhein (`df.corr()`)

---

## 57. Scikit-Learn Intro (ML Library)

Machine Learning algorithms ka toolbox.

```python
from sklearn.linear_model import LinearRegression
model = LinearRegression()
```

---

## 58. Linear Regression (Predictive Modeling)

```python
import numpy as np
from sklearn.linear_model import LinearRegression
X = np.array([[1], [2], [3]])
y = np.array([2, 4, 6])

model = LinearRegression()
model.fit(X, y)
print(model.predict([[4]])) # Output: [8.]
```

---

## 59. Classification Models

Email spam detection ya image recognition ke liye.

```python
from sklearn.tree import DecisionTreeClassifier
clf = DecisionTreeClassifier()
clf.fit(X_train, y_train)
predictions = clf.predict(X_test)
```

---

## 60. Train/Test Split (Evaluation)

Model ko unseen data par test karna zaroori hai.

```python
from sklearn.model_selection import train_test_split
X_train, X_test, y_train, y_test = train_test_split(X, y, test_size=0.2)
```

---

## 61. TensorFlow/Keras Basics (Deep Learning)

```python
import tensorflow as tf
model = tf.keras.Sequential([
    tf.keras.layers.Dense(10, activation='relu'),
    tf.keras.layers.Dense(1, activation='sigmoid')
])
model.compile(optimizer='adam', loss='binary_crossentropy')
```

---

## 62. Neural Networks Intro

Layers, Neurons, Weights, Biases, Activation Functions (ReLU, Sigmoid).
---

## 63. OpenCV for Computer Vision

Image processing aur video analysis.

```python
import cv2
img = cv2.imread('image.jpg')
gray = cv2.cvtColor(img, cv2.COLOR_BGR2GRAY)
cv2.imshow('Gray', gray)
cv2.waitKey(0)
```

---

## 64. NLP with NLTK/Spacy (Text Processing)

```python
import spacy
nlp = spacy.load("en_core_web_sm")
doc = nlp("Apple is looking at buying U.K. startup")
for ent in doc.ents:
    print(ent.text, ent.label_)
```

---

## 65. Hugging Face Transformers (LLMs)

Pre-trained models use karna easy hai.

```python
from transformers import pipeline
classifier = pipeline("sentiment-analysis")
result = classifier("I love Python!")
print(result) # [{'label': 'POSITIVE', 'score': 0.99}]
```

---

## 66. Time Complexity (Big O Notation)

Code efficiency mapne ka tarika.
- O(1): Constant (Fastest)
- O(n): Linear
- O(n^2): Quadratic (Slow for large data)

---
## 67. Profiling Code (cProfile)

Bottlenecks dhundhne ke liye.

```bash
python -m cProfile my_script.py
```

---

## 68. Multiprocessing (True Parallelism)

CPU-bound tasks ke liye.

```python
from multiprocessing import Process

def worker():
    print("Working...")

p = Process(target=worker)
p.start()
p.join()
```

---

## 69. Threading vs Asyncio (Concurrency)

- **Threading:** I/O bound tasks (Network calls).
- **Asyncio:** Single-threaded concurrency (High performance web servers).

---

## 70. Caching (functools.lru_cache)

Results ko memory mein save karein taaki dobara calculate na karna pade.

```python
from functools import lru_cache

@lru_cache(maxsize=None)
def fib(n):
    if n < 2: return n
    return fib(n-1) + fib(n-2)
```

---
## 71. Memory Management (Garbage Collection)

Python automatically unused objects delete karta hai. `gc` module se control kar sakte hain.

```python
import gc
gc.collect() # Force garbage collection
```

---

## 72. Unit Testing (unittest)

```python
import unittest

class TestMath(unittest.TestCase):
    def test_add(self):
        self.assertEqual(1 + 1, 2)

if __name__ == '__main__':
    unittest.main()
```

---

## 73. Pytest Framework (Modern Testing)

`unittest` se simple aur powerful.

```python
# test_main.py
def test_add():
    assert 1 + 1 == 2
```
Run: `pytest`

---

## 74. Mocking & Patching (Isolating Dependencies)

External APIs ya DB ko fake karna testing ke liye.

```python
from unittest.mock import patch

@patch('module.external_api_call')
def test_function(mock_api):
    mock_api.return_value = {"data": "fake"}
    # Test logic here```

---

## 75. Test Driven Development (TDD)

1. Test likho (Fail hoga).
2. Code likho (Pass hoga).
3. Refactor karo.

---

## 76. Code Coverage

Check karein kitna code test ho raha hai.

```bash
pytest --cov=my_module
```

---

## 77. SOLID Principles (Clean Code)

- **S**ingle Responsibility
- **O**pen/Closed
- **L**iskov Substitution
- **I**nterface Segregation
- **D**ependency Inversion

---

## 78. Singleton Pattern

Ek class ka sirf ek instance ensure karna.

```python
class Singleton:
    _instance = None
    def __new__(cls):
        if cls._instance is None:
            cls._instance = super().__new__(cls)
        return cls._instance
```

---

## 79. Factory Pattern

Objects create karne ke liye interface provide karna bina specific class bataye.
---

## 80. Observer Pattern

Event-based programming. Jab state change ho, subscribers notify hon.

---

## 81. Dependency Injection

Dependencies ko bahar se inject karna taaki code loosely coupled ho.

---

## 82. MVC Architecture (Model-View-Controller)

- **Model:** Data & Logic
- **View:** UI
- **Controller:** Input handling

---

## 83. Docker Basics (Containerization)

App ko isolate environment mein run karna.

```bash
docker build -t myapp .
docker run -p 8000:8000 myapp
```

---

## 84. Dockerfile for Python

```dockerfile
FROM python:3.9-slim
WORKDIR /app
COPY requirements.txt .
RUN pip install -r requirements.txt
COPY . .
CMD ["python", "app.py"]
```

---

## 85. CI/CD with GitHub Actions

Automated testing aur deployment.
```yaml
# .github/workflows/main.yml
name: Python CI
on: [push]
jobs:
  build:
    runs-on: ubuntu-latest
    steps:
      - uses: actions/checkout@v2
      - name: Set up Python
        uses: actions/setup-python@v2
        with:
          python-version: '3.9'
      - name: Install dependencies
        run: pip install -r requirements.txt
      - name: Run tests
        run: pytest
```

---

## 86. Cloud Deployment (AWS/Heroku)

- **Heroku:** Easy deploy (`git push heroku main`).
- **AWS EC2:** Virtual server.
- **AWS Lambda:** Serverless functions.

---

## 87. Gunicorn & Nginx (Production Server)

Flask/Django ko directly run na karein. Gunicorn use karein.

```bash
gunicorn -w 4 -b 0.0.0.0:8000 app:app
```

---

## 88. Hashing Passwords (bcrypt)

Passwords ko plain text mein store na karein.

```python
import bcrypt
hashed = bcrypt.hashpw(b"password", bcrypt.gensalt())
bcrypt.checkpw(b"password", hashed)
```
---

## 89. SQL Injection Prevention

Always use parameterized queries.

```python
# Bad
cursor.execute(f"SELECT * FROM users WHERE name = '{name}'")

# Good
cursor.execute("SELECT * FROM users WHERE name = %s", (name,))
```

---

## 90. XSS Protection

User input ko escape karein HTML mein. Jinja2 auto-escape karta hai by default.

---

## 91. Rate Limiting

API abuse rokne ke liye requests limit karein.

```python
from flask_limiter import Limiter
limiter = Limiter(app, default_limits=["200 per day"])
```

---

## 92. Secrets Management

AWS Secrets Manager ya HashiCorp Vault use karein production mein.

---

## 93. Metaclasses (Class of a Class)

Classes ko dynamically create ya modify karna.

```python
class Meta(type):
    def __new__(cls, name, bases, dct):
        print(f"Creating class {name}")
        return super().__new__(cls, name, bases, dct)

class MyClass(metaclass=Meta):    pass
```

---

## 94. Descriptors (Managing Attributes)

Attribute access ko customize karna (`__get__`, `__set__`).

---

## 95. Context Managers (Advanced)

`__enter__` aur `__exit__` methods implement karna.

---

## 96. Coroutines Deep Dive

`async` aur `await` ke peeche ka event loop.

---

## 97. Bytecode & Disassembly (Under the Hood)

Python code kaise machine instructions mein badalta hai.

```python
import dis
def foo(): pass
dis.dis(foo)
```

---

