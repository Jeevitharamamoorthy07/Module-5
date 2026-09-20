# # Constructors in Python: Welcome Message with Student Name

## 🎯 Aim
To write a Python program that creates a **Student** class with a **default constructor** and a method to display a welcome message along with the student’s name provided by the user.

## 🧠 Algorithm
1. **Get user input**: Accept the student's name from the user.
2. **Define the class**: Create a class `Student` with a default constructor (`__init__`).
3. **Default Constructor**: In the constructor, assign the user input (student name) to an instance variable `self.a`.
4. **Display Message**: Define a method `show` that prints "This is non-parameterized constructor" and a welcome message with the student’s name.
5. **Execute the Program**: Instantiate the `Student` class and call the `show` method.

## 🧾 Program
```py
class student():
    def __init__(self, name):
        self.name=name
        print("This is non parametrized constructor")
    def display(self):
        greetings="Hello"
        print(greetings, self.name)
name=input()
c=student(name)
c.display()
```

## Output
<img width="915" height="247" alt="{632B2585-EB37-4457-AD60-C8BC4FED5487}" src="https://github.com/user-attachments/assets/56480a8f-fa8c-4211-ab69-ad3e6145b87e" />

## Result
Thus,the program is executed successfully.

# Destructor in Python

This project demonstrates how to implement a **destructor** in Python using a simple class.

## 🚀 Overview

The program defines a class `Demo` with:

- A **constructor** `__init__` that initializes an instance variable and prints a message.
- A **destructor** `__del__` that prints a message when the object is destroyed.

## 🧠 Algorithm

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
```py
class Demo:
    def live(self):
        print("Alive")
    def __del__(self):
        print("The object no longer exists")
obj=Demo()
obj.live()
del obj
```
        

## 🧪 Output
<img width="688" height="189" alt="{C7A10E35-81DB-4A73-9641-27C5DA27BAD3}" src="https://github.com/user-attachments/assets/be3e53b5-e8e3-43e5-bbd7-23face524c2e" />

## Result
Thus,the program is executed successfully.


