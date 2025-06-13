# Titanic Survival Prediction 🚢🎯

This project predicts the survival of passengers on the Titanic using the Random Forest algorithm. It is based on the dataset provided by Kaggle:  
🔗 [Titanic - Machine Learning from Disaster](https://www.kaggle.com/c/titanic)

## 📊 Features Used
- **Pclass**: Passenger class (1st, 2nd, 3rd)
- **Sex**: (Male/Female)
- **Age**: Age of the person (in years)
- **Embarked**: (S, C, Q)
- **SibSp**: Number of siblings/spouses aboard
- **Parch**: Number of parents/children aboard
- **Fare**: Passenger fare

## ⚙️ Tech Stack
- Python
- NumPy
- Pandas
- Scikit-learn
- Matplotlib
- Seaborn

## 🗂️ Project Structure
 - main.ipynb # Jupyter notebook with complete code
 - requirements.txt # Required packages
 - README.md # Project overview
 - predictions.csv # My submission
 - .gitignore # Ignored files/folders

## ✅ Steps Performed
1. Data Cleaning (handling missing values)
2. Feature Engineering (encoding categorical features)
3. Stratified train-test splitting
4. Data Standardization
5. Model Training (Random Forest)
6. Hyperparameter Tuning with GridSearchCV
7. Model Evaluation

## 🚫 Note
Make sure to add `.ipynb_checkpoints/` to your `.gitignore` file to avoid pushing Jupyter's auto-save files.
