# **Geohackathon: Seismic-Well Log Integration and Prediction**

This repository contains the workflow for integrating seismic and well log data, applying machine learning models, and visualizing subsurface properties as part of the **Geohackathon** project.

---

## **Project Structure**

📦 repository-name/ ├── 📂 datasets/ # Contains the input datasets and preprocessed files │ ├── seismic_data/ # Original seismic files (.sgy, .csv) │ ├── well_logs/ # Well log data for known wells │ ├── combined_dataset.csv # Final combined dataset with seismic and well log features │ ├── 📂 notebooks/ # Jupyter notebooks for analysis and modeling │ ├── 01_data_preprocessing.ipynb # Data cleaning, feature engineering │ ├── 02_model_training.ipynb # Machine learning model training and optimization │ ├── 03_predictions.ipynb # Prediction and visualization for unknown wells │ ├── 📂 scripts/ # Standalone Python scripts │ ├── preprocess_data.py # Data preprocessing │ ├── train_model.py # Model training pipeline │ ├── make_predictions.py # Generating predictions │ ├── 📂 outputs/ # Results and outputs │ ├── predictions/ # Prediction CSV files for each well │ ├── figures/ # Visualizations and plots │ ├── 📂 team_approach/ # Alternative solutions by team members │ ├── approach_by_member_A.ipynb │ ├── approach_by_member_B.py │ ├── main.py # Main entry point to run the full pipeline ├── requirements.txt # Python dependencies └── README.md # Project documentation (this file)

---

## **Project Highlights**
- **Data Integration:** Combines seismic data with well logs using depth-matching algorithms.
- **Feature Engineering:** Extracts seismic attributes (amplitude, frequency, phase) and engineered features for machine learning.
- **Machine Learning Models:** Models for predicting porosity, permeability, and temperature gradients.
- **Prediction Pipeline:** Predicts properties for unknown wells using seismic data and trained models.
- **Visualization:** Depth-wise property plots for validation and insights.

---

## **Getting Started**

### **1. Clone the Repository**
```bash
git clone https://github.com/yourusername/repository-name.git
cd repository-name

## **License**
This project is licensed under the MIT License.

