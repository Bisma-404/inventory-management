# Inventory-management-system
**Overview**
This repository contains an Inventory Management System implemented in C. The program allows users to manage a list of products, including adding, updating, deleting, searching, and sorting products. It also features user authentication (sign-in and sign-up) and advanced functionalities like restocking low-quantity items and recording sales. The system uses file handling to store user credentials and inventory data persistently.

**Features**
***User Authentication:***

Sign up to create a new account.

Sign in to access your inventory.

***Inventory Management:***

Add Product: Add new products with details like ID, name, price, quantity, and items sold.

Display Products: View all products in a tabular format.

Delete Product: Remove a product by specifying its ID.

Update Product: Modify product details (name, price, or quantity).

Search Product: Search for a product by its ID.

Product Sold: Record sales and update inventory.

Sorting: Sort products by price, quantity, or name.

Restock: Identify products with low stock (quantity < 10) for restocking.

***File Handling:***

User data is stored in users.txt.

Each user has a separate inventory file named <username>_inventory.txt.

***Error Handling:***

Input validation ensures users enter valid data.

Clear error messages are displayed for invalid inputs or operations.

***User Interface:***

Colored text enhances readability and provides visual feedback.

ASCII art is displayed at the start of the program for a visually appealing introduction.
