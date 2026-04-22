#LW5-Activity_Comparative-Analysis-of-Pre-trained-CNN-Models-for-Custom-Image-Classification

 .[Heres the Google colab link for LW5)](https://colab.research.google.com/drive/1Q6FN4xhLjOoc6KNhE_nvY1h6YthSePLn#scrollTo=fpLDZiSsu7Xn)


GUIDE QUESTIONS

### **A. Model Performance**

**1. Which pre-trained model achieved the highest accuracy? Why?**
The model with the highest accuracy is usually the one with deeper architecture like InceptionV3 because it extracts more detailed and complex features from images.

**2. Which model had the lowest performance? What could be the reason?**
The lowest performing model is usually a simpler or lightweight model because it has limited ability to learn complex patterns from the dataset.

**3. How did loss values compare across models?**
Better-performing models have lower loss values, while weaker models usually have higher loss because their predictions are less accurate.

### **B. Evaluation Metrics**

**4. Why is accuracy not enough to evaluate a model?**
Accuracy alone is not enough because it does not show how well the model performs on each class, especially when the dataset is imbalanced.

**5. Which model had the best F1-score? What does it indicate?**
The model with the best F1-score is the one that balances precision and recall well, meaning it performs consistently across classes.

**6. How did Precision and Recall differ across models?**
Precision and recall vary depending on how each model handles false positives and false negatives.

### **C. Confusion Matrix Analysis**

**7. Which classes were frequently misclassified?**
Classes that look similar visually were often confused by the model.

**8. What patterns did you observe in the confusion matrix?**
The confusion matrix shows that misclassifications mostly happen between similar categories.

### **D. ROC and AUC**

**9. Which model had the highest AUC score?**
The model with the highest AUC is the one that best separates different classes.

**10. What does AUC tell us about model performance?**
AUC shows how well the model can distinguish between classes overall.

### **E. Explainability (Grad-CAM)**

**11. What did Grad-CAM reveal about model decision-making?**
Grad-CAM shows which parts of the image the model focused on when making predictions.

**12. Did the model focus on relevant image regions?**
In a good model, yes—it highlights the important object areas in the image.

**13. Which model produced the most meaningful heatmaps?**
The best-performing model usually produces the most accurate and meaningful heatmaps.

### **F. Model Comparison & Improvement**

**14. Which model would you recommend for deployment? Why?**
The best model with highest accuracy, F1-score, and stable results is recommended for deployment.

**15. How can you further improve your best-performing model?**
It can be improved using data augmentation, hyperparameter tuning, and fine-tuning the model.

### **G. Real-World Application**

**16. How can your model be applied in real-world scenarios?**
It can be used in healthcare, agriculture, security, and image classification systems.

**17. What are the risks of deploying an inaccurate model?**
It may lead to wrong predictions, poor decisions, and possible real-world harm.

**18. How can this system be integrated into a mobile/web app?**
It can be integrated using APIs like Flask or FastAPI and deployed in mobile apps using TensorFlow Lite.

---
