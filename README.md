# NYC-Car-Bookings-Analysis
 NYC Car Bookings Analysis: A/B Testing &amp; Time Series to Maximize Taxi Revenue

 📌 Project Title:
NYC Car Bookings Analysis: A/B Testing & Time Series to Maximize Taxi Revenue

💼 Problem Statement
To maximize the revenue streams for taxi drivers, our research focuses on determining whether payment methods (Card vs. Cash) have a statistically significant impact on fare prices.

To run an A/B test examining the relationship between fare amount and payment type using Python. We applied hypothesis testing and descriptive statistics to discover actionable insights that can help taxi drivers increase earnings.
Specifically, we ask:

“Is there a significant difference in the total fare between riders who pay with credit cards and those who pay with cash?”

🧪 Techniques Used
✅ Exploratory Data Analysis (EDA)

✅ Feature Engineering (Trip duration, Hour extraction)
✅ Date Range Identification (2020–2021)
✅ A/B Testing (t-test between Card & Cash)
✅ Hypothesis Testing with QQ Plots
✅ Data Visualization (Pie chart, Stacked bar, Histplot)
✅ Linear Regression (fare_amount ~ duration)
✅ Time Series Analysis (Daily Fare Trends)
✅ Hourly Fare Patterns by Payment Type


📊 Visual Insights
🔹 Linear Regression
We modeled the relationship between trip duration and fare amount.

Fare = m × Duration + c

Observed that longer trips generally increase fare, but variation exists.

🔹 Hypothesis Testing (A/B)
1.Used t-test to compare Card vs Cash fare distributions.
2.Visualized with QQ plots and stacked bar graphs.

Result: Statistically significant difference found in average fare between payment types.


🔹 Time Series (2020–2021)
Created daily average fare trend plots.
Conducted hourly fare analysis:
Found morning and evening peaks.
Card payments tend to yield higher average fares at almost every hour.


📅 Data Timeframe
The dataset spans from January 2020 to early 2021.
Features like tpep_pickup_datetime were cleaned and used to create hourly, daily, and monthly trends.

├── nyc_taxi_analysis.ipynb       # Main ana lysis notebook
├── yellow_tripdata_2020-01.csv   # Sample raw data
├── outputs/
│   ├── regression_plot.png
│   ├── time_series_fare.png
│   └── payment_type_bar.png
🔍 Key Findings
1.Fare amounts vary significantly based on payment method — card payments often correlate with higher fares.
2.Trip duration is positively correlated with fare, but the relationship is not strictly linear (other factors like traffic, surge pricing may play a role).
3.Revenue-maximizing times for taxi drivers appear to be 8–10 AM and 6–8 PM.
4.Daily and hourly fare trends are useful for driver scheduling and surge prediction.

🛠️ Tools Used
Python (pandas, matplotlib, seaborn, scipy, statsmodels)
Jupyter Notebook
Power BI (initial exploration phase – removed due to size)

📌 Conclusion
This project demonstrates a data-driven approach to supporting NYC taxi drivers in maximizing their earnings.
Using real-world data, we applied statistical rigor and visual storytelling to uncover actionable business insights — like which payment type and time of day are most profitable.


