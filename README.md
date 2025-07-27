# 🌾 Intercrop Recommendation System

A hybrid crop recommendation system that combines **machine learning** and **rule-based logic** to help farmers choose optimal primary and inter crops based on environmental and soil parameters.

---

## 📌 Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Tech Stack](#tech-stack)
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Results](#results)
- [Future Work](#future-work)
- [Contributors](#contributors)

---

## ✅ Overview

This project provides an end-to-end decision support system for sustainable agriculture through:

- **Stage 1**: Predicting the best crop (`Crop-1`) using machine learning (Random Forest, SVM, KNN, etc.) based on:
  - Soil nutrients (N, P, K)
  - pH
  - Temperature
  - Humidity
  - Rainfall

- **Stage 2**: Recommending compatible intercrops (`Crop-2`) using a **rule-based engine** based on:
  - Nutrient and water compatibility
  - Root depth
  - Pest/disease overlap
  - Maturity time
  - Seasonal alignment

---

## 🚀 Features

- Supports intercropping suggestions for sustainable farming.
- Combines data-driven ML models with agricultural rules.
- Custom synthetic data generation for intercrop compatibility.
- Highly interpretable and extendable architecture.

---

## 🛠 Tech Stack

| Component        | Technology         |
|------------------|--------------------|
| Language         | Python             |
| IDE              | Jupyter Notebook   |
| ML Libraries     | `scikit-learn`, `pandas`, `numpy` |
| Visualization    | `matplotlib`, `seaborn` |
| Dataset          | [Kaggle Crop Recommendation Dataset](https://www.kaggle.com/datasets/atharvaingle/crop-recommendation-dataset) |

---

## ⚙️ Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/intercrop-recommender.git
   cd intercrop-recommender
