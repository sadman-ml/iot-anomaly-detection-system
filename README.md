# IoT Anomaly Detection & Machine Health Monitor

This is a student project where I built a system to monitor industrial machines. Using **Machine Learning**, the system can detect if a machine is behaving strangely (Anomaly) and identify what kind of problem it might have.

## What does this project do?
In big factories, if a machine breaks suddenly, it costs a lot of money. My project helps by:

1. **Detecting Problems:** Spotting unusual sensor readings (Temperature, Vibration, etc.).
2. **Identifying Issues:** Telling us if it's an "Overheating" issue or a "Vibration" issue.
3. **Smart Alerts:** Giving a quick health report of any machine.

## Tools & Technologies Used
- **Language:** Python 🐍
- **Environment:** Google Colab
- **Libraries:** Pandas (Data), Scikit-Learn (ML), Seaborn (Graphs)
- **Algorithms:** - **Isolation Forest** (to find anomalies)
  - **Random Forest** (to classify failure types)

## Project Steps (How I did it)
1. **Data Cleaning:** Loaded the sensor data and prepared it for the model.
2. **Feature Engineering:** Calculated "Rolling Averages" to understand the machine's behavior over time.
3. **Visualization:** Created Heatmaps and Scatter plots to see the relationship between sensors.
4. **Model Training:** Trained the AI to recognize normal vs. abnormal machine behavior.
5. **Testing:** Built an alert function to test real-time machine health.

## Files in this Repo
- `IoT_Anomaly_Detection.ipynb`: The main code file with explanations.
- `smart_manufacturing_data.csv`: The dataset containing sensor values.
- `Models/`: Contains saved files (`.pkl`) so the model can be reused without retraining.
- `Reports/`: All the charts generated from the data.

---
**Developed by:** Sadman Ahmed  
