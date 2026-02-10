💰 Python Price Formatter

This Python program demonstrates how to format numeric values using f-strings to create clean, aligned, and readable monetary output.

It showcases advanced formatting options such as:

Thousand separators

Fixed decimal places

Zero padding

Explicit positive and negative signs

📄 File Structure
main.py
README.md

🚀 What This Program Does

Formats three price values using Python f-strings

Displays:

A leading + or - sign

Comma-separated thousands

Exactly 2 decimal places

Zero-padded width for alignment

This is commonly used in financial reports, invoices, and logs.

🛠️ Formatting Breakdown

The format specifier used:

+010,.2f


Means:

+ → always show sign

0 → pad with zeros

10 → total width of 10 characters

, → use commas as thousand separators

.2f → two decimal places (float)

📄 Code Example
price1 = 30023.3344
price2 = -4330001.33
price3 = 1200.3

print(f"Price 1 : ${price1:+010,.2f}")
print(f"Price 2 : ${price2:+010,.2f}")
print(f"Price 3 : ${price3:+010,.2f}")

▶️ How to Run

Make sure Python is installed

Open a terminal in the project folder

Run:

python main.py

📌 Example Output
Price 1 : $+030,023.33
Price 2 : $-4,330,001.33
Price 3 : $+001,200.30

🎯 Learning Objectives

This project helps understand:

Python f-string formatting

Numeric alignment and padding

Financial-style number presentation

Readable console output
