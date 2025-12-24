# Brain Tumor Detection Using Feature-Based Machine Learning

## Project Overview
This project focuses on detecting brain tumors from MRI images using
feature-based machine learning techniques. The aim is to assist in
early diagnosis by classifying MRI images as tumor or non-tumor.

## Objectives
- Preprocess brain MRI images
- Extract meaningful features from images
- Train machine learning classifiers
- Evaluate model performance using accuracy and other metrics

## Methodology
1. Data Collection (MRI Images)
2. Image Preprocessing
   - Resizing
   - Noise removal
   - Normalization
3. Feature Extraction
   - HOG (Histogram of Oriented Gradients)
   - GLCM (Gray Level Co-occurrence Matrix)
4. Classification Algorithms
   - Logistic Regression
   - Random Forest
   - Support Vector Machine (SVM)
5. Model Evaluation
   - Accuracy
   - Precision
   - Recall
   - F1-score

## Technologies Used
- Python
- Jupyter Notebook
- OpenCV
- Scikit-learn
- NumPy
- Pandas
- Matplotlib
- seaborn

## 📁 Project Structure

```
Brain-Tumor-Detection-ML/
│
├── Project.ipynb
├── README.md
├── requirements.txt
├── dataset/
│   └── README.txt
└── outputs/
    ├── accuracy.png
    └── confusion_matrix.png
    
```
*Note: dataset folder contains a placeholder README.txt. Users should download the actual dataset from Kaggle.*


## How to Run the Project
1. Install required libraries:
   pip install numpy, pandas, opencv-python, scikit-learn, matplotlib, seaborn

2. Open Jupyter Notebook:
   jupyter notebook

3. Run the file:
   Project.ipynb

## Results
The machine learning models were able to classify brain MRI images
with good accuracy. Among the classifiers, SVM and Random Forest
performed better.

## Conclusion
Feature-based machine learning techniques can effectively classify
brain tumors from MRI images and can be used as a supportive tool
in medical diagnosis.

## Future Work
- Use deep learning models like CNN
- Increase dataset size
- Improve accuracy with feature selection



