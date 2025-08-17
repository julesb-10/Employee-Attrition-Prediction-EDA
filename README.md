# Employee Attrition Analysis & Prediction

This project explores the factors driving employee attrition and builds machine learning models to predict whether an employee is likely to leave a company. It combines exploratory data analysis (EDA) with predictive modeling, and concludes with actionable recommendations to reduce attrition.

---

## Project Structure
- **Employee Attrition EDA + Prediction.ipynb** – Main Jupyter Notebook containing EDA, feature engineering, modeling, and recommendations.  
- **Data Source**: [IBM HR Analytics Attrition Dataset](https://www.kaggle.com/datasets/pavansubhasht/ibm-hr-analytics-attrition-dataset)  

---

## Exploratory Data Analysis (EDA)
Using **pandas, numpy, seaborn, matplotlib**, the notebook investigates:  
- Distribution of employee demographics and job-related factors  
- Comparison between employees who stayed vs. those who left  
- Correlations between attrition and variables such as age, salary, tenure, job role, promotions, and work-life balance
- Many visualizations made to show patterns in Attrition and driving factors

### Key Insights
- Employees who left tend to be younger and lower paid compared to their peers and often were working overtime
- Attrition is higher among employees with few years in current role or no recent promotion  
-  Employees who were younger and had worked at several companies before were likely candidates for Attrition
-  Compan's key problem as a whole was keeping new hires for more than 2 years, after which attrition rates dramatically reduced

---

## Machine Learning Approach
The predictive modeling was done with **scikit-learn, Keras, and TensorFlow**.  

### Preprocessing & Feature Engineering
- Encoding categorical variables  
- Handling class imbalance (not fully applied due to resource limits, which impacted performance)  

### Modeling
- Logistic Regression (baseline)  
- Neural Networks (Keras/TensorFlow)  
- Evaluation using accuracy, precision, recall, and F1-score  

### Limitations
- The dataset is imbalanced (far fewer attrition cases than non-attrition)  
- Advanced resampling methods like SMOTE were planned but not fully applied due to memory constraints  

---

## Recommendations
Based on EDA and modeling, the project provides commentary and actionable suggestions:  
- Improve career development opportunities (e.g., timely promotions or raises)  
- Address salary gaps, especially for younger employees  
- Enhance work-life balance policies to retain talent  
- Focus retention efforts on groups with historically higher attrition risk  

---

## Tech Stack
- Python  
- pandas, numpy – data manipulation  
- seaborn, matplotlib – visualization  
- scikit-learn – preprocessing and machine learning models  
- Keras, TensorFlow – deep learning models  

---

## How to Run
1. Clone the repository:  
   ```bash
   git clone https://github.com/yourusername/employee-attrition.git
   cd employee-attrition
