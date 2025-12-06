# Basic Operations & Greeting (Single Script)

This single Python script performs **basic math operations** on two numbers and then prints a **personalized greeting** using your first and last name.

## 🧩 What it does
- Prompts for two numbers and prints: **Addition, Subtraction, Multiplication, Division**.
- Prompts for **first name** and **last name**, then prints a friendly greeting.

## 📜 Code (combined)
```python
# Task - 1 Perform Basic Mathematical Operations
number1 = int(input("Enter a number: "))
number2 = int(input("Enter another number: "))

addition = number1 + number2
subtraction = number2 - number1
multiplication = number1 * number2
division = number2 / number1

print("Addition:", addition)
print("Subtraction:", subtraction)
print("Multiplication:", multiplication)
print("Division:", division)

# Task - 2 Create a Personalized Greeting
first_name = input("Enter your first name: ").strip()
last_name = input("Enter your last name: ").strip()
full_name = f"{first_name} {last_name}" if first_name and last_name else "(name not provided)"
print(f"Hello {full_name}! Welcome to the Python Program.")
```

## 🧪 Example
**Task-1 Input**
```
Enter a number: 40
Enter another number: 60
```
**Task-2 Input**
```
Enter your first name: Baldutt
Enter your last name: Upadhyay
```

**Task-1 Output**
```
Addition: 100
Subtraction: 20
Multiplication: 2400
Division: 1.5
```
**Task-2 Output**
```
Hello Baldutt Upadhyay! Welcome to the Python Program.
```

## ✅ Notes
- Division by zero is handled gracefully: prints `undefined (division by zero)`.
- `.strip()` removes accidental spaces from names.

---
**Author:** Baldutt Upadhyay
