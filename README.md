# EMI-Calculator
Java program to calculate EMI
EMI Calculator – Java Console Application

This is a simple Java console-based EMI Calculator that computes the monthly loan repayment (EMI) based on the loan amount, annual interest rate, and loan tenure.
It uses the standard EMI formula commonly applied in loan and mortgage calculations.

📌 Features

Accepts user input for:

Loan amount (Principal)

Annual interest rate (in %)

Loan tenure (in years)

Converts annual interest rate to monthly rate

Converts loan tenure from years to months

Calculates EMI using the standard financial formula:

EMI = P × r × (1 + r)ⁿ / ((1 + r)ⁿ − 1)


Displays the calculated monthly EMI amount

🧮 How the EMI Formula Works

The EMI (Equated Monthly Installment) formula is:

EMI = P × r × (1 + r)ⁿ / ((1 + r)ⁿ − 1)


Where:

P = Principal loan amount

r = Monthly interest rate

(Annual interest rate ÷ 12 ÷ 100)

n = Total number of monthly installments

(Tenure in years × 12)

📂 Code Structure
day3/
 └── EMICalculator.java


The program performs:

User input collection via Scanner

Conversion of years → months

Conversion of annual interest → monthly interest

EMI calculation using Math.pow()

Result output to the console

▶️ Running the Program
Prerequisites

Java Development Kit (JDK) 8 or above installed

Steps

Open a terminal/command prompt

Navigate to the folder containing EMICalculator.java

Compile:

javac EMICalculator.java


Run:

java EMICalculator

📝 Example Usage
Enter loan amount in USD
50000
Enter annual interest rate (in %)
7.5
Enter loan tenure in years
5

Your monthly EMI is: 1001.19

💡 Potential Enhancements

Format EMI output to 2 decimal places

Add input validation for negative or invalid values

Calculate and print:

Total payable amount

Total interest payable

Provide an option for multiple calculations in one run

Add support for different currencies

Convert program into a GUI or web-based calculator
