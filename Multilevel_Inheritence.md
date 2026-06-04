# 5d) Multilevel Inheritance Example in Python

This Python project demonstrates the concept of **Multilevel Inheritance** to collect and display the **name**, **age**, and **location** of a person.

##  Aim

To write a Python program that uses multilevel inheritance to get and display a person’s name, age, and location.

##  Algorithm

1. **Parent Class**  
   - `__init__(name)` initializes the `name` attribute.  
   - `getName()` returns the `name`.

2. **Child Class (inherits Parent)**  
   - `__init__(name, age)` initializes `name` using `super()` and adds `age`.  
   - `getAge()` returns the `age`.

3. **Grandchild Class (inherits Child)**  
   - `__init__(name, age, location)` initializes `name` and `age` using `super()` and adds `location`.  
   - `getLocation()` returns the `location`.

4. **Input & Output**  
   - Take user input for name, age, and location.  
   - Create an instance of `Grandchild`.  
   - Print all details using class methods.

## Program
```
class student:
    def __init__(self,name,age,location):
        self.name=name
        self.age=age
        self.location=location
    def display(self):
        print(self.name,self.age,self.location)
name=input()
age=int(input())
location=input()
obj=student(name,age,location)
obj.display()
```

## Sample Output
<img width="810" height="213" alt="image" src="https://github.com/user-attachments/assets/d830fcbd-de85-4d8a-b376-7d7b5f0697ea" />

## Result
Progrm executed Successfully.
