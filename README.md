# WESAD-Stress-Detection
# 🧠 Mapping Physiological Signals for Student Stress Detection
**Using the WESAD Dataset & Random Forest Classification**

## 📌 Project Overview
This project explores how wearable technology can protect student mental health. By analyzing data from the **WESAD (Wearable Stress and Affect Detection)** dataset, we built a machine learning model capable of distinguishing between baseline, stress, and amusement states with **91.65% accuracy**.

## 📊 Key Findings
We analyzed three primary physiological markers:
1. **EDA (Sweat):** Shown to be the most discriminative feature for stress.
2. **ECG/PPG (Heart Activity):** Used to track cardiac variability under pressure.
3. **Skin Temperature:** Used to monitor thermal regulation during high-arousal states.

### Joint Probability Analysis
![Joint KDE Plot](./visualizations/your_joint_plot_name.png)
*The plot above shows the "Stress Migration," where data points shift toward higher EDA values as psychological pressure increases.*

## ⚙️ Technical Implementation
* **Dataset:** WESAD (Multimodal wearable sensor data).
* **Model:** Random Forest Classifier.
* **Validation:** 5-Fold Cross-Validation.
* **Libraries:** Scikit-Learn, Seaborn, Matplotlib, Pandas.

## 🚀 How to Use
1. Clone the repo: `git clone https://github.com/YourUsername/WESAD-Stress-Detection-ML.git`
2. Run the preprocessing notebook in `/notebooks`.
3. Evaluate the model performance.
