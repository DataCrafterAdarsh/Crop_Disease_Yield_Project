Crop_Disease_Yield_Project/
│
├── data/
│   ├── images/                     # PlantVillage image dataset
│   ├── yield_data.csv              # Raw yield dataset
│   └── yield_data_cleaned.csv      # Cleaned yield dataset
│
├── notebooks/
│   ├── 01_Disease_Data_Understanding.ipynb
│   ├── 02_Image_Preprocessing.ipynb
│   ├── 03_CNN_Model.ipynb
│   ├── 04_Disease_Model_Evaluation.ipynb
│   ├── 05_Yield_Data_Cleaning.ipynb
│   ├── 06_Yield_EDA.ipynb
│   ├── 07_Yield_Model_Training.ipynb
│   └── 08_Final_Prediction_Demo.ipynb
│
├── models/
│   ├── crop_disease_cnn_model.keras
│   ├── yield_prediction_rf.pkl
│   └── yield_scaler.pkl
│
├── results/
│   ├── confusion_matrix.png
│   ├── disease_classification_report.csv
│   └── yield_correlation_heatmap.png
│
├── report/
│   └── Project_Report.docx / .pdf
│
└── README.md
