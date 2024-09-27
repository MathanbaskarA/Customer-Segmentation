# RFM Customer Segmentation Notebook
## Overview
This Jupyter Notebook, `RFM_Analysis.ipynb`, performs RFM (Recency, Frequency, Monetary) analysis to segment customers based on their transaction behavior. The aim is to classify customers into different segments, helping businesses understand their customer base and tailor marketing strategies accordingly.

### 1. **Data Loading and Preparation**
   - Load the customer transaction data from the `Cleaned_dataset.csv` file.
   - Basic data exploration to understand the structure of the data, including columns for customer IDs, transaction dates, and purchase amounts.

### 2. **RFM Metric Calculation**
   - **Recency (R):** How recently a customer made a purchase.
   - **Frequency (F):** How often a customer makes purchases.
   - **Monetary (M):** How much money a customer spends.
   - These metrics are calculated for each customer based on their historical purchase behavior.

### 3. **RFM Segmentation**
   - Assign scores to each customer for recency, frequency, and monetary values on a scale (e.g., 1 to 4).
   - Combine these scores to assign each customer to an RFM segment.

### 4. **Segment Analysis**
   - Identify distinct customer segments such as high-value customers, churned customers, and frequent shoppers.
   - Provide insights and potential strategies for each segment and Visualized by Matplotlib,Seaborn Libraries

### 5. **Data Export**
   - The final segmentation results are saved as a CSV file (`RFM_Segments.csv`), which includes the RFM scores and segment labels for each customer.

## Prerequisites
To run the notebook, ensure you have the following Python packages installed:

- **pandas**: For data manipulation.
- **numpy**: For numerical calculations.
- **matplotlib** and **seaborn**: For data visualization.

# Tableau [**Segmenting customers based on RFM (Recency, Frequency, Monetary) analysis**]

### **RFM Segmentation by Recency, Frequency, and Monetary Value**

1. **Segmenting by Recency**:
   - Shows how recently customers in each category made a purchase.
   - For example, **Best Customers** and **Loyal Customers** tend to have more recent purchases, while **Churned Customers** have a high maximum recency value, indicating they haven’t purchased in a long time.

2. **Segmenting by Frequency**:
   - Depicts how frequently customers in each segment make purchases.
   - **Best Customers** and **Loyal Customers** show higher frequency of purchases, while **Others** and **At-Risk Customers** have lower frequency.

3. **Segmenting by Monetary Value**:
   - Reflects the total spending of customers in each segment.
   - **Best Customers** and **Loyal Customers** contribute more in terms of monetary value, while **Churned Customers** and **Others** spend less overall.

### **Segmenting by Customer Categories**
This page displays customer segmentation into distinct categories based on RFM analysis. The segments include:

1. **Churned Customers**: 405 customers
2. **At-Risk Customers**: 670 customers
3. **Loyal Customers**: 313 customers
4. **Best Customers**: 447 customers
5. **Others**: 2,473 customers

The visualization uses a bar or pie chart to display the distribution of customers across these segments. The size of each segment indicates how many customers fall into each category, giving insight into the overall distribution of customer behavior.
