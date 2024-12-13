# Python Projects README

## Overview
This repository contains Python projects developed using Jupyter Notebooks. Each project highlights specific programming concepts such as web scraping, object-oriented programming, and advanced mathematical operations.

## Projects

### 1. Web Scraping Project
This project demonstrates how to scrape data from Wikipedia using the Beautiful Soup library. Users can input a search term, and the script fetches relevant information such as infobox details and introductory paragraphs.

#### Key Features:
- Accepts user input for search terms.
- Constructs a Wikipedia URL dynamically.
- Extracts and displays table details and summary paragraphs from the page.

#### Libraries Used:
- `requests`
- `BeautifulSoup` (from `bs4`)
- `string`

---

### 2. OOP Checkpoint
This notebook introduces a basic implementation of an **Account** class to practice object-oriented programming principles.

#### Features:
- **Attributes**: Account number, balance, and holder's name.
- **Methods**:
  - `deposit(amount)`: Adds the specified amount to the balance.
  - `withdraw(amount)`: Deducts the specified amount if sufficient funds are available.
  - `check_balance()`: Returns the current account balance.

#### Example Usage:
```python
my_account = Account("0236155481", 1000.00, "Osato Osazuwa")
my_account.deposit(500)
print(my_account.check_balance())  # Output: 1500.0
my_account.withdraw(200)
```
---

### 3. Calculator 2.0
This project extends the functionality of a basic calculator with object-oriented programming. It includes additional mathematical operations and error handling mechanisms.

#### Key Features:
- **Basic Operations**: Addition, subtraction, multiplication, and division.
- **Advanced Operations**: Exponentiation, square roots, and logarithms.
- **Error Handling**: Manages division by zero and invalid inputs gracefully.

#### Example Usage:
```python
calculator = Calculator()
result = calculator.calculate(10, '+', 5)  # Output: 15
result = calculator.logarithm(100, 10)    # Output: 2.0
```

---

## Prerequisites
Ensure you have the following installed:
- Python 3.x
- Jupyter Notebook
- Required Python libraries: `requests`, `bs4`, `math`

---

## Usage
1. Clone this repository.
2. Open the respective Jupyter Notebook (`.ipynb`) in your Jupyter environment.
3. Run the cells sequentially to execute the code.
