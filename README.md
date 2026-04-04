# satellite-telemetry-analysis
📡Project overview
Satellite generates continuous telemetry data such as temperature,voltage and current readings.
Monitoring this data manually is difficult.
This project detect anomalies in satellite telemetry parameters using statistical techniques like Z-score and visualizes abnormal behaviour using python

Data:
Source:satellite telemetry dataset
Format:CSV file
parameters:Timestamp,Sensor_ID,Temperature,voltage,Current,Power.

Approach:
1. data cleaning: remove invalid data.
2. exploratory analysis: statistical summaries
3. Anomaly Detection : explored the z-score based detection.
4. visualization: plot the anomalies 

Results:
1. Identified parameter trends over Time
2. Observed relationship between volatge,current and Power
3. Detect the anomaly detection 

Tech Stack:
1. Python
2. Pandas
3. Matplotlib
4. Scikit-learn

Model implemented :
1. Logestic Regression
2. Decision Tree
3. K Nearest Neighbour (KNN)

Model evaluated using:
1.Accuracy score
2.Recall score
3.F1 Score

Conclusion:
Model selection depends on the importance of detecting anomalies (Recall) vs overall correctness (Accuracy).







