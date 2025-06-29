# 🛒 Purchase Intention Prediction

This repository contains an end-to-end machine learning project to predict whether an online shopper will complete a purchase, using behavioral session data. Multiple classification models were evaluated to determine the best performing algorithm.

---

## 📦 Dataset Overview

- **Source**: [UCI Machine Learning Repository](https://archive.ics.uci.edu/dataset/468)
- **Dataset**: Online Shoppers Purchasing Intention
- **Rows**: 12,330 sessions  
- **Target**: `Revenue` (True if purchase completed, False otherwise)

---

## 🎯 Project Goals

- Preprocess and analyze e-commerce visitor data
- Apply multiple ML classifiers to predict purchase intention
- Compare performance with and without cross-validation
- Identify key features that influence purchasing behavior

---

## 📁 Project Structure

```bash
Purchase-Intention-Prediction/
├── Final/
│   ├── K-Fold Validation/
│   │   ├── Copy of CatBoost.ipynb
│   │   ├── Copy of LightGBM.ipynb
│   │   ├── Copy of XGBoost.ipynb
├── Normal/
│   ├── AdaBoost - KFold.ipynb
│   ├── CatBoost - KFold.ipynb
│   ├── LightGBM - KFold.ipynb
│   └── Gradient Boosting.ipynb
├── CNN.ipynb
├── AdaBoostClassifier.ipynb
├── CatBoost.ipynb
├── Light_Gradient_Boosting_Machine.ipynb
├── Random Forest.ipynb
├── XGBoost.ipynb
├── LICENSE
├── README.md
