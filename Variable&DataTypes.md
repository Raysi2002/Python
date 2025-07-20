Sure, Aashish! Let’s dive deep into Variables and Data Types in Python, which are fundamental building blocks for everything you’ll write in Python—including Machine Learning code later on.

⸻

🧠 Python Variables & Data Types — Detailed Guide

⸻

🔹 What is a Variable in Python?

A variable is a name that refers to a value stored in memory. In Python, you don’t need to declare data types explicitly; it’s dynamically typed.

📌 Syntax:

variable_name = value

✅ Example:

name = "Aashish"
age = 22
height = 5.9
is_coder = True

Python automatically understands the type of value and assigns the appropriate data type.

⸻

🔹 Rules for Naming Variables

✅ Can contain letters, digits, and underscores
✅ Must start with a letter or underscore
❌ Cannot start with a number
❌ No special characters (like @, $, %)
❌ Can’t use Python keywords (like if, class, def)

✅ Valid Examples:

first_name = "Preeti"
_age = 22
height2 = 5.8

❌ Invalid Examples:

2height = 5.8      # Starts with digit
first-name = "..." # Contains special character
class = "..."       # 'class' is a keyword


⸻

🧮 Python Data Types (Built-in)

Python has several built-in data types. Let’s categorize and understand them with examples.

⸻

🔸 1. Text Type: str
	•	Represents textual data, enclosed in quotes (single ', double ", or triple ''').

name = "Aashish"
quote = 'Keep going'
multiline = """This
is a multiline string."""

🔧 Common str operations:

len(name)                   # length
name.upper(), name.lower() # case
name[0], name[-1]          # indexing
name[1:4]                  # slicing
"sh" in name               # membership


⸻

🔸 2. Numeric Types

✅ int – Integer (whole numbers)

a = 10
b = -100

✅ float – Floating-point (decimal numbers)

pi = 3.14
height = 5.9

✅ complex – Complex numbers

z = 3 + 4j   # 3 is real, 4 is imaginary
print(z.real, z.imag)  # 3.0, 4.0


⸻

🔸 3. Boolean Type: bool
	•	Only two values: True or False
	•	Often result of comparisons:

is_adult = True
is_minor = False
print(5 > 3)  # True
print(3 == 4) # False


⸻

🔸 4. Sequence Types

✅ list – Ordered, Mutable

fruits = ["apple", "banana", "mango"]
fruits.append("grape")

✅ tuple – Ordered, Immutable

coordinates = (10, 20)

✅ range – Sequence of numbers

nums = range(5)  # 0 to 4


⸻

🔸 5. Mapping Type: dict
	•	Key-value pairs, unordered (in < Python 3.7)

person = {"name": "Aashish", "age": 22}
print(person["name"])  # Aashish


⸻

🔸 6. Set Types: set, frozenset

✅ set – Unordered, Unique, Mutable

s = {1, 2, 3, 3, 2}
print(s)  # {1, 2, 3}

✅ frozenset – Immutable version of set

⸻

🔸 7. None Type: NoneType

Used to represent absence of value (like null in other languages)

result = None


⸻

🔄 Type Conversion (Type Casting)

Python allows conversion between types:

✅ Examples:

int("5")        # 5
float("3.14")   # 3.14
str(123)        # "123"
bool(0)         # False
list("abc")     # ['a', 'b', 'c']


⸻

🧪 Type Checking

Use type() function:

x = 42
print(type(x))  # <class 'int'>


⸻

⚠️ Bonus Tip: isinstance()

Safer way to check type:

if isinstance(x, int):
    print("It's an integer")


⸻

🧠 Practice Exercises (Try These)
	1.	Create variables for your name, age, height, and whether you’re a student.
	2.	Make a dictionary about your favorite movie: title, year, director, genre.
	3.	Convert float 5.7 into int and string.
	4.	Check if the word “Python” is in a given sentence.
	5.	Try creating a set from a list with duplicates.

⸻

Would you like me to create a cheat sheet PDF or exercises with solutions for this?