# Python-Customer-Data-Churn-Analysis
                    Customer Data Churn Analysis Report

Introduction:

In this analysis, I have leveraged a myriad of data science and machine learning techniques to scrutinize customer churn patterns within the telecommunications sector. By employing Python's robust libraries, including pandas, matplotlib, numpy, scikit-learn, and tensorflow, I created a comprehensive model that not only visualizes but also predicts customer churn with considerable accuracy.

Data Exploration and Preprocessing:

Initially, I performed a thorough data exploration by loading the dataset and sampling random entries to understand its structure. I dropped unnecessary columns and converted the TotalCharges column from an object type to a numeric type, identifying and rectifying any missing values. It is important that for the model all data types are the same and follow a concrete layout. This means changing things like gender from male and female to 0 and 1.

<img width="649" alt="Screenshot 2024-10-31 at 6 31 31 PM" src="https://github.com/user-attachments/assets/94692860-f545-4907-acff-39fb60088d9c">

Visualization:

To gain insights into customer behavior, I created histograms depicting the relationship between churn and features such as tenure and monthly charges. This visualization revealed that customers with shorter tenures and higher monthly charges are more likely to churn.

<img width="677" alt="Screenshot 2024-10-31 at 6 32 19 PM" src="https://github.com/user-attachments/assets/67f6aa46-6670-4cff-8c82-8a8e6f04b5f6">

Data Transformation:

To prepare the data for machine learning, I converted categorical variables to numeric using the replace and get_dummies functions. This included transforming yes/no columns and encoding other categorical variables.
<img width="672" alt="Screenshot 2024-10-31 at 6 32 57 PM" src="https://github.com/user-attachments/assets/1aefbbd7-188e-4716-a926-777b9204985b">

Scaling:

Normalization was crucial for the model’s performance. I applied MinMaxScaler to scale features like tenure, MonthlyCharges, and TotalCharges to a range suitable for machine learning algorithms.

<img width="691" alt="Screenshot 2024-10-31 at 6 33 26 PM" src="https://github.com/user-attachments/assets/d8a67d52-600f-4a14-9d3e-1e5221998b13">

Model Training:

I split the data into training and test sets and developed a neural network model using TensorFlow and Keras. The model comprised layers designed to capture intricate patterns in the data, which were then used to predict customer churn.

<img width="684" alt="Screenshot 2024-10-31 at 6 33 53 PM" src="https://github.com/user-attachments/assets/06a09000-8ba0-4612-9f5d-98a978e2dd57">

Conclusion:

In conclusion, the model achieved an accuracy of 79%, indicating a strong ability to predict customer churn. The confusion matrix and classification report further detailed the model’s precision, recall, and F1 score, underscoring its effectiveness.
Through meticulous data preparation, visualization, and the application of neural networks, I developed a robust model that effectively predicts customer churn. This analysis highlights key areas for potential intervention, helping to reduce churn and improve customer retention
