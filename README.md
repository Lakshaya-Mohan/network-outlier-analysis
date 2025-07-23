# Real-Time Network Traffic Anomaly Detection System

A real-time network traffic monitoring system built with Streamlit to enhance network security by detecting anomalous packet behavior using machine learning algorithms.A lightweight, real-time, Wireshark-like traffic monitor that includes anomaly detection using machine learning.

---

## Project Overview

This project captures live network traffic and applies detailed protocol analysis to identify irregularities in data flow. It uses machine learning techniques like Isolation Forest and Local Outlier Factor (LOF) to automatically detect suspicious patterns that may indicate potential cyber threats. The interactive Streamlit interface allows users to monitor and visualize anomalies in real time.

---

## Objectives

- Capture live network packets from the system
- Perform protocol-level inspection and extract relevant features
- Apply ML models to detect outliers (anomalies)
- Display results via an interactive Streamlit dashboard
- Send real-time alerts via email for detected threats

---

## Machine Learning Algorithms Used

- **Isolation Forest** – Detects anomalies by isolating them in feature space
- **Local Outlier Factor (LOF)** – Identifies data points that deviate significantly from their neighbors

---

## Features

- Real-time packet sniffing using `scapy`
- Feature extraction and ML-based anomaly detection
- Live visualization and logging with Streamlit
- Email alerts on detected anomalies
- Export logs for offline analysis

---

## Tech Stack

- Python
- Streamlit – UI & dashboard
- Scapy – Live packet sniffing
- Scikit-learn – ML models
- SMTP (smtplib) – Email alerts
- Pandas, NumPy – Data processing

---

##Output:

#Packets Captured:
<img width="1150" height="784" alt="Screenshot 2025-07-23 174755" src="https://github.com/user-attachments/assets/93f1b3c1-c153-4648-baa2-1542edc3bae3" />

#Pie Chart Distribution
<img width="1253" height="502" alt="Screenshot 2025-07-23 174803" src="https://github.com/user-attachments/assets/e41c7c6d-4669-446a-8711-bd2341434243" />

#Plotting of anomalies
<img width="1260" height="420" alt="Screenshot 2025-07-23 174809" src="https://github.com/user-attachments/assets/5421a270-9c6f-4469-a82e-d15f6a759271" />

#Alerts
<img width="859" height="474" alt="Screenshot 2025-07-23 174814" src="https://github.com/user-attachments/assets/1d293c7f-3309-480b-b4ef-b13a90e5a5d8" />

#Auto-generated Email alerts
<img width="1322" height="494" alt="Screenshot 2025-07-23 174824" src="https://github.com/user-attachments/assets/0178b80f-4b7d-4623-9d83-86c9c44e03b4" />


##Important 

This is made using Streamlit , so to run this code on your system , use this command - streamlit run network_outlier.py
Make sure your system has scapy installed in it - pip install scapy
Replace the mail id in your code to send email alerts from your designated mail id

