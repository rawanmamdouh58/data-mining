# Discription
This project demonstrates a comprehensive approach to analyzing a vehicle dataset, from data preprocessing and exploratory analysis to building and evaluating predictive models. 
The models developed can be used to predict the fuel type of vehicles, which could be valuable for applications such as market analysis, environmental impact studies, and vehicle classification systems.
The use of both classification and ensemble techniques provides insights into the dataset from different perspectives, highlighting patterns and relationships among the features. 
The project also emphasizes the importance of data preprocessing and model evaluation in achieving high accuracy and robustness in predictive modeling.

# Key Steps and Components:
# 1-Data Loading and Preprocessing:

The dataset is loaded from a CSV file using Pandas.

Null values are identified and handled by dropping rows with missing data.

Duplicate rows are removed to ensure data quality.

Categorical features (e.g., brand, bodyType, transmission, fuelType) are encoded into numerical values using LabelEncoder.

# 2-Exploratory Data Analysis (EDA):

Descriptive statistics are computed to understand the distribution of numerical features like year and power.

Histograms and line plots are created to visualize the distribution of categorical features like brand, year, and fuelType.

Insights are derived from the dataset, such as the most common fuel types and the distribution of body types among brands.

# 3-Feature Engineering:

Features are prepared for machine learning by encoding categorical variables and scaling numerical features.

The dataset is split into training and testing sets for model evaluation.

# 4-Predictive Modeling:

Decision Tree Classifier: A decision tree model is trained to predict the fuel type (fuelType) based on features like brand, bodyType, transmission, and year. The model achieves an accuracy of approximately 91.33%.

K-Nearest Neighbors (KNN): A KNN model is implemented to predict the fuel type, achieving an accuracy of approximately 89.47%.

# 5-Ensemble Learning:

Stacking: A stacking ensemble model combining Decision Trees and KNN with a Logistic Regression meta-classifier achieves an accuracy of 92.19%.

Bagging: Bagging classifiers are applied to Decision Trees and KNN, improving model robustness and accuracy.

Random Forest: A Random Forest classifier is also implemented, achieving an accuracy of 93.12%.

# 6-Model Evaluation:

The accuracy of the classification models is evaluated using test data.

Confusion matrices, precision, recall, and F1 scores are computed to assess model performance.

Decision boundaries are visualized using PCA and decision regions for better interpretability.

# 7-Visualization:

Histograms, bar plots, and box plots are used to visualize data distributions and relationships.

Decision trees are visualized using Graphviz and Pydotplus.
