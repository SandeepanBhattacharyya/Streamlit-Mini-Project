# Mortgage Repayment Calculator - Streamlit-Mini-Project

A simple Streamlit web application that helps users estimate mortgage repayments based on home value, deposit amount, interest rate, and loan term.

## Features

* Calculate monthly mortgage repayments
* View total repayment amount over the loan term
* Calculate total interest paid
* Visualize the remaining loan balance over time using an interactive line chart
* Simple and user-friendly Streamlit interface

## Technologies Used

* Python
* Streamlit
* Pandas

## Installation

### 1. Clone the repository

```bash
git clone <your-repository-url>
cd mortgage-repayment-calculator
```

### 2. Install dependencies

```bash
pip install -r requirements.txt
```

### 3. Run the application

```bash
streamlit run mortgage_calculator.py
```

The application will open automatically in your browser.

## How It Works

The calculator uses the standard mortgage amortization formula to determine monthly repayments:

* Loan Amount = Home Value − Deposit
* Monthly Interest Rate = Annual Interest Rate ÷ 12
* Monthly Payment is calculated using the amortization formula

The application also generates a payment schedule showing how the remaining balance decreases throughout the loan term.

## Example Inputs

| Parameter     | Value    |
| ------------- | -------- |
| Home Value    | $500,000 |
| Deposit       | $100,000 |
| Interest Rate | 5.5%     |
| Loan Term     | 30 Years |

## Project Structure

```text
├── mortgage_calculator.py
├── requirements.txt
└── README.md
```

## Credit for the inspiration:
[Get Started With Streamlit by pixegami](https://www.youtube.com/watch?v=D0D4Pa22iG0&t=18s)
HAVE FUN

