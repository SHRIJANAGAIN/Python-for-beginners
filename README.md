## Python-for-beginners

---

# **OVERVIEW ONLY OF PYTHON**












---


# 🚀 Python for Beginners: From Zero to Hero

Welcome to the ultimate Python guide! standard format mein structured ye tutorial series aapko bilkul basic se lekar advanced level tak asani se guide karegi. Agar aap coding mein naye hain, toh fikar mat kijiye—Python ko sikhna bohot hi simple hai!

## 1. Your First Python Program

Python mein screen par kuch bhi display karne ke liye hum

 **print()** function ka use karte hain.

```python
# Displaying text on the screen
print("Hello, World!")

```

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

## 3. Basic Arithmetic (Python as a Calculator)
Python out-of-the-box ek powerful calculator ki tarah kaam kar sakta hai:

```python
addition = 5 + 3        # Output: 8
subtraction = 10 - 4    # Output: 6
multiplication = 3 * 4  # Output: 12
division = 20 / 5       # Output: 4.0 (Note: Python mein division hamesha float return karta hai)

```
## 4. Making Decisions (If / Else Statements)

Jab aapko decision lena ho ki code kis raste par chalega, tab hum if-elif-else ka use karte hain.

>  **NOTE-  (Indentation):** Python mein braces {} nahi hote. Code ka hissa dikhane ke liye hum 

**indentation (tabs ya spaces)** ka use karte hain.
> 


```python
score = 85

if score >= 90:
    print("Excellent! You got an A.")
elif score >= 75:
    print("Good job! You passed.")
else:
    print("Keep practicing!")

```
## 5. Loops (Repeating Tasks)
Agar aapko ek hi code baar-baar run karna ho, toh loops ka use kiya jata hai.


### 1. For Loop
Jab aapko pata ho ki code ko kitni baar run karna hai, tab for loop best hai:

```python
# This will print numbers from 0 to 4
for i in range(5):
    print("Counting:", i)

```
### 2. While Loop
Ye loop tab tak chalta rehta hai jab tak di gayi condition **True** rehti hai:

```python
countdown = 3

while countdown > 0:
    print(countdown)
    countdown = countdown - 1  # Har baar value 1 se kam hogi

print("Blast off!")

```
## 6. Functions (Reusable Code)
Functions code ke wo blocks hote hain jinhe aap ek baar banate hain aur poore program mein **baar-baar reuse** kar sakte hain. Isse def keyword se banaya jata hai.

```python
# Defining a function
def greet_user(username):
    print("Welcome back, " + username + "!")

# Calling the function to execute it
greet_user("Shrijan")

```

## 7. Lists (The Ultimate Collection Box)
Ab tak hum variables mein sirf ek value store kar pa rahe the. Lekin agar aapko ek sath bohot saari cheezein ek hi jagah rakhni hon (jaise shopping list ya programming languages ke naam), toh hum **List** ka use karte hain. Ise square brackets [] se banaya jata hai.
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
## 8. Tuples (The Unchangeable List)
Tuple bilkul list ki tarah hota hai, lekin ye **Immutable** hota hai—yaani ek baar banane ke baad aap iski values ko badal (change) nahi kar sakte. Ise round brackets () se banaya jata hai.
```python
# Fixed numbers ya coordinates ke liye best hai
coordinates = (40.7128, -74.0060)

print(coordinates[0])  # Output: 40.7128

# Agar aap ise change karne ki koshish karenge, toh Python error dega:
# coordinates[0] = 50.0  --> TypeError (Python iski permission nahi deta)

```
## 9. Dictionaries (Key-Value Pairs)
Dictionary real-life phonebook ya words dictionary ki tarah kaam karti hai. Ismein har data ka ek unique **Key (Naam)** hota hai aur uski ek **Value** hoti hai. Ise curly braces {} se banaya jata hai.
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
## 10. Advanced Loop Operations
Ab seekhte hain ki in Lists aur Dictionaries ke upar Loops ko thoda aur smart tareeqe se kaise chalate hain.
### A. Looping Directly Through a List
Aapko range() ki zaroorat nahi hai, aap direct list ke items par loop chala sakte hain:
```python
fruits = ["Apple", "Banana", "Mango"]

for fruit in fruits:
    print("I love eating", fruit)

```
### B. List Comprehension (The Pro Shortcut)
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
## 11. Sets (Only Unique Items)
Agar aapko duplicate values hatani hon aur sirf unique items chahiye hon, toh **Set** ka use hota hai. Ismein koi bhi item repeat nahi ho sakta aur iska koi fixed order nahi hota.
```python
# Notice duplicate numbers here
raw_data = [1, 2, 2, 3, 4, 4, 4, 5]

unique_set = set(raw_data)
print(unique_set)  # Output: {1, 2, 3, 4, 5} (Duplicates automatically gayab!)

```

## 12. File Handling (Reading and Writing Files)
Real-world programs mein data ko files (jaise .txt ya .csv) mein save karna aur wahan se read karna padta hai. Python mein ye kaam open() function aur with statement ke sath bohot asani se hota hai.

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
> 💡 **Why use with?** with keyword ka fayda ye hai ki kaam khatam hote hi Python file ko apne aap close kar deta hai, jisse memory waste nahi hoti.
> 
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
## 17. Lambda Functions (Anonymous Functions)
Python mein bina naam ke chote aur single-line functions banane ke liye lambda keyword ka use hota hai. Ye tab kaam aate hain jab aapko koi chota operation turant karna ho.
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
## 21. PIP and Package Management
Jab aapko professional development karni hoti hai, toh aapko bahar ki libraries (jaise Data Science ke liye **Pandas**, Web Development ke liye **Django**, AI ke liye **OpenAI/TensorFlow**) ki zaroorat padti hai. Unhe install karne ke liye hum Terminal/Command Prompt mein pip tool ka use karte hain.
```bash
# Terminal mein run karne ke liye commands:

# 1. Kisi library ko install karna
pip install requests

# 2. Installed libraries ki list dekhna
pip list

# 3. Library ko uninstall karna
pip uninstall requests

```

