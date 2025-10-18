# Celestial Object Detection  
**Author:** Mohammad Shahnewaz Morshed  
**Date:** October 18, 2024  

---

### Problem Statement  
Accurately identifying celestial objects such as stars, galaxies, and quasars is a key step in understanding the universe. Sky survey data often contain millions of observations with overlapping features, varying brightness, and background noise, which make simple rule-based or visual classification unreliable.  

A statistical approach helps overcome these challenges by using measurable patterns in the data to separate true celestial objects from background or noise. By applying data-driven, transparent, and interpretable methods, it becomes possible to detect and classify these objects with higher accuracy and consistency.

---

### Objective  
The objective of this project is to build a clear, statistical framework for identifying celestial objects from survey data. The notebook shows how basic exploratory analysis, feature scaling, and classical machine learning models; such as k-Nearest Neighbors, Decision Trees, and Random Forests, used to classify stars, galaxies, and quasars.  


---

### Methodology  
The dataset **Skyserver250k.csv** contains spectroscopic and photometric information of celestial objects labeled as *Star*, *Galaxy*, or *Quasar*. The workflow begins with basic data cleaning and inspection to check for missing values and remove non-informative fields. All features are standardized so that differences in scale do not bias the results.  

Exploratory analysis is then used to understand feature relationships and identify patterns in brightness, wavelength, and spectral intensity. After this, models are trained and compared using standard evaluation metrics such as accuracy, precision, recall, and F1-score.  

---

### Python Notebook  
**[Celestial_Object_Detection.ipynb](https://github.com/ShahnewazMorshed/Image-based-Celestial-Object-Detection/blob/main/Celestial_Object_Detection.ipynb)** demonstrates the full workflow from data import and cleaning to feature transformation, model training, and result visualization. It shows how statistical learning methods can be applied to classify astronomical objects using simple, explainable, and reproducible steps.

---




