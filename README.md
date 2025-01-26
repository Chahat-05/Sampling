# README: Sampling Techniques and Model Evaluation  
## Chahat Verma    
## 102203637 
## C35
## Objective  
To sample an imbalanced dataset using various techniques and evaluate the performance of five machine learning models on each sample. The goal is to identify the best sampling technique for each model and the overall best-performing model.  

## Steps  

1. **Dataset Exploration**  
   - The dataset (`Creditcard_data.csv`) was loaded, checked for null values, and found to be imbalanced.  
   - Class imbalance was addressed using **RandomOverSampler**.  

2. **Sampling Techniques**  
   - **Simple Random Sampling**: Random selection.  
   - **Bootstrap Sampling**: Sampling with replacement.  
   - **Stratified Sampling**: Maintained class proportions.  
   - **Systematic Sampling**: Selected every kth element.  
   - **Cluster Sampling**: Sampled specific clusters of data.  

3. **Models Applied**  
   - **Logistic Regression**  
   - **Decision Tree**  
   - **Random Forest**  
   - **Naive Bayes**  
   - **Support Vector Machine (SVM)**  

4. **Performance Evaluation**  
   - Each model was trained and tested on all five sampled datasets.  
   - Accuracy was recorded for comparison in a results table.  

5. **Key Insights**  
   - **Random Forest** consistently achieved 100% accuracy across all sampling techniques.  
   - Best sampling technique for each model was identified, e.g., `Cluster` for **Decision Tree**, `Simple-Random` for **Naive Bayes**.  

## Conclusion  
- **Random Forest** is the best-performing model overall.  
- Sampling techniques impact model performance differently.  

