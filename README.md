📊 Climate Data Analysis Using NumPy


🔍 Overview
This project demonstrates the use of NumPy for efficient numerical computations and data analysis. Using a real-world climate dataset from Delhi, India, 
we analyze temperature, humidity, wind speed, and atmospheric pressure to derive meaningful insights such as averages, trends, and extreme conditions.


🗃️ Dataset
Source: Kaggle - Daily Climate Time Series Data
File: DailyDelhiClimateTrain.csv
Attributes:
date: Daily observation date
meantemp: Mean temperature (°C)
humidity: Relative humidity (%)
wind_speed: Wind speed (km/h)
meanpressure: Mean atmospheric pressure (mbar)


🧠 Objective
Apply various NumPy operations to:
Analyze average and extreme weather conditions
Perform statistical computations like mean, standard deviation, and percentiles
Identify anomalies in pressure and temperature
Convert and transform data using broadcasting
Apply convolution for a 7-day moving average of temperature



🛠️ Tools & Libraries
Python 3.x
NumPy
Pandas (for initial data loading)
Matplotlib (optional visualization)


📌 Key Features
Basic and advanced statistical operations using NumPy
Identification of extreme climate conditions
Data transformation via vectorized operations
Rolling average computation using convolution
Clean, well-commented, and modular code


📈 Sample Outputs
Average Temperature: 25.28°C
Max Temperature: 40.55°C
Number of Extremely Hot Days (>40°C): 11
Number of Low Pressure Days (<1000 mbar): 83


🧪 Future Improvements
Automate anomaly detection using thresholds
Extend analysis to multiple cities or longer timeframes
Integrate with real-time weather APIs


🚀 Getting Started
Clone the repo
Install dependencies:
pip install numpy pandas matplotlib
Run the notebook or script


📁 Folder Structure
climate-numpy-analysis/
├── DailyDelhiClimateTrain.csv
├── climate_analysis.py / climate_analysis.ipynb
├── README.md


📝 License
This project is open source and available under the MIT License.
