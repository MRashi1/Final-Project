# Final-Project

**Predicting Employee Attrition and Layoff Trends Using Machine Learning
Project Overview**

This project aims to analyze and predict employee attrition and layoff trends using machine learning. The dataset contains demographic details, job satisfaction scores, salary information, layoff records, and exit interview feedback to build predictive models that can help businesses retain employees and understand the reasons behind workforce movement.

**Repository Structure**

📂 Employee_Attrition_Prediction
 
 ├── 📁 data                     # Raw and processed datasets
 
 ├── 📁 notebooks                # Jupyter Notebooks for data preprocessing and modeling
 
 ├── 📁 models                   # Trained machine learning models
 
 ├── 📁 reports                  # Analysis reports and presentations
 
 ├── 📁 scripts                  # Python scripts for data processing and model training
 
 ├── 📄 README.md                # Project documentation (this file)
 
 ├── 📄 requirements.txt         # Required Python libraries
 
 ├── 📄 LICENSE                  # Licensing information
 
**Dataset Overview**


Source: Public HR datasets (Kaggle, Glassdoor, LinkedIn Analytics)

Format: CSV, JSON

Size: ~500MB

Number of Records: ~100,000 employee data points

Features:Employee ID, Age, Gender, Job Role, Department, Salary, Work Experience
Work-Life Balance, Job Satisfaction Score, Layoff Reason, Attrition Type, etc.

**Machine Learning Techniques Used:**

Classification Models: Logistic Regression, Random Forest, XGBoost (Predicting if an employee will leave)

Clustering Models: K-Means (Grouping employees based on attrition risk)

Natural Language Processing (NLP): BERT for sentiment analysis of exit interviews

Anomaly Detection: Isolation Forest to detect unusual layoff trends\

**Installation and Setup:**

**1. Clone the Repository**
git clone https://github.com/yourusername/Employee_Attrition_Prediction.git
cd Employee_Attrition_Prediction

**2. Install Dependencies**
pip install -r requirements.txt

**3. Running the Jupyter Notebook**
jupyter notebook
Open notebooks/Attrition_Prediction.ipynb and run the cells.

**Version Control**

GitHub Repository: https://github.com/MRashi1/Final-Project

Commit Frequency: Weekly commits with clear descriptions.

File Naming Convention:

attrition_data_v1.csv - Initial dataset

ml_model_v1.ipynb - First model implementation

**Ethical Considerations**

GDPR Compliance: Data is anonymized and does not contain personal identifiers.

UH Ethical Approval: Data usage aligns with university guidelines.

Permission for Data Use: Sourced from publicly available datasets.

Bias Mitigation: Ensuring fair treatment across demographics.

**Expected Outcomes**

A machine learning model that predicts employee attrition trends.
Insights into key factors affecting employee retention.
Recommendations for HR strategies to reduce turnover.

**Contributors**

Rashi Meda

University of Hertfordshire

Supervisor: William Alston

**License**

This project is licensed under the MIT License.

