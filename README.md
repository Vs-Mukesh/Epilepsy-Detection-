# Epilepsy-Detection-

Real-Time Patient Condition Prediction and Decision Output
Figure 4.7 illustrates the real-time testing of the proposed deep learning model using a new patient input sample. The example input consists of multiple physiological parameters, including EEG band power, EEG entropy, EEG spike rate, heart rate, heart rate variability (HRV), RR interval, respiration rate, and SpO2 level. These parameters are representative of real-time biosignal features obtained from the embedded sensing system.
 
<img width="468" height="640" alt="image" src="https://github.com/user-attachments/assets/0ddb5e8d-4877-48dd-8b51-4c9aa1f8d49a" />

# Classification Performance and Evaluation Results

	Figure presents the classification report obtained from evaluating the trained CNN-based model on the test dataset. The performance is analyzed using standard metrics including precision, recall, F1-score, and overall accuracy. These metrics provide a comprehensive assessment of the model’s ability to correctly classify different physiological signal classes related to epileptic and non-epileptic conditions.
The results show that the proposed model achieves an overall classification accuracy of 95%, indicating strong predictive capability. For Class 0, the model achieves a precision, recall, and F1-score of 0.91, demonstrating reliable classification of this category. Class 1 achieves a precision of 0.91, recall of 0.93, and F1-score of 0.92, indicating balanced performance in identifying samples belonging to this class.
For Class 2, the model achieves higher performance with a precision of 0.97, recall of 0.95, and F1-score of 0.96, reflecting excellent discrimination capability for this physiological condition. Similarly, Class 3 records strong performance with a precision of 0.97, recall of 0.99, and F1-score of 0.99, indicating highly accurate classification.
The macro-average and weighted-average values for precision, recall, and F1-score are all reported as 0.94, further confirming consistent performance across all four classes. The balanced support values indicate that the dataset is well distributed among classes, which contributes to stable and unbiased evaluation results. 
<img width="468" height="585" alt="image" src="https://github.com/user-attachments/assets/557b070b-10d7-4d62-a1d6-4c096934da6e" />
