# Healthcare-Analytics
Contents of Repository:
- Python Notebook file contains project code for Data Exploration, Feature Engineering, and Machine Learning models (Naive Bayes, XGBoost, Neural Networks).
- PDF Report file contains overview of the project, predicitions and results.
- Datasets.zip contains both the test and train data used in the project.
- HTML file is a markdown of the jupyter notebook with alll the outputs to View without python or its IDE.

Introduction:

  Healthcare organizations are under increasing pressure to improve patient care outcomes and achieve better care. While this situation represents a challenge, it also offers organizations an opportunity to dramatically improve the quality of care by leveraging more value and insights from their data. Health care analytics refers to the analysis of data using quantitative and qualitative techniques to explore trends and patterns in the acquired data. While healthcare management uses various metrics for performance, a patient’s length of stay is an important one.

  Being able to predict the length of stay (LOS) allows hospitals to optimize their treatment plans to reduce LOS, to reduce infection rates among patients, staff, and visitors.

Project Highligths:

Hospital admission data was analyzed to accurately predict the patient’s Length of Stay at the time of admit so that the hospitals can optimize resources and function better. Built 3 models in Python to predict the length of stay,

-	A supervised algorithm Naïve Bayes which was classifying with an accuracy of 34.55%.

-	An ensemble method XGBoost which was predicting with an accuracy of 43.05%.

-	A dense neural network with 6 layers which yields an accuracy of 42.5%.

  # 🏥 Patient Outcome Prediction: Improving Healthcare Decisions with Data Analytics



## 🎯 Objectives
- Predict patient outcomes using clinical and demographic data.  
- Identify significant risk factors that influence health outcomes.  
- Support healthcare professionals in **evidence-based decision making**.  
- Demonstrate how data-driven approaches can enhance patient care.  

---

## 📂 Dataset
- Patient data with features like:  
  - Age, Gender, Medical history  
  - Diagnosis & treatment details  
  - Lab results and clinical observations  
- Target variable: **Patient Outcome** (e.g., Recovered / Not Recovered / Risk category).  

> ⚠️ Note: All data used is anonymized and for research/academic purposes only.

---

## 🛠️ Tools & Technologies
- **Programming:** Python 🐍  
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn  
- **Models:** Logistic Regression, Decision Trees, Random Forest, XGBoost  
- **Visualization:** Graphs, heatmaps, feature importance plots  

---

## 🔎 Methodology
1. **Data Preprocessing**
   - Handling missing data, normalization, encoding categorical variables  
2. **Exploratory Data Analysis (EDA)**
   - Visualization of feature distributions, correlation analysis  
3. **Model Building**
   - Train/test split, applying multiple ML models  
4. **Evaluation**
   - Accuracy, Precision, Recall, F1-Score, Confusion Matrix  
5. **Insights**
   - Identify critical features that affect patient outcomes  

---

## 📊 Results
- Best-performing model: **[Insert your model name & accuracy here]**  
- Achieved **XX% accuracy** on test data.  
- Key influencing factors: **[Top 3–5 features from your results]**  

---

## 🚀 How to Run
```bash
# Clone this repo
git clone https://github.com/Abigna2/Healthcare-Analytics.git

# Navigate into the project folder
cd Healthcare-Analytic

# Install dependencies
pip install -r requirements.txt

# Run Jupyter Notebook
jupyter notebook


