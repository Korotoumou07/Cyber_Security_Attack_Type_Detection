# Cyber Security Attack Type Detection
## Project Overview
This project focuses on detecting and classifying cyber-attacks using Machine Learning techniques.

The objective is to identify different attack categories and improve cybersecurity monitoring systems.


## Business Problem
Cybersecurity threats are increasing rapidly and organizations need intelligent systems capable of identifying malicious activities.

This project aims to:
- Detect cyber-attacks automatically
- Classify attack categories
- Improve threat monitoring
- Support cybersecurity analytics


## Dataset
Dataset: cybersecurity_attacks.csv

Target classes:
- DDoS
- Malware / SQL Injection
- Intrusion
- Normal traffic


## Technologies Used
- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- Streamlit


## Workflow

### 1. Exploratory Data Analysis (EDA)
Analyzed:
- Attack distribution
- Feature correlations
- Network behavior

### 📸 Screenshots 
- Attack distribution chart
<img width="602" height="368" alt="image" src="https://github.com/user-attachments/assets/a95ab80d-028c-44ea-a34a-99e90483f372" />

- Correlation heatmap
<img width="766" height="526" alt="image" src="https://github.com/user-attachments/assets/97782826-665b-4abf-ae71-1e1a24f3706c" />


### 2. Feature Engineering
Performed:
- Data cleaning
- Encoding
- Feature selection
- Data balancing


### 3. Modeling
Models evaluated:
- Logistic Regression
- Random Forest
- Ensemble methods

### 📸 Screenshots 

- Model comparison results
<img width="1368" height="705" alt="image" src="https://github.com/user-attachments/assets/16f7a8d5-f524-4a5e-9a19-769fcc4a98c9" />
- Confusion matrix
<img width="1343" height="698" alt="image" src="https://github.com/user-attachments/assets/e84e45ab-ca95-4f9d-94af-9d083b62a9ba" />
- Classification reports
<img width="1234" height="725" alt="image" src="https://github.com/user-attachments/assets/1f3bfd1b-02c3-47a1-9780-6adbbe615ab2" />



### 4. Streamlit Web Application
Features:
- CSV upload
- Dataset preview
- Real-time prediction
- Threat visualization

### 📸 Screenshots 
- Prediction interface
<img width="1909" height="1077" alt="image" src="https://github.com/user-attachments/assets/f7218ecc-2438-462d-bf8e-5779e6394a11" />
<img width="1897" height="1066" alt="image" src="https://github.com/user-attachments/assets/bb2156c7-e314-40ba-9848-916609793985" />
<img width="1920" height="1069" alt="image" src="https://github.com/user-attachments/assets/2e12dc5e-0db9-4839-b0da-b16c16769c25" />



## Results
Key findings:
- Logistic Regression performed slightly better than other evaluated models
- Feature quality significantly impacted model performance


## Installation
```bash
git clone https://github.com/Korotoumou07/Cyber_Security_Attack_Type_Detection.git
pip install -r requirements.txt
streamlit run Website.py
````


## Future Improvements

* Better feature engineering
* Deep learning models
* Real-time monitoring system



