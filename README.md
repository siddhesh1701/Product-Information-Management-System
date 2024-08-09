# Product-Information-Management-System
Product Information Management System
# Introduction
Accurate and efficient management of product information is crucial for e-commerce businesses to succeed. This includes handling product details, sales data, and descriptions, which enable informed decision-making and effective marketing strategies. Traditional methods of managing this data can be error-prone and inefficient due to manual entry and maintenance processes. This project aims to automate these tasks using Python, providing a streamlined approach to managing product information and enhancing operational efficiency.

# Problem Statement
In the fast-paced e-commerce sector, organizing and updating product information is vital. Without a robust system, inconsistencies and errors can arise, leading to operational inefficiencies. As a software developer for an e-commerce technology company, your task is to automate the management of product details, sales data, and descriptions. The goal is to implement functionalities that allow seamless addition, reading, updating, and deletion of product information.

# CRUD Operations Overview
CRUD operations represent the four basic functions required to interact with a database or data storage system:

* Create: Add new records.
* Read: Retrieve existing data.
* Update: Modify existing records.
* Delete: Remove records.
* Understanding CRUD operations is fundamental for developers working with databases and data management systems.

# Project Structure
The project includes the following components:

# Folder Structure
* main_folder: Contains data files and subfolders.
* sales_data.csv: Contains sales data for various products over 14 days.
* product_details: Contains JSON files with product details.
* product_description: Contains TXT files with product descriptions.
# Data Files
* sales_data.csv: Contains sales data where each row represents a product identified by Product_SKU, and each column represents sales numbers for a specific day (Day1 to Day14).
* product_details: JSON files named after product SKUs with detailed product information.
* product_description: TXT files named after product SKUs with product descriptions.
# Implementation Steps
* Q1: Set Up the Environment
Import the following packages:
os for handling file paths.
json for working with JSON files.
csv for handling CSV files.
pprint for pretty-printing data structures.
* Q2: Load Data
Write a function load_data() to:
Load sales data from sales_data.csv.
Load product details from JSON files in product_details.
Load product descriptions from TXT files in product_description.
* Q3: Explore the Data
Display the content of:
sales_data dictionary.
product_details dictionary.
product_descriptions dictionary.
Create a list product_skus with SKUs from one of the dictionaries.
Display data for a specific product using product_skus.
Find and display the length of each dictionary.
* Q4: Add New Product
Implement functions to:
add_sales_data(): Add sales data for a new product (e.g., Acer Aspire 3).
add_product_details(): Add product details for the new product.
add_product_description(): Add product description for the new product.
create(): Call the above functions to add a new product.
* Q5: Review Product Details
Implement functions to:
display_sales_data(): Display sales data for a specific product.
display_product_details(): Display product details.
display_product_descriptions(): Display product description.
read(): Call the above functions to review a product's information.
* Q6: Update Product Information
Implement functions to:
update_sales_data(): Update sales data.
update_product_details(): Update product details.
update_product_descriptions(): Update product description.
update(): Call the above functions to update product information.
* Q7: Delete Product Information
Implement a function delete() to remove all information related to a product, including:
Sales data.
Product details.
Product description.
# How to Run
* Set Up: Ensure you have all necessary packages installed.
* Load Data: Use the load_data() function to load the initial data.
* Explore Data: Use provided functions to explore and verify data.
* Add Product: Use the create() function to add a new product.
* Review Product: Use the read() function to review product information.
* Update Product: Use the update() function to make updates.
* Delete Product: Use the delete() function to remove a product.
# Data Access
The dataset and files used in this project are located in the folder named "LW - Python Project - FileHandler". Ensure this folder is correctly set up in your environment.
