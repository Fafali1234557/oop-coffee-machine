# ☕ OOP Coffee Machine — Python

A simple command-line coffee machine built while learning **Object-Oriented Programming (OOP)** in **Day 16 of Angela Yu's 100 Days of Code: The Complete Python Pro Bootcamp**.

This is my own main-program solution built around the course's starter classes. It helped me practise creating objects, calling methods, and coordinating multiple Python classes.

## ✨ Features

- **Three drinks:** espresso, latte, and cappuccino
- **Ingredient checks:** orders only proceed when enough resources are available
- **Coin payments:** accepts quarters, dimes, nickels, and pennies
- **Change and profit:** gives change and keeps track of earnings
- **Reports:** prints remaining ingredients and money earned
- **Power off:** type `off` to exit
- **Invalid orders:** shows a friendly message instead of crashing for an unknown drink name

## 🛠️ Built with

- Python 3
- Object-Oriented Programming (classes, objects, attributes, and methods)
- Python standard library only — **no `pip install` required**

## 🚀 Run locally

1. Download or clone this repository.
2. Open its root folder in **PyCharm**, VS Code, or a terminal.
3. Run:

```bash
python main.py
```

On Windows, `py main.py` also works if Python is registered with the launcher.

## ☕ Try it out

At the prompt, enter `espresso`, `latte`, or `cappuccino`:

```text
What would you like? (latte/espresso/cappuccino/): latte
Please insert coins.
How many quarters?: 10
How many dimes?: 0
How many nickles?: 0
How many pennies?: 0
Here is $0.0 in change.
Here is your latte ☕️. Enjoy!
```

Other commands:

| Command | Purpose |
| --- | --- |
| `report` | Display remaining water, milk, coffee, and profit |
| `off` | Turn the machine off |
| Other text | Tell you the drink is not available |

## 📁 Project files

All project files live directly in the repository root:

```text
.
├── main.py          # Starts the machine and handles orders
├── menu.py          # MenuItem and Menu classes (course starter)
├── coffee_maker.py  # CoffeeMaker class (course starter)
├── money_machine.py # MoneyMachine class (course starter)
├── README.md
└── .gitignore
```

## 🧠 What I learned

- **Classes and objects:** each class models a part of the machine
- **Attributes:** objects store data like ingredients and money
- **Methods:** objects perform actions like reporting and making coffee
- **Working across files:** importing and using existing classes in `main.py`
- **Program flow:** checking ingredients *before* taking payment

## 🎓 Credits

Project based on **Angela Yu's 100 Days of Code — Day 16**. The starter modules `menu.py`, `coffee_maker.py`, and `money_machine.py` are supplied as part of the learning exercise; `main.py` was developed and adapted for my learning project.

## 👨🏽‍💻 Developer

**Saviour Fafali** — Computer Science student at KNUST, Ghana.

- GitHub: [@Fafali1234557](https://github.com/Fafali1234557)
- LinkedIn: [Saviour Fafali](https://linkedin.com/in/saviourfafali)
