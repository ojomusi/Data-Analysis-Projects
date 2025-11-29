# Data Analysis Projects
My projects showcasing data analysis and use of machine learning algorithms.

**Iris Analysis**
_November 2025 - December 2025_
Examined the Iris dataset (Fisher) by analyzing the column distributions. Did ordinary least squares regression to predict the flower, performed principal component analysis (PCA) on the input columns, found correlation between sepal and petal measurements, and identified outliers.

**Percent Body Fat Analysis**
_November 2025 - December 2025_
Examined the UCI Body Fat dataset with an exploratory data analysis on columns, their distributions and correlation. Selected 3 charts that depicted interesting relationships between body measurements and percent of body fat. Used 3 Sklearn regression models, Passive Aggressive Regressor, Huber Regressor, and RANSAC Regressor to plot Target vs. Predictions and find L2 and L1 Losses. Dived deeper into models using 5-fold cross-validation and standardization before ultimately picking RANSAC as the best of the three models for this dataset.

**Continuous Manufacturing Mixing Process Optimization** 

_Feb 2025 - May 2025_


Optimized continuous manufacturing (CM) processes to improve throughput and product quality in pharmaceutical production. Using a Pyomo-based optimization model with IPOPT, I successfully increased throughput by 12% while keeping blend potency within ±10% of the target. Focused on optimizing screw speeds and mass flow, with PD1, PD2, and PD4 handling 86% of total flow, this work resulted in significant reductions in production time and waste. The optimization also enhanced resource utilization and energy efficiency, providing a scalable solution adaptable to changing production needs. Optimization is ~3/4 of the way down on page 38, but you can read through the rest for the imports, data info, data transformation, etc.

Key Achievements:
* Increased throughput by 12%, maintaining blend potency within target range
* Improved mass flow efficiency, with 86% of the flow controlled by three feeders
* Reduced production time and waste, while improving resource utilization and energy efficiency
* Enhanced scalability and flexibility for adapting to dynamic production needs
* Ensured regulatory compliance with optimized processes, minimizing rework and product rejections
  
This project helped drive cost savings, improve product consistency, and provided long-term benefits in scaling manufacturing operations efficiently.

More info about the dataset from the 2024 INFORMS Data-Driven Research Challenge: https://pubsonline.informs.org/doi/10.1287/msom.2024.0860

**Game Recommendations Analysis**

_Mar 2025 - May 2025_

Worked on a machine learning project to predict whether a user would recommend a game based on Steam review data. The project aimed to tackle choice overload, where users feel overwhelmed by the sheer number of games available. Using a dataset with over 41 million rows, I performed data preprocessing, including stratified sampling to balance the recommendation outcomes, and engineered features to optimize model performance. I applied several models, including Decision Trees and Gradient Boosting, and fine-tuned hyperparameters using GridSearchCV to achieve the best results.
Key Achievements:
* Downsampled dataset to 115,000 rows with a 1:1 True/False recommendation ratio, improving model efficiency.
* Implemented Decision Tree and Gradient Boosting models with accuracy rates of 74.04% and 75.10%, respectively.
* Applied out-of-bag sample evaluation, achieving 80.18% accuracy on the best model.
* Used feature selection to optimize models, though it did not improve performance, demonstrating key insights into data handling.
Delivered actionable insights on model performance, with an emphasis on improving generalization by extending the dataset and incorporating additional features.
Dataset: https://www.kaggle.com/datasets/antonkozyriev/game-recommendations-on-steam
