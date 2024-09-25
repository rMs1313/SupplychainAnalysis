# Supply Chain Analysis Project

## Table of Contents
1. [Introduction](#introduction)
2. [Project Structure](#project-structure)
3. [Data Description](#data-description)
4. [Results](#results)
5. [Technologies Used](#technologies-used)

---

### 1. Introduction
This project focuses on analyzing supply chain data to optimize operations and reduce costs. By analyzing transportation modes, defect rates, and product distribution, the project aims to uncover insights that can help companies improve their logistics efficiency.

---

### 2. Project Structure
- `data/` - Contains the dataset used for the analysis.
- `notebooks/` - Jupyter notebooks with the analysis and visualizations.
- `README.md` - Project documentation.

---

### 3. Data Description
The dataset contains the following columns:

- **Product type**: The type/category of the product ( Cosmetics, Skincare, Haircare).
- **SKU**: Stock Keeping Unit, a unique identifier for each product.
- **Price**: The selling price of the product.
- **Availability**: Whether the product is in stock or not.
- **Number of products sold**: The quantity of the product sold.
- **Revenue generated**: The total revenue generated from the sales of the product.
- **Customer demographics**: Information about the customers (e.g., age, location).
- **Stock levels**: Current inventory levels of the product.
- **Lead times**: Time taken from order to delivery.
- **Order quantities**: Number of products ordered in each transaction.
- **Shipping times**: Time taken to ship the product.
- **Shipping carriers**: Companies responsible for shipping the product.
- **Shipping costs**: Costs associated with shipping the product.
- **Supplier name**: The name of the product’s supplier.
- **Location**: The geographic location related to the product (e.g., warehouse, supplier).
- **Lead time**: The time required for suppliers to deliver products.
- **Production volumes**: The number of units produced in a given time period.
- **Manufacturing lead time**: Time taken to manufacture the product.
- **Manufacturing costs**: Costs incurred during the manufacturing process.
- **Inspection results**: Outcome of product quality checks.
- **Defect rates**: Percentage of defective products.
- **Transportation modes**: The mode of transportation used (rail, air, sea, road).
- **Routes**: The transportation routes taken.
- **Costs**: Overall costs associated with the product’s supply chain process (including transportation, production, etc.).


---

### 4. Results
Key insights:
- Skincare products have the most sales
- Haircare Products have the most defect rate. It also showed the highest defect rate accross both sea and air.
- Road transport had the highest transportation costs and also the highest defect rates.
- Product Type B showed the highest defect rates across all transportation modes.

---

### 5. Technologies Used
- Python
- Pandas
- Plotly
- Jupyter Notebook

---
