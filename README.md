# 6-Digit Password Maker

This project is a simple Python script that generates a 6-digit password using random choices from a predefined set of characters.

## How I Made It
I started by importing the `random` module in Python. Then, I created a list of characters (`["0", "1", "A", "G", "4", "K"]`) from which the password will be formed. Using the `random.choice()` function, I selected six random characters from this list. The program takes an input from the user, and if the input matches `"make password"`, the script prints out the generated password.

## How It Works
When the program runs, it waits for the user to enter a command. If the user types `"make password"`, the script randomly picks six characters from the predefined list and joins them to form a password. This password is then displayed on the screen. Each run generates a different password because of the randomness.

Example:Input: make password
Output: A4GK10 is your password

## Core Functions
- `input()` → Takes the command from the user.
- `random.choice(my_list)` → Picks a random element from the provided list.
- `print()` → Displays the generated password.

## Code
```python
import random

A = input()
my_list = ["0", "1", "A", "G", "4", "K"]
B = random.choice(my_list)
G = random.choice(my_list)
H = random.choice(my_list)
I = random.choice(my_list)
J = random.choice(my_list)
K = random.choice(my_list)

if A == "make password":
    print(B + G + K + H + I + J + " is your password")

This script is a basic random password generator and helps in learning how randomization and user input handling works in Python.
