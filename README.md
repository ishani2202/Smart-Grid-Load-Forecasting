# ⚡ Smart Grid Load Forecasting with Transformers and Machine Learning Models

This repository contains an in-depth study and implementation of time series forecasting techniques applied to electrical grid data. By leveraging big data analytics and advanced machine learning models, this project aims to optimize load forecasting, paving the way for smarter energy distribution in renewable energy-driven grids.

---

## 📂 Repository Contents
1. **`Updated_Transformer_TimeSeries.ipynb`**  
   - Implementation of a custom Transformer model with an encoder-decoder structure for time series forecasting.  
   - Includes data preprocessing with Apache Spark, enabling scalable and efficient handling of large datasets.  
   - Benchmarks the Transformer against other machine learning models:
     - Random Forest  
     - CatBoost  
     - LightGBM  

2. **`Forecasting_Electrical_Grid_Data.pdf`**  
   - A detailed report covering:
     - Data preprocessing workflows
     - Model architectures and hyperparameter tuning
     - Evaluation metrics and performance comparison
     - Ethical considerations in data usage and forecasting  

---

## 🛠️ Tools and Technologies
- **Big Data Processing**: Apache Spark  
- **Development Environment**: Google Colab  
- **Machine Learning Models**:
  - Random Forest  
  - CatBoost  
  - LightGBM  
  - Transformer Model  
- **Visualization**: Matplotlib, Seaborn for detailed insights  

---

## 🔍 Problem Overview
The shift to renewable energy has introduced challenges in managing fluctuating power demands. Traditional grids struggle with:
- Demand-supply imbalances  
- Integration of decentralized renewable energy sources  
- Energy wastage due to inefficiencies  

This project investigates the potential of **smart grids**, which utilize vast data resources from sensors and meters to optimize load predictions and energy distribution.

---

## 📊 Results and Key Findings
The custom Transformer model demonstrated superior performance compared to traditional machine learning methods. Evaluation metrics include:

| Model             | RMSE   | MAE    | R²     |
|--------------------|--------|--------|--------|
| **Transformer**    | 0.220  | 0.109  | 0.618  |
| LightGBM           | 0.224  | 0.106  | 0.604  |
| CatBoost           | 0.226  | 0.107  | 0.597  |
| Random Forest      | 0.227  | 0.114  | 0.595  |

---

## 🌟 Features of the Transformer Model
- **Positional Encoding** for sequential data processing.  
- **Multi-head Attention Mechanism** for capturing long-term dependencies.  
- Designed to handle sparse and high-dimensional time series data effectively.  

---

## 🌐 Live Demo
Test the interactive model hosted on **GitHub Pages**:  
[Live Demo](https://geareab.github.io/TimeSeriesGardio)  

_Note_: Due to size constraints, only LightGBM and CatBoost models are included in the demo. For Random Forest and Transformer models, refer to the provided codebase.


---

## 🤝 Contributions and Feedback
Contributions to improve the models, code, or documentation are welcome! Please feel free to open an issue or submit a pull request.

---

## 📄 License
This project is open-source and available under the MIT License.

---


