# OCR Digit Classification using Machine Learning

##  Overview
This project focuses on classifying handwritten digit images (0–9) using machine learning algorithms. The data used is from Kaggle’s “Digit Recognizer” dataset, which contains grayscale images of handwritten digits in a flattened CSV format.

##  Dataset
- **Source**: [Kaggle - Digit Recognizer](https://www.kaggle.com/competitions/digit-recognizer/data)
- **Image Size**: 28x28 pixels (flattened to 784 features)
- **Classes**: Digits from 0 to 9

##  Technologies & Libraries Used
- Python (Jupyter Notebook)
- **Libraries**:
  - pandas, numpy – for data handling
  - matplotlib, seaborn – for visualization
  - scikit-learn – for ML algorithms and evaluation

##  Exploratory Data Analysis (EDA)
- Checked for missing/null values
- Visualized class distribution with bar plots
- Displayed sample digit images using matplotlib
- Normalized pixel values (0–255 scaled to 0–1)

##  Machine Learning Models Applied
The following supervised learning algorithms were used:
1. Logistic Regression
2. Random Forest Classifier
3. K-Nearest Neighbors (KNN)

Each model was trained on the training set and evaluated on the test set.

##  Results

| Model                 | Accuracy   |
|----------------------|------------|
| Logistic Regression  | ~92%       |
| Random Forest        | ~96%       |
| K-Nearest Neighbors  | ~94%       |

>  Random Forest showed the best performance.

##  Conclusion
This project demonstrates how simple machine learning algorithms can accurately classify digit images with proper preprocessing and model evaluation. Random Forest proved most effective due to its ensemble nature.

##  Project Structure
```
OCR_Digit_Classification/
├── OCR_Digit_Classification.ipynb    # Jupyter Notebook
├── OCR_Digit_Classification.py       # Python Script
├── README.md                         # Project Description
```

##  How to Run
1. Clone this repository
2. Install dependencies (`pip install -r requirements.txt`)
3. Run the notebook or Python file to train and test the models
