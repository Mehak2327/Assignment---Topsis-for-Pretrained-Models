# Applying TOPSIS to Select the Best Pre-trained Model for Text Classification

## 1. Introduction
Selecting an appropriate pre-trained model is an important step in building effective Natural Language Processing (NLP) systems. Different models vary in terms of accuracy, efficiency, and resource requirements. This project applies the Technique for Order Preference by Similarity to Ideal Solution (TOPSIS), a multi-criteria decision-making method, to identify the best pre-trained model for text classification based on multiple evaluation metrics.

---

## 2. Objective
To apply the TOPSIS method for selecting the best pre-trained model for text classification by considering both performance and computational efficiency.

---

## 3. Models Considered
The following popular pre-trained transformer-based models are evaluated:

- BERT-base  
- RoBERTa-base  
- DistilBERT  
- ALBERT  
- XLNet  

---

## 4. Evaluation Criteria
Four evaluation criteria are used:

| Criterion | Type |
|---------|------|
| Accuracy | Benefit |
| F1-Score | Benefit |
| Inference Time (seconds) | Cost |
| Model Size (MB) | Cost |

- Benefit criteria: Higher value is better  
- Cost criteria: Lower value is better  

---

## 5. Methodology
1. Constructed a decision matrix using evaluation metrics for each model.  
2. Normalized the decision matrix.  
3. Assigned weights to each criterion based on importance.  
4. Computed the weighted normalized matrix.  
5. Determined the ideal best and ideal worst solutions.  
6. Calculated separation measures from ideal best and worst.  
7. Computed TOPSIS scores and ranked all models.  

---

## 6. Tools & Technologies
- Python  
- NumPy  
- Pandas  
- Matplotlib  
- Google Colab  

---

## 7. Results
The TOPSIS ranking table and visualization are included in the notebook.  
The model with the highest TOPSIS score is selected as the best pre-trained model for text classification.

**Final Result:**  
RoBERTa-base achieves the highest TOPSIS score and is selected as the best model considering both performance and efficiency.

---

## 8. How to Run the Project
1. Open the notebook in Google Colab.  
2. Run all cells sequentially.  
3. View the ranking table and bar chart generated at the end.  

---

## 9. Conclusion
This project demonstrates how TOPSIS can be effectively applied for multi-criteria decision making in machine learning. It provides an objective way to compare multiple pre-trained NLP models and select the most suitable one for a specific task.

---

## 10. Author
Mehak  
Roll Number: 102303792
