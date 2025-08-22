# 🚗 Vehicle CO₂ Emission Exploratory Data Analysis

## 📌 Project Overview

This project focuses on performing **Exploratory Data Analysis (EDA)** on a dataset of vehicle specifications to understand factors affecting **CO₂ emissions**.
The analysis explores how **engine size, cylinders, transmission type, fuel type, and vehicle class** influence both **fuel consumption** and **CO₂ emissions**.

The goal of this project is to extract **meaningful insights and patterns** from the dataset that can help in making sustainable choices and better understanding environmental impacts.

---

## 📊 Dataset

* **Features** include:

  * Make & Model
  * Vehicle Class
  * Engine Size (L)
  * Cylinders
  * Transmission
  * Fuel Type
  * Fuel Consumption (City, Highway, Combined)
  * CO₂ Emissions (g/km)

---

## 🔍 Exploratory Data Analysis (EDA)

### Key Insights:

* **Engine Size & Cylinders**: Larger engines and higher cylinders strongly correlate with higher CO₂ emissions.
* **Fuel Type**:

  * Gasoline-powered vehicles tend to emit more CO₂.
  * Diesel vehicles are relatively more efficient.
  * Hybrid vehicles are the most eco-friendly.
* **Vehicle Class**:

  * SUVs and Pickup Trucks are the highest contributors to CO₂ emissions.
  * Compact and Subcompact cars emit significantly less.
* **Fuel Consumption**: Strong positive correlation with CO₂ emissions — as consumption increases, emissions rise.

### Visualizations:

* Scatterplots of **Fuel Consumption vs CO₂ Emissions**, segmented by Vehicle Class, Transmission, Fuel Type.
* Pairplots for top car brands and models.
* Histograms for distribution of Engine Size, Cylinders, Fuel Consumption, and CO₂.
* Correlation analysis between numerical features.

---

## 🛠️ Tech Stack

* **Language**: Python
* **Libraries**: pandas, numpy, matplotlib, seaborn
* **Environment**:  Google Colab

---

## 🚀 How to Run

1. Clone the repository

   ```bash
   git clone https://github.com/your-username/vehicle-co2-emission-analysis.git
   cd vehicle-co2-emission-analysis
   ```
2. Install dependencies

   ```bash
   pip install -r requirements.txt
   ```
3. Run the Jupyter Notebook

   ```bash
   jupyter notebook
   ```
4. Open `co2_emission_EDA.ipynb` and follow the analysis.

---

## 📌 Future Improvements

* Extend analysis with **time-based or region-based vehicle data**.
* Compare emissions across **brands and models** in more detail.
* Build a **predictive ML model** for CO₂ emissions.

---

## 📄 License

This project is licensed under the MIT License – free to use and modify.

---

## ✨ Acknowledgements

* Kaggle for providing the dataset
* Python libraries: pandas, seaborn, matplotlib
