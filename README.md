# LS Machine Learning

This repository contains machine learning assignments and projects completed as part of the IIT Bombay Learner's Space coursework.  
Among these, the main final project is a real-time **Face Verification System** using Siamese Neural Networks.

---

## Projects Included

### Facial Verification System
A real-time face verification pipeline built with a Siamese Neural Network. The system verifies whether a face captured from a webcam matches stored reference images.

**Key features:**
- Custom dataset with anchor, positive, and negative face images  
- Data augmentation to handle lighting and pose variations  
- CNN-based embedding model for feature extraction  
- L1 distance layer to compare face embeddings  
- Precision and recall used for evaluation  
- Live webcam integration using OpenCV  
- Similarity scoring and threshold-based verification

The model learns to measure similarity between two faces and outputs a match score. A threshold is used to decide if the current webcam face is verified against stored images.

---

### Other Learner Assignments
These include typical machine learning tasks from the Learner Space course:
- Linear Regression
- Logistic Regression
- Python basics and modules


