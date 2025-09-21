# Drug_classification

This project applies different supervised ML models and chooses the one that best fits, to predict which type of drug should be prescribed to a patient, based on their medical attributes.

The dataset used is Drug.xls, which contains patients information and the prescribed drug.
**Features:**
- Age
- Sex
- Blood Pressure (BP)
- Cholesterol
- Na leyels
- K levels

**Target classes:** DrugA, DrugB, DrugC, DrugX, DrugY

##  Models Trained
Models tested and compared:
- **Logistic Regression**
- **Support Vector Classifier (SVC)**
- **k-Nearest Neighbors (kNN)**
- **Decision Tree**
- **Random Forest**

## Hyperparameter Tuning
We applied **GridSearchCV** with cross-validation to the best-performing model(**Logistic Regression**, with accuracy: 0.975).  
- **Best parameters found:**
  `C = 10.0`, `class_weight = None`, `penalty = l2`, `solver = lbfgs`   
- **Best CV accuracy:** ≈ 0.982

## Ejecution
1. Clone the repository:
```
git clone https://github.com/Moniica22/Drug_classification.git
cd Drug_classification
```
2. Install dependencies
```
pip install -r Requirements.txt
```
3. Run Jupyter notebook
```
jupyter notebook Drug_classification.ipynb
```

## License
MIT (or your preferred license).
