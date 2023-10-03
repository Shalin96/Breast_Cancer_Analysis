# Breast_Cancer_Analysis

Project Title:

Predicting Breast Cancer Diagnosis with Decision Trees

Problem Statement:

Develop a decision tree classification model to predict breast cancer diagnosis (Malignant or Benign) based on tumour characteristics.

Introduction:

Breast cancer is a critical health concern, and early diagnosis is essential for effective treatment. In this project, we utilize decision tree classification to predict breast cancer diagnosis. Our dataset contains various tumour characteristics, and the goal is to create an accurate model for early cancer detection.

Dataset:

The dataset includes 569 samples with 31 features, such as 'radius_mean,' 'texture_mean,' 'perimeter_mean,' and more. The target variable is 'diagnosis,' with two classes: 'M' (Malignant) and 'B' (Benign).

Tools and Statistical Methods:

Programming Language: Python

Environment: Google Colab

Libraries: NumPy, Matplotlib, Seaborn, Pandas, Scikit-Learn


Data Exploration and Insights:

Data Overview:

We loaded the dataset, which consists of 569 samples and 31 features, providing essential information for analysis.


Data Summary: 

Descriptive statistics revealed critical insights, including mean values for features like 'radius_mean' and 'texture_mean.' These statistics serve as an initial understanding of data distribution.


Data Distribution: 

The dataset exhibits a class imbalance, with 'M' (Malignant) being the majority class and 'B' (Benign) as the minority class. Addressing this imbalance may be necessary to optimize model performance.


Decision Tree Modeling:

Data Split: 

We divided the dataset into training (70%) and testing (30%) sets to train and evaluate our decision tree model.

Decision Tree Model: 

Employing a decision tree classifier, we constructed a predictive model to classify breast cancer tumours based on their characteristics.


Model Evaluation:

The decision tree model demonstrated a remarkable accuracy of approximately 92.4% on the test data, showcasing its ability to effectively classify tumour samples.
Visualization:

We generated a visual representation of the decision tree, providing insights into how the model makes classification decisions. This tree plot helps interpret the model's decision-making process.


Feature Importance:

We calculated feature importances and identified that 'radius_worst' played a crucial role in classifying tumours as malignant or benign. Other noteworthy features included 'smoothness_se' and 'concavity_mean.'


Node Description:

A significant finding was the identification of a critical node in the decision tree, where 'radius_worst' emerged as the primary parameter for classification. At this node, the Gini index was 0.466, with a value distribution of [251, 147]. When specific criteria related to 'radius_worst' were met, the model followed the path leading to a classification of 'M' (Malignant). Conversely, when these criteria were not met, the model followed the path leading to a classification of 'B' (Benign).

![Screenshot 2023-10-03 at 3 09 23 PM](https://github.com/Shalin96/Breast_Cancer_Analysis/assets/139086441/043b50c1-b296-4c17-82c9-da7063c724e4)



Conclusion:

In summary, the decision tree classification model proved effective in predicting breast cancer diagnosis based on tumour characteristics. Its high accuracy underscores its value as a tool for early cancer diagnosis. However, it is essential to address the class imbalance and explore further optimizations for enhanced model performance.


Future Work:

Future work may entail tackling class imbalance through techniques like oversampling and exploring alternative machine-learning algorithms to improve model robustness. Additionally, incorporating domain-specific medical knowledge could further enhance the model's diagnostic capabilities.
