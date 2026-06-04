# Module 5
# 5a)  Constructors in Python: Welcome Message with Student Name

##  Aim
To write a Python program that creates a **Student** class with a **default constructor** and a method to display a welcome message along with the student’s name provided by the user.

##  Algorithm
1. **Get user input**: Accept the student's name from the user.
2. **Define the class**: Create a class `Student` with a default constructor (`__init__`).
3. **Default Constructor**: In the constructor, assign the user input (student name) to an instance variable `self.a`.
4. **Display Message**: Define a method `show` that prints "This is non-parameterized constructor" and a welcome message with the student’s name.
5. **Execute the Program**: Instantiate the `Student` class and call the `show` method.

##  Program
```
class Student:
  
    def __init__(self):
        print("This is non parametrized constructor")
    def display(self, name):
        print("Hello", name)
student_name = input()
obj = Student()
obj.display(student_name)
```
## Output
<img width="897" height="244" alt="image" src="https://github.com/user-attachments/assets/77bb0c5c-d2da-42c2-af05-02db2116cbf5" />

## Result
Program executed Successfully.
