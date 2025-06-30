# Conformal Predictors for Transfer Learning

A Python implementation of Conformal Prediction algorithms using KNN-1 nearest neighbor for transfer learning scenarios. This project demonstrates the effectiveness of conformal prediction methods in handling data distribution shifts and varying noise levels.

## 🎯 Overview

Conformal Prediction is a framework that provides reliable confidence measures for machine learning predictions. This implementation focuses on:

- **Two Conformal Prediction Methods**: 
    Method 1: Nearest Neighbors to Different Class
    Method 2: Nearest Neighbors to Different/Same Class Ratio
- **Transfer Learning Evaluation**: Testing algorithm performance under distribution shifts
- **Noise Robustness Analysis**: Assessing performance across varying noise levels
- **Artificial Dataset Generation**: Creating controlled experimental environments

## 🚀 Key Features

- **Conformal Prediction Implementation**: Two distinct conformity measures for binary classification
- **Artificial Data Generation**: Controlled dataset creation with configurable noise levels
- **Performance Metrics**: Comprehensive evaluation including accuracy, validity, and efficiency
- **Transfer Learning Simulation**: Testing robustness to data distribution changes
- **Visualization**: Data distribution plots and performance analysis
- **Color-coded Results**: Easy-to-interpret performance tables with visual indicators

## 📊 Results Summary

The implementation demonstrates:
- **High Accuracy**: Both methods achieve >95% accuracy on test datasets
- **Good Validity**: Conformal prediction validity measures around 0.55-0.59
- **Reasonable Efficiency**: Efficiency scores between 0.63-0.75
- **Noise Robustness**: Performance analysis across different noise levels (1-9)
- **Transfer Learning Capability**: Effective handling of distribution shifts

## 🛠️ Installation

### Prerequisites
- Python 3.7+
- Required packages listed in `requirements.txt`

### Setup
```bash
# Clone the repository
git clone https://github.com/sourabhmarne777/python-conformal-prediction-for-transfer-learning
cd conformal-predictors-transfer-learning

# Install dependencies
pip install -r requirements.txt

# Run the Jupyter notebook
jupyter notebook "Conformal Predictors.ipynb"
```

## 📋 Requirements

```
numpy>=1.19.0
matplotlib>=3.3.0
termcolor>=1.1.0
tabulate>=0.8.7
jupyter>=1.0.0
```

## 📊 Performance Analysis

The implementation includes comprehensive performance analysis:

- **Seed Variation Analysis**: Testing across multiple random seeds (1-9)
- **Noise Level Analysis**: Evaluating robustness to increasing noise (1-9)
- **Color-coded Tables**: Visual performance indicators
  - 🟢 Green: Good performance
  - 🟡 Yellow: Moderate performance  
  - 🔴 Red: Poor performance

## 🔍 Key Findings

1. **Both methods achieve similar accuracy** (~95%) on standard test sets
2. **Method 2 shows slightly better validity** in most scenarios
3. **Method 1 demonstrates better efficiency** (lower p-value sums)
4. **Performance degrades gracefully** with increasing noise levels
5. **Conformal prediction provides reliable confidence measures** for transfer learning

## 📁 Project Structure

```
conformal-predictors-transfer-learning/
├── Conformal Predictors.ipynb    # Main implementation notebook
├── README.md                     # Project documentation
├── LICENSE                       # MIT License
├── requirements.txt              # Python dependencies
├── .gitignore                   # Git ignore rules
```



## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.


⭐ If you find this project useful, please consider giving it a star!
