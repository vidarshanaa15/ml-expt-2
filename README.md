# Experiment 2:  Loan Amount Prediction using Linear Regression

## 🎯 Objective
To apply Linear Regression to predict the sanctioned loan amount for users using the provided dataset. Visualize and interpret the results to evaluate model performance and insights.

---

## 🧰 Tools & Libraries Used
- **Python 3.10+** – Primary language for implementation
- **NumPy** – Used for efficient numerical operations and array handling
- **Pandas** – Managed datasets, handled missing values, and performed data preprocessing
- **Scikit-learn** – Performed regression modeling and 5-fold cross-validation
- **Matplotlib** – Visualized residuals and performance metrics using line and scatter plots
- **Seaborn** – Correlation heatmaps and improved visual styling


---

## 📁 Folder Structure
```bash
ml-expt-1/
├── README.md                       # Overview, tools, file summary, run instructions
├── datasets/
│   └── train.csv                   # Dataset for training LR model
├── Experiment-2/
│   ├── exp_2.ipynb                 # Implementation notebook
├── screenshots/
│   ├── actualpred.png             
│   ├── dataset1.png
│   ├── encoded.png
│   ├── heatmap.png
│   ├── hist.png
│   ├── metrics.png
│   ├── missingvals.png
│   └── residual.png
├── Assignment2_ML_Vidarshanaa.pdf  # Lab report
├── Assignment2_ML_Vidarshanaa.tex  # Latex report
└── requirements.txt                # Python packages and versions used
```

## 🚀 Instructions to Execute the Code

1. **Clone the Repository**
```bash
   git clone https://github.com/yourusername/ml-expt-2.git
   cd ml-expt-2
```

2. **Open the Notebooks**
- **Using Google Colab:**
  - Go to Google Colab
  - Click File > Upload Notebook and upload any .ipynb file from the Experiment-2 folder
  - *Or* paste the GitHub URL directly in Colab to open from repo
    
- **Running Locally with Jupyter Notebook:**
  - Install required packages:
  ```bash
  pip install -r requirements.txt
  ```
  - Then run
  ```bash
  pip install notebook
  jupyter notebook
  ```
  - Navigate to the Experiment-2 folder and open a notebook in your browser

## 📈 Model Performance
The Linear Regression model was evaluated using the following metrics:

- **Mean Absolute Error (MAE)**: `0.44087`
- **Mean Squared Error (MSE)**: `0.41455`
- **Root Mean Squared Error (RMSE)**: `0.64364`
- **R² Score**: ` 0.62649`

## 🙌 Credits

This experiment is part of the course **“ICS1512-Machine Learning Algorithms Laboratory”** at **SSN College of Engineering**.
