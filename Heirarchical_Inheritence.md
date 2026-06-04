# 5c)  Hierarchical Inheritance in Python

This Python project demonstrates **Hierarchical Inheritance** using a base class `Details` and two derived classes `Doctor` and `Patient`. The program collects and displays details for both employees and patients.

##  Aim

To write a Python program that uses **Hierarchical Inheritance** to input and display **Doctor** and **Patient** details.

##  Description

- **Base Class:** `Details`
  - Stores common attributes: `name`, `age`
  - Provides methods: `getName()`, `getAge()`

- **Derived Class 1:** `doctor`
  - Inherits from `Details`
  - Adds: `Doctor_id`, `department`
  - Method: `getDoctorDetails()`

- **Derived Class 2:** `Patient`
  - Inherits from `Details`
  - Adds: `patient_id`, `disease`
  - Method: `getPatientDetails()`

##  Algorithm

1. Create base class `Details` with common attributes.
2. Create `Doctor` class extending `Details`, adding employee-specific data.
3. Create `Patient` class extending `Details`, adding patient-specific data.
4. Get user input for Doctor and patient data.
5. Display collected information using class methods.

## Program
```


class Details:
    def __init__(self, id, name, gender, hospital, department):
        self.id = id
        self.name = name
        self.gender = gender
        self.hospital = hospital
        self.department = department


class Doctor(Details):
    def display(self):
        print("Doctor Object")
        print("Id: ", self.id)
        print("Name: ", self.name)
        print("Gender: ", self.gender)
        print("Hospital: ", self.hospital)
        print("Department: ", self.department)
        print()


class Patient(Details):
    def display(self):
        print("Patient Object")
        print("Id: ", self.id)
        print("Name: ", self.name)
        print("Gender: ", self.gender)
        print("Hospital: ", self.hospital)
        print("Department: ", self.department)
        print()



doc_id = int(input())
doc_name = input()
doc_gender = input()
doc_hospital = input()
doc_department = input()


doctor = Doctor(doc_id, doc_name, doc_gender, doc_hospital, doc_department)


pat_id = int(input())
pat_name = input()
pat_gender = input()
pat_hospital = input()
pat_department = input()


patient = Patient(pat_id, pat_name, pat_gender, pat_hospital, pat_department)


doctor.display()
patient.display()
```
## Sample Output
<img width="721" height="458" alt="image" src="https://github.com/user-attachments/assets/c7c66c36-6eb0-4d5f-9a56-ebb818449428" />

## Result
Program executed Successfully.

