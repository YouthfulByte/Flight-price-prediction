# Flight-price-prediction
Air travel pricing is highly dynamic and varies significantly based on multiple factors. Travelers often struggle to determine the optimal time to book flights and frequently overpay. We aim to develop a predictive model that can accurately forecast flight prices, helping travelers make informed booking decisions.


By leveraging advanced machine learning techniques and data analytics, this project addresses the complexity of airfare pricing, which is influenced by variables such as:
- Demand and supply fluctuations
- Airline competition and route popularity
- Booking lead time and flight duration
- Time of day and day of the week
- Number of stops and ticket class (Economy vs. Business)

---

## Key Objectives
- **Identify Pricing Factors:** Understand how factors such as airlines, departure times, stopovers, and booking lead time impact ticket costs.
- **Predict Flight Prices:** Develop machine learning models to forecast airfare trends.
- **Compare Pricing Strategies:** Analyze the differences between Economy and Business class fares.
- **Optimize Booking Strategies:** Identify the best times and methods to book flights for maximum cost savings.

---

## Tech Stack & Tools
- **Programming Language:** Python
- **Data Analysis & Visualization:** Pandas, NumPy, Matplotlib, Seaborn
- **Machine Learning Models:** 
  - Linear Regression
  - Random Forest
  - XGBoost
  - Gradient Boosting
- **Model Evaluation Metrics:** 
  - Mean Absolute Error (MAE)
  - Root Mean Squared Error (RMSE)
  - R² Score

---

##  Project Structure
📂 flight-price-prediction
├── 📁 data
│   ├── flight_data.csv
│   └── Holdout.csv
├── 📁 notebooks
│   └── flight_price_prediction.ipynb
├── 📁 models
│   └── model.pkl
├── 📁 scripts
│   ├── data_preprocessing.py
│   └── model_training.py
└── README.md

---

## Methodology
1. **Data Collection & Cleaning:** Processed over 300,000 flight records to remove inconsistencies and missing values.
2. **Feature Engineering:** Developed features like peak hours, weekend indicators, and route popularity.
3. **Model Training & Evaluation:** Trained and compared multiple models to select the best-performing one.
4. **Prediction & Insights:** Predicted future flight prices and derived actionable insights.

---

## Insights & Recommendations
- **Book Early:** Tickets booked at least 14 days in advance tend to be significantly cheaper.
- **Choose Mid-Week Flights:** Prices are generally lower on weekdays compared to weekends.
- **Consider Alternative Routes:** Popular routes often offer lower prices due to competition.
- **Mind the Stops:** Non-stop flights are usually more expensive compared to those with stopovers.

---

## Model Performance
The **Random Forest** model performed the best with the lowest RMSE and high accuracy. Model performance was evaluated based on RMSE, MAE, and R² scores to ensure robust prediction quality.

---

