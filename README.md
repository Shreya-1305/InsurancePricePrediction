# 📈 Insurance Price Prediction using Machine Learning

This project predicts insurance costs using a machine learning model based on features such as age, sex, BMI, number of children, smoking status, and region. The model uses Linear Regression from scikit-learn and includes optimization techniques to improve accuracy.

## 📝 Dataset
The dataset consists of:
- **Age**: Age of the primary beneficiary
- **Sex**: Gender of the beneficiary (male/female)
- **BMI**: Body Mass Index
- **Children**: Number of dependents covered by health insurance
- **Smoker**: Smoking status (yes/no)
- **Region**: Residential area in the US (northeast, northwest, southeast, southwest)
- **Charges**: Actual medical costs billed to health insurance

## 🚀 Project Overview
1. **Data Preprocessing**:
   - Encoding categorical variables using One-Hot Encoding
   - Data normalization and scaling
   - Splitting the dataset into training and testing sets

2. **Model Building**:
   - Linear Regression model using scikit-learn
   - Model training and prediction

3. **Model Evaluation**:
   - Performance metrics: Mean Squared Error (MSE) and R² Score
   - Model optimization to improve prediction accuracy

4. **Results**:
   - Achieved strong predictive accuracy
   - Successfully minimized prediction errors

## 🛠️ Tech Stack
- **Python**: Core programming language
- **Pandas**: Data manipulation and analysis
- **NumPy**: Numerical operations
- **Scikit-learn**: Machine learning model implementation
- **Matplotlib/Seaborn**: Data visualization (if applicable)

## 💻 How to Run
1. Clone the repository:
```bash
git clone https://github.com/yourusername/insurance-price-prediction.git
cd insurance-price-prediction
