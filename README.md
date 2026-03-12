# 🎬 Movie Revenue Prediction using Machine Learning

This project uses **Machine Learning** to predict the **Worldwide Gross Revenue of movies** based on different features such as budget, runtime, metascore, and opening weekend earnings.

The model is trained using a dataset containing movie details and financial performance.

---

# 📌 Project Overview

The goal of this project is to build a **regression model** that can estimate the **Gross Worldwide revenue** of a movie based on available movie attributes.

Machine learning techniques are used to analyze the relationship between movie characteristics and their financial success.

---

# 📊 Dataset Features

The dataset contains the following attributes:

| Feature             | Description                               |
| ------------------- | ----------------------------------------- |
| Original Title      | Name of the movie                         |
| Company             | Production company                        |
| Rate                | Movie rating                              |
| Metascore           | Critics score                             |
| Minutes             | Runtime of the movie                      |
| Release             | Release year                              |
| Budget              | Production budget                         |
| Opening Weekend USA | First weekend box office                  |
| Gross USA           | Total revenue in the USA                  |
| Gross Worldwide     | Total worldwide revenue (Target Variable) |

---

# ⚙️ Technologies Used

* Python
* NumPy
* Pandas
* Scikit-learn
* Kaggle Notebook

Libraries used from scikit-learn for building the machine learning model.

---

# 🧠 Machine Learning Model

The project uses:

**Random Forest Regressor**

Why this model?

* Handles complex relationships
* Works well with tabular datasets
* Reduces overfitting using ensemble learning

---

# 🔄 Workflow

The machine learning pipeline follows these steps:

1. Import required libraries
2. Load dataset
3. Data preprocessing
4. Remove non-numeric columns
5. Feature selection
6. Train-test split
7. Model training
8. Model prediction
9. Model evaluation

---

# 📈 Model Evaluation

The model is evaluated using regression metrics:

* Mean Squared Error (MSE)
* Mean Absolute Error (MAE)
* R² Score

The R² score is converted to a **percentage to represent model accuracy**.

---

# 🚀 How to Run the Project

1. Clone the repository

```bash
git clone https://github.com/your-username/your-repository-name.git
```

2. Install dependencies

```bash
pip install pandas numpy scikit-learn
```

3. Run the notebook or Python script

```bash
python main.py
```

---

# 📂 Project Structure

```
movie-revenue-prediction
│
├── dataset
│   └── movie_data.csv
│
├── notebook
│   └── movie_prediction.ipynb
│
├── model
│   └── trained_model.pkl
│
└── README.md
```

---

# 📊 Example Output

The model predicts the **expected worldwide revenue** based on movie features such as:

* Budget
* Runtime
* Metascore
* Opening Weekend revenue

---

# 📌 Future Improvements

* Add more datasets
* Improve feature engineering
* Try advanced models like XGBoost
* Build a web interface for predictions

---

# 👨‍💻 Author

**Akshay Aneesh**

---

⭐ If you found this project useful, consider giving it a star on GitHub.


