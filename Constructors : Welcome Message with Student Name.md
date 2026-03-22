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
```
student_name = input("Enter the student's name: ")

class Student:
    def __init__(self):
        self.a = student_name

    def show(self):
        print("This is non-parameterized constructor")
        print(f"Welcome, {self.a}!")

obj = Student()  
obj.show()       
```
## Output
<img width="1092" height="363" alt="image" src="https://github.com/user-attachments/assets/e9920fe2-ac05-4419-91ff-6bcf50bea904" />

<img width="1268" height="277" alt="{C03D20EE-AE53-4AB7-804F-CDC4312C0A14}" src="https://github.com/user-attachments/assets/ee414b7e-f1a3-480f-adfc-5bc14874507d" />

## Result
Hence the code is written and executed.
