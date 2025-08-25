# 📰 Fake-News-Classifier-NLP-for-Truth-Detection

## Overview
This project simulates working as a data scientist for a social media company concerned about the growing spread of fake news on its platform.  
The goal is to investigate how fake news can be recognized and build a method to classify news articles as **Fake** or **Factual** using Natural Language Processing (NLP) techniques.  

## Project Workflow
1. **Data Exploration & Cleaning**  
   - Handle raw text data and remove noise (special characters, metadata, etc.)  
   - Create a cleaned text column for further analysis  

2. **Natural Language Processing (NLP)**  
   - Tokenization, POS tagging, and Named Entity Recognition (NER) with spaCy  
   - Visualization of top entities and patterns in Fake vs. Factual news  

3. **Feature Engineering**  
   - Bag of Words representation  
   - Optionally extend to TF-IDF for richer features  

4. **Model Training & Evaluation**  
   - Logistic Regression for classification  
   - Evaluation with accuracy, precision, recall, and F1-score  
   - Achieved ~82% accuracy on the test set  

5. **Visualization & Communication**  
   - Charts and plots for dataset insights and model results  
   - Clear reporting of findings for stakeholders  

## Results
- **Accuracy:** ~82% on test data  
- Balanced performance across Fake and Factual news  
- Fake news slightly easier to detect with higher precision  

## Tech Stack
- **Python**  
- **spaCy** (NLP processing)  
- **scikit-learn** (modeling & evaluation)  
- **pandas, matplotlib, seaborn** (data handling & visualization)  

## Key Takeaways
This project showcases:  
- How to preprocess and analyze text data  
- Applying NLP for fake news detection  
- Building a machine learning classifier for real-world problems  
- Communicating insights effectively through visuals and reports  

---
