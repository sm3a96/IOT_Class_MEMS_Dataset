# IoT Anomaly and Failure Detection using Ensemble Learning
![Framework](https://github.com/user-attachments/assets/f8692269-d012-4e6c-9c12-6af0a35972f8)

## Overview
This project presents an ensemble learning framework for enhanced anomaly and failure detection in IoT systems. As IoT devices become more ubiquitous and complex, reliable anomaly detection methods are critical for maintaining the security and functionality of these systems. This research uses ensemble methods alongside individual machine learning models to improve anomaly detection accuracy, tested across two real-world datasets.
## IoT Anomaly and Failure Detection using Ensemble Learning Framework 

## Project Structure
- **data/**: Contains data preprocessing scripts and datasets (MEMS and N_BaIoT).
- **models/**: Holds individual AI models, ensemble methods, and combined model implementations.
- **notebooks/**: Jupyter notebooks demonstrating exploratory data analysis (EDA) and model evaluation.
- **src/**: Core code files for training and evaluating models.
- **results/**: Stores results, evaluation metrics, confusion matrices, and comparative analysis plots.
- **README.md**: This file, providing an overview and instructions for use.

## Datasets
This project utilizes:
- **MEMS Dataset**: Collected from IoT-enabled manufacturing sensors to detect operational status: normal, near-failure, and failure states.
- **N-BaIoT Dataset**: Collected from IoT devices infected with botnets like Mirai and Gafgyt, designed to identify and classify network anomalies and various attack types.

## Key Features
- **Anomaly Detection Framework**: Integrates individual AI models and ensemble techniques to detect and classify anomalies and failures in IoT systems.
- **Comprehensive Model Comparison**: Evaluates single models (e.g., SVM, KNN) and ensemble models (e.g., stacking, blending) based on accuracy, precision, recall, F1-score, and runtime.
- **Real-World Evaluation**: Provides performance results and runtime metrics across two IoT datasets, showcasing the practical applicability of the framework in varied IoT environments.

## Getting Started

### Prerequisites
- Python 3.10.9
- Libraries: TensorFlow/Keras, Scikit-learn, Pandas, NumPy, Matplotlib

## Results
The research findings demonstrate that ensemble methods, particularly stacking and blending, outperform single models in anomaly detection tasks across both datasets. Performance highlights:
- **MEMS Dataset**: Stacking and blending achieved accuracy up to 72.1%.
- **N-BaIoT Dataset**: Stacking models achieved near-perfect accuracy of 99.9%.

## Contributions
This project contributes:
- A flexible framework for anomaly detection in IoT systems.
- Benchmark data and code, publicly available for reproducibility and further research.


## Contact
- Mustafa Abdallah - abdalla0@purdue.edu
- Ismail Bibers - ibibers@purdue.edu


