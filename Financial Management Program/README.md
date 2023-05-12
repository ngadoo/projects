# Program README 

This program is a simple financial tracker that allows the user to record their expenses, incomes, and budgets. The program saves the transactions to separate text files (expenses.txt, incomes.txt, and budget.txt) and provides functionality to view and reset data, as well as display a balance. 

## Prerequisites 

This program is written in C++ and requires a C++ compiler to run. 

## How to use 

Clone the repository or download the files to your computer. 

Compile the program using a C++ compiler. 

Run the compiled executable. 

Use the menu to select an action: 

Add an expense 

Add an income 

Add a budget 

View balance 

View expenses or incomes in a specific day 

Reset data 

### Add an expense, income, or budget 

When selecting to add a transaction, the user will be prompted to enter the name/category and amount. The program will record the transaction in the appropriate text file, along with the current date and time. 

### View balance 

The program will calculate the sum of all expenses and incomes and display the difference as the current balance. 

### View expenses or incomes in a specific day 

The user can view all expenses or incomes recorded on a specific day by selecting this option from the menu and entering the date in the format "day/month/year". If there are no transactions recorded for the specified date, the program will display a message indicating this. 

### Reset data 

The user can reset data for a specific category (expenses, incomes, or budgets) or reset all data by selecting this option from the menu. The program will clear the corresponding text file(s) and display a message indicating success. 
