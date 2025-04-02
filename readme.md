# Inventory Management System

## Introduction
This is a simple **Inventory Management System** built using Python. It allows users to **add, remove, update, search, and generate reports** for products in an inventory. The data is stored in a JSON file for persistence.

## Features
- **Add a Product:** Add new products with ID, name, price, and quantity.
- **Remove a Product:** Delete a product using its ID.
- **Update a Product:** Modify the price or quantity of a product.
- **Search for a Product:** Search by product ID or name.
- **Product Report:** Display all products in the inventory.
- **Data Persistence:** The inventory is saved in a `inventory.json` file.

## Requirements
- Python 3.x

## How to Run
1. Clone the repository or copy the script to your local machine.
2. Open a terminal and navigate to the script's directory.
3. Run the script using the command:
   ```bash
   python inventory.py
   ```
4. Follow the on-screen instructions to manage the inventory.

## File Structure
```
|-- inventory.py (Main Script)
|-- inventory.json (Data Storage - Auto-created)
```

## Example Usage
```
Welcome to inventory management. Enter an option:
1. Add a new product to the inventory.
2. Remove a product
3. Update product details
4. Search for a product
5. Generate a product report
6. Exit
```

## Notes
- Ensure the `inventory.json` file is in the same directory as `inventory.py`.
- The system automatically saves and loads data.
- Input validation is handled to prevent invalid entries.

## License
This project is open-source and free to use.

## Author
Developed by **Revathi**

