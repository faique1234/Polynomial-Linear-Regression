# 📌 Polynomial Linear Regression – 

This project demonstrates **Polynomial Linear Regression** using Python, NumPy, Pandas, Matplotlib, and scikit-learn.  
The dataset represents **House Size (sq. ft)** vs **Price (Rs. 1000)**.  

---

## 📊 Dataset
| House Size (sq. ft) | Price (Rs. 1000) |
|----------------------|------------------|
| 50                   | 150              |
| 80                   | 220              |
| 120                  | 300              |
| 150                  | 400              |
| 180                  | 510              |
| 200                  | 580              |
| 250                  | 750              |

---

## ⚙️ Steps Implemented
1. **Import Libraries** → NumPy, Pandas, Matplotlib, scikit-learn  
2. **Load Dataset** → Hardcoded values of house size vs price  
3. **Visualize Dataset** → Scatter plot  
4. **Linear Regression** → Fit and plot regression line  
5. **Polynomial Regression (Degree 4)** → Fit and plot curve  
6. **Predictions** → Predict house price for 350 sq. ft  
7. **Model Evaluation** → RMSE & R² score comparison  

---

## 📈 Visualizations
- 📍 Dataset Scatter Plot  
- 📍 Linear Regression Fit  
- 📍 Polynomial Regression Fit (Degree 4)  

---

## 🔮 Predictions
For a house size of **350 sq. ft**:  
- **Linear Regression Prediction:** `≈ 1,029,750 Rs.`  
- **Polynomial Regression Prediction:** `≈ 268,580 Rs.`  

---

## 📊 Model Evaluation
| Model                  | RMSE  | R² Score |
|-------------------------|-------|----------|
| Linear Regression       | 21.21 | 0.9883   |
| Polynomial Regression   | 4.02  | 0.9996   |

✅ Polynomial Regression provides a **much better fit** for the dataset.

---

## 🚀 How to Run
1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/polynomial-linear-regression.git
   cd polynomial-linear-regression
