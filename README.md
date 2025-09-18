# Experiment-13
## Pytest Python program for Sum of Digits 
# Aim: 
To write a Python program using Pytest for testing the sum of digits of a number.

# Algorithm
Step 1: Write the python program for sum of digits of a number.
Step 2: Make sure that function name should be “def test_*():” and the line to be tested
should have assert keyword at the beginning.
Step 3: Write some test cases for to be tested and save it as “test_sumofdig.py”.
Step 4: Open command prompt and change the directory to where pytest and program is
saved and type “pytest test_sumofdig.py” and run it.
Step 5: Stop the program. 
# Program: 
EX13.py
```
def sum_of_digits(n):
    total = 0
    while n > 0:
        total += n % 10
        n //= 10
    return total
```
TEST_EX13.py
```
from EX13 import sum_of_digits

def test_sum_of_digits():
    print()

    print("sum_of_digits(123) =", sum_of_digits(123))  
    assert sum_of_digits(123) == 6

    print("sum_of_digits(4567) =", sum_of_digits(4567))
    assert sum_of_digits(4567) == 22

    print("sum_of_digits(0) =", sum_of_digits(0))      
    assert sum_of_digits(0) == 0

    print("sum_of_digits(9999) =", sum_of_digits(9999)) 
    assert sum_of_digits(9999) == 36
```
# Output

<img width="1040" height="297" alt="486362392-05619e8c-5a9a-44c5-8702-d7c2b2610869" src="https://github.com/user-attachments/assets/a592424b-7e73-4561-b742-4ff72c242150" />

# Result 
Thus, the Pytest program for Sum of Digits (EX13.py & TEST_EX13.py) was successfully written, executed, and tested. ✅

