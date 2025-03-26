# Customer-Segmentation-Using-Clustering-
Customer segmentation using K-Means clustering to analyze spending behavior, age, income, and gender for targeted marketing strategies
# **Customer Segmentation Using Clustering**

## **Project Overview**
This project applies **K-Means clustering** to segment mall customers based on **age, income, spending behavior, and gender**, helping businesses tailor marketing strategies effectively.

## **Dataset**
- **Mall_Customers.csv**
- Features: CustomerID, Gender, Age, Annual Income (k$), Spending Score (1-100)
- Source: [Kaggle - Mall Customers](https://www.kaggle.com/datasets/vjchoudhary7/customer-segmentation-tutorial-in-python)

## **Technologies Used**
- **Python** (Pandas, Scikit-learn, Matplotlib, Seaborn)

## **Methodology**
1. **Exploratory Data Analysis (EDA)**
2. **Feature Selection & Scaling**
3. **Clustering using K-Means (k=5 determined via Elbow Method)**
4. **Visualization (3D Scatter Plot, Pairplot)**
5. **Interpretation & Business Applications**

## **Key Findings**
- Identified **5 customer segments** based on spending behavior and demographics.
- High-income individuals tend to be more frugal, while younger customers exhibit higher spending scores.

## **Business Applications**
✔ **Targeted Marketing** (customized promotions for different segments)
✔ **Personalized Recommendations** (product suggestions based on spending patterns)
✔ **Store Layout Optimization** (placing high-margin items strategically)

## **Challenges & Improvements**
- Considered **incremental clustering** for adapting to dynamic data.
- Future work: **Hierarchical clustering, real-time updates, and A/B testing on marketing strategies**.

## **How to Run the Project**
1. Clone the repository and install dependencies:
   ```bash
   git clone <https://github.com/Samra029/Customer-Segmentation-Using-Clustering-.git>
   cd customer-segmentation
   pip install -r requirements.txt
   ```
2. Run the Jupyter Notebook:
   ```bash
   jupyter notebook customer_segmentation.ipynb
   ```
3. View clustering results and business insights.

## **Contributors**
- **Samra Zubair**



