# 🧮 Simple Python Calculator

A simple Python program that performs **basic arithmetic operations**: addition, subtraction, multiplication, and division. Perfect for beginners learning Python functions and user input! 🐍✨

---

## Features ⭐

- ➕ Add two numbers  
- ➖ Subtract two numbers  
- ✖️ Multiply two numbers  
- ➗ Divide two numbers (handles division by zero)  
- 🖥️ Interactive menu for choosing operations  

---

## Requirements 🛠️

- Python 3.x  

---

## How to Run ▶️

1. Clone or download this repository.  
2. Open the Python file (`calculator.py`) in your IDE or editor.  
3. Run the script:

```bash
python calculator.py
```
4. Follow the prompts to choose an operation and enter numbers.

### Code Overview 📝

``` bash
def add (a, b):
    return a + b

def subtract (a, b):
    return a - b

def multiply (a, b):
    return a * b

def divide (a, b):
    if b == 0:
        return "Cannot divide by zero"
    return a / b

print ()
print ("===================================")
print ("      Welcome to My Calculator")
print ("           1. Add")
print ("           2. Subtract")
print ("           3. Multiply")
print ("           4. Divide")
print ("====================================")
print ()

choice = input ("Choose (1 / 2 / 3 / 4): ")

print ()
num1 = float (input ("Enter first number: "))
num2 = float (input ("Enter second number: "))

print ()
if choice == "1":
    print ("Result:", add (num1, num2))
elif choice == "2":
    print ("Result:", subtract (num1, num2))
elif choice == "3":
    print ("Result:", multiply (num1, num2))
elif choice == "4":
    print ("Result:", divide (num1, num2))
else:
    print ("Invalid choice")
print ()
```
### How it Works 🔍

1. The program displays a menu for selecting an operation.
2. The user enters their choice (1-4)
3. The program asks for two numbers.
4. It performs the chosen operation using the corresponding function.
5. The result is displayed.
6. If division by zero is attempted, it shows a friendly error message.

### Example Output 📸
[![Calculator](https://github.com/owaiskazmi/Calculator/blob/main/Screenshots/SS1.png)](https://github.com/owaiskazmi/Calculator/blob/main/Screenshots/SS1.png)
