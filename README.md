# Sentiment Analysis of Amazon Alexa Reviews

## Overview
This project analyzes the sentiment of Amazon Alexa product reviews to classify them as positive or negative. It addresses class imbalance issues using data augmentation techniques and compares the performance of different machine learning models.

## Key Features
- **Class Imbalance Handling:** Techniques like SMOTE and manual upsampling were applied to balance the dataset.
- **Model Evaluation:** Logistic Regression, Random Forest, and XGBoost models were trained and compared.
- **Performance:** Achieved 98% accuracy using Random Forest after hyperparameter tuning.

## Technologies Used
- Python
- scikit-learn
- NumPy, Pandas, Matplotlib

## Dataset
The dataset consists of Amazon Alexa reviews labeled with sentiments (positive or negative). The dataset is included in the `data/` folder.

## Results
- Random Forest: 98% accuracy
- Logistic Regression: 96% accuracy
- XGBoost: 97% accuracy
- Improved model performance through hyperparameter tuning and data augmentation techniques.

## File Descriptions
- **`notebooks/analysis_notebook.ipynb`**: Jupyter notebook with exploratory data analysis and model training steps.

## Instructions to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/Amazon-Alexa-Reviews.git
   cd Amazon-Alexa-Reviews
