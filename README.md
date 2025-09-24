# Inventory-Management-System
A command-line application for managing inventory and logging sales in a department store setting. This system is built using object-oriented principles and modular design.

Features

Add, remove, update inventory items

Search items by keyword

Apply discounts to individual items

Log and track sales transactions

Display inventory summaries and sales reports

Save/load inventory and sales data from files

Requirements

Python 3.6+

No external libraries required (uses only Python Standard Library)

How to Run

Step 1: Download or Clone the Repository - add link here

Step 2: Navigate to the Project Directory - cd inventory-system

Step 3: Run the Program - python main.py (or py main.py)

File Descriptions

inventory_system.py: Contains core classes: Item, InventoryManager, SalesLogger, and IOUtils

main.py: Command-line interface to interact with the system

inventory.txt: (Optional) File storing saved inventory data

sales.txt: (Optional) File storing sales log data

Example Use

When running main.py, a menu will guide you to:

Add an item with ID, name, category, quantity, price, and discount

Update item attributes like price or quantity

Record a sale and automatically reduce inventory

View a sales report and inventory summary

Save data to or load data from text files
