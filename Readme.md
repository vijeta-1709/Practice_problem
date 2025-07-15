# 🍷 Wine Classification using Neural Networks (Keras & TensorFlow)

This project demonstrates the use of a simple neural network model built using **TensorFlow/Keras** to classify wine samples into three different classes using the classic `load_wine` dataset from **scikit-learn**.

---

##Dataset Overview

The **Wine** dataset is a classic multi-class classification dataset. It contains the results of a chemical analysis of wines grown in the same region in Italy but derived from three different cultivars.

- **Source**: UCI Machine Learning Repository
- **Samples**: 178
- **Features**: 13 numerical features (all continuous)
- **Classes**: 3 wine cultivars (`0`, `1`, `2`)

### Features

- Alcohol  
- Malic acid  
- Ash  
- Alcalinity of ash  
- Magnesium  
- Total phenols  
- Flavanoids  
- Nonflavanoid phenols  
- Proanthocyanins  
- Color intensity  
- Hue  
- OD280/OD315 of diluted wines  
- Proline

---

## Setup

### Prerequisites

Install required Python libraries:

```bash
pip install numpy pandas scikit-learn tensorflow matplotlib
