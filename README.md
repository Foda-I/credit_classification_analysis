# 💳 Credit Risk Classification Analysis

## 📌 Project Overview
This project implements and compares multiple machine learning classification algorithms to predict credit approval outcomes based on customer demographic and financial data. The goal is to identify the most reliable algorithm for financial risk assessment and automate the loan approval decision-making process.

To demonstrate technical versatility, **this repository contains two parallel implementations of the exact same analysis pipeline**: one written in **Python** and one written in **R**.

## 🛠️ Tech Stack
- **Languages:** Python, R
- **Python Libraries:** `pandas`, `numpy`, `scikit-learn`, `matplotlib`, `seaborn`
- **R Libraries:** `rpart`, `MASS`, `class`, `nnet`, `e1071`, `randomForest`
- **Tools:** Jupyter Notebook, R Markdown, Git/GitHub

##  Methodology & Models Evaluated
1. **Data Preprocessing:** Handled missing values, encoded categorical variables (One-Hot Encoding), and applied feature scaling (StandardScaler) where appropriate.
2. **Train/Test Splitting:** Implemented stratified sampling to ensure balanced class distribution in both training and testing sets.
3. **Models Implemented & Compared:**
   - Naive Bayes (GaussianNB)
   - Linear Discriminant Analysis (LDA)
   - K-Nearest Neighbors (k-NN) with hyperparameter tuning for optimal `k`
   - Multinomial Logistic Regression
   - Support Vector Machines (SVM with RBF kernel)
   - Decision Trees (CART with 1-SE pruning)
   - Ensemble Methods: Random Forest and AdaBoost
4. **Evaluation Metrics:** Accuracy, Precision, Recall, F1-Score, ROC-AUC, and Confusion Matrices.

## 📂 Repository Structure
- `credit_classification_analysis.ipynb`: The complete analysis pipeline written in Python.
- `credit_classification_analysis.Rmd`: The complete analysis pipeline written in R.
- `credit_classification_analysis.html`: The rendered HTML report of the R analysis.

*(Note: The dataset is embedded directly inside both scripts to ensure the code runs out-of-the-box without requiring external file dependencies!)*

## 💡 Key Insights
- **Model Performance:** Ensemble methods (Random Forest, AdaBoost) and SVM demonstrated the highest predictive accuracy and robustness for this dataset.
- **Feature Scaling:** Standardizing features significantly improved the performance of distance-based algorithms like k-NN and SVM.
- **Hyperparameter Tuning:** The optimal number of neighbors for k-NN was determined empirically using an accuracy vs. `k` plot, preventing overfitting.

## 💻 How to Run

### Python
1. Open `credit_classification_analysis.ipynb` in Jupyter Notebook or VS Code.
2. Run the cells sequentially to generate the visualizations and metrics.

### R
1. Open `credit_classification_analysis.Rmd` in RStudio.
2. Install required packages if prompted, then click **Knit** to generate the HTML report, or run the chunks sequentially.

## 📬 Contact
- **Email:** ibrahim.fadyy@gmail.com
- **LinkedIn:** linkedin.com/in/ibrahim-fady
