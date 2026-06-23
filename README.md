# 🔬 Sensor Fusion with Anomaly Detection

[![Live Demo](https://img.shields.io/badge/Live-Demo-success?style=for-the-badge&logo=googlechrome)](https://heavy-banks-bathe.loca.lt)

A machine learning project that combines data from multiple sensor modalities...

A machine learning project that combines data from multiple sensor modalities and applies anomaly detection techniques to identify unusual or suspicious patterns. By fusing sensor inputs into a unified representation, the system achieves more robust and accurate anomaly detection than any single sensor could provide alone.

---

## 📌 Overview

This project demonstrates a **sensor fusion pipeline** where data from multiple sources (audio, thermal, EM, GPS, proximity, IMU, etc.) is merged and analyzed to detect anomalies. It leverages both supervised and unsupervised ML techniques to flag deviations from normal system behavior in real time or batch scenarios.

---

## 🚀 Features

- Multi-sensor data ingestion and preprocessing
- Sensor fusion via feature-level or decision-level merging
- Anomaly detection using statistical and ML-based approaches
- Visualization of fused sensor signals and detected anomalies
- Modular design — easily extendable to new sensor types

---

## 🗂️ Project Structure

```
Sensor-fusion-with-anomaly-detection/
│
├── Sensor Fusion with Anomaly Detection.ipynb   # Main notebook
└── README.md
```

---

## 🛠️ Tech Stack

| Tool | Purpose |
|------|---------|
| Python | Core language |
| Pandas / NumPy | Data manipulation & fusion |
| Scikit-learn | ML models & anomaly detection |
| Matplotlib / Seaborn | Visualization |
| Jupyter Notebook | Interactive development |

---

## ⚙️ Setup & Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/ManaswiGaur/Sensor-fusion-with-anomaly-detection.git
   cd Sensor-fusion-with-anomaly-detection
   ```

2. **Install dependencies**
   ```bash
   pip install pandas numpy scikit-learn matplotlib seaborn jupyter
   ```

3. **Launch the notebook**
   ```bash
   jupyter notebook "Sensor Fusion with Anomaly Detection.ipynb"
   ```

---

## 📊 How It Works

1. **Data Ingestion** — Load raw data from multiple sensor sources (CSV or simulated streams)
2. **Preprocessing** — Handle missing values, normalize signals, encode categoricals
3. **Sensor Fusion** — Merge sensor features into a unified feature matrix
4. **Anomaly Detection** — Apply detection algorithms (e.g., Isolation Forest, One-Class SVM, statistical thresholds) to identify outliers
5. **Visualization** — Plot fused signals, highlight anomalies, and evaluate detection performance

---

## 🧠 Anomaly Detection Approaches

- **Isolation Forest** — Tree-based unsupervised outlier detection
- **One-Class SVM** — Boundary-based anomaly identification
- **Statistical Methods** — Z-score and IQR-based thresholding
- **Supervised Classification** — Label-based detection when ground truth is available

---

## 📈 Evaluation Metrics

- Precision, Recall, F1-Score
- Confusion Matrix
- ROC-AUC Curve
- Anomaly score distributions

---

## 🔮 Future Work

- Real-time streaming anomaly detection via Kafka or MQTT
- Deep learning approaches (Autoencoders, LSTMs) for temporal anomalies
- Dashboard for live sensor monitoring and alerting
- Integration with IoT edge devices

---

## 👤 Author

**Manaswi Gaur**  
[GitHub](https://github.com/ManaswiGaur)

---

## 📄 License

This project is open-source and available under the [MIT License](LICENSE).
