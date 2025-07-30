Machine Failure Prediction Using Sensor Data

This project aims to predict machine failures in advance using sensor data from industrial machines. Early failure prediction helps in proactive maintenance, reducing downtime and improving operational efficiency.

The dataset contains real-time sensor readings from various machines. It includes the following features:

Feature	Description
footfall	Number of people/objects passing near the machine
temp Mode	Temperature mode/setting of the machine
AQ	Air Quality index near the machine
USS	Ultrasonic Sensor (proximity data)
CS	Current sensor readings (power consumption)
VOC	Volatile organic compounds level
RP	Rotational position (RPM)
IP	Input pressure
Temperature	Operating temperature of the machine
fail	Binary target (1 = failure, 0 = no failure)

Tools & Libraries
Python
Pandas, NumPy – Data manipulation
Matplotlib, Seaborn – Data visualization
Scikit-learn – Machine learning models & evaluation

Model Training & Comparison
We tested multiple classification models:

Algorithm	Notes
Logistic Regression	Baseline model using sigmoid function
K-Nearest Neighbors (KNN)	Simple distance-based model

Final model accuracy: 94%
