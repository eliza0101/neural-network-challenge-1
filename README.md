# neural-network-challenge-1
**Module 18 Challenge**


**Overview**
This project uses machine learning to predict the likelihood of a student repaying their loan based on various factors. It uses a neural network model built with TensorFlow and Keras to analyze student data and make predictions.

**Dataset**
https://static.bc-edx.com/ai/ail-v-1-0/m18/lms/datasets/student-loans.csv

**Project Structure**


**Key Findings**

Model Performance:
   - Overall Accuracy: 75%
   - Class 0 (Likely to default):
     - Precision: 0.70
     - Recall: 0.81
     - F1-score: 0.75
   - Class 1 (Likely to repay):
     - Precision: 0.80
     - Recall: 0.69
     - F1-score: 0.74

The balanced performance shows that the model could be useful for initial screening in loan approval processes. But, given the 25% error rate, it should not be the sole factor in decision-making.