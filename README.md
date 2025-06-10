---
# Budget Planner!

This is a simple yet effective web-based Budget Planner that helps you manage your weekly pocket money by tracking your expenses, categorizing them, and visualizing your spending habits. You can plan payments over multiple months and see how much of your budget is allocated to different categories. It's a very simple way of viewing what you owe and how you can break them down. 

## Features

* **Customizable Weekly Budget**: Set your own weekly budget to see how much you have available after accounting for your planned payments.
* **Monthly Payment Scheduling**: Plan to pay off items over specific months, allowing for long-term financial planning.
* **Item Categorization**: Assign categories like Leisure, Entertainment, Food, Utilities, Clothing, and Other to your expenses for better organization.
* **Automatic Weekly Payment Calculation**: The planner automatically calculates the weekly amount needed to pay off an item based on the total owed and the selected payment period.
* **Summary View**: Get a quick overview of your total weekly commitments and the remaining amount from your budget.
* **Interactive Chart Visualization**: A pie chart displays a breakdown of your weekly spending by category, powered by Chart.js.

## How to Use

To use this budget planner, simply save the provided HTML and JavaScript code as an `.html` file (e.g., `budget_planner.html`) and open it in your web browser.

### Getting Started

1.  **Set Your Weekly Budget**: Enter your desired weekly budget in the "Weekly budget" input field.
2.  **Add an Item**:
    * Enter the **Item name** (e.g., "New Shoes").
    * Enter the **Total owed** amount (e.g., "120.00").
    * Select a **Category** from the dropdown (e.g., "Clothing").
    * Choose a **Start Month** and **End Month** for the payment period. If you plan to pay something off within a single month, select the same month for both start and end.
    * Click the **"Add Item"** button.

### Understanding the Display

* **Table**: The table will display all your added items, including their name, total amount owed, category, the months over which they'll be paid, and the calculated weekly payment.
* **Summary**: Below the table, you'll see a summary showing your **Total Weekly Commitment** (the sum of all weekly payments for your added items) and the **Remaining from your budget** (your weekly budget minus your total weekly commitment).
* **Chart**: A pie chart visualizes your weekly spending, breaking it down by category. This helps you quickly identify where most of your money is going.


## Dependencies
* **Chart.js**: This project uses Chart.js for creating the interactive pie chart. The library is loaded directly from a CDN:
    `<script src="https://cdn.jsdelivr.net/npm/chart.js"></script>`

---