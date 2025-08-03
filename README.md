# 🍷 Wine Quality Prediction  
![Correlation Heatmap](assets/correlation_heatmap.png)  

## 🔍 Key Insights  
- **Alcohol** shows strongest positive correlation with quality (0.48)  
- **Volatile acidity** negatively impacts quality (-0.39)  
- Achieved **R²: 0.525** using Random Forest  

## 🚀 Quick Start  
```bash
git clone https://github.com/MuhammadHassan667/wine-quality-prediction.git
pip install -r requirements.txt
jupyter notebook wine_quality.ipynb

├── assets/          # Visualizations (heatmaps, plots)
├── models/          # Trained model (wine_quality_model.pkl)
├── wine_quality.ipynb      # Complete analysis notebook
├── requirements.txt # Python dependencies
└── feature_names.json # Model features

