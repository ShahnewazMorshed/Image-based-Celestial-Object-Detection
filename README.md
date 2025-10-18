# Celestial Object Detection  
**Author:** Mohammad Shahnewaz Morshed  
**Date:** May 11, 2024  

---

### Problem Statement  
Accurately identifying celestial objects such as stars, galaxies, and quasars is a key step in understanding the universe. Sky survey data often contain millions of observations with overlapping features, varying brightness, and background noise, which make simple rule-based or visual classification unreliable.  

A statistical approach helps overcome these challenges by using measurable patterns in the data to separate true celestial objects from background or noise. By applying data-driven, transparent, and interpretable methods, it becomes possible to detect and classify these objects with higher accuracy and consistency.

---

### Objective  
The objective of this project is to build a clear, statistical framework for identifying celestial objects from survey data. The notebook shows how basic exploratory analysis, feature scaling, and classical machine learning models — such as k-Nearest Neighbors, Decision Trees, and Random Forests — are used to classify stars, galaxies, and quasars.  

---

### Methodology  
The dataset **Skyserver250k.csv** contains spectroscopic and photometric information of celestial objects labeled as *Star*, *Galaxy*, or *Quasar*. The analytical process follows a simple and interpretable structure:  

1. **Data Preparation** — Cleaning, screening, and removing non-informative fields to ensure quality and consistency.  
2. **Feature Standardization** — Scaling all variables to comparable ranges so that no single measurement dominates model training.  
3. **Exploratory Data Analysis (EDA)** — Understanding how different features (such as redshift, brightness, and color indices) interact across object types.  
4. **Model Development** — Applying classical statistical learning algorithms to detect patterns and separability among classes.  
5. **Model Evaluation** — Comparing models through standard performance metrics including accuracy, precision, recall, and F1-score.  

A detailed explanation of the full analytical process, including mathematical background and statistical reasoning, is available in the **[Methodology: Statistical Modeling of Celestial Object Detection (PDF)](https://github.com/ShahnewazMorshed/Image-based-Celestial-Object-Detection/blob/main/Methodology%20-%20Celestial%20Object%20Detection.pdf)** document.

---

### Python Notebook  
**[Celestial_Object_Detection.ipynb](https://github.com/ShahnewazMorshed/Image-based-Celestial-Object-Detection/blob/main/Celestial_Object_Detection.ipynb)** demonstrates the complete workflow from data import and cleaning to feature transformation, model training, and visualization. It shows how statistical learning methods can be applied to classify astronomical objects using clear, explainable, and reproducible steps.

---
