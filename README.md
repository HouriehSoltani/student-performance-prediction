# Student Performance Prediction

A comprehensive machine learning project that predicts student academic performance using multiple linear regression. This project analyzes factors affecting student performance and builds a highly accurate predictive model.

## Overview

This project uses a synthetic dataset of 10,000 students to predict a **Performance Index** (10-100) based on various factors including study hours, sleep, previous scores, extracurricular activities, and practice questions.

## Key Results

- **Model Accuracy**: 98.9% R² score (explains 98.9% of variance)
- **Prediction Error**: ±1.61 points average error
- **Most Important Factor**: Study hours (+2.85 points per hour)

## Features Analyzed

1. **Hours Studied** - Most powerful predictor
2. **Previous Scores** - Strong indicator of future performance
3. **Extracurricular Activities** - Provides meaningful boost
4. **Sleep Hours** - Moderate positive effect
5. **Practice Papers** - Smaller but positive impact

## Repository Structure

```
student-performance-prediction/
├── student-performance-prediction.ipynb  # Main analysis notebook
├── README.md                             # This file
└── requirements.txt                      # Python dependencies
```

## Getting Started

### Prerequisites

- Python 3.8+
- Jupyter Notebook
- Required Python packages (see requirements.txt)

### Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/student-performance-prediction.git
cd student-performance-prediction
```

2. Install dependencies:
```bash
pip install -r requirements.txt
```

3. Run the notebook:
```bash
jupyter notebook student-performance-prediction.ipynb
```

## Dataset

The dataset used in this project is from Kaggle:
- **Source**: [Student Performance - Multiple Linear Regression](https://www.kaggle.com/datasets/nikhil7280/student-performance-multiple-linear-regression)
- **Size**: 10,000 students
- **Features**: 5 input variables + 1 target variable

## Methodology

1. **Data Loading & Exploration** - Understanding the dataset structure
2. **Exploratory Data Analysis** - Visualizing relationships and patterns
3. **Data Preprocessing** - Feature engineering and train/test split
4. **Model Training** - Multiple Linear Regression implementation
5. **Evaluation & Insights** - Performance analysis and interpretation

## Key Insights

- Study time is the most critical factor for academic success
- Previous academic performance strongly predicts future performance
- Extracurricular activities provide a modest but meaningful boost
- Sleep and practice have smaller but positive effects
- The model achieves exceptional accuracy with minimal prediction error

## Model Performance

| Metric | Value |
|--------|-------|
| R² Score | 98.9% |
| RMSE | 2.02 points |
| MAE | 1.61 points |

## Future Improvements

- Implement ensemble methods (Random Forest, XGBoost)
- Add more features (attendance, teacher quality, socioeconomic factors)
- Cross-validation for robust evaluation
- Feature engineering and interaction terms
- Non-linear relationship exploration

## Technologies Used

- **Python** - Programming language
- **Pandas** - Data manipulation
- **NumPy** - Numerical computing
- **Matplotlib/Seaborn** - Data visualization
- **Scikit-learn** - Machine learning
- **Jupyter Notebook** - Interactive development

## Contributing

Feel free to fork this project and submit pull requests for any improvements.

## License

This project is open source and available under the [MIT License](LICENSE).

## Contact

For questions or suggestions, please open an issue on GitHub.
