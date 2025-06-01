# 🇪🇬 Terrestrial Heat Flow Modeling in Egypt using Machine Learning

![Graphical Abstract](./Graphical_Abstract.png)

## 📌 Overview

This repository supports the research titled:
**"Machine Learning-Based Terrestrial Heat Flow Modeling in Egypt"**.

Our study presents a robust pipeline that utilizes **Random Forest Regression (RFR)** to model Egypt’s terrestrial heat flow (THF) based on 16 geophysical and geological datasets. The primary objective is to create an accurate spatial model of THF to assess Egypt's geothermal energy potential.

---

## 🧠 Abstract

This work aims to create a machine-learning model that can contribute to a comprehensive understanding of Egypt's terrestrial heat flow distribution. The model is based on the random forest regression method, with a sparsely distributed dataset of heat flow measurements. The model is trained using 16 geophysical and geological databases, which are well-known for their efficacy in geothermal evaluation.

The results confirm that the **Red Sea rift region** exhibits the highest THF (100–185 mW/m²), while the **Western Desert's Arabo-Nubian Massif** shows the lowest (30–60 mW/m²). These findings highlight Egypt’s diverse geothermal regime, influenced by tectonic and structural variations.

---

## 🔁 Workflow

The pipeline follows these key steps:

1. **Data Downloading and Gridding**
2. **Data Merging**  
   - Training Data [X]  
   - Reference Data [Y]
3. **Data Preprocessing**
4. **Data Processing**  
   - Outlier detection using Isolation Forest  
   - Feature selection (`T`, `D`, `S`, `K`, `F`)
5. **Hyperparameter Tuning**
6. **Random Forest Regression Modeling**
7. **Optimum Model Selection**
8. **Final Output: THF Model**

---

## 🛠️ Technologies Used

- Python
- scikit-learn
- Pandas, NumPy
- Matplotlib / Seaborn
- GIS libraries (e.g., Rasterio, Geopandas)
- Jupyter Notebooks

---

## 📊 Output

- Geospatial THF maps of Egypt
- Performance metrics of the model
- Feature importance insights

---

## 📂 Repository Structure
├── data/
│ ├── raw/
│ └── processed/
├── notebooks/
│ ├── 01_data_preprocessing.ipynb
│ ├── 02_feature_engineering.ipynb
│ └── 03_model_training.ipynb
├── models/
├── outputs/
│ └── THF_prediction_map.tif
├── utils/
│ └── helper_functions.py
├── Graphical_Abstract.png
├── README.md
└── requirements.txt

## 🌍 Applications

- Geothermal energy exploration
- Environmental and geophysical studies
- Energy infrastructure planning

---

## 📬 Contact

For questions or collaborations, feel free to reach out via [your-email@example.com] or open an issue.

---

## 📄 License

This project is licensed under the MIT License. See `LICENSE` for more information.
