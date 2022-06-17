# ATM Functions Activity CLI

This is a command-line interface application for nagivating an ATM machine. It allows you to check balances and make withdrawals/deposits after inputting your 6 digit PIN. It is written in python. 

---

## Technologies

This project leverages python 3.7 with the following packages:

* [fire](https://github.com/google/python-fire) - For the command line interface, help page, and entry-point.

* [questionary](https://github.com/tmbo/questionary) - For interactive user prompts and dialogs

--- 

## Installation Guide

Before running the application first install the following dependencies.

```python
  pip install fire
  pip install questionary
```

---

## Usage

To use the ATM Functions Activity application, simply clone the repository and run **atm.py**.

Upon launching, you will first be greeted with the following prompt to input your pin. 

![ATM Function PIN](Unsolved/atm/Screenshot%202022-06-16%20203131.png)

Once you enter a correct pin, it will then ask you to choose what action you'd like to complete.

![ATM Function Questions](Unsolved/atm/Screenshot%202022-06-16%20203413.png)

---

## Contributors

Brought to you by Rice University Fintech Bootcamp. 
Edited by Brittanie Polasek

---

## License

MIT