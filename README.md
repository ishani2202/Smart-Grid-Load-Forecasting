# ⚡️ Smart Grid Load Forecasting with Transformers and ML Models 🌟

Welcome to the **Smart Grid Load Forecasting** repository! This project leverages cutting-edge machine learning and AI techniques to predict electricity load patterns. By combining Big Data with advanced algorithms, we aim to enhance energy efficiency and pave the way for smarter, sustainable energy management.

---

## 🚀 What's Inside?

### 📂 Files and Insights
1. **`Updated_Transformer_TimeSeries.ipynb`**  
   _"Let the transformer work its magic!"_  
   - Hands-on implementation of a custom Transformer model for time series forecasting.  
   - Apache Spark-powered preprocessing optimized for large-scale data handling.  
   - Benchmarking results compared to:
     - **Random Forest**
     - **CatBoost**
     - **LightGBM**

2. **`Forecasting_Electrical_Grid_Data.pdf`**  
   _"Deep dives into the methods and results."_  
   - Comprehensive documentation detailing:
     - Data preprocessing workflow
     - Model architecture and performance metrics
     - Ethical considerations in AI-driven forecasting
     - Visualization of results and key insights

---

## 📊 Problem Statement
With the rise of renewable energy, managing fluctuating power demands has become a critical challenge for traditional grids. This project investigates the potential of smart grids, leveraging their vast data resources to optimize load forecasting and enhance energy distribution.

---

## 🛠️ Tools and Frameworks
- **Apache Spark** for Big Data preprocessing  
- **Google Colab** for collaborative model development  
- **Machine Learning Models**:
  - Random Forest  
  - CatBoost  
  - LightGBM  
  - Custom Transformer with an encoder-decoder structure  
- **Visualization**: Matplotlib, Seaborn  

---

## 🌟 Results
The custom Transformer model emerged as the best-performing approach, surpassing traditional models across multiple evaluation metrics, including RMSE, MAE, and R².

| Model             | RMSE   | MAE    | R²     |
|--------------------|--------|--------|--------|
| Transformer        | 0.220  | 0.109  | 0.618  |
| LightGBM           | 0.224  | 0.106  | 0.604  |
| CatBoost           | 0.226  | 0.107  | 0.597  |
| Random Forest      | 0.227  | 0.114  | 0.595  |

---

## 🌐 Live Demo
Test the model on our interactive web tool hosted on **GitHub Pages**:  
[Live Demo](https://geareab.github.io/TimeSeriesGardio)  
(Note: Random Forest and Transformer models are excluded from the demo due to size constraints.)

---

## 🤝 Contribution
Feel free to explore, suggest improvements, or contribute new ideas. Let’s innovate together!  

---

## 📄 License
This project is open-source and available under the MIT License.

---

🎉 _Happy Forecasting!_ 🌟
