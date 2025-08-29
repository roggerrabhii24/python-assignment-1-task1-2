# Python Greeting Program

## Overview
This Python program:
1. Takes a user's first name and last name as input.
2. Concatenates them to form the full name.
3. Prints a personalized greeting message including the full name.

---

## How It Works
1. The program uses `input()` to take the first name and last name from the user.
2. It concatenates them with a space in between to form the full name.
3. It prints a greeting message in the format:

```
Hello, <Full Name>! Welcome to the Python program.
```

---

## Code Example
```python
first_name = str(input('Enter Your First Name: '))
last_name = str(input('Enter Your Last Name: '))
full_name = first_name + " " + last_name
print("Hello,", (full_name + "!"), "Welcome to the Python program.")
```

---

## Example Run
```
Enter Your First Name: John
Enter Your Last Name: Doe
Hello, John Doe! Welcome to the Python program.
```
```

---
