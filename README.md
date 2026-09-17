# Heart Disease Prediction

A Machine Learning project focused on analyzing clinical data and building predictive models to detect the presence of heart disease in patients.

---

## 📌 Project Overview

Heart disease is one of the leading causes of death worldwide. Early diagnosis and risk assessment play a critical role in preventative healthcare. This repository implements data analysis, preprocessing, feature exploration, and Machine Learning models to predict heart disease risk based on patient physiological attributes.

---

## 📁 Repository Structure

```text
Heart_Disease_prediction/
│
├── Heart database/
│   ├── HeartData.csv            # Primary dataset containing clinical indicators
│   └── heart.csv                # Secondary/processed cardiovascular dataset
│
├── Heart_Disease_Prediction.ipynb # Jupyter Notebook with EDA, training, and evaluation
├── source code.txt              # Script containing core model implementation logic
└── README.md                    # Project documentation
```

---

## 📊 Dataset Overview

The dataset includes standard physiological metrics associated with cardiovascular health. Key features typically analyze:

- **Age**: Patient age in years
- **Sex**: Biological sex ($1 = \text{male}$, $0 = \text{female}$)
- **Chest Pain Type (`cp`)**: Severity and type of chest pain (1 to 4)
- **Resting Blood Pressure (`trestbps`)**: Measured in mm Hg on admission to the hospital
- **Serum Cholesterol (`chol`)**: Measured in mg/dl
- **Fasting Blood Sugar (`fbs`)**: Fasting blood sugar $> 120\text{ mg/dl}$ ($1 = \text{true}$, $0 = \text{false}$)
- **Resting ECG (`restecg`)**: Resting electrocardiographic results
- **Maximum Heart Rate Achieved (`thalach`)**: Peak heart rate recorded during exercise
- **Exercise Induced Angina (`exang`)**: Presence of angina after exercise ($1 = \text{yes}$, $0 = \text{no}$)
- **ST Depression (`oldpeak`)**: Exercise-induced ST depression relative to rest
- **Slope (`slope`)**: Slope of the peak exercise ST segment
- **Major Vessels (`ca`)**: Number of major vessels ($0-3$) colored by fluoroscopy
- **Thalassemia (`thal`)**: Blood disorder classification
- **Target (`target`)**: Heart disease status ($0 = \text{No Disease}$, $1 = \text{Disease Present}$)

---

## 🚀 Getting Started

### Prerequisites

Ensure you have Python 3.8+ installed along with the required libraries:

```bash
pip install numpy pandas matplotlib seaborn scikit-learn jupyter
```

### Installation & Execution

1. **Clone the repository:**
   ```bash
   git clone https://github.com/your-username/Heart_Disease_prediction.git
   cd Heart_Disease_prediction
   ```

2. **Run the Jupyter Notebook:**
   ```bash
   jupyter notebook Heart_Disease_Prediction.ipynb
   ```

3. **Alternative Script Execution:**
   You can also execute or inspect the standard script using python from `source code.txt`.

---

## 🧪 Workflow & Methodology

1. **Data Preprocessing & Cleaning:**
   - Handling missing or corrupted values.
   - Encoding categorical values and standardizing numeric ranges using standard scaling ($z = \frac{x - \mu}{\sigma}$).

2. **Exploratory Data Analysis (EDA):**
   - Correlation heatmaps to detect feature relationships with the target variable.
   - Distribution plots across age, chest pain type, and cholesterol levels.

3. **Model Training & Evaluation:**
   - Training multiple classification algorithms (e.g., Logistic Regression, Random Forest, Support Vector Machines, KNN).
   - Metrics evaluated include Accuracy, Precision, Recall, F1-Score, and ROC-AUC curves.

---

## 📈 Results & Future Enhancements

- **Model Performance:** Detailed accuracy comparisons and confusion matrices can be found directly within the notebook.
- **Future Improvements:**
  - Hyperparameter tuning via GridSearchCV.
  - Deployment of the model as a web service using Streamlit or Flask.
  - Integration of larger, multi-center clinical datasets.

---

## 📄 License

This project is open-source and available under the standard MIT License.
