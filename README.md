

# F1 Driver Aggression Predictor(2018-2024)

##Overview
This project analyzes F1 pit stop strategies and driver aggression using real race data from 2018 to 2024.
It includes:
- A large dataset of pit stops, tire compounds, weather, and performance metrics.
- A Colab Notebook (`F1Aggipynb.ipynb`) with:
- Data cleaning (including encoding fixes and corrupt/missing data fixes)
- Feature engineering (aggression score, lap variation, etc.)
- Custom Transformer architecture(inspired from the Tabtransformer) to predict driver aggression rates during races
- SHAP explainability for model insights
## Files
f1_pitstops_2018_2024.csv - Raw dataset with 100+ races, weather, lap times, stints
Cleaned_pitstops.csv - Cleaned and pre-processed dataset 
F1Agg.ipynb - Full analysis, modeling, training, testing and visualization notebook

## Key Features
- Fixes corrupted values in the dataset
- Model engineered for Driver Aggression Score prediction
- Predicts using a trained custom transformer architecture
- Uses SHAP values, various metrics and scores to explain model predictions
## How to Run
1. Clone he repo:
```bash
git clone https://github.com/Shashank7490/F1DriverAggressionPredictor.git
2. Open F1Aggipynb.ipynb in Colab/JupyterLab/VSCode
3. Run all cells
*Requires: pandas, numpy, scikit-learn, tensorflow, shap, matplotlib

Model Performance:
Trained on 2018-2023 real race data
Tested on 2024 real race data 
The following benchmarks were acheived: Test Loss (MSE): 2.7204, Test MAE: 0.7897,  R2 Score: 0.9979247654120625

Made with a passion for Deep Learning and Formula 1
