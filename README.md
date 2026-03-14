# python-basics-projects
My solutions and practice projects from CS50P and Python learning journey

# Variant Pathogenicity Prediction using Machine Learning

This project aims to predict the pathogenicity of genetic variants using machine learning techniques. The dataset is derived from the ClinVar database and includes various genomic annotations such as SIFT scores, PolyPhen predictions, exon positions, and protein positions.

The goal of the project is to classify variants as benign or pathogenic using a Logistic Regression model.

---

# Dataset

The dataset is obtained from the ClinVar database and contains information about genetic variants and their annotations.

Important columns used in the model include:

- SIFT prediction
- PolyPhen prediction
- EXON
- cDNA position
- CDS position
- Protein position
- Amino acids
- Codons

Some categorical genomic features were encoded and positional values were converted to numerical format for model training.

---

# Data Preprocessing

Several preprocessing steps were applied before training the model:

- Removing unnecessary columns
- Handling missing values
- Converting categorical values into numeric representations
- Parsing genomic position fields
- Feature selection

Categorical variables such as amino acids and codons were encoded using category encoding.

---

# Model

The machine learning model used in this project is:

Logistic Regression

The dataset was split into training and testing sets using an 80/20 split. The model was trained on the training data and evaluated on the test dataset.

---

# Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Jupyter Notebook

---

# Project Structure
