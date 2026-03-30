#  RetailForecast AI – Walmart Demand Forecasting

RetailForecast AI is a powerful and interactive web application that predicts **weekly sales** for Walmart stores and departments using machine learning. This app empowers retailers to make **data-driven decisions**, avoid stockouts, and optimize inventory with clear forecasts and actionable insights.

##  Features

-  **Sales Prediction** based on store, department, and date
-  **Interactive Charts** (Sales Trends, Store-wise & Dept-wise Analysis)
-  **Holiday vs Non-Holiday Impact** on sales (box plot + pie chart)
-  **Email Alert System** for high/low sales thresholds
-  **Multi-language Support** (English, Hindi, Spanish, French)
-  **Responsive UI** for mobile and desktop
-  Export predictions to Excel
-  Actual vs Predicted comparison chart
-  Built using **RandomForestRegressor**, trained on Walmart sales data


## 🛠 Tech Stack

| Layer        | Tools / Frameworks                      |
|--------------|-----------------------------------------|
| Frontend     | Streamlit, Plotly, Seaborn, Matplotlib  |
| Backend      | Python, Pandas, Scikit-learn, Joblib    |
| Model        | RandomForestRegressor                   |
| Deployment   | GitHub, Streamlit Cloud                 |
| Other        | Gmail SMTP (for email alerts), Git      |

---

## ![Screenshot 2025-06-25 133916](https://github.com/user-attachments/assets/1cba733b-7bb4-4a36-9fe8-891c00dc12c2)
![Screenshot 2025-06-25 133859](https://github.com/user-attachments/assets/4f6fa498-cb7e-4411-af4c-3573b207435a)
![Screenshot 2025-06-25 133845](https://github.com/user-attachments/assets/437f00a7-5553-4e56-a1e7-bff035a7377e)
 Folder Structure

```bash
RetailForecast-AI/
│
├── app.py                  # Main Streamlit app
├── requirement.txt         # Required packages
├── .env                    # Environment variables (EMAIL, PASSWORD)
│
├── assets/                 # Backgrounds, GIFs
├── model/                  # Trained model + feature_names.pkl
├── dataset/                # Data files, preprocessing notebooks
│   ├── train.csv
│   ├── test.csv
│   ├── final_df.csv
│   ├── final_df_cleaned.csv
│   ├── y_test.csv
│   ├── y_pred.csv
│   └── ...
└── .streamlit/             # Theme & layout config
