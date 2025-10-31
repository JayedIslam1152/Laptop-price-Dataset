# 💻 Laptop Price Analysis

This project uses the **Laptop Price Dataset** to build a Machine Learning model. The main goal is to accurately **predict** a laptop's price based on its various specifications (such as RAM, CPU, storage, and screen size).

---

## 📖 Project Goal

The primary objective is to identify which features most significantly influence the price of a laptop and to use these insights to create a reliable price prediction model.

---

## 🛠️ Technologies Used

The entire analysis and modeling process is performed using **Python**. The main libraries utilized are:

* **Pandas & Numpy:** For data cleaning, processing, and numerical operations.
* **Seaborn & Matplotlib:** For visualizing the relationship between laptop specs and price.
* **Scikit-learn (Sklearn):** For building and evaluating Machine Learning models (such as Linear Regression and Random Forest).
* **Jupyter Notebook:** For step-by-step documentation of code, analysis, and results.

---

## 📊 Analysis and Modeling Steps

In the `Laptop_price Dataset.ipynb` notebook, you will find the following core steps:

1.  **Exploratory Data Analysis (EDA):** Exploring the relationships among columns like `Company`, `CPU`, `RAM`, `Inches`, and `Price`.
2.  **Feature Engineering:** Dividing some columns (e.g., `ScreenResolution`, `Memory`) into more useful features, and encoding `Operating System` and other categorical data.
3.  **Data Scaling:** Applying a logarithmic scale to skewed data, such as Price, to improve model performance.
4.  **Model Training:** Training price prediction models using various Machine Learning algorithms.
5.  **Model Evaluation:** Comparing the performance of the trained models and selecting the best one.

---

## 🚀 How to Run

1.  Clone this repository or download the `Laptop_price Dataset.ipynb` file.
2.  Open **Jupyter Notebook** or **Google Colab** on your system.
3.  Open the notebook and run the cells sequentially.
