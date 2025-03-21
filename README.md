# Predicting Mortality of Heart Failure Patients

## Overview
This project aims to predict the mortality risk of heart failure patients using machine learning techniques. By analyzing clinical data, the model helps in identifying high-risk patients and supports healthcare professionals in decision-making.

## Dataset
The dataset contains patient information including:
- Age
- Gender
- Blood Pressure
- Ejection Fraction
- Serum Creatinine
- Diabetes
- Smoking Status
- Other clinical variables

These features are used to train a predictive model for mortality risk.

## Technologies Used
- **Python**
- **Jupyter Notebook**
- **Pandas** for data preprocessing
- **NumPy** for numerical computations
- **Scikit-learn** for machine learning models
- **Matplotlib & Seaborn** for data visualization

## Model Training
1. **Data Preprocessing**: Handling missing values, scaling, and encoding categorical variables.
2. **Exploratory Data Analysis (EDA)**: Understanding feature distributions and correlations.
3. **Feature Selection**: Choosing the most important features for prediction.
4. **Model Selection**: Training different ML models such as:
   - Logistic Regression
   - Random Forest
   - Support Vector Machine (SVM)
   - XGBoost
5. **Evaluation**: Measuring performance using accuracy, precision, recall, and ROC-AUC score.

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/your-repo/heart-failure-prediction.git
   cd heart-failure-prediction
   ```
2. Install required dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the Jupyter Notebook:
   ```bash
   jupyter notebook
   ```

## Usage
- Open the `Predicting_Morality_Of_Heart_Failure_Patients.ipynb` file in Jupyter Notebook.
- Execute the cells step by step to preprocess data, train models, and evaluate performance.
- Modify parameters to experiment with different models.

## Results
The best-performing model achieves an accuracy of **X%** and an ROC-AUC score of **Y**. The model effectively identifies high-risk patients, assisting healthcare providers in making informed decisions.

## Future Improvements
- Integrate deep learning models (e.g., Neural Networks).
- Deploy the model as a web application.
- Expand dataset with more patient records for better generalization.

## Contributors
- **Your Name** (your email/contact)

## License
This project is licensed under the MIT License.

