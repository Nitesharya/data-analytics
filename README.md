🚗 Uber Rides Data Analysis (EDA)

This project performs Exploratory Data Analysis (EDA) on an Uber rides dataset to uncover patterns related to trip purpose, distance, time, and category using Python.

📌 Project Overview

The notebook focuses on:

Cleaning and preprocessing Uber trip data

Handling missing and duplicate values

Feature engineering (date, time, duration, speed)

Visualizing trends and correlations

Gaining insights into ride behavior

🛠️ Tech Stack

Python

Pandas – data manipulation

NumPy – numerical operations

Matplotlib & Seaborn – data visualization

📂 Dataset

File used: UberDataset.csv

Contains ride details such as:

Start & stop locations

Miles traveled

Ride purpose

Category (Business / Personal)

Start & end timestamps

🔍 Key Steps Performed

✔️ Checked and handled missing values

✔️ Removed duplicates

✔️ Converted date & time columns to datetime

✔️ Extracted month, year, duration, speed

✔️ Fixed invalid and negative values

✔️ Reorganized and cleaned dataset structure

📊 Visualizations & Insights

Correlation heatmap between numerical features

Monthly distribution of Uber rides

Ride purpose analysis

Category-wise comparison (Business vs Personal)

These visualizations help understand usage trends and travel behavior.

📈 Key Insights

Certain months show significantly higher ride activity

Business rides dominate specific purposes

Distance and duration are strongly correlated

Data quality issues (negative speed) were identified and addressed

▶️ How to Run

Clone the repository

Place UberDataset.csv in the same directory

Open the notebook:

jupyter notebook uber.ipynb


Run cells sequentially

📌 Future Improvements

Add outlier treatment

Build predictive models (trip duration / category)

Interactive dashboards (Plotly / Streamlit)

👤 Author

Nitesh Arya
BE – Information Science & Engineering
Interested in Data Science & Machine Learning

If you want:

a shorter README

a more corporate tone

or a resume/project-description version

just tell me 👍
