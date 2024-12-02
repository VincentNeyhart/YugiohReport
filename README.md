# YugiohReport
DSC-140S Yu-Gi-Oh! Project Report
# Overview
This project involves a very in depth look at the yugioh TCG dataset. 

# Dataset:
13,281 Entries, 29 Columns representing every TCG card ever printed, including:
Name
Attributes
ATK/DEF
Level/Rank/Link Value/Pendulum Scale
Type

# Goals
Perform data analysis to answer the research question: Does Yu-Gi-Oh! feature correlating values between basic statistics on cards across archetypes and the entire TCG?

# Key Analyses
1. Exploratory Data Analysis
Correlation Analysis: Examined relationships between features like ATK, DEF, and levels.
Visualizations: Created scatter plots, heatmaps, boxplots, and pie charts to explore data distribution and trends.
Chi-Squared Test: Investigated associations between categorical features (e.g., archetype vs. race).
2. Machine Learning Models
Logistic Regression: Achieved ~40% accuracy in predicting card archetypes using categorical and textual data.
Random Forest Classifier: Improved archetype prediction accuracy to ~43% by incorporating more card attributes.
Random Forest Regressor: Used to predict card levels with ~45% accuracy and 71% accuracy within one level.
Tools and Technologies
Programming Language: Python
Libraries:
Data Analysis: pandas, numpy
Visualization: matplotlib
Statistical Tests: scipy
Machine Learning: scikit-learn
Key Visualizations
Scatter plots and heatmaps to reveal correlations between features.
Boxplots comparing distributions of ATK, DEF, link values, and pendulum scales across card types.
Pie charts showing the distribution of monster races and attributes.
Challenges
Handling extreme outliers in the dataset, such as cards with very high or zero ATK/DEF values.
Managing underrepresented archetypes in machine learning models.
Balancing the complexity of non-linear relationships between features.
Results
EDA revealed trends like a positive correlation between ATK and DEF values.
Machine learning successfully identified patterns but was limited by the diverse and complex nature of the TCG dataset.
