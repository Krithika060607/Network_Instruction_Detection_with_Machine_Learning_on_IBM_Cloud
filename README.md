# Network Intrusion Detection Using Machine Learning on IBM Cloud

## Problem Statement
Build a Network Intrusion Detection System (NIDS) using a machine-learning approach capable of analyzing network traffic data and discriminating between various kinds of cyber-attacks, such as:
- DoS (Denial of Service)
- Probe
- R2L (Remote to Local)
- U2R (User to Root)

The system must be capable of discriminating between activities that are normal and activities that are malicious to warn early in communication network

## Proposed Solution
Basically, a machine-learning model was developed that can learn from network traffic data to predict whether a given data point represents normal or attack behavior. Also, this trained model is currently hosted on **IBM Cloud Watson Machine Learning** and is accessible via REST API. 

## Technologies Used
- IBM Cloud (Lite Plan)
- Watson Machine Learning
- Dataset: [Kaggle NIDS Dataset] (https://www.kaggle.com/datasets/sampadab17/network-intrusion-detection)
  
## ML Algorithms Used
- Decision Tree Classifier 
(You may choose to use Random Forest, Logistic Regression, etc.)
---

## 📂 Project Structure
├── README.md
├── NIDS_Model.ipynb
├── nids_model.pkl
└── data.csv


