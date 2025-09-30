# 🏠 Boston House Price Prediction

An end-to-end machine learning project to predict house prices in Boston using linear regression, with a deployed Flask web application.

## 📌 Project Objective

To build a regression model that accurately predicts house prices based on various features like crime rate, number of rooms, property tax, and others. This project demonstrates the complete ML pipeline — from data analysis and model training to deployment via a web app.

---

## 📊 Dataset

- **Name**: Boston Housing Dataset
- **Source**: `sklearn.datasets.load_boston()` (Note: This dataset is deprecated in latest versions; can be replaced with an open CSV in future)
- **Features**: CRIM, RM, TAX, PTRATIO, etc.
- **Target**: MEDV (Median value of owner-occupied homes)

---

## 🛠️ Technologies Used

| Component    | Tools/Tech Stack                     |
|--------------|--------------------------------------|
| Language     | Python                               |
| Libraries    | pandas, numpy, matplotlib, seaborn, scikit-learn, pickle |
| Model        | Linear Regression                    |
| Web Framework| Flask                                |
| Frontend     | HTML (Jinja2 template)               |

---

## software and Tools requirements

1. [Github Account](https://github.com)
2. [VS CODE IDE](https://code.visualstudio.com)
3. [Render](https://render.com/)
4. [GitCLI](https://git-scm.com/book/en/v2)


## ⚙️ Project Workflow

1. **Data Preprocessing**
   - Loaded the dataset
   - Checked for nulls and outliers
   - Visualized correlations with heatmaps and pairplots

2. **Model Training**
   - Used Linear Regression
   - Trained/tested with an 80/20 split
   - Evaluated with R² score and MSE

3. **Model Saving**
   - Used `pickle` to save the trained model (`boston_model.pkl`)

4. **Deployment**
   - Built a web form with Flask
   - Integrated the model into a backend API
   - User inputs features → model predicts price

---

## 🚀 How to Run the Project Locally

### 🔧 Prerequisites
- Python 3.x
- `pip install -r requirements.txt` (create this file if needed)

### ▶️ Steps

```bash
# Clone the repo
git clone https://github.com/dineshtyagi1511/Boston_HousePrice_Prediction-.git
cd Boston_HousePrice_Prediction-

# Run the Flask app
python app.py

