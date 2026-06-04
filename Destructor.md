# 5b) Destructor in Python

This project demonstrates how to implement a **destructor** in Python using a simple class.

## Aim

The program defines a class `Demo` with:

- A **constructor** `__init__` that initializes an instance variable and prints a message.
- A **destructor** `__del__` that prints a message when the object is destroyed.

##  Algorithm

1. Define a class named `Demo`.
2. Inside the class, define the `__init__` method:
   - Initialize an instance variable `status` with the value `"Alive"`.
   - Print the value of `status`.
3. Define the `__del__` method:
   - Print a message indicating the object is being destroyed.
4. Outside the class:
   - Create an instance of the `Demo` class.
   - Delete the object using the `del` keyword.
## Program
```
class Vehicle:
    def __init__(self):
        print("Vehicle created.")
    def __del__(self):
        print("Destructor called, vehicle deleted.")
v1 = Vehicle()
del v1
```
##  Output
<img width="848" height="196" alt="image" src="https://github.com/user-attachments/assets/a87db2bb-4ece-4d82-91eb-83c95d85894d" />

## Result
Program executed Successfully.
