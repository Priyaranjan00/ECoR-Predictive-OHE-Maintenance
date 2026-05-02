Here is a professional, concise `README.md` formatted specifically for a GitHub repository.

# ECoR Predictive OHE Maintenance

**AI-driven Predictive Maintenance of 25kV OHE Systems for East Coast Railway using Random Forest and Python.**

---

## 📌 Project Overview
This project addresses the challenge of **Insulator Flashovers** in coastal railway corridors. Using **Machine Learning**, we simulate a Condition-Based Monitoring (CBM) system to predict potential failures in 25kV Overhead Equipment (OHE) due to environmental factors like high humidity and salt-air corrosion, specifically focused on the **East Coast Railway (ECoR)** zone.

## 🛠️ Tech Stack
*   **Language:** Python 3.x
*   **Libraries:** `Pandas`, `NumPy`, `Scikit-Learn`, `Matplotlib`
*   **Platform:** Jupyter Notebook

## 📂 Project Structure
*   `ECoR_Maintenance_Model.ipynb`: The main Jupyter Notebook containing data cleaning, simulation, and ML modeling.
*   `railway_data.csv`: Station and train metadata sourced from Kaggle.
*   `requirements.txt`: Necessary Python libraries.

## 🧠 Model Logic
The project utilizes a **Random Forest Classifier** to analyze the following parameters:
*   **Input Features:** Traction Voltage (kV), Humidity (%), and Leakage Current (mA).
*   **Target:** `Maintenance_Required` (Binary prediction of flashover risk).
*   **Logic:** If Leakage Current > 10mA during high humidity (>75%), the system triggers a maintenance alert for the specific station/section.



## 📊 Key Results
The model achieves high accuracy in identifying "High Risk" zones. By filtering data for ECoR stations (Bhubaneswar, Puri, Visakhapatnam, etc.), the project provides a visual heat-map of where maintenance resources should be prioritized to prevent line trips.

## 🚀 How to Run
1. Clone the repository: `git clone [https://github.com/yourusername/ECoR-Predictive-OHE-Maintenance.git](https://github.com/yourusername/ECoR-Predictive-OHE-Maintenance.git)`
2. Install dependencies: `pip install -r requirements.txt`
3. Run the Jupyter Notebook to view the model training and risk visualizations.

---
**Author:** Priya Ranjan Biswal 
**Department:** Electrical Engineering  
**Focus:** Railway Electrification & Data Analytics
