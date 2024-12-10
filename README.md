# B2B Case Study Assignment

This repository contains the files and results for the **B2B Case Study Assignment** as part of the E-Commerce & Retail domain project. The objective of the assignment was to analyze customer payment behaviors and predict the likelihood of delayed payments using machine learning models.

## **Objective**
- Understand and segment customer payment behaviors based on historical data.
- Build a predictive model to identify late payments on open invoices.
- Provide actionable insights to prioritize follow-ups and improve payment timelines.

---

## **Repository Structure**

### 1. **Notebook**
- **`b2b_case_study_final_notebook.ipynb`**:
  - Contains all the code, data processing, exploratory data analysis (EDA), clustering, and machine learning models.
  - Steps included:
    - Data cleaning and preparation.
    - Exploratory data analysis with visualizations.
    - Customer segmentation using K-means clustering.
    - Binary classification using logistic regression and random forest models.
    - Model evaluation and insights.

### 2. **Presentation**
- **`B2b_case_study_final_presentation.pdf`**:
  - A concise, visually appealing summary of the project.
  - Includes:
    - Business context and problem statement.
    - Approach and methodologies used.
    - Key results, insights, and recommendations.

---

## **How to Use This Repository**
1. **View the Presentation**:
   - Download and open `B2b_case_study_final_presentation.pdf` for a summary of the assignment.

2. **Run the Notebook**:
   - Open `b2b_case_study_final_notebook.ipynb` in Jupyter Notebook or Google Colab.
   - Follow the step-by-step analysis and modeling process.

---

## **Key Insights**
1. **Customer Segmentation**:
   - Vendors were segmented into three clusters based on their payment behaviors:
     - Early payers.
     - Medium-duration payers.
     - Prolonged payers (prone to late payments).

2. **Model Performance**:
   - **Logistic Regression**: Simpler, interpretable, with an AUC of 0.83.
   - **Random Forest**: Better performance, achieving an AUC of 0.92 with significant predictive power for late payments.

3. **Actionable Insights**:
   - Prolonged payers have a significantly higher likelihood of late payments.
   - USD amount, invoice month, and payment terms were the most influential predictors.

---

## **Tools and Technologies**
- Python (Jupyter Notebook)
- Libraries: pandas, numpy, matplotlib, seaborn, scikit-learn
- Git for version control

---

## **Contact**
For any questions or issues regarding this repository, please contact:
- **Name**: Prathamesh Salunke
- **Email**: salunke0715@gmail.com
- **GitHub Profile**: [Prathamesh0715](https://github.com/Prathamesh0715)

---

## **Acknowledgments**
Special thanks to:
- **Joydeep Barman** (Subject Matter Expert) for providing insights and guidance.
- UpGrad and IIIT Bangalore for the project framework and resources.
