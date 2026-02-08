# SPAM_EMAIL_DETECTION]]

## Project Overview
This project demonstrates the implementation of a **Machine Learning predictive model** using **scikit-learn** to classify emails as **Spam** or **Not Spam (Ham)**.  
The project is developed as part of an **internship task** to showcase model implementation and evaluation using a Jupyter Notebook.

---

## Objective
To build a text classification model that can automatically detect spam emails using:
- TF-IDF for feature extraction
- Naive Bayes for classification

---

## Technologies & Libraries Used
- Python
- Jupyter Notebook
- pandas
- numpy
- scikit-learn

---

## Project Structure

Spam_Email_Detection/
- Spam_Email_Detection.ipynb 
- README.md # Project documentation


---

##  Dataset
A small sample dataset containing email messages labeled as:
- **Spam (1)**
- **Ham (0)**

The dataset is created manually within the notebook for simplicity and academic demonstration.

---

##  Implementation Steps
1. Import required libraries  
2. Create and load the dataset  
3. Convert labels into numeric format  
4. Split data into training and testing sets  
5. Perform feature extraction using TF-IDF  
6. Train the Naive Bayes classifier  
7. Evaluate the model using accuracy and classification report  
8. Test the model with custom email input  

---

## Model Used
**Multinomial Naive Bayes**

**Why Naive Bayes?**
- Efficient for text classification
- Works well with word frequency-based features
- Commonly used for spam detection problems

---

## Evaluation Metrics
- Accuracy Score
- Classification Report (Precision, Recall, F1-score)
- Confusion Matrix

---

##  Sample Prediction
The model can classify a custom email such as:
