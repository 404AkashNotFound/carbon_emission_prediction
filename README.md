# CO₂ Emission Predictor – ML for a Greener Planet

### Using Machine Learning to Model and Predict Environmental Impact
### Shell–Edunet Foundation – AICTE Virtual Internship

## 🧠 Project Overview

This project uses machine learning to predict CO₂ emissions of countries using historical data. Built as part of a green skills initiative, the goal is to explore how AI and data science can be applied to tackle global climate challenges.

We analyzed a wide range of socioeconomic, energy, climate, and population features to understand their influence on CO₂ emissions and built multiple regression models to make predictions based on these insights.

---

## 🌍 Dataset Summary

**Source:** World Bank Climate Change Dataset (1990–2011)  
This dataset provides environmental, economic, and social indicators for over 200 countries.

### 📌 Key Data Categories:

- 🌫️ Greenhouse gases (CO₂, CH₄, N₂O)
- 👥 Population (total, urban %, growth rate)
- 💰 Economic indicators (GDP, GNI, FDI)
- ⚡ Energy usage (per capita, consumption)
- 🌾 Agriculture & land use (cereal yield, forest area)
- ☁️ Climate and natural disasters
- 🏥 Health infrastructure (medical staff, hospitals)

---

## 🛠️ Tech Stack

| Purpose              | Tools / Libraries                     |
|----------------------|----------------------------------------|
| Data Cleaning        | Python, Pandas, NumPy                 |
| Visualization        | Matplotlib, Seaborn                   |
| Modeling             | Scikit-learn, XGBoost                 |
| Development          | Jupyter Notebook                      |
| Data Source Format   | Excel (initial), CSV (processed)      |

---

## 🔍 Project Workflow

### 1️⃣ Data Preprocessing
- Cleaned raw Excel data  
- Filled missing values  
- Removed statistical outliers  
- Converted categorical/numeric formats  
- Selected relevant features based on correlation  

### 2️⃣ Exploratory Data Analysis (EDA)
- Correlation heatmaps  
- Country-wise emissions distribution  
- Feature importance visualizations  
- Trend analysis using line & bar plots  

### 3️⃣ Machine Learning Models
We built and compared the performance of:
- Linear Regression  
- Decision Tree Regressor  
- Random Forest Regressor  
- XGBoost Regressor  

### 4️⃣ Model Evaluation
Evaluated model performance using:
- R² Score — Coefficient of determination  
- MAE — Mean Absolute Error  
- RMSE — Root Mean Squared Error  

---

## 🚀 How to Run

1. **Clone the repository:**
   ```bash
   git clone https://github.com/404AkashNotFound/carbon_emission_prediction.git
   ```

2. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

3. **Launch the Jupyter Notebook:**
   ```bash
   jupyter notebook 1_data_preparation.ipynb
   jupyter notebook 2_data_preparation.ipynb
   
   ```

4. **Follow the notebook cells to:**
   - Load and clean data  
   - Visualize patterns  
   - Train and evaluate models  

---

## ✨ Future Enhancements

- 📈 Add time-series forecasting using ARIMA or Prophet  
- 📊 Build an interactive dashboard with Streamlit  
- 🌐 Integrate global live datasets via APIs  
- 🐳 Dockerize the project for easy deployment  
- 🔁 Add CI/CD pipeline using GitHub Actions  
- 🧪 Include unit testing with Pytest  

---

## 👨‍💻 Author

**Akash Kumar**  
B.Tech (Electronics & Computer Science) – Final Year
Summer Intern at Shell-Edunet Foundation
📧 [aks231273@gmail.com]  
