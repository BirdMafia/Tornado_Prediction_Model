
# Tornado Prediction Model 🌪️

This repository contains a machine learning pipeline designed to predict tornado intensity (EF scale) using historical weather data from Tornado Alley. The model leverages **PyTorch**, **scikit-learn**, and **progressive learning methods** for accurate forecasting.

## Key Features
- End-to-end ML pipeline with data preprocessing, feature engineering, and model evaluation.
- Random Forest Classifier optimized using GridSearchCV for better performance.
- Visualizations of feature importance and classification metrics.
- Historical tornado dataset (1950–2023).

## Dataset
The dataset used is **1950-2023_actual_tornadoes.csv**, containing tornado events, geographic data, and weather conditions. Additional references are included in the `/docs` folder.

## Project Structure
```
tornado-prediction-model/
│
├── mldak.py                  # Main ML pipeline code
├── data/
│   └── 1950-2023_actual_tornadoes.csv
├── docs/
│   ├── Background.pdf
│   ├── Phase_2_DAK.pdf
│   ├── Phase_3_Plan.docx
│   ├── In-Depth.docx
│   └── Data_Sets.docx
├── images/
│   └── feature_importance.png
└── README.md
```

## Installation
Clone the repository and install dependencies:
```bash
git clone https://github.com/<your-username>/tornado-prediction-model.git
cd tornado-prediction-model
pip install -r requirements.txt
```

## Usage
Run the ML pipeline:
```bash
python mldak.py
```

The script will:
- Preprocess and clean the dataset.
- Train and evaluate the Random Forest model.
- Output metrics and feature importance plots.

## Sample Output
- **Model Accuracy:** ~90% (varies by random split)
- **Feature Importance Plot:** Available in `/images`.

## Contributors
- Yusuf Sarigul (Lead ML Engineer)
- Team DAK (Trace Hodge, William Lan, Citlali Lopez, Josh McCoy)
