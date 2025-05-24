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
```
class Demo:
    def __init__(self):
        self.status = "Alive"
        print(self.status)

    def __del__(self):
        print("Demo object is being destroyed.")

# Create an instance of Demo
d = Demo()

# Delete the object
del d
```

## 🧪 Output
![image](https://github.com/user-attachments/assets/8ec63ed8-6a5b-41f6-b9ca-f40f494d9616)

## Result
Thus,the program is executed successfully
