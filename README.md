# Humaid Mohammed's CBSE Project 2022-23

## Overview

Welcome to the **CBSE Project 2022-23** for Grade 11, designed by Humaid Mohammed. This project simulates a point-of-sale (POS) system for a retail store, allowing managers and cashiers to perform various tasks, such as managing inventory, processing sales, and handling customer loyalty programs.

## Features

- **User Authentication:** Different access levels for Managers and Cashiers, ensuring secure operations.
- **Product Management:** View a list of available products with their prices.
- **Sales Processing:** Cashiers can add products to a bill and calculate the total amount.
- **Customer Loyalty Program:** Customers can earn and redeem loyalty points based on their purchases.
- **Member Management:** Managers can view and manage customer accounts and their loyalty points.

## Requirements

Before running the program, ensure you have the following installed:

- Python 3.x
- PrettyTable library

To install the PrettyTable library, run the following command:

pip install prettytable

## Usage

1. **Running the Application:**
   - Open your terminal or command prompt.
   - Navigate to the directory where the project files are located.
   - Run the program using Python:

   python main.py

2. **Choose User Mode:**
   - Enter `1` if you are a **Manager**.
   - Enter `2` if you are a **Cashier**.
   - Enter `0` to exit the application.

3. **Manager Functions:**
   - View members' phone numbers and loyalty points.
   - Check employee data.
   - Switch to cashier mode to assist customers.

4. **Cashier Functions:**
   - View available products and their prices.
   - Enter product serial numbers to create a bill.
   - Process payments and manage loyalty points for customers.

## Code Structure

- **Functions Module:** Contains all the functions for managing operations, such as `manager_mode`, `cashier_mode`, and utility functions for handling member data.
- **Main Module:** Initializes the program, sets up product tables, and handles user input for different modes.

## Sample Output


WELCOME to Humaid Mohammed's CBSE Project 2022-23

If you are a manager please enter 1 to continue
If you are the Cashier then please enter 2 to continue
To Exit the Software enter 0

## Future Enhancements

- Implement a database for persistent data storage.
- Enhance user interfaces for better user experience.
- Include features for product search and inventory management.
- Add detailed reporting features for sales and member statistics.

## Acknowledgements

- Thanks to the developers and contributors of the PrettyTable library for making it easy to display tabular data in Python.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

Feel free to reach out if you have any questions or need assistance regarding this project!



This README provides a comprehensive overview of your project, making it easier for users to understand its purpose, how to set it up, and how to use it. Let me know if you need any modifications or additional sections!
