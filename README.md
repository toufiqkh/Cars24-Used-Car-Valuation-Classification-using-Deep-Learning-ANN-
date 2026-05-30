# Cars24-Used-Car-Valuation-Classification-using-Deep-Learning-ANN-
An end-to-end Deep Learning classification system built with **TensorFlow 2 / Keras** to predict whether a used car's market value falls into the "Premium" bracket (above national median price) or "Budget" bracket based on historical operational vehicle data.


## 📌 Project Overview
An end-to-end Deep Learning classification system built with **TensorFlow 2 / Keras** to predict whether a used car's market value falls into a "Premium" or "Budget" bracket based on historical operational vehicle data.

## 🛠️ Data Pipeline & ETL (Excel & Python)
Before building the neural network, a comprehensive **ETL (Extract, Transform, Load)** process was carried out to ensure high data quality:
* **Extract & Profile:** Extracted and handled large-scale raw operational scales and customer rating data schemas from the core dataset.
* **Transform (Excel):** Utilized advanced Excel data modeling features to scrub erratic inputs, map geospatial variables, drop irrelevant tracking columns, and establish structural price thresholds.
* **Load (Python):** Imported the refined staging data into Python for final vectorization, generating 19 scaled features using `StandardScaler` to maximize neural network gradient descent efficiency.

## 📈 Key Technical Milestones & Achievements
* **Predictive Performance:** Achieved a robust **84.39% accuracy** on unseen test data.
* **Architecture Design:** Built a Sequential Artificial Neural Network (ANN) featuring 2 Dense hidden layers (6 nodes each) utilizing `ReLU` activations and a single-node `Sigmoid` output layer.
