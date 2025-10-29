# IoT Botnet Detection Research

This repository contains experiments and analysis for detecting IoT botnet attacks using both Machine Learning (ML) and Deep Learning (DL) approaches.

---

## 🧠 Research Overview
IoT devices are increasingly vulnerable to botnet-based Distributed Denial of Service (DDoS) attacks such as Mirai and Bashlite.  
The goal of this research is to evaluate and compare different ML and DL models to identify effective yet lightweight methods suitable for real-world IoT environments.

---

## ⚙️ Experimental Design
- **Models:** Random Forest, Autoencoder, Bi-LSTM  
- **Datasets:** N-BaIoT and Bot-IoT  
- **Feature Configurations:** All Features vs Extra Trees Selected Features  
- **Evaluation Metrics:** Accuracy, Precision, Recall, F1-score, AUC, Detection Latency, and Computational Cost.

---

## 📁 Project Structure
---

## 🚀 Getting Started

### 1. Clone the repository
```bash
git clone https://github.com/Serenechien0172/iot-botnet-detection.git
cd iot-botnet-detection
conda create -n iot_botnet_research python=3.9
conda activate iot_botnet_research
pip install -r requirements.txt
