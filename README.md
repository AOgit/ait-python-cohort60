# 🐍 Python Basics Course — AIT TR GmbH (Cohort 60)

Lecture notes and homework assignments from the **Python Basics** course at [AIT TR GmbH](https://ait-tr.de/).  
The course covers the fundamentals of Python programming — from variables and data types to loops and lists.

---

## 📁 Repository Structure

```
ait-python-cohort60/
├── lesson_01/   # Intro to Python
├── lesson_02/   # Variables and data types
├── lesson_03/   # Practical tasks on variables
├── lesson_04/   # Data type str. Input and output
├── lesson_05/   # Functions
├── lesson_06/   # Boolean. Logical data type and basics of logic
├── lesson_07/   # Practical tasks on logical operations
├── lesson_08/   # Conditional operators
├── lesson_09/   # while Loop
└── lesson_10/   # Lists. For loop
```

---

## 🛠️ Tech Stack

| Technology | Details |
|-----------|---------|
| **Python 3** | Core language |
| **PyCharm / VS Code** | IDE (`.idea/` config included) |

---

## 👨‍🏫 Instructor

| Instructor | Lessons |
|-----------|---------|
| **Sergey Bugaenko** | Lessons 01–10 (full course) |

---

## 📚 Lessons

### Lesson 01 — Intro `28.01.2025`
> `lesson_01/`

First steps in Python. Setting up the environment and understanding what programming is.

- What is Python and why it's popular
- Installing Python and PyCharm
- First program: `print("Hello, World!")`
- Comments: `#` single-line, `''' '''` multi-line
- Python syntax basics: indentation, case sensitivity

---

### Lesson 02 — Variables and Data Types `29.01.2025`
> `lesson_02/`

Understanding how data is stored and typed in Python.

- Variables: naming rules, assignment `=`
- Basic data types: `int`, `float`, `str`, `bool`
- `type()` — checking the type of a value
- Dynamic typing in Python
- Constants (convention: `UPPER_CASE`)

---

### Lesson 03 — Practical Tasks on Variables `30.01.2025`
> `lesson_03/`

Practice session — applying knowledge of variables and types.

- Arithmetic operations: `+`, `-`, `*`, `/`, `//`, `%`, `**`
- Integer division and remainder
- Solving practical math tasks with variables
- Swapping variable values

---

### Lesson 04 — Data Type `str`. Input and Output `31.01.2025`
> `lesson_04/`

Working with text data and interacting with the user.

- String creation: single `'`, double `"`, triple `'''` quotes
- String operations: concatenation `+`, repetition `*`
- String methods: `.upper()`, `.lower()`, `.strip()`, `.replace()`, `.split()`, `.find()`, `.count()`
- String indexing and slicing: `s[0]`, `s[1:5]`, `s[::-1]`
- `len()` — string length
- f-strings: `f"Hello, {name}!"`
- `input()` — reading user input
- `print()` — formatted output with `sep`, `end`

---

### Lesson 05 — Functions `03.02.2025`
> `lesson_05/`

Writing reusable blocks of code with functions.

- Defining functions: `def function_name():`
- Parameters and arguments
- Default parameter values
- `return` — returning a value
- Calling functions
- Scope: local vs global variables
- `global` keyword

---

### Lesson 06 — Boolean. Logical Data Type and Basics of Logic `04.02.2025`
> `lesson_06/`

Understanding truth values and logical reasoning in code.

- `bool` type: `True`, `False`
- Comparison operators: `==`, `!=`, `>`, `<`, `>=`, `<=`
- Logical operators: `and`, `or`, `not`
- Truthy and falsy values in Python
- `bool()` — explicit conversion

---

### Lesson 07 — Practical Tasks on Logical Operations `05.02.2025`
> `lesson_07/`

Practice session — applying boolean logic to real tasks.

- Combining multiple conditions with `and` / `or`
- Operator precedence in logical expressions
- Checking ranges: `10 <= x <= 100`
- Practical problem solving with logical operators

---

### Lesson 08 — Conditional Operators `06.02.2025`
> `lesson_08/`

Branching program flow based on conditions.

- `if` / `elif` / `else` statements
- Nested conditions
- One-line ternary: `x if condition else y`
- `match` / `case` (Python 3.10+) — pattern matching
- Practical exercises: grade calculator, number classifier, etc.

---

### Lesson 09 — `while` Loop `07.02.2025`
> `lesson_09/`

Repeating actions while a condition is true.

- `while condition:` — basic syntax
- `break` — exiting the loop early
- `continue` — skipping to the next iteration
- `while True:` — infinite loop with break
- Input validation loops
- Counting and accumulating with `while`

---

### Lesson 10 — Lists. `for` Loop `10.02.2025`
> `lesson_10/`

Storing multiple values and iterating over sequences.

- Lists: `[]`, creating, accessing elements by index
- List methods: `.append()`, `.insert()`, `.remove()`, `.pop()`, `.sort()`, `.reverse()`, `.count()`, `.index()`
- Slicing lists: `lst[1:4]`
- `for item in list:` — iterating over a list
- `range(start, stop, step)` — generating number sequences
- `for` + `range()` — classic counter loop
- Nested loops
- List comprehension: `[x * 2 for x in lst]`

---

## 🚀 Getting Started

```bash
# Clone the repository
git clone https://github.com/AOgit/ait-python-cohort60.git
cd ait-python-cohort60

# Run any lesson file
python lesson_01/main.py

# Or open the project in PyCharm
# (.idea/ configuration is already included)
```

**Requirements:** Python 3.10+

---

## 📖 Course

**AIT TR GmbH** — IT courses for career changers  
🌐 [https://ait-tr.de](https://ait-tr.de)
