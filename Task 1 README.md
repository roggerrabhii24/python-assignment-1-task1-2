# Basic Math Operations in Python

## Overview
This Python program takes **two numbers** as input from the user and performs the following basic mathematical operations:

1. **Addition**
2. **Subtraction**
3. **Multiplication**
4. **Division**

It then displays the results for each operation.

---

## How It Works
1. The program prompts the user to enter the first and second numbers.
2. These inputs are converted to `float` so that both integers and decimal numbers can be used.
3. The program calculates:
   - **Sum** (`i1 + i2`)
   - **Difference** (`i1 - i2`)
   - **Product** (`i1 * i2`)
   - **Quotient** (`i1 / i2`)
4. The results are printed to the console.

---

## Code Example
```python
i1 = float(input('Enter The First Number :'))
i2 = float(input('Enter The Second Number :'))

i3 = i1 + i2
print('The sum of two numbers is:', i3)

i4 = i1 - i2
print('The difference of two numbers is:', i4)

i5 = i1 * i2
print('The product of two numbers is:', i5)

i6 = i1 / i2
print('The division of two numbers is:', i6)
```

---

## Note
- This code does **not** handle division by zero. If the second number entered is `0`, the program will raise a `ZeroDivisionError`.  
- To make the program safer, you can add a check before performing division:
```python
if i2 != 0:
    print('The division of two numbers is:', i1 / i2)
else:
    print('Division by zero is undefined!')
```

---

## Example Run
```
Enter The First Number : 10
Enter The Second Number : 5
The sum of two numbers is: 15.0
The difference of two numbers is: 5.0
The product of two numbers is: 50.0
The division of two numbers is: 2.0
```
```
Enter The First Number : 7
Enter The Second Number : 0
ZeroDivisionError: float division by zero
```
