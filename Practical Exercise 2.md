# Modules, Packages & Virtual Environments

## Practical Exercise 2: Creating Packages

## Exercise instructions:

1. Create a new directory called customer_management inside the existing customer_management directory. 
2. Move the customer.py and customer_utils.py files into the new customer_management directory. 
3. Create a new file called __init__.py inside the customer_management directory. Leave this file empty. 
4. Open the main.py file in the root customer_management directory. 
5. Update the import statements in main.py to use the package name when importing the Customer class and utility functions: 
    * Import the Customer class from customer_management.customer 
    * Import the get_preferred_customers and get_customer_emails functions from customer_management.customer_utils 
6. In main.py, use the imported classes and functions: 
    * Load the "Ecommerce Customers.csv" dataset using pandas. 
    * Create instances of the Customer class based on the dataset. 
    * Use the get_preferred_customers function to get the preferred customers and print their information. 
    * Use the get_customer_emails function to get a list of all customer emails and print the list. 
7. Run the main.py script and verify that it works correctly with the new package structure. 
   
**Stretch Activity:**
1. Inside the customer_management package directory, create a new file called customer_analytics.py. 
2. In customer_analytics.py, define a function called get_top_customers(customers, n) that takes a list of customer instances and an integer n as parameters. This function should return a list of the top n customers based on their total amount spent. 
3. Open the main.py file in the root customer_management directory. 
4. Import the get_top_customers function from the customer_management.customer_analytics module. 
5. Call the get_top_customers function with the list of customers and a desired value of n, and print the information of the top customers. 
6. Run the main.py script and verify that the top customers are displayed correctly.
