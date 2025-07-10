# 🐸 Frog Presence Prediction – EY Biodiversity Challenge

This repository contains our team’s submission for the **EY Biodiversity Challenge 2024**.  
We built a machine learning model to predict the presence of frogs in southeastern Australia using the **TerraClimate** dataset and frog occurrence records.

---

## 🌱 Project Objective

Frogs are considered important indicators of ecosystem health.  
Our goal was to build a classification model that accurately predicts frog presence, helping support:

- Biodiversity conservation planning  
- Eco-friendly land-use decisions  
- Fungal disease (Bd) surveillance  
- Governmental environmental zoning and ESG initiatives  

---

## 🧠 Key Features

- Used frog occurrence data + climate features (tmax, ppt, soil, etc.)
- Applied **RandomOverSampler** for class balancing
- Removed outliers using **Z-score** method
- Trained and fine-tuned **XGBoost**, **LightGBM**, and **ExtraTreesClassifier**
- Final model: `ExtraTreesClassifier` with **83.10% test accuracy**

---

## 💡 Business Applications

- Climate-resilient **conservation planning**
- **Bd fungal infection** detection support
- Site selection for **sustainable agriculture**
- Biodiversity zoning for **governmental policy-making**

---

## Team Members

- Jayasree Lakshmi Narayanan  
- Haeun Kim 
- Samarth Verma  
