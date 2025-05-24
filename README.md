# 🔐 PyPassword Generator - Python Project

Welcome to the **PyPassword Generator**, a secure and customizable password generator built using Python. Whether you need a quick password or a strong one with specific requirements, this tool generates a randomized password with letters, symbols, and numbers!

## 🔑 Project Description

This is a simple **command-line password generator** that asks the user how many **letters**, **symbols**, and **numbers** they want in their password. It then randomly selects characters based on your input and shuffles them to produce a strong and unpredictable password.

The project has two main variations:

* **Easy Level (sequential)**: Password characters are added in order.
* **Hard Level (shuffled)**: Password characters are randomized for better security. *(This is the one currently used.)*

### Character Pools:

* Letters: A–Z, a–z
* Numbers: 0–9
* Symbols: `! # $ % & ( ) * +`

## 🧠 What You’ll Learn

* Using Python’s `random` module (`choice`, `shuffle`)
* Working with lists and loops
* Getting user input and converting it to `int`
* Building and joining strings dynamically
* Password security basics (character randomness, shuffling)

## 🛠️ How to Run the Program

1. Make sure you have Python installed (version 3.x).
2. Save the script as `password_generator.py`.
3. Open a terminal or command prompt.
4. Run the script:

   ```bash
   python password_generator.py
   ```

## 💡 Sample Output

```
Welcome to the PyPassword Generator!
How many letters would you like in your password?
> 5
How many symbols would you like?
> 2
How many numbers would you like?
> 3
Your password is: @7gH3a!E2
```

> ⚠️ The output will be different every time due to randomness.

## 📁 Files

* `task.py` — The main script that generates your password.

## 🚀 Future Improvements (Optional Ideas)

* Add option to exclude similar-looking characters (`l`, `1`, `I`, `O`, `0`)
* Add option to copy password to clipboard
* Add GUI version with Tkinter
* Export passwords to a text file
* Enforce minimum security rules (e.g., at least one letter, one number, etc.)

## 📄 License

This project is licensed under the MIT License.
