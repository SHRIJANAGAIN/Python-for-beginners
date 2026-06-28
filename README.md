# Python-for-beginners
Python for beginners 




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
