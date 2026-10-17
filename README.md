# TESS Exoplanet Classification: Addressing Data Leakage in Machine Learning


## Abstract
This project investigates data leakage in exoplanet machine learning classification using TESS data. We demonstrate that random train-test splits inflate accuracy estimates, and propose star-grouped cross-validation as a solution.


## Key Results
- Star-grouped validation prevents data leakage from same-star transits
- Deep residual MLP with attention achieves 70% accuracy (beats Random Forest by 1%)
- Identified 43 new exoplanet candidates for follow-up
- SMOTE oversampling reduces accuracy by 9.7% (removed from final pipeline)


## Dataset
TESS Exoplanet Dataset: 7,201 samples, 10 features, 6 classes
Source: Kaggle (mithunmeenakshis/tess-exoplanet-dataset)


## How to Reproduce
1. Clone this repository
2. Install dependencies: `pip install -r requirements.txt`
3. Download TESS dataset from Kaggle
4. Open `notebook.ipynb` and run all cells


## Author
Sai Rakesh Nagaram & Kavin Gnanaprakash
High Tech High School & County Prep
ISEF 2027


## Citation
Nagaram & Gnanaprakash (2026). TESS Exoplanet Classification: Addressing Data Leakage in Machine Learning. ISEF 2027.

