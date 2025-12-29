# Cafe-Management-System-Python-
A Python-based interactive cafe management system that handles digital menu display, order placement, and automated billing using dictionaries and conditional logic
📌 Project Overview
This is a simple, interactive Restaurant Management System built using Python. It allows customers to view a digital menu, place an order for multiple items, and receive an instantly calculated bill. This project is ideal for understanding how data structures like dictionaries work in real-world applications.

🛠️ Key Features
Digital Menu: A pre-defined list of food items and drinks with their prices.

Interactive Input: Users can type in the name of the item they wish to order.

Availability Check: The system validates if the item is present in the menu before adding it to the bill.

Dynamic Billing: Automatically calculates the total cost based on user selection.

💻 Technologies Used
Python 3.x

Data Structures: Dictionaries (for menu storage).

Logic: Conditional Statements (if-else) and formatted strings (f-strings).

📋 How the Code Works
Define Menu: The items are stored in a dictionary where the key is the item name and the value is the price.

Order Placement: The script takes user input for the first item.

Validation: If the item exists in the dictionary, its price is added to the order_total.


Multi-item Support: The script asks if the user wants to add another item. If "Yes", it repeats the selection process.

Final Output: Displays the total amount due.
