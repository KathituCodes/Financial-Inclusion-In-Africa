# Financial Inclusion in Africa – ML Classification Project

````markdown

## Problem Statement
Millions of individuals across East Africa remain excluded from formal financial systems.
This project uses machine learning to predict whether a person is likely to own or use a **bank account**,
based on their demographic and socio-economic attributes.

## Project Objective
The primary goal is to:
- Develop a machine learning classifier that predicts financial inclusion.
- Identify underserved individuals and communities.
- Enable smarter decision-making for financial outreach programs.

## Dataset
The dataset contains information on **33,600 individuals** from East Africa, including:
- Age, gender, education, and job type
- Urban vs. rural location
- Access to electricity, phone ownership, etc.

**Target variable**: `bank_account` (Yes/No)

## Implementation Summary
The project was implemented in the following phases:

### 1. Data Exploration & Cleaning
- Displayed general information about the dataset
- Used `pandas-profiling` for exploratory data analysis
- Handled missing values, removed duplicates, treated outliers
- Encoded categorical variables using label encoding

### 2. Model Training
- Built and tested multiple classification models (e.g., Decision Tree, Random Forest)
- Evaluated using cross-validation, accuracy, precision, and recall

### 3. Deployment via Streamlit
- A local **Streamlit** app was built to interact with the model
- The app accepts user input for all model features and provides real-time predictions
- Trained model was saved using `joblib` and loaded into the Streamlit interface

## Results
- The classifier successfully predicts bank account ownership with solid performance.
- Streamlit interface allows real-time, user-friendly predictions.
- The project supports data-driven interventions for improving financial inclusion.

## 🖥️ How to Use (Locally)
1. **Clone the repository**:
   ```bash
   git clone https://github.com/your-username/financial-inclusion-ml.git
   cd financial-inclusion-ml
````

2. **Install dependencies**:

   ```bash
   pip install -r requirements.txt
   ```

3. **Run the Streamlit app**:

   ```bash
   streamlit run streamlit_app.py
   ```

## Project Structure

* `Financial_Inclusion_in_Africa_–_ML_Classification_Project.ipynb`: Main notebook
* `model.pkl`: Trained ML model (saved using `joblib`)
* `streamlit_app.py`: Streamlit app code
* `requirements.txt`: Project dependencies

## Notes

* This project is **deployed locally**. To interact with it, clone the repo and run the app using the instructions above.
* For now, no public deployment link is available.

## Additional Materials

* Dataset: Provided via the Zindi Africa platform
* Background on Financial Inclusion: [World Bank – Financial Inclusion Overview](https://www.worldbank.org/en/topic/financialinclusion)

---

## Author

Urbanus Peter Kathitu

> *This project supports the mission of increasing access to inclusive financial services across Africa.*

```

