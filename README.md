# ML From Scratch - Linear Regression with Gradient Descent

![Linear Regression](https://upload.wikimedia.org/wikipedia/commons/3/3a/Linear_regression.svg)

## 🚀 Project Overview
This project implements **Linear Regression from scratch** using **Gradient Descent**, without using external machine learning libraries like Scikit-Learn.

### ✨ Features
- Reads and processes input data
- Normalizes features for better performance
- Computes the cost function (Mean Squared Error)
- Implements **Gradient Descent** to find optimal parameters
- Visualizes the regression line and cost reduction over iterations

---

## 📂 Dataset
The project expects two CSV files in the root directory:
- **`linearX.csv`** → Independent variable (features)
- **`linearY.csv`** → Dependent variable (target/output)

⚠️ **Important**: Ensure the dataset files are in **CSV format** (not PDFs). If using different data, update the file paths in the notebook.

---

## 🔧 Installation
Before running the notebook, install the required dependencies:

```bash
pip install numpy pandas matplotlib
```

---

## 🛠 Implementation Steps
1️⃣ **Importing Libraries** → Load essential libraries (`numpy`, `pandas`, `matplotlib`).  
2️⃣ **Loading the Dataset** → Reads `linearX.csv` & `linearY.csv` and merges them.  
3️⃣ **Feature Normalization** → Standardizes `X` and `Y` for better model convergence.  
4️⃣ **Initializing Parameters** → Sets initial values for slope (`m`), intercept (`b`), learning rate (`lr`), and iterations.  
5️⃣ **Cost Function Calculation** → Uses **Mean Squared Error (MSE)** to evaluate model performance.  
6️⃣ **Gradient Descent Optimization** → Updates `m` and `b` iteratively to minimize the cost function.  
7️⃣ **Results Visualization** →
   - 📉 **Cost vs Iterations** → Shows how the loss reduces over time.
   - 📈 **Regression Line Fit** → Plots the data points and the best-fit line.

---

## 🎯 Usage
Run the Jupyter Notebook:

```bash
jupyter notebook ML_From_Scratch.ipynb
```

---

## 🚀 Potential Improvements
✅ Add dataset validation to check for incorrect file formats.  
✅ Extend the model to support **multiple linear regression**.  
✅ Compare performance with **Scikit-Learn’s LinearRegression**.  
✅ Save trained model parameters for future use.  

---

## 💡 Contributing
If you want to improve this project, feel free to submit a pull request! 🙌

---

