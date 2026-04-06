# FIFA_Player_Value_Prediction


This project focuses on predicting the **market value of football players** using Machine Learning techniques. The prediction is based on player attributes like physical stats, technical skills, and performance metrics.

---

## 📌 Project Objective

The main goal of this project is to build a model that can answer:

👉 *"What should be the market value of a player based on their performance and skills?"*

---

## 📊 Dataset Information

- Dataset: `player_stats.csv`
- Total Records: 5682 players
- Total Features: 41
- Target Variable: **value (player market value in USD)**

### Features include:
- Physical: height, weight, age  
- Technical: dribbling, passing, finishing, etc.  
- Performance: speed, stamina, strength  
- Categorical: country, club  

---

## ⚙️ Steps Performed

### 1. Data Cleaning
- Removed unnecessary columns (like player name)
- Handled missing values using mean, median, mode
- Removed duplicate records
- Fixed incorrect/invalid values

### 2. Outlier Treatment
- Used **IQR method** to remove outliers

### 3. Feature Engineering
- Converted categorical data into numerical using Label Encoding
- Applied feature scaling using StandardScaler

### 4. Dimensionality Reduction
- Applied **PCA** to reduce features
- Retained 95% of data variance

### 5. Model Building
- Linear Regression (baseline)
- Random Forest Regressor
- Hyperparameter tuning using GridSearchCV

---

## 📈 Model Performance

| Model | Performance |
|------|------------|
| Linear Regression | Low |
| Random Forest | Good |
| Tuned Random Forest | ⭐ Best |

👉 The **tuned Random Forest model** gave the best results.

---

## 🛠️ Technologies Used

- Python  
- Pandas, NumPy  
- Matplotlib, Seaborn  
- Scikit-learn  

---

## 🚀 How to Run the Project

1. Open Google Colab  
2. Upload the notebook file  
3. Upload the dataset (`player_stats.csv`)  
4. Run all cells  

---

## 📚 Key Learnings

- Real-world data cleaning techniques  
- Handling missing values and outliers  
- Feature scaling and encoding  
- PCA (Dimensionality Reduction)  
- Model comparison and tuning  
