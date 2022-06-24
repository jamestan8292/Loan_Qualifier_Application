# Loan Qualifier Application

This application filters out a list of loans that a user is qualified for, based on a list of loans provided by the user.

The list of loans must be in a comma-separated values (CSV) file with the following data:
    Lender
    Max Loan Amount
    Max LTV (loan to value) ratio
    Max DTI (debt to income) ratio
    Min Credit Score
    Interest Rate

The application will first ask for the file path and file name, followed by the set of data for the user as given below:
     Credit Score
     Current Amount of Monthly Debt
     Total Monthly Income
     Desired Loan Amount
     Home Value

The application will then calculate and display the Monthly Debt-to_Income Ratio, the Loan-to-Value (LTV) ratio, and number of qualifying loans based on the list of loans provided. The application will then ask if the user would like to save the qualifying loans to a CSV file, and the desired file path and filename.


---

## Technologies

This application is written Python 3.7 with the following packages:

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

In the Mac Terminal app or Windows GitBash app, clone the loan qualifier application repository and run the **app.py** with:

```python
python app.py
```

The following are the prompts you will see in your Terminal app.

![Loan Qualifier Prompts](Images/loan_qualifier_1.png)
![Loan Qualifier Prompts](Images/loan_qualifier_2.png)

---

## Contributors

This application is written by James Tan, with code snippets provided UBC Extension.

---

## License

MIT.
