# Diabetes Outcome Visualization Project

This project explores the distribution and relationships of diabetic vs. non-diabetic patients using a real-world health dataset. Through a series of visualizations — from pie charts to pairplots — it demonstrates Python-based data storytelling and analysis.

## 🗂️ Dataset

- Source: [IBM Skills Network Diabetes Dataset](https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBMDeveloperSkillsNetwork-PY0101EN-SkillsNetwork/labs/Module%205/data/diabetes.csv)
- Total records: 768 patients
- Key features: Glucose, BMI, Age, Insulin, BloodPressure, DiabetesPedigreeFunction, Outcome

## 📌 Project Highlights

- ✅ Data import and structure inspection
- ✅ Missing data check
- ✅ Class distribution analysis (`Outcome`: 0 = Not Diabetic, 1 = Diabetic)
- ✅ Advanced visualizations using Matplotlib and Seaborn

## 📊 Visualizations

| Type           | Description                                            |
|----------------|--------------------------------------------------------|
| 🥧 Pie Chart   | Percentage split between diabetic and non-diabetic     |
| 📊 Bar Chart   | Count comparison of outcome classes                    |
| 📦 Box Plot    | BMI and Glucose spread by outcome                      |
| 🎻 Violin Plot | Age distribution shaped by outcome                     |
| 🔥 Heatmap     | Feature correlation matrix                             |
| 🧮 Pairplot    | Pairwise relationships across key features             |

## 🧠 Insights

- Around **35%** of patients are classified as diabetic
- Diabetics tend to show **higher BMI, Glucose, and Age**
- Strong correlations observed between **Outcome, Glucose, and BMI**

## 🛠️ Tech Stack

- Python 3.x
- Pandas
- Matplotlib
- Seaborn
- Jupyter Notebook

## 📂 Repository Structure

