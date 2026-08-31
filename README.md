This repository contains two Python mini-projects developed to practice data handling, preprocessing, and basic password validation.
## Projects

## 1. Data Imputer Module

A Python program that handles missing values in a dataset using **Pandas** and **NumPy**.

The program creates a sample employee dataset containing missing values in the `Age` and `Department` columns. Missing ages are replaced using the **mean age**, while missing departments are replaced using the **mode**.

The cleaned dataset is then saved as `output.csv`.

#### Features
- Creates a DataFrame using Pandas
- Identifies missing values
- Replaces missing `Age` values with the mean
- Replaces missing `Department` values with the mode
- Exports the cleaned data to a CSV file

#### Technologies Used
- Python
- Pandas
- NumPy

---

### 2. Password Strength Checker

A Python program that evaluates the strength of a password based on its length and character requirements.

The program checks:
- Password length
- Lowercase letters
- Uppercase letters
- Numbers
- Special characters

It provides feedback such as **Weak**, **Medium**, or **Good**, and performs an additional validation using a regular expression.

#### Features
- Accepts password input from the user
- Checks password length
- Validates different character types
- Uses regular expressions for password validation
- Displays password strength feedback

#### Technologies Used
- Python
- Regular Expressions (`re`)

---

## Installation

Install the required libraries for the Data Imputer Module:

```bash
pip install pandas numpy
