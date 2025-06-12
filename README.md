🔎 Exploratory Data Analysis (EDA) - Breast Cancer Dataset

📌 Project Overview

This project applies Exploratory Data Analysis (EDA) techniques to examine and summarize key insights from a breast cancer dataset. The primary goal is to understand the distribution of features, identify potential relationships.

🛠️ Technologies Used
- Python (Pandas, NumPy)
- Matplotlib & Seaborn (for visualizations)
- Scikit-learn (for data preprocessing and encoding)

  📊 Key Steps in EDA
  
- Dataset Exploration
- Understanding the dataset shape and structure
- Checking data types & distinguishing categorical and numerical columns
- Data Cleaning & Preprocessing
- Removing unnecessary columns (Unnamed: 32, id)
- Checking for missing values (none found)
- Descriptive Statistics & Distributions
- Summary statistics (mean, median, std) to detect skewness
- Checking class distribution (Benign vs Malignant)
- Target Encoding & Group-wise Analysis
- Encoding diagnosis into a numerical target variable
- Grouping by target to observe differences in mean values
  
🔍 Insights & Findings
- No missing values in the dataset
  
- The dataset has a slight imbalance (Benign: 357 | Malignant: 212)
  
- Most feature values are higher for malignant cases compared to benign
  
- The mean of several features exceeds the median, indicating right skewed distributions
  

 🚀 How to Run
 
- Install dependencies: pip install pandas numpy matplotlib seaborn scikit-learn
  
- Run the Python notebook: jupyter notebook EDA_Breast_Cancer.ipynb
  
📂 Repository Structure

/EDA_Breast_Cancer  
│── data/                # Raw dataset  
│── scripts/             # Preprocessing & visualization scripts  
│── README.md            # Project documentation  
│── EDA_Breast_Cancer.ipynb  # Full analysis notebook


📢 Conclusion
This EDA process provides a strong foundation for further data modeling and classification. Potential next steps include feature engineering, scaling techniques, and applying classification algorithms for predictive insights.










