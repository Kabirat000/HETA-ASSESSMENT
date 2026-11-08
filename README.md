# Predictive Maintenance for Industrial Training Rigs

A machine learning project that predicts equipment failure using industrial sensor data from a manufacturing training rig. The system uses Gradient Boosting to estimate failure probability and demonstrates how predictive maintenance can support engineering training through real-time risk assessment, explainable AI, and configurable alert thresholds. :chatgpt-content-reference{index="0"}

## Project Overview

Unexpected equipment failures increase maintenance costs, reduce equipment availability, and interrupt engineering training. This project develops a predictive maintenance model capable of identifying potential failures from sensor measurements before they become critical.

Rather than providing only a binary prediction, the model outputs a probability score that supports configurable AMBER and RED alert thresholds, allowing different operating environments to balance early warnings against false alarms. SHAP explainability is incorporated to improve transparency by showing which sensor readings contribute most to each prediction. :chatgpt-content-reference{index="1"}

---

## Objectives

- Predict equipment failures using historical sensor data
- Build an interpretable machine learning model suitable for industrial deployment
- Demonstrate explainable AI using SHAP
- Support engineering apprentices through real-time risk monitoring
- Provide a foundation for deployment on live industrial training rigs

---

## Dataset

The project uses two datasets representing operating conditions of an industrial training rig:

- `rig_sensor_fail.csv`
- `rig_sensor_no failure.csv`

The datasets contain multiple sensor measurements captured during normal operation and failure conditions.

---

## Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Scikit-learn
- XGBoost / Gradient Boosting
- SHAP
- Matplotlib
- Seaborn

---

## Project Structure

```
.
├── predictive_maintenance_analysis.ipynb
├── rig_sensor_fail.csv
├── rig_sensor_no failure.csv
├── predictive_maintenance.docx
├── predictive_maintenance copy.docx
├── Predictive_Maintenance_Final_speech_notes.pptx
└── README.md
```

---

## Methodology

The project follows a standard machine learning workflow:

1. Load and combine sensor datasets
2. Data preprocessing
3. Exploratory Data Analysis
4. Feature engineering
5. Model training using Gradient Boosting
6. Model evaluation
7. SHAP explainability
8. Failure probability prediction

The model was selected because it trains quickly on standard hardware while providing high predictive performance without requiring GPU resources, making it suitable for industrial deployment. :chatgpt-content-reference{index="2"}

---

## Industrial Application

The solution is designed for manufacturing training environments where engineers and apprentices can monitor equipment health in real time.

Key features include:

- Live failure probability estimation
- Configurable AMBER and RED alert thresholds
- Explainable predictions using SHAP
- Support for maintenance decision-making
- Integration into engineering training platforms :chatgpt-content-reference{index="3"}

---

## Future Improvements

Potential enhancements include:

- Live sensor integration
- Drift monitoring
- Scheduled model retraining
- Probability calibration
- Earlier failure prediction using lead-time forecasting
- Docker deployment
- Dashboard integration
- AR/VR learning platform integration :chatgpt-content-reference{index="4"}

---

## Repository Contents

| File | Description |
|------|-------------|
| `predictive_maintenance_analysis.ipynb` | Machine learning analysis notebook |
| `rig_sensor_fail.csv` | Failure dataset |
| `rig_sensor_no failure.csv` | Normal operating dataset |
| `predictive_maintenance.docx` | Technical report |
| `predictive_maintenance copy.docx` | Revised report |
| `Predictive_Maintenance_Final_speech_notes.pptx` | Presentation slides |

---

## Author

**Kabirat Olajire**

MSc Artificial Intelligence & Data Science

University of Hull
