# Drug Prediction using Decision Trees

## 📌 Overview
This project demonstrates how to use **Decision Tree Classifiers** to predict the type of drug prescribed to patients based on their medical attributes. The dataset contains information about patients who responded to one of five medications: **Drug A, Drug B, Drug C, Drug X, and Drug Y**.

---

## 📂 Dataset
- Source: [Drug200 dataset](https://s3-api.us-geo.objectstorage.softlayer.net/cf-courses-data/CognitiveClass/ML0101ENv3/labs/drug200.csv)
- Features:
  - Age
  - Sex
  - Blood Pressure (BP)
  - Cholesterol
  - Na_to_K ratio
- Target:
  - Drug type (Drug A, B, C, X, Y)

---

## ⚙️ Technologies Used
- **Python 3.x**
- **NumPy / Pandas** → Data handling
- **Scikit-learn** → Decision Tree Classifier, preprocessing, train-test split
- **Matplotlib** → Visualization
- **Jupyter Notebook / Google Colab** → Interactive development

---

## 🚀 Steps in the Project
1. **Import Libraries**  
   Load NumPy, Pandas, and Scikit-learn modules.

2. **Load Dataset**  
   Download and read `drug200.csv`.

3. **Preprocessing**  
   - Convert categorical variables (Sex, BP, Cholesterol) into numerical values using `LabelEncoder`.
   - Split dataset into features (`X`) and target (`y`).

4. **Train-Test Split**  
   - Split data into training (70%) and testing (30%).

5. **Model Training**  
   - Train a
