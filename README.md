# 🚗 AutoSale Prediction

## 📌 Project Overview
AutoSale Prediction is a Machine Learning project that predicts automobile prices using vehicle specifications and a Decision Tree Regression model. It uses Python and Scikit-learn to analyze automobile data, preprocess the dataset, train the model, and evaluate prediction performance.

## 🎯 Objectives
- Predict automobile prices using machine learning.
- Clean and preprocess automobile datasets.
- Understand the relationship between vehicle features and prices.
- Evaluate model performance using regression metrics.
- Explore hyperparameter tuning to improve model performance.

## 🛠️ Technologies Used
- **Python** – Programming language
- **Pandas** – Data manipulation and analysis
- **NumPy** – Numerical computations
- **Matplotlib** – Data visualization
- **Seaborn** – Statistical visualization
- **Scikit-learn** – Machine learning and model evaluation
- **Jupyter Notebook** – Development environment

## 📂 Dataset
The project uses `autos_dataset.csv`, which contains automobile information, including vehicle specifications such as:
- Number of cylinders
- Horsepower
- Peak RPM
- Automobile price

## ⚙️ Project Workflow
1. Import the required Python libraries.
2. Load and explore the automobile dataset.
3. Clean missing values and convert data types.
4. Select input features and the target variable (`price`).
5. Split the dataset into training and testing sets.
6. Train a Decision Tree Regressor.
7. Evaluate predictions using regression metrics.
8. Explore hyperparameter tuning using GridSearchCV.

## 🤖 Machine Learning Algorithm
**Decision Tree Regression**

The model learns patterns from automobile features to estimate vehicle prices.

## 📊 Evaluation Metrics
The model is evaluated using:
- **MAE (Mean Absolute Error):** Measures the average absolute prediction error.
- **MSE (Mean Squared Error):** Measures the average squared prediction error.
- **RMSE (Root Mean Squared Error):** Measures the square root of the average squared error.
- **R² Score:** Measures how well the model explains variation in automobile prices.

## 🚀 How to Run the Project

1. Clone the repository:
   ```bash
   git clone https://github.com/SanketBacche/Machine-Learning-Project.git
   ```

2. Navigate to the project folder:
   ```bash
   cd Machine-Learning-Project
   ```

3. Install the required libraries:
   ```bash
   pip install numpy pandas matplotlib seaborn scikit-learn jupyter
   ```

4. Place `autos_dataset.csv` in the appropriate working directory.

5. Open Jupyter Notebook:
   ```bash
   jupyter notebook
   ```

6. Open the AutoSale Prediction notebook and run the cells.

## 💡 Applications
- Automobile price estimation
- Used-car market analysis
- Understanding vehicle pricing factors
- Data-driven automobile business decisions

## 🔮 Future Improvements
- Compare Decision Tree Regression with Linear Regression and Random Forest.
- Improve model performance through hyperparameter optimization.
- Add a user-friendly interface for entering vehicle specifications.
- Deploy the model as a web application.

## 👨‍💻 Author
**Sanket Bacche**

GitHub: [SanketBacche](https://github.com/SanketBacche)
LinkedIn: (linkedin.com/in/sanket-bacche-00320a380)

## 📜 License
This project is intended for educational and learning purposes.
