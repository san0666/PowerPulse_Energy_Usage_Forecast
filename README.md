##🔌PowerPulse: Household Energy Usage Forecast

PowerPulse is a machine learning project focused on predicting household energy consumption using historical electrical usage data. By analyzing minute-level features such as voltage, current, and time-based patterns, the project delivers insights into energy behavior and builds a predictive model to support smarter energy decisions.

---

 📌 Project Objective

- Build a machine learning regression model to forecast **Global Active Power** usage.
- Analyze and visualize **key patterns** in household electricity consumption.
- Identify influential features contributing to energy usage.
- Deliver actionable insights and a reliable predictive tool for energy management.

---

🧠 Problem Statement

Accurate energy consumption forecasting is essential for efficient energy planning, cost reduction, and household optimization. This project aims to help users and energy providers understand and anticipate power usage patterns through machine learning.

---

🧾 Dataset Overview

- **Source**: [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/individual+household+electric+power+consumption)
- **Data Type**: Minute-level power measurements over multiple years
- **Key Features**:
  - `Global_active_power` (Target)
  - `Voltage`, `Global_reactive_power`, `Global_intensity`
  - `Sub_metering_1`, `Sub_metering_2`, `Sub_metering_3`
  - Time-based: Hour, Day, Month, Weekday, etc.

---

🛠️ Tools & Technologies

| Category           | Tools & Libraries                       |
|--------------------|------------------------------------------|
| Programming        | Python                                  |
| Data Analysis      | Pandas, NumPy                           |
| Visualization      | Matplotlib, Seaborn                     |
| Machine Learning   | scikit-learn (Linear Regression, Random Forest, Gradient Boosting) |
| Development        | Jupyter Notebook                        |

---

⚙️ Project Workflow

1. **Data Loading & Cleaning**
2. **Feature Engineering** – Extracted time components, rolling averages, and peak hour flags
3. **Exploratory Data Analysis (EDA)** – Visualized trends, correlations, and sub-metering
4. **Model Training** – Trained Linear Regression, Random Forest, and Gradient Boosting
5. **Model Evaluation** – Compared using RMSE, MAE, and R² Score
6. **Insights & Recommendations** – Identified top usage patterns and optimization opportunities

---

📊 Visualizations Included

- Global Active Power over Time
- Hourly & Weekly Usage Patterns
- Sub-metering Comparison (Pie Chart)
- Correlation Heatmap
- Actual vs Predicted Plots
- Feature Importance Chart
- Model Performance Comparison

---

 🏆 Results

| Model              | RMSE    | MAE     | R² Score |
|-------------------|---------|---------|----------|
| Linear Regression | 0.0039  | 0.0026  | 0.9983   |
| Random Forest      | ✅ **0.0029**  | ✅ **0.0013**  | ✅ **0.9990**   |
| Gradient Boosting | 0.0347  | 0.0262  | 0.8684   |

**🎯 Best Model:** Random Forest Regressor

---

🔍 Key Insights

- Energy usage peaks at **6–9 AM** and **6–9 PM**
- **Voltage** and **Global Intensity** are strong predictors
- **Water heater & AC** consume more energy than kitchen appliances
- Weekends show **different energy patterns** compared to weekdays

---


---

🚀 Future Work

- Integrate weather and temperature data
- Deploy as a web app using **Streamlit**
- Add live energy monitoring via IoT devices
- Expand to multi-household or city-scale energy prediction

---

 🙌 Acknowledgements

- [UCI ML Repository](https://archive.ics.uci.edu/ml/datasets/individual+household+electric+power+consumption) for the dataset
- scikit-learn, pandas, and matplotlib teams for amazing open-source tools

---

 📬 Contact

**Created by**: Sanjana Agarwal
**Email**: sanjanaa543@gmail.com  
**GitHub**: [github.com/san0666](https://github.com/san0666)

---




