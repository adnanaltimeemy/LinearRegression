# Linear Regression: Predicting Medical Insurance Costs

## 📘 Project Overview
This project demonstrates how to apply **Linear Regression** to predict **medical insurance charges** based on demographic and lifestyle factors such as age, BMI, number of children, smoking status, and region.  
It provides an end-to-end walkthrough of data preprocessing, model training, evaluation, and visualization using Python.

The Jupyter Notebook `Linear_Regression.ipynb` includes all the analysis steps from data import to interpretation of model performance.

---

## 🧩 Dataset Description

The dataset used is **`insurance.csv`**, which contains information about individuals and their corresponding insurance charges.

| Column Name | Description |
|--------------|-------------|
| `age` | Age of the insured person |
| `sex` | Gender (`male` or `female`) |
| `bmi` | Body Mass Index — a measure of body fat based on height and weight |
| `children` | Number of dependents covered by the insurance |
| `smoker` | Smoking status (`yes` or `no`) |
| `region` | Residential area in the US (`northeast`, `northwest`, `southeast`, `southwest`) |
| `charges` | Medical insurance cost (target variable) |

---

## 🧠 Methodology

1. **Data Loading & Exploration**
   - Imported dataset using `pandas`
   - Displayed summary statistics and explored data types
   - Checked for missing or inconsistent values

2. **Exploratory Data Analysis (EDA)**
   - Visualized distributions and relationships using `matplotlib` and `seaborn`
   - Generated correlation heatmaps and pair plots

3. **Data Preprocessing**
   - Encoded categorical features using one-hot encoding
   - Normalized and split the dataset into **training** and **testing** sets

4. **Model Training**
   - Trained a **Linear Regression** model using `scikit-learn`
   - Estimated insurance charges based on input variables

5. **Model Evaluation**
   - Evaluated model accuracy using **R²**, **MAE**, **MSE**, and **RMSE**
   - Visualized predicted vs actual charges and residual errors

---

## 📊 Results

Key findings and insights include:

- **Positive correlation** between `age`, `bmi`, and `charges`  
- **Smoking status** has the largest effect on insurance cost  
- The model explains a significant portion of the variance in `charges` (high R² score)  
- Residuals show a mostly random distribution, validating the linearity assumption  

*(Exact performance metrics and plots are available in the notebook.)*

---

## ⚙️ How to Run

### 1. Clone the repository
```bash
git clone https://github.com/adnanaltimeemy/linear-regression-insurance.git
cd linear-regression-insurance
```

### 2. Install dependencies
Ensure Python 3.8+ is installed, then run:
```bash
pip install -r requirements.txt
```

### 3. Launch the Jupyter Notebook
```bash
jupyter notebook Linear_Regression.ipynb
```

---

## 🧰 Dependencies

This project requires the following Python libraries:

- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`
- `scikit-learn`
- `jupyter`

---

## 📈 Example Outputs

Visual outputs include:
- **Correlation heatmap** of features  
- **Predicted vs Actual charges** scatter plot  
- **Residual analysis**  
- **Feature coefficients** interpretation  

---

## 🧑‍💻 Author

**Adnan Altimeemy**  
Data Scientis  - 
Educational Data Science & Machine Learning Enthusiast

---

## 📄 License

This project is licensed under the **MIT License**.  
You may use, modify, and distribute this work with attribution.
