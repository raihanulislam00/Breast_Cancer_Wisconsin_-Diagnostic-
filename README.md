# Breast Cancer Wisconsin Diagnostic

## Project Overview

This project implements machine learning techniques to classify breast cancer tumors as either malignant or benign using the Wisconsin Breast Cancer Diagnostic dataset. Using advanced data analysis and various ML models, we achieve high accuracy in cancer detection.

## Features

- Comprehensive data preprocessing and exploration
- Implementation of multiple machine learning models:
  - Logistic Regression
  - Support Vector Machine (SVM)
  - Random Forest Classifier
  - XGBoost
- Detailed model evaluation and comparison
- Feature importance analysis
- Interactive visualizations of results

## Dataset Information

The dataset contains features computed from digitized images of fine needle aspirates (FNA) of breast masses. Key characteristics include:

- 569 instances
- 30 numeric features
- Binary classification: Malignant (1) or Benign (0)
- No missing values

Features are computed from cell nucleus characteristics:
- Radius
- Texture
- Perimeter
- Area
- Smoothness
- Compactness
- Concavity
- Concave points
- Symmetry
- Fractal dimension

## Requirements

```
numpy==1.21.5
pandas==1.4.4
matplotlib==3.5.2
seaborn==0.11.2
scikit-learn==1.0.2
xgboost==1.5.0
```

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/raihanulislam00/Breast_Cancer_Wisconsin_Diagnostic.git
   cd Breast_Cancer_Wisconsin_Diagnostic
   ```

2. Install required packages:
   ```bash
   pip install -r requirements.txt
   ```

## Usage

1. Open the Jupyter notebook:
   ```bash
   jupyter notebook Breast_Cancer_Wisconsin_Diagnostic.ipynb
   ```

2. Run the cells sequentially to:
   - Load and preprocess the data
   - Train various models
   - Evaluate model performance
   - Visualize results

## Project Structure

```
├── Breast_Cancer_Wisconsin_Diagnostic.ipynb
├── README.md
├── requirements.txt
└── data/
    └── breast_cancer_data.csv
```

## Model Performance

Our implementation achieves the following accuracy scores:

- Logistic Regression: 97%
- Support Vector Machine: 98%
- Random Forest: 98%
- XGBoost: 98%

## Visualizations

The project includes various visualizations:
- Correlation heatmaps
- Feature importance plots
- ROC curves
- Confusion matrices
- Distribution plots of key features

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request. For major changes, please open an issue first to discuss what you would like to change.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## Author

- Raihanul Islam

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments

- Wisconsin Diagnostic Breast Cancer dataset from UCI Machine Learning Repository
- Scikit-learn documentation and community
- All contributors and maintainers

## References

- [UCI Machine Learning Repository: Breast Cancer Wisconsin (Diagnostic) Data Set](https://archive.ics.uci.edu/ml/datasets/Breast+Cancer+Wisconsin+%28Diagnostic%29)
- Original dataset creators: Dr. William H. Wolberg, W. Nick Street, Olvi L. Mangasarian
