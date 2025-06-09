# 🧬 Mice Classification Based on Protein Expression Levels
  
**Project Type:** First Major Project  
**Topic:** Machine Learning for Biological Data Analysis

## 📌 Overview

This project uses **machine learning** techniques to classify different types of mice based on their **protein expression levels** in the cerebral cortex. The dataset includes data from both control and Down syndrome mice subjected to context fear conditioning.

## 🎯 Problem Statement

The goal is to identify proteins that are discriminant between different classes of mice and classify them into **eight distinct classes** based on **genotype, behavior, and treatment**.

## 🧠 Objectives

- **Understand the Data:** Explore the dataset and identify inconsistencies or missing values.
- **Prepare the Data:** Clean, normalize, and encode the dataset for modeling.
- **Analyze Patterns:** Use visualization and statistics to identify trends in protein data.
- **Build and Compare Models:** Train multiple models and compare their performance.
- **Evaluate and Interpret:** Use metrics (accuracy, confusion matrix) and identify key features.

## 📊 Dataset Information

- **Instances:** 1080 (Each mouse has 15 measurements per protein)
- **Features:** 80 (77 protein expression values + 3 metadata columns: Mouse ID, Genotype, Treatment)
- **Classes:** 8 (Combinations of genotype, treatment, and behavior)

## 🔄 Steps Involved

1. **Data Loading & Cleaning:** Handle nulls and inconsistencies.
2. **EDA (Exploratory Data Analysis):** Use visualizations like histograms and pair plots.
3. **Preprocessing:** Normalize values, encode labels.
4. **Feature Selection:** Reduce dimensionality using statistical techniques.
5. **Model Building:** Train models like Random Forest, SVM, etc.
6. **Model Evaluation:** Evaluate using accuracy, confusion matrix, cross-validation.
7. **Interpret Results:** Identify influential protein features.
8. **Conclude Findings:** Discuss biological implications.

   ## 📈 Visualizations

### Histogram
- Shows distribution of protein values.
- Highlights skewness and helps in deciding normalization.

### Box Plot
- Shows median, variability, and outliers.
- Identifies potential biological anomalies.

### Pair Plot
- Displays scatter plots between protein pairs.
- Useful for observing clustering and separation of classes.

## ⚠️ Challenges Faced

- **High Dimensionality:** Over 70 protein features made model tuning complex.
- **Class Imbalance:** Some classes had fewer examples.
- **Missing & Noisy Data:** Required careful imputation and filtering.
- **Overlapping Classes:** Made classification difficult.
- **Model Tuning:** Required iterative experimentation.

## 📚 Learnings

- Gained hands-on experience in **biological data preprocessing**.
- Understood pros/cons of different **classification algorithms**.
- Realized the importance of **data visualization** in biology.
- Learned that machine learning can provide meaningful **insights into neuroscience**.

  ## ✅ Conclusion

This project successfully demonstrates how machine learning can classify mice based on brain protein expression. It also highlights the potential of data science in supporting research in **neuroscience and drug 

## 🙏 Acknowledgment

Thank you for reviewing this project!
