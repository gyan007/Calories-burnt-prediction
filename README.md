# Calories-burnt-prediction

## 📚 Project Overview

This project aims to predict the number of calories burnt during physical exercises using various physiological and activity-related factors. By leveraging machine learning models, the project estimates calorie expenditure, helping individuals and fitness enthusiasts monitor and optimize their workout routines.

## 📂 Dataset Description

The project uses two datasets:

1. **Calories Dataset** (`calories.csv`): Contains the following columns:

   * `User_ID`: Unique identifier for each individual.
   * `Calories`: Total calories burnt.

2. **Exercise Dataset** (`exercise.csv`): Contains the following columns:

   * `User_ID`: Unique identifier for each individual.
   * `Gender`: Gender of the individual (`male`/`female`).
   * `Age`: Age in years.
   * `Height`: Height in centimeters.
   * `Weight`: Weight in kilograms.
   * `Duration`: Duration of the exercise in minutes.
   * `Heart_Rate`: Heart rate during the exercise.
   * `Body_Temp`: Body temperature during the exercise (°C).

## 🛠️ Technologies Used

* Python
* Jupyter Notebook
* Pandas, NumPy
* Scikit-learn (for model training)
* Matplotlib, Seaborn (for data visualization)

## 🚀 Getting Started

1. Clone the repository:

   ```bash
   git clone https://github.com/username/Calories-Burnt-Prediction.git
   ```
2. Install the required libraries:

   ```bash
   pip install pandas numpy scikit-learn matplotlib seaborn
   ```
3. Run the notebook:

   ```bash
   jupyter notebook Project_16_Calories_Burnt_Prediction.ipynb
   ```

## 💡 Key Features

* Data Preprocessing: Handling missing values, encoding categorical data, and scaling.
* Exploratory Data Analysis: Visualizing correlations and distribution patterns.
* Model Building: Using regression algorithms to predict calories burnt.
* Model Evaluation: Measuring accuracy, RMSE, and more.

## 📊 Results

The model predicts calorie expenditure with high accuracy, offering insights into the relationship between exercise duration, heart rate, and calorie burn.

## 🙌 Contributing

Feel free to open issues or submit pull requests to improve the project.

## 📧 Contact

For any questions or suggestions, reach out to the project maintainer.

Happy Predicting! 😎
