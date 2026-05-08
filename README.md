🚦 Road Traffic Accident Data Analysis

👥 Team 9

Menna Fawzy
Nada Ahmed
Sondos Waheed
Alaa Ibrahim
Menna Allah Taha
📌 Project Overview

This project focuses on analyzing a Road Traffic Accident dataset to understand patterns and factors affecting accident severity.

The goal is to extract meaningful insights that can help improve road safety and decision-making.

🎯 Objectives

Analyze accident severity distribution
Study the impact of road and weather conditions
Explore driver-related factors (age & experience)
Prepare the dataset for further machine learning tasks
🧹 Data Preprocessing

Handled missing values:
Categorical → filled using mode
Numerical → filled using median
Replaced invalid entries (e.g., "NA", "null")
Managed columns with high missing values (casualty-related)
📊 Exploratory Data Analysis (EDA)

Key findings:

Most accidents result in Slight Injury (84.56%)
Serious injuries: 14.15%
Fatal injuries: 1.28%
Most accidents occur on dry roads
Slight injuries dominate across all conditions
👨‍✈️ Driver Insights

Most drivers involved:
Age: 18–30 and 31–50
Driving experience:
Most common: 5–10 years
🚗 Vehicle Insights

Most common vehicle involved:
Automobiles
Followed by:
Lorries and other vehicle types
⚠️ Outliers Analysis

Detected using boxplots and IQR method
Extreme values were analyzed
Some outliers were kept as they represent real-world scenarios
🔄 Encoding

Label Encoding applied to ordinal features (e.g., Accident_severity)
One-Hot Encoding applied to nominal categorical features
Prepared data for machine learning
🧠 Key Insights

Most accidents are not fatal but occur frequently
Road conditions and driver characteristics significantly impact accidents
Data preprocessing is essential for accurate analysis
🔮 Future Work

Apply machine learning models to predict accident severity
Improve dataset quality
Add more real-world features
📁 Tools & Technologies

Python
Pandas
NumPy
Matplotlib
Seaborn
✅ Conclusion

This project highlights the importance of data analysis in understanding road accidents and emphasizes how preprocessing and visualization can uncover meaningful insights.
