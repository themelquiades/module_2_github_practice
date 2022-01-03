# Loan Qualifier App

This is a python command-line interface application that allows users to filter and find loans from multiple lenders quickly and efficiently. The application works by asking users for various information on their desired loan and cross-referencing/qualifying against loan criteria from various lenders taken from a `daily_rate_sheet` 

---

## Technologies

This project leverages python 3.7 with the following packages:

* [fire](https://github.com/google/python-fire) - For the command line interface

* [questionary](https://github.com/tmbo/questionary) - For interactive user prompts and dialogs

---

## Installation Guide

Before running the application, install the following dependencies:

```python
pip install fire
pip install questionary
```

---

## Usage

To use the loan qualifier application simply clone the repository and run the **app.py** with:

```python
python app.py
```

After launching the loan qualifier application you will be greeted with the following prompts:

![Loan app command-line prompts](images/loan_input_screenshot)

* Be sure to input the appropriate path for the current `daily_rate_sheet`


---

## Contributors

Nico Cortese and the lovely folks teaching the Columbia School of Engineering FinTech Coding Boot Camp

nicolasacortese@gmail.com

---

## License

MIT
