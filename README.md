# Skin-Cancer-Binary-Classifier
![Project Status](https://img.shields.io/badge/status-Completed-brightgreen.svg)
![Platform](https://img.shields.io/badge/platform-Kaggle-pink.svg)
![Environment](https://img.shields.io/badge/environment-Jupyter%20Notebook-orange.svg)
![Language](https://img.shields.io/badge/language-Python-blue.svg)

A machine learning project for binary classification of skin cancer as malignant or benign, utilizing models like XGBoost, LGBM Classifier, Adaboost, SVM, and Logistic Regression. This pipeline involves preprocessing, visualization, modeling, and evaluation, making it a powerful diagnostic aid in dermatology.

![Introduction](https://github.com/user-attachments/assets/a4d22af5-9553-47ea-835a-59f639172f06)


##  EDA & Preprocessing

### Exploratory Data Analysis
- Load and integrate image and metadata files.
![Image](https://github.com/user-attachments/assets/ca96df0d-ebec-4ecd-9d49-891d09add81b)

- Visualize sample images for quality checks.

![Image](https://github.com/user-attachments/assets/0e617997-50d1-44e1-b3a2-16b90650bfcf)

- Count of Targets by Anatomical Site
![Image](https://github.com/user-attachments/assets/741e745a-d990-42f7-b468-e6617a5ea078)

- Count of Targets by Age 
![Image](https://github.com/user-attachments/assets/ddc5fede-8b81-4867-b777-1ba1210c51d3)

- Count of Targets by Sex
![Image](https://github.com/user-attachments/assets/8fc07d31-d2fa-40c0-a706-6418963a0890)
- Analyze class distribution (malignant vs. benign).
   Benign         400666
   Malignant       393

![Image](https://github.com/user-attachments/assets/fdf47299-6d82-4b04-8af3-a8386a7e90f2)

- Review metadata (patient age, lesion location, etc.).
![Image](https://github.com/user-attachments/assets/b1f39c1c-2023-4d35-b058-4f986008ccfb)

###  Preprocessing
![Image](https://github.com/user-attachments/assets/1de69677-eb57-47ac-9c11-eb8f4d15f11f)

![Image](https://github.com/user-attachments/assets/65611ace-a879-40c6-92a4-82b9d690314f)

- **Data Cleaning**: Remove duplicates, handle missing values.
- **Data Augmentation**: Random rotations, flips, brightness/contrast variations.
![Image](https://github.com/user-attachments/assets/a6a4f88e-19fb-4613-9f62-d55f31199d88)

- **Normalization**: Scale pixel intensities, normalize image dimensions.
- **Resizing**: Uniform image dimensions while preserving aspect ratio.
![Image](https://github.com/user-attachments/assets/867e1d33-5549-4ac1-aae4-3797b14e6604)

---

## Modeling & Training

### Models Used
- XGBoost
- AdaBoost
- LightGBM (LGBMClassifier)
- Support Vector Machine (SVM)
- Logistic Regression
- (Optional) Neural Network (for deep learning approach)

![Image](https://github.com/user-attachments/assets/e538dcf7-7fc5-4795-ad73-1611b0f7ecad)

---

### Training Techniques
- Hyperparameter tuning using Grid/Random Search.
- K-Fold Cross-validation.
- Model-specific optimizations (e.g., SVM kernels, NN architecture).

![Image](https://github.com/user-attachments/assets/2cf85eb7-fb61-4547-bc29-b5d16545e086)

---

## Evaluation

- **Metrics**: Accuracy, Precision, Recall, F1-Score, AUC.
- **Validation**: Regular monitoring using a validation set.
- **Confusion Matrix**: For visualizing classification errors.

![Image](https://github.com/user-attachments/assets/5377603a-7b55-4825-a533-c9c13819db28)

---

## Tech Stack

| Category      | Tool/Framework              |
|---------------|------------------------------|
| **Platform**  | Kaggle                       |
| **Notebook**  | Jupyter Notebook             |
| **Language**  | Python                       |
| **Libraries** | scikit-learn, XGBoost, LightGBM, matplotlib, seaborn, OpenCV, NumPy, pandas |

---

## How to Run

1. Go to the Kaggle Notebook using the link below:

https://www.kaggle.com/code/masharjavid/final-skin-cancer-binary-classifier 

2. Open the notebook and run all cells.
3. Dataset is already uploaded in the Kaggle environment and linked within the notebook.

---

## Results
- **Best AUC Score**: _0.963_
- **Highest Accuracy**: _90.02%_
- **Top Performing Model**: _LGBM-Classifier_
- **Train loss**: _0.1646_
- **Validation loss**: _0.1245_
- **Recall**: _0.876_
- **Time taken**: _60.94sec_

![Image](https://github.com/user-attachments/assets/d1a54183-7afe-43c8-bd53-0a1e8d9f11e1)

![Image](https://github.com/user-attachments/assets/63cfd5e8-b9ce-4dcd-9269-0add796e33e6)

---

## Future Work
- Web/Mobile app deployment with UI for diagnosis.
- Explore larger datasets for improved generalization.
