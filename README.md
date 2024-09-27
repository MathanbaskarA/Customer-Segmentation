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


  
