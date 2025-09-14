# Early Detection of Alzheimer’s Disease using DARWIN Handwriting Dataset

The project applies supervised machine learning to the **DARWIN dataset** to classify handwriting-based features for **early detection of Alzheimer’s Disease (AD).**

---

## Dataset

The dataset used is the **DARWIN (Diagnosis AlzheimeR WIth haNdwriting) dataset**

- **Participants**: 174 (89 AD patients, 85 healthy controls)  
- **Tasks**: 25 handwriting/drawing tasks  
- **Features**: 18 features extracted per task → 450 features total  
- **Target**: Binary classification → Healthy (H) vs Patient (P)

Dataset reference:  
Cilia ND, De Gregorio G, De Stefano C, Fontanella F, Marcelli A, Parziale A.  
[*Diagnosing Alzheimer’s disease from online handwriting: A novel dataset and performance benchmarking*](https://doi.org/10.1016/j.engappai.2022.104822).  
*Engineering Applications of Artificial Intelligence, 2022.*

---

## Workflow

1. **Data loading & exploration**
   - Inspect dataset structure  
   - Check missing values, class balance  

2. **Preprocessing**
   - Log transformation  
   - Scaling (StandardScaler, RobustScaler)  
   - Feature correlation analysis  

3. **Train-test split**  
   - Stratified split for balanced evaluation  

4. **Model training and selection**
   - Logistic Regression  
   - Support Vector Machine (SVM)  
   - Random Forest  
   - k-Nearest Neighbors (KNN)  
   - etc.  

5. **Model evaluation**
   - Accuracy, Precision, Recall, F1-score  
   - ROC-AUC  
   - Visualization: correlation heatmaps, regression plots  

---

## Results

- Explored correlations across handwriting features  
- Evaluated multiple classifiers  
- Highlighted strengths/limitations in early Alzheimer’s detection  
