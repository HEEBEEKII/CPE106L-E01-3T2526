# Python Beginner Scripts
A collection of three simple Python programs to learn the basics.

## Project Overview
This collection contains three foundational Python scripts designed to demonstrate input/output handling, arithmetic operations, and basic game logic using loops and conditionals.

---

## 1. Hello My Name (Greeting Script)
A simple program that demonstrates how to capture user input and concatenate strings to create a personalized greeting.

### Source Code:
# Get the user's name
name = input("What is your name? ")

# Print a personalized message
print("Hello, " + name + "! Welcome to Python.")

---

## 2. Simple Calculator
This script performs basic arithmetic. It introduces float() conversion, allowing the program to handle decimal numbers for addition and multiplication.

### Source Code:
# Get two numbers from the user
num1 = float(input("Enter first number: "))
num2 = float(input("Enter second number: "))

# Perform calculations
sum_result = num1 + num2
product_result = num1 * num2

# Display results
print("The sum is:", sum_result)
print("The product is:", product_result)

---

## 3. Number Guessing Game
A mini-game where the computer selects a random number between 1 and 10, and the user must guess it. This script demonstrates the use of the random library, while loops, and if/elif/else statements.

### Source Code:
import random

# Generate a random number between 1 and 10
secret_number = random.randint(1, 10)
guess = None

print("I'm thinking of a number between 1 and 10!")

# Loop until the user guesses correctly
while guess != secret_number:
    guess = int(input("Take a guess: "))

    if guess < secret_number:
        print("Too low! Try again.")
    elif guess > secret_number:
        print("Too high! Try again.")
    else:
        print("Correct! You nailed it.")

---

## How to Run
1. Ensure you have Python 3.x installed on your system.
2. Copy the code for any script into a file ending in .py (e.g., calculator.py).
3. Open your terminal or command prompt.
4. Run the script using the command: python filename.py
