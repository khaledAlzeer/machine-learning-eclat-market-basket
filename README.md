# 🛒 Market Basket Analysis – Eclat Algorithm

## Project Overview
This project demonstrates Market Basket Analysis using the **Eclat algorithm** in Python.  
The main goal is to find **frequent itemsets based on Support** and visualize them for business insights.

## Dataset
- **File:** Market_Basket_Optimisation.csv  
- **Transactions:** 7501 rows  
- **Products per transaction:** up to 20  

## Steps in the Project

### 1. Importing Libraries
- NumPy, Pandas, Matplotlib  

### 2. Data Preprocessing
- Read CSV file and convert it to a list of transactions  
- Remove `nan` values  

### 3. Applying Eclat Algorithm
- Extract frequent itemsets based on **Support**  
- Focus on strong associations between products  

### 4. Visualizing Results
- Display top frequent itemsets sorted by Support  
- Professional visualization with:
  - **Support (Red bars)** on primary axis
  - Optional **Confidence & Lift** for additional insights  

### Algorithm Used
- **Eclat Algorithm** for Association Rule Learning  

### Why Eclat?
- Efficiently finds frequent itemsets using **vertical data representation (TID lists)**  
- Focuses on **Support**, making it simple and fast for large datasets  
- Helps in marketing, promotions, and product placement decisions  
- Widely used in retail Market Basket Analysis  

### Model Evaluation
Evaluation focuses on:
- **Support:** How frequently items appear together  
- **Confidence (Optional):** Probability of the consequent given the antecedent  
- **Lift (Optional):** Strength of the association relative to random chance  
- Visualization of top frequent itemsets to interpret product relationships  

### Technologies Used
- Python  
- NumPy  
- Pandas  
- Matplotlib  
