🧼 Titanic Dataset Preprocessing
This project focuses on cleaning and preparing the Titanic dataset for analysis and machine learning.

🔍 Data Cleaning
🧠 Filled missing Age values with the median.

🛳️ Filled missing Embarked values with the most common port.

🧺 Dropped the Cabin column due to too many missing entries.

🔁 Encoding Categorical Variables
🚻 Converted Sex to numeric values (male = 1, female = 0).

🚢 One-hot encoded Embarked into separate columns (e.g., Embarked_Q, Embarked_S).

📏 Feature Scaling & Transformation
⚖️ Scaled Age and Fare to standardize values (mean = 0, std = 1).

📉 Applied log transformation to Fare to reduce the effect of high-value outliers.

⚠️ Outlier Removal
🧹 Removed the top 5% of Fare values to limit the impact of extreme outliers.

✅ Final Output
📂 Output file: titanic_cleaned.csv

✅ Contains only cleaned and transformed features ready for machine learning.

🧾 Columns include:

PassengerId, Survived, Pclass, Sex, Age, SibSp, Parch, Fare

Encoded embarkation ports: Embarked_Q, Embarked_S

❌ Excludes columns with text or unstructured data:

Removed: Name, Ticket, Cabin

This cleaned dataset is now ready for modeling, analysis, or visualization.
