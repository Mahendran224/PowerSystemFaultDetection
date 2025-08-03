# ⚡ Power System Fault Detection and Classification

This project implements a machine learning-based approach to detect and classify faults in electrical power systems using historical measurement data.

## 📊 Problem Statement
Accurate and real-time fault detection in power systems is crucial for maintaining the stability and safety of the grid. This project leverages supervised learning methods to predict fault types based on voltage, current, and frequency data from simulated fault scenarios.

## 🚀 Project Overview

- ✅ Built and trained ML models using **IBM watsonx.ai AutoAI**
- ✅ Dataset: [Kaggle - Power System Faults Dataset](https://www.kaggle.com/datasets/ziya07/power-system-faults-dataset)
- ✅ Deployed using **IBM Watson Machine Learning**
- ✅ Inference handled through Python notebooks using `ibm-watson-machine-learning` SDK

## 📁 Repository Contents

| File | Description |
|------|-------------|
| `AutoAI_Fault_Detection.ipynb` | Notebook to access deployed model and perform prediction |
| `fault_data.csv` | Dataset used for training and testing |
| `ProjectTemplate (3).pdf` | Final project report with results and architecture |

## 🛠️ Technologies Used

- IBM Cloud (Watsonx, AutoAI, WML)
- Python (pandas, requests)
- JSON API integration
- Jupyter Notebooks

## 📌 Model Output
- Fault types detected: LG, LL, LLG, LLLG
- Evaluation metrics: Accuracy, F1-score (evaluated in AutoAI)

## 📈 Future Improvements
- Add time-series RNN/LSTM for real-time detection
- Expand dataset with SCADA/real-world signals
- Create dashboard via Node-RED or Streamlit
---

> Created as part of **IBM Skillsbuild – Problem Statement 41: Power System Fault Detection**
