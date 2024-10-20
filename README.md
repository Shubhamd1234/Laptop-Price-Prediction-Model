# Laptop-Price-Prediction-Model

## **Goal of the Model**

The primary objective of this project is to predict laptop prices based on various specifications and features using machine learning techniques. The project involves building, training, and evaluating multiple regression models, including ensemble methods like Voting Regression and Stacking Regression, to achieve accurate price predictions.

## **Source of Data**
The dataset used for training and testing was sourced from **Kaggle**

## **Work Flow**

### Basic Information of Data
- Checked the shape of the dataset, described the columns, verified data types, and performed initial data inspections to understand the dataset's structure.
### Data Preprocessing
- Cleaned the dataset by handling missing values, removing duplicate entries, correcting invalid values, and ensuring data consistency.
### Exploratory Data Analysis (EDA)
- Performed data exploration and feature analysis, visualizing important patterns in the data, including correlation matrices to understand relationships between features and the target variable (price).
### Model Building and Training 
- Trained multiple regression models, including Linear Regression, Decision Tree Regression, and ensemble methods like Voting Regression and Stacking Regression to enhance performance.
### Model Evaluation
- Assessed the model's performance using relevant metrics such as R² score and Mean Absolute Error (MAE). Analyzed results to understand the strengths and weaknesses of each model.

### Conclusion

In this project, I developed a laptop price prediction model and evaluated it using various machine learning algorithms. To improve performance, I applied **Voting Regression** and **Stacking Regression** as ensemble methods.

The results are as follows:
- The **Voting Regression** achieved a mean R² score from cross-validation of **87%**, with an R² score on the training data of **93%**.
- The **Stacking Regression** produced a mean R² score from cross-validation of **86%**, and an R² score on the training data of **91.35%**.
- The overall **Mean Absolute Error (MAE)** was **0.17**, indicating a good level of prediction accuracy.

In conclusion, the ensemble models performed well, with cross-validated R² scores ranging from **86% to 87%**, and training R² scores between **91% and 93%**, making these models suitable for predicting laptop prices.

