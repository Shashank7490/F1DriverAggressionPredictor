{\rtf1\ansi\ansicpg1252\cocoartf2865
\cocoatextscaling0\cocoaplatform0{\fonttbl\f0\froman\fcharset0 Times-Roman;}
{\colortbl;\red255\green255\blue255;\red0\green0\blue0;}
{\*\expandedcolortbl;;\cssrgb\c0\c0\c0;}
{\*\listtable{\list\listtemplateid1\listhybrid{\listlevel\levelnfc23\levelnfcn23\leveljc0\leveljcn0\levelfollow0\levelstartat1\levelspace360\levelindent0{\*\levelmarker \{disc\}}{\leveltext\leveltemplateid1\'01\uc0\u8226 ;}{\levelnumbers;}\fi-360\li720\lin720 }{\listname ;}\listid1}}
{\*\listoverridetable{\listoverride\listid1\listoverridecount0\ls1}}
\paperw11900\paperh16840\margl1440\margr1440\vieww11520\viewh8400\viewkind0
\pard\tx720\tx1440\tx2160\tx2880\tx3600\tx4320\tx5040\tx5760\tx6480\tx7200\tx7920\tx8640\pardirnatural\partightenfactor0

\f0\fs24 \cf0 # F1 Driver Aggression Predictor(2018-2024)\
\
##Overview\
This \expnd0\expndtw0\kerning0
\outl0\strokewidth0 \strokec2 project analyzes F1 pit stop strategies and driver aggression using real race data from 2018 to 2024.\
\pard\pardeftab720\sa240\partightenfactor0
\cf0 \strokec2 It includes:\
- A large dataset of pit stops, tire compounds, weather, and performance metrics.\
- A Colab Notebook (`F1Aggipynb.ipynb`) with:\
- Data cleaning (including encoding fixes and corrupt/missing data fixes)\
- Feature engineering (aggression score, lap variation, etc.)\
- Custom Transformer architecture(inspired from the Tabtransformer) to predict driver aggression rates during races\
- SHAP explainability for model insights\
## Files\
f1_pitstops_2018_2024.csv - Raw dataset with 100+ races, weather, lap times, stints\
Cleaned_pitstops.csv - Cleaned and pre-processed dataset \
\pard\pardeftab720\sa240\partightenfactor0
\cf0 F1Aggipynb.ipynb - Full analysis, modeling, training, testing and visualization notebook\
\
## Key Features\
- Fixes corrupted values in the dataset\
- Model engineered for Driver Aggression Score prediction\
- Predicts using a trained custom transformer architecture\
- Uses SHAP values, various metrics and scores to explain model predictions\
## How to Run\
1. Clone he repo:\
```bash\
git clone https://github.com/Shashank7490/F1DriverAggressionPredictor.git\
2. Open F1Aggipynb.ipynb in Colab/JupyterLab/VSCode\
3. Run all cells\
*Requires: pandas, numpy, scikit-learn, tensorflow, shap, matplotlib\
\
Model Performance:\
\pard\tx220\tx720\pardeftab720\li720\fi-720\sa240\partightenfactor0
\ls1\ilvl0\cf0 \kerning1\expnd0\expndtw0 \outl0\strokewidth0 {\listtext	\uc0\u8226 	}Trained on 2018-2023 real race data\
{\listtext	\uc0\u8226 	}Tested on 2024 real race data \
{\listtext	\uc0\u8226 	}The following benchmarks were acheived: Test Loss (MSE): 2.7204, Test MAE: 0.7897,  R\'b2 Score: 0.9979247654120625\expnd0\expndtw0\kerning0
\outl0\strokewidth0 \strokec2              \
\pard\tx720\pardeftab720\sa240\partightenfactor0
\cf0 Made with a passion for Deep Learning and Formula 1 \
\pard\pardeftab720\sa240\partightenfactor0
\cf0 \
\pard\pardeftab720\sa240\partightenfactor0
\cf0 \
}