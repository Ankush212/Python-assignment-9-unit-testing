# Assignment 9: Unit Testing, Logging and Code Quality

## Objective
To understand unit testing, logging and code quality using pytest and Ruff in Python.

## Files Description

1. **order.py** – Implements discount calculation, GST calculation and order total.
2. **test_order.py** – Contains pytest test cases for order processing functions.
3. **logging_demo.py** – Demonstrates DEBUG, INFO, WARNING and ERROR logging levels.
4. **bad_code.py** – Demonstrates code quality checking and formatting using Ruff.
5. **application.log** – Contains generated application log messages.

## Commands Used

### Run Order Program
`python order.py`

### Run Unit Tests
`python -m pytest -v`

### Run Logging Program
`python logging_demo.py`

### Ruff Checks
`ruff check bad_code.py`

### Automatic Fixes
`ruff check bad_code.py --fix`

### Format Code
`ruff format bad_code.py`

### Final Check
`ruff check bad_code.py`

## Tools Used
- Python
- Pytest
- Ruff
- VS Code