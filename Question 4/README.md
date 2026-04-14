# Sales Tracker

A Python script that collects, calculates, and organizes sales data for a team of salesmen into a cleanly formatted text-based table.

## How It Works
When executed, the program operates through three main functions:
1. **Data Collection (`user_data`):** Prompts the user to input the name of 10 different salesmen. For each salesman, it requires the user to input sales figures for 5 distinct items.
2. **Error Handling:** Includes a built-in safeguard (`try/except` block) during data entry. If a user accidentally types a letter instead of a number for a sales figure, the program will ask them to try again rather than crashing. 
3. **Calculations:** Automatically tallies the total sales for each individual salesman as the data is entered, while simultaneously keeping a running "Grand Total" of all sales combined.
4. **Output (`display_table`):** Takes all the stored data and formats it into an aligned, easy-to-read table showing each salesman's name, their itemized sales, their individual total, and the final grand total at the very bottom.
