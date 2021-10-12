# Loan Qualifier App

This is a python command-line interface application that allows users to see qualifying loans from lenders quickly and easily. The application works by taking in a `daily_rate_sheet` of loan criteria from various loan providers, asking the user a number of questions to evaluate their loan eligibility, and then returning to them a list of qualifying loans. It finishes by asking if the user would like to save the list of qualifying loans to a new csv file.
---

## Technologies

This project leverages python 3.7 with the following packages:
* [fire](https://github.com/google/python-fire) - for the command line interface, help page and entry-point.
* [questionary](https://github.com/tmbo/questionary) - For interactive user prompts and dialogues. 

---

## Installation Guide

Before running the application, use the package manager [pip](https://pip.pypa.io/en/stable/) to install fire and questionary.

```python
pip install fire
pip install questionary
```

---

## Usage

To use the loan qualifying application, clone the repository and run **app.py** with:

```python
python app.py
```
![Loan Qualifier Prompts](readme_images/loan_qualifier_prompts.png)
---

## Contributors

Brought to you by NB Home Loans

---

## License

MIT
