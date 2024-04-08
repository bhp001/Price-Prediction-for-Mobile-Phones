Feature Extraction and Price Prediction for Mobile Phones using Python

Project Description:
In this project, I worked with a dataset that contains detailed information about various mobile phones, including their model, color, memory, RAM, battery capacity, rear camera specifications, front camera specifications, presence of AI lens, mobile height, processor, and most importantly, the price. My primary goal is to develop a predictive model for mobile phone prices.

Steps and Methods involved in the Project :
1) Data Exploration :- Started by loading and exploring the dataset to understand its structure, data types, the range of values for each feature etc.
2) Data Preprocessing :- Handled missing values, outliers and inconsistencies in the dataset. Converted categorical variables into a suitable numerical format, using One-hot encoding, Ordinal encoding and Label Encoding.
3) Feature Extraction :- Performed feature extraction to identify the most relevant features that strongly affect the price of mobile phones with Principal Component Analysis (PCA).
4) Model Building and Evaluation :- Splitted the dataset into training and testing sets and Developed a machine learning model for price prediction using various algorithms such as Linear Regression, Decision tree, Random forest and Gradient Boosting and evaluated the performance matrics such as mean absolute error, root mean squared error, R2 score.
5) Feature Importance Analysis :-  Analyzed the feature importances obtained from the model to confirm the significance of the features identified during the feature extraction phase.
6) Report, Visualization and Recommendations :- Created a comprehensive presentation that summarizes the project's findings. Include visualizations and insights about feature importance and their impact on price prediction.

Python Libraries Used - Data science libraries such as Numpy, Pandas, Matplotlib, Seaborn and Machine learning libraries such as Scikit-learn (for Python) for building and evaluating the predictive model in the Jupyter Notebook Environment.



Project Conclusion :-
When we use Principal Component Analysis (PCA) to understand data, the first few components capture the most important information. In this case, PC1 is the most important, showing that it holds a lot of the key details for predicting mobile phone prices. PC2 is also important but not as much as PC1.

When we look at memory size (RAM and storage) in phones, we see that having more memory and storage tends to make a phone more expensive. This is good news for people who care about performance because it means they're getting their money's worth when they buy phones with more memory and storage.

Memory Size (RAM and Storage) : High positive loading in PC1. It means that Phone with more Memory and Storage tends to be priced higher and are important for performance-focused consumers.





