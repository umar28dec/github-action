# My Calculator Project

This project is a simple calculator that performs basic arithmetic operations such as addition, subtraction, multiplication, and division. It is designed to help users understand how to implement a calculator in Python and how to set up continuous integration using GitHub Actions.

## Project Structure

```
my-calculator-project
├── src
│   └── calculator.py       # Contains the implementation of the calculator
├── tests
│   └── test_calculator.py   # Contains test cases for the calculator functions
├── .github
│   └── workflows
│       └── ci.yml          # GitHub Actions workflow for continuous integration
├── requirements.txt         # Lists the dependencies required for the project
└── README.md                # Documentation for the project
```

## Installation

To set up the project, follow these steps:

1. Clone the repository:
   ```
   git clone https://github.com/yourusername/my-calculator-project.git
   cd my-calculator-project
   ```

2. Install the required dependencies:
   ```
   pip install -r requirements.txt
   ```

## Usage

To use the calculator, you can import the `calculator` module from the `src` directory and call the desired functions. For example:

```python
from src.calculator import add, subtract, multiply, divide

result = add(5, 3)
print(result)  # Output: 8
```

## Running Tests

To run the tests, you can use the following command:

```
pytest tests/test_calculator.py
```

Make sure you have `pytest` installed, which can be done via:

```
pip install pytest
```

## Continuous Integration

This project uses GitHub Actions for continuous integration. The workflow is defined in the `.github/workflows/ci.yml` file. It automatically runs tests and checks code quality on every push and pull request.

## License

This project is licensed under the MIT License. See the LICENSE file for more details.