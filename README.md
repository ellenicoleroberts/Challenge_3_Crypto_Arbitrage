# Crypto Arbitrage


<img src= "images/banner.png" width="930" height="200">

# Loan Qualifier

This application connects a customer in search of a loan with a number of suitable banks. Using command-line-interface (CLI), the customer informs the app of their credit score, monthly debt-to-income ratio, loan-to-value ratio, and the size of their requested loan. The app then uses these metrics to filter through a list of banks, selecting only those which the customer qualifies for. The customer is able to save their list of applicable banks to a spreadsheet.

This application is an efficient and easy solution for the customer to quickly find a custom-tailored list of banks who can offer them a loan.

---

## Technologies

This application leverages python 3.7 with the following packages:

* pandas: an open-source library that offers easy-to-use data analysis tools for Python.
* pathlib: for user prompts and dialogues permitting an interactive experience.
* matplotlib: for creation of file paths allowing the application to interact with a computer's filesystem.

To run this application, first clone the GitHub repo this file is in into your Terminal. Next, to install these packages, while in this same repo in your Terminal, enter `pip install -r requirements.txt`.

---

## Installation Guide

In addition to the normal dependencies above, to install the Loan Qualifier you need to first activate the correct environment with the following comand:

`conda activate dev`

Next, while in this repo within your Terminal, run the app:

`$ python app.py`

---

## Usage

To begin with, the app asks the user to enter a file path to access a list of banks. The user needs to enter the exact filepath, data/daily_rate_sheet.csv, as shown here:

![Prompts customer to enter .csv file path.](images/input_file_path.png)

Next, the user will be prompted to input a number of metrics that quantify their eligibility to apply for a loan at select banks. For example:

![Prompts user to enter various metrics.](images/user_metrics.png)

A list of applicable banks will then be generated depending on the user's eligibility. The user will then be asked if they wish to save their list of banks they qualify for:

![Asks user if they would like to save their list of applicable banks.](images/to_save_list.png)

If the user answers "y", they will be asked to input an output file path (.csv) to save their list of applicable loans to. The application will save the data accordingly and then terminate:

![Asks user if they would like to save their list of applicable banks.](images/saved_list.png)

---

## Contributors

Nicole Roberts,
elle.nicole.roberts@gmail.com

---

## License

[BSD 3](https://choosealicense.com/licenses/bsd-3-clause-clear/): BSD 3-clause is a permissive licence, allowing nearly unlimited freedom with the software as long as BSD copyright and license notice is included.

