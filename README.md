# BMW Sales Volume Prediction

A Machine Learning project to **predict BMW car sales volume** using historical data and features like model, year, color, fuel type, transmission, engine size, and price.

---

## 📊 Features / Highlights
- Data preprocessing: sorting, filtering, and handling categorical variables  
- Encoding categorical columns using **LabelEncoder**  
- Scaling price using **MinMaxScaler**  
- Train-test split for model validation  
- Regression models implemented:  
  - **Linear Regression**  
  - **Decision Tree Regressor**  
  - **Random Forest Regressor**  
- Model evaluation using **Mean Squared Error (MSE)** and **Root Mean Squared Error (RMSE)**  
- Predict sales volume for new unseen data  

---

## 🔹 Key Graphs (Visualizations)
- **Distribution of Sales Volume**: to check spread, skewness, and outliers  
  ```python
  import seaborn as sns
  import matplotlib.pyplot as plt

  sns.histplot(df['Sales_Volume'], bins=50)
  plt.title("Distribution of Sales Volume")
  plt.show()
<img width="580" height="455" alt="image" src="https://github.com/user-attachments/assets/07f0f883-8c2f-47ec-971e-55162ee479b3" />
