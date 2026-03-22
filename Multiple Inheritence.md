# Arithmetic Operations Using Multiple Inheritance in Python

This Python program demonstrates **multiple inheritance** by performing basic arithmetic operations — Addition, Subtraction, and Division — using three classes.

## 🎯 Aim

To write a Python program to calculate **Add, Sub & Division** using **Multiple Inheritance**.

## 🧠 Algorithm

1. **Define `Calculation1` class**
   - Contains `Summation(a, b)` method to return the sum of two numbers.
2. **Define `Calculation2` class**
   - Contains `Subtraction(a, b)` method to return the difference of two numbers.
3. **Define `Derived` class**
   - Inherits from both `Calculation1` and `Calculation2`.
   - Contains `Division(a, b)` method to return the division result.
4. **Input**
   - Prompt the user to enter two numbers.
5. **Process**
   - Create an object of the `Derived` class.
   - Call `Summation`, `Subtraction`, and `Division` methods.
6. **Output**
   - Display the results of the three operations.

## 💻 Program 
```
class Calculation1:
    def Summation(self, a, b):
        return a + b


class Calculation2:
    def Subtraction(self, a, b):
        return a - b


class Derived(Calculation1, Calculation2):
    def Division(self, a, b):
        return a / b   


a = float(input("Enter first number: "))
b = float(input("Enter second number: "))

obj = Derived()
sum_result = obj.Summation(a, b)
sub_result = obj.Subtraction(a, b)
div_result = obj.Division(a, b)

print("Summation:", sum_result)
print("Subtraction:", sub_result)
print("Division:", div_result)
#output
<img width="1113" height="591" alt="image" src="https://github.com/user-attachments/assets/db60ba11-b324-432e-94b4-f21468a6a57e" />
<img width="1167" height="299" alt="image" src="https://github.com/user-attachments/assets/9e90fbc3-3243-42e2-a558-452a1d645db1" />

#result
hence,the code is written and executed successfully
