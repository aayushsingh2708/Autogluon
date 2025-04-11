# 📊 Laptop Price Prediction & Income Classification (AutoGluon + EDA)

## 📚 Table of Contents
- [Introduction](#introduction)
- [Dataset Information](#dataset-information)
  - [Laptop Price Dataset](#laptop-price-dataset)
  - [Adult Income Dataset](#adult-income-dataset)
- [Installation & Usage](#installation--usage)

## Introduction
This repository contains Jupyter Notebooks showcasing **machine learning modeling and exploratory data analysis (EDA)** on two different problems:

1. **Laptop Price Prediction (Regression)**: Predicts the selling price of laptops based on features like brand, processor, storage, GPU, and more.
2. **Income Classification (Classification)**: Predicts whether an individual earns more than \$50K per year based on demographic and work-related features.

The AutoGluon library is used for automated machine learning (AutoML), significantly reducing the manual tuning workload.

---

## Dataset Information

### Laptop Price Dataset
- Features include laptop brand, processor type, storage, screen size, and graphics card.
- **Target Variable**: `Price` (continuous variable for regression).
- Dataset file: [`laptop_prices.csv`](data/laptop_prices.csv)

### Adult Income Dataset
- Commonly used benchmark dataset for classification tasks.
- Features like age, education, occupation, race, and hours-per-week are used.
- **Target Variable**: `Income` (`<=50K` or `>50K`)
- Dataset file: [`adult.csv`](data/adult.csv)

---

## Installation & Usage

### 1. Clone the Repository
```bash
git clone https://github.com/aayushsingh2708/Autogluon.git
cd Autogluon
