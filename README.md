# ML-Fish-Weight-Predictor
# 🎣 Fish Weight Prediction

This is a machine learning project to predict the **weight of a fish** based on its physical measurements like length, height, and width. The project was done as part of the **YBI Foundation Internship**.

## 📁 Dataset

- Source: [YBI Foundation Fish Dataset](https://raw.githubusercontent.com/YBIFoundation/Dataset/main/Fish.csv)
- Features:
  - Length1, Length2, Length3
  - Height
  - Width
  - Species (encoded)
- Target: `Weight` (in grams)

## 🚀 Project Workflow

1. Data loading and exploration
2. Data preprocessing (dummy encoding of species)
3. Train-test splitting
4. Model building with **Linear Regression**
5. Model evaluation using **R² Score** and **RMSE**
6. Visualization of predictions

## 📈 Sample Output

- **R² Score**: ~0.85  
- **RMSE**: ~120 grams  
- **Scatter plot** of predicted vs actual weights

## 📦 Libraries Used

- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

## ✅ How to Run

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
