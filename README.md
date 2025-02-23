# Diabetes Prediction using Machine Learning

## Overview
This project aims to predict the likelihood of diabetes in patients using machine learning techniques. It utilizes patient attributes such as **Pregnancies, Glucose, Blood Pressure, Skin Thickness**, and other health indicators to develop a reliable prediction model.

## Dataset
- The dataset used is the **PIMA Indians Diabetes Dataset**, which contains medical records of female patients aged 21 and older.
- Key features include:
  - **Pregnancies**
  - **Glucose**
  - **Blood Pressure**
  - **Skin Thickness**
  - **Insulin**
  - **BMI**
  - **Diabetes Pedigree Function**
  - **Age**

## Technologies Used
- **Python**
- **Pandas & NumPy** – Data manipulation and preprocessing
- **Seaborn & Matplotlib** – Data visualization and EDA
- **Scikit-learn** – Machine learning modeling

## Data Preprocessing & Feature Engineering
- Handled missing values and outliers.
- Scaled numerical features for better model performance.
- Applied **feature selection and transformation** to improve predictions.

## Machine Learning Models
- **Logistic Regression**
- **Hyperparameter tuning** for optimal performance

## Results
- Achieved **80% accuracy**, making it a useful tool for early detection of high-risk diabetes patients.

## Installation & Usage
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/diabetes-prediction.git
   ```
2. Install required dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the Jupyter Notebook:
   ```bash
   jupyter notebook
   ```

## Repository Structure
```
📂 diabetes-prediction
 ├── 📜 README.md  # Project documentation
 ├── 📜 diabetes_prediction.ipynb  # Jupyter Notebook with full implementation
 ├── 📜 requirements.txt  # Required dependencies
 ├── 📜 dataset.csv  # Dataset used for training
 └── 📂 models  # Saved trained models (if applicable)
```

## Future Improvements
- Implement advanced classification models (e.g., Random Forest, XGBoost)
- Enhance feature engineering techniques
- Deploy as a web application

## License
This project is open-source and available under the [MIT License](LICENSE).
