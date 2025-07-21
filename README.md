# 🌧️ Prediction - The Onset of Rainy Season with LSTM

This repository contains the code, data, and results for predicting the onset of the rainy season in Kalimantan using the Long Short-Term Memory (LSTM) neural network model. The goal of this project is to analyze and improve the seasonal prediction capability based on climate model outputs (GCMs) and observed rainfall data.

---

## 📂 Repository Structure

    ├── LSTM/                         # Core LSTM model and scripts
    ├── codingan + Data fix/         # Final code and cleaned dataset
    ├── Output perbandingan model/   # Model output comparison results
    └── README.md                    # Project documentation

---

## 📌 Objectives

- Predict the onset of the rainy season in Kalimantan using machine learning (LSTM).
- Compare multiple climate model outputs (e.g., NCEP-CFSv2, CanSIPS-IC3).
- Analyze model performance under extreme climate events (El Niño / La Niña).

---

## 🛠️ Methods

- **Data Sources:** CHIRPS rainfall data, GCM outputs (Jan-May issued, Aug-Oct lead).
- **Preprocessing:** Time series preparation, normalization, and anomaly calculation.
- **Model:** LSTM with tuned architecture (2 hidden layers, 8 & 16 units).
- **Validation:** K-Fold Cross Validation and correlation skill maps.
- **Toolkits:** Python (Keras, NumPy, Pandas), GIS (ArcGIS/QGIS), R Studio.

---

## 📊 Results Highlight

- High accuracy in East, Central, and South Kalimantan.
- Negative correlation observed: more rainfall (Aug–Oct) → earlier onset.
- Notable years analyzed: 1988, 1998, 2010.

---

## 📁 Folders Detail

| Folder                       | Description |
|-----------------------------|-------------|
| `LSTM/`                     | Main LSTM scripts and structure |
| `codingan + Data fix/`      | Finalized code and cleaned input data |
| `Output perbandingan model/`| Model output maps and evaluation results |

---

## 🧠 Author

**Rashad Muhammad Fajar**  
Fresh graduate in Applied Meteorology – IPB University  
📍 Indonesia  
📧 rashadfajar@gmail.com  
🔗 [LinkedIn](https://www.linkedin.com/in/rashadmf)

---

## 📄 License

This project is for academic and research purposes only. For collaborations or further use, please contact the author.

