# Waste Image Classification using Traditional Machine Learning Techniques

## Overview
This project implements an end-to-end machine learning pipeline to classify household waste images into recyclable and non-recyclable categories. The focus is on classical machine learning using handcrafted features instead of deep learning.

## Objective
- Automate waste classification using image-based features  
- Compare performance of classical ML models  
- Analyze the impact of feature engineering  

## Approach

### Feature Extraction
- Color features: Mean RGB values  
- HOG (Histogram of Oriented Gradients) for shape and edge detection  
- LBP (Local Binary Patterns) for texture representation  
- GLCM (Gray Level Co-occurrence Matrix) for statistical texture features  

### Preprocessing
- Outlier handling using IQR capping  
- Feature scaling using StandardScaler  
- Dimensionality reduction using LDA  

### Models Used
- Logistic Regression  
- Decision Tree  
- Random Forest  

## Results
- Achieved approximately 65% accuracy across models  
- Decision Tree showed slightly better balance  
- Feature overlap observed between classes  

## Key Insights
- Texture features are more informative than color features  
- No single feature provides complete separation  
- Combining multiple features improves performance  

## Limitations
- Limited dataset (~1000 images)  
- Feature overlap reduces classification accuracy  
- Handcrafted features may not capture complex patterns  

## Future Scope
- Increase dataset size and diversity  
- Apply deep learning techniques such as CNNs  
- Develop a real-time classification system  
