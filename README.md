                                                                                   Mine vs Rock Classification System

This project implements a classification system to distinguish between mines and rocks using sonar signal data. The system is built using **Python** and utilizes **scikit-learn** for machine learning. The primary objective is to analyze sonar signals and accurately predict the type of object detected based on the data collected.

The dataset used in this project is the **Sonar Dataset**, which consists of 208 instances and 60 features. Each instance represents sonar signals, with the last column indicating whether the object is a mine (M) or a rock (R).

## Technologies Used
- Python
- Pandas
- NumPy
- scikit-learn

## Code Explanation
- **Data Loading**: The dataset is loaded into a pandas DataFrame.
- **Data Preprocessing**: Statistical measures and value counts are generated for exploratory analysis.
- **Data Splitting**: The data is divided into training and test sets, ensuring stratification to maintain class distribution.
- **Model Training**: A Logistic Regression model is trained using the training dataset.
- **Model Evaluation**: The model's accuracy is calculated for both the training and test datasets.
- **Prediction**: A predictive system is implemented to classify new sonar signal data.

## Results
The Logistic Regression model achieved:
- **Training Accuracy**: 83.4%
- **Test Accuracy**: 76.2%



