


# 🚕 Taxi Fare Prediction Project  

Welcome to the **Taxi Fare Prediction** project! This repository showcases my workflow for analyzing and building machine learning models to predict taxi trip fares. It uses a dataset rich with features such as trip distance, traffic conditions, weather, and passenger count.  

---

## 📂 **Dataset Description**  

The dataset is designed for regression tasks, offering realistic synthetic data to explore pricing trends in the taxi industry.  

### **Features**  
- `Trip_Distance_km`: Distance of the trip in kilometers.  
- `Time_of_Day`: The time when the trip occurred (Morning, Afternoon, Evening, Night).  
- `Day_of_Week`: Whether the trip occurred on a weekday or weekend.  
- `Passenger_Count`: The number of passengers.  
- `Traffic_Conditions`: Categorical indicator (Low, Medium, High).  
- `Weather`: Weather conditions (Clear, Rain).  
- `Base_Fare`: Fixed base fare amount.  
- `Per_Km_Rate`: Cost per kilometer.  
- `Per_Minute_Rate`: Cost per minute of the trip.  
- `Trip_Duration_Minutes`: Duration of the trip in minutes.  
- `Trip_Price`: Total price of the trip (target variable).  

---

## 🚀 **Workflow Overview**  

### **1. Data Exploration**  
- Explored key features with **count plots**, **histograms**, and **scatter plots**.  
- Identified missing values and outliers.  

### **2. Data Cleaning**  
- Handled missing values using imputation techniques.  
- Removed or treated outliers for robust model performance.  

### **3. Feature Engineering**  
- Created new features based on existing ones (e.g., trip speed).  
- Performed Min-Max scaling to normalize the dataset.  

### **4. Model Building**  
- Built and evaluated regression models:  
  - **Linear Regression**  
  - **Random Forest Regressor**  
  - **Gradient Boosting Machines (GBM)**  
- Compared model performance using **R²**, **MAE**, and **RMSE** metrics.  

### **5. Visualization**  
- Used **box plots**, **violin plots**, and **kde plots** for detailed insights.  
- Plotted model predictions vs. actual trip prices.  

---

## 📊 **Visual Highlights**  
Here are some key plots from the analysis:  

- **Outlier Detection**: Visualized using box plots.  
- **Trip Price Distribution**: Histogram and KDE plot.  
- **Correlation Heatmap**: Showcasing feature relationships.  

---

## 🛠️ **How to Run**  

1. Clone the repository:  
   ```bash
   git clone https://github.com/Arif-miad/Taxi-Fare-Prediction.git
   cd Taxi-Fare-Prediction
   ```  

2. Install dependencies:  
   ```bash
   pip install -r requirements.txt
   ```  

3. Run the notebook:  
   Open `Taxi_Fare_Prediction.ipynb` in Jupyter Notebook or VS Code.  

---

## 💡 **Key Takeaways**  
- This project emphasizes the importance of handling missing values and outliers.  
- Feature engineering plays a crucial role in improving model performance.  
- Taxi fare prediction is a real-world regression task with significant applications in urban planning and transportation systems.  

---

## 🤝 **Connect with Me**  

👨‍💻 **Arif Miah** – *Data Scientist*  
- 💻 [Kaggle Profile](https://www.kaggle.com/arifmia)  
- 🔗 [LinkedIn Profile](www.linkedin.com/in/arif-miah-8751bb217)  



