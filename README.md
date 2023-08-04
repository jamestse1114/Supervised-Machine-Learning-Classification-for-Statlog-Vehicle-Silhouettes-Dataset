# Supervised-Machine-Learning-Classification-for-Statlog-Vehicle-Silhouettes-Dataset

This repository contains the code and resources for a project focused on supervised machine learning tasks using the Statlog (Vehicle Silhouettes) dataset. This dataset includes real-world images of various vehicles, and the objective is to categorize these vehicles based on their silhouettes.

## Project Description

The project applies several machine-learning techniques to classify the vehicles in the dataset. These techniques include Decision Trees, Instance-based Learning, Neural Networks, Bayesian Learning, and Model Ensembles. The performance of these models is measured using accuracy and precision metrics.

## Dataset

The dataset used in this project comes from the Turing Institute, Glasgow, Scotland, and was initially gathered in 1986-87. It consists of 946 examples of four types of vehicles: Opel, Saab, Bus, and Van. Each vehicle is described by 18 attributes, extracted from the silhouettes by the Hierarchical Image Processing System (HIPS) extension BINATTS.

The features include a combination of classical moments-based measures such as scaled variance, skewness, and kurtosis about the major/minor axes, and heuristic measures such as hollows, circularity, rectangularity, and compactness.

## Methodology

The approach to this project involves:

1. **Data Cleaning and Preprocessing:** This step includes removing any empty values and encoding any categorical factors.
2. **Feature Selection:** A subset of the most significant features for classification is chosen using statistical techniques like principal component analysis, feature significance ranking, and correlation analysis.
3. **Visual Analysis:** The images of the vehicle silhouettes in the dataset are manually inspected to identify any visible patterns.
4. **Supervised learning:** The machine learning approaches are utilized to test and classify the dataset, and metrics are compared to evaluate the effectiveness of the methods.

## Dependencies

This project uses the following Python libraries:

1. numpy
2. pandas
3. matplotlib
4. scikit-learn
5. Keras
6. seaborn

You can install these libraries using pip.

## Contributors

James Yik-Kien Tse
Jiayun Kang
Gagan Kumar B. A.
Atsumi Hirose
Qianxi Feng
