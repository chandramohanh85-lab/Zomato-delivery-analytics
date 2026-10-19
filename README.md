# Zomato Delivery Analytics & Time Prediction

This project is about analyzing food delivery data to understand what affects delivery time and how machine learning can help predict it. I used Python, PostgreSQL, Power BI, and XGBoost to explore delivery patterns, find useful insights, and build a delivery time prediction model.

## Project Overview

The main goal of this project was to study delivery performance and understand how factors such as traffic, weather, vehicle condition, multiple deliveries, and festivals affect delivery time.

I started by cleaning the dataset and performing exploratory data analysis in Python. I then used PostgreSQL to analyze the data, built a machine learning model to predict delivery time, and created a Power BI dashboard to present the results.

## Tools and Technologies

- Python (Pandas, NumPy, Matplotlib, Seaborn)
- PostgreSQL
- Power BI
- XGBoost
- Scikit-learn
- Excel and CSV for data handling

## Key Results

| Metric | Result |
|---|---:|
| Total delivery records | 45,584 |
| Average delivery time | 26.29 minutes |
| Mean Absolute Error (MAE) | 3.12 minutes |
| Root Mean Squared Error (RMSE) | 3.92 minutes |
| R² Score | 0.824 |

The latest XGBoost model achieved an MAE of approximately 3.12 minutes on the test dataset. This means its predictions differed from the actual delivery times by about 3.12 minutes on average.

## Key Insights

- Delivery time generally increases when traffic conditions become heavier.
- Orders involving two or more deliveries tend to take longer than orders with a single delivery.
- Weather conditions show noticeable differences in average delivery time.
- Festival periods are associated with longer delivery times in this dataset.
- Vehicle condition and delivery partner ratings are also useful factors to study when analyzing delivery performance.

## Power BI Dashboard

I created an interactive Power BI dashboard to make the results easier to understand. It includes key performance indicators and comparisons based on traffic, weather, vehicle type, distance, city, and festival conditions.

The dashboard also includes filters that allow users to explore different parts of the dataset.

## Optimization Scenario Analysis

I also tested a hypothetical scenario to understand how average delivery time might change if some orders involving multiple deliveries could be handled more efficiently.

| Scenario | Average Delivery Time | Estimated Reduction |
|---|---:|---:|
| Baseline | 26.29 minutes | — |
| 10% scenario | 26.22 minutes | 0.28% |
| 20% scenario | 26.14 minutes | 0.58% |
| 30% scenario | 26.07 minutes | 0.87% |

These results are estimates based on a simplified assumption. They do not represent a real-world optimization system or guaranteed improvements.

## Project Workflow

1. Cleaned and prepared the delivery dataset.
2. Performed exploratory data analysis using Python.
3. Analyzed delivery trends using PostgreSQL.
4. Trained and evaluated an XGBoost regression model.
5. Created an interactive Power BI dashboard.
6. Tested hypothetical scenarios to study the potential reduction in delivery time.

## Future Scope

- Improve prediction accuracy by testing other machine learning models.
- Include real-time traffic and weather information.
- Explore route planning and delivery assignment optimization.
- Develop a simple application for predicting delivery time.

## Project Files

- [Cleaned Dataset](data/Zomato_Cleaned_Data.csv)
- [Delivery Predictions](data/Delivery_Predictions.csv)
- [Model Performance](data/Model_Performance.csv)
- [Feature Importance](data/Feature_Importance.csv)
- [Traffic Analysis](data/Traffic_Analysis.csv)
- [Project Summary](data/Project_Summary.csv)
- [Multiple Delivery Experiment](data/Multiple_Delivery_Experiment.csv)
- [Multiple Delivery Policy Comparison](data/Multiple_Delivery_Policy_Comparison.csv)
- [Optimization Scenario Results](data/Optimization_Scenario_Results.csv)
- [Project Report (PDF)](dashboard/Zomato_Delivery_Analytics_Project_Report_Final.pdf)

## About Me

I am a Mechanical Engineering student at BIT Mesra with an interest in data analytics, machine learning, and operations optimization. Through this project, I wanted to apply data analysis and machine learning techniques to a real-world delivery problem.
