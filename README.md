# Financial Report Generator / Automate Your Day Job with Python

![Revenue](Images/revenue-per-lead.jpg)


This program "PyBank/main.ipynb" reads in a CSV file of budget data and outputs a financial detail report. The report contains the total number of months, total net profit/loss, average change in profit/loss, best month for increase in profit/loss, worst month for decrease in profit/loss, and the amount for the best and worst months.

## Required Libraries
The following libraries are required to run this program:
* pathlib
* csv
* pandas

## Input
This program takes as input a CSV file containing budget data, with the first row as header and subsequent rows as the data. Each row should have two columns: the first column is the month and year, and the second column is the profit/loss for that month.

## Output
The program outputs a financial detail report that includes the following information:
* Total number of months
* Total net profit/loss
* Average change in profit/loss
* Best month for increase in profit/loss
* Worst month for decrease in profit/loss
* Amount for the best and worst months

## How to Run
The program can be run by simply executing the Python script in a suitable environment that has the required libraries installed. The CSV file should be located in the same directory as the script and named budget_data.csv.

