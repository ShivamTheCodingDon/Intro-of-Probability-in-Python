# Intro-of-Probability-in-Python

# Intro-of-Probability-in-Python

This repository provides an introductory crash course on **Probability and Statistics using Python**, leveraging Jupyter notebooks for hands-on learning. It includes foundational concepts in probability, statistical reasoning, and data analysis using real-world datasets such as **NHANES (National Health and Nutrition Examination Survey)**.

## 📁 Repository Structure

| Notebook | Description |
|----------|-------------|
| `00-basic-python-crash-course.ipynb` | Quick Python refresher covering variables, loops, functions, and NumPy basics. |
| `00-nhanes_data_basics.ipynb` | Introduces the NHANES dataset. Includes basic data exploration, cleaning, and variable understanding. |
| `01-data-types.ipynb` | Overview of categorical and numerical data types; includes examples from NHANES. |
| `02-studying-variables.ipynb` | Summarizing single variables using measures like mean, median, mode, and visualizations. |
| `03-dispersion.ipynb` | Discusses measures of spread: variance, standard deviation, IQR, and range. |
| `04-coin-flips.ipynb` | Simulates coin flips to explain basic probability concepts like outcomes and distributions. |
| `05-spam-detection.ipynb` | Applies basic probability to a real-world classification problem: spam email detection. |
| `06-distributions.ipynb` | Introduction to probability distributions (Bernoulli, Binomial, Normal, etc.). |
| `06-joints-and-marginals.ipynb` | Explains joint and marginal probability distributions using NHANES. |
| `07-decision-tree.ipynb` | A simple decision tree classifier to illustrate probabilistic decision-making. |
| `08-bayesian-inference.ipynb` | Introduction to Bayesian inference and belief updating with prior and likelihood. |

---

## 📊 NHANES Dataset

We use a subset of the NHANES dataset which includes the following variables:


### Key Variables Explained

| Variable | Description |
|----------|-------------|
| `SEQN` | Respondent sequence number |
| `RIAGENDR` | Gender (1 = Male, 2 = Female) |
| `RIDAGEYR` | Age in years |
| `RIDRETH1` | Race/ethnicity |
| `SMQ020` | Smoking status |
| `ALQ101` | Ever had at least 12 drinks in 1 year |
| `BPXSY1`, `BPXDI1` | Systolic and Diastolic BP readings |
| `BMXWT`, `BMXHT`, `BMXBMI` | Body weight, height, and BMI |
| `DMDEDUC2` | Education level |
| `INDFMPIR` | Family poverty income ratio |
| `HIQ210` | Health insurance coverage |

---

## 🧠 Learning Outcomes

By working through this repository, you will:

- Understand basic and intermediate probability concepts
- Learn to apply statistics using real-world health survey data
- Gain practical experience with Python tools like Pandas, NumPy, and Matplotlib
- Apply Bayesian reasoning and explore predictive modeling techniques

---

## 📌 Requirements

Install the required libraries using:

```bash
pip install -r requirements.txt

Minimal libraries used:

1.pandas

2.numpy

3.matplotlib

4.seaborn

5.scikit-learn (for ML examples)
```
---

## 🚀 Getting Started

### Clone this repository

```bash
git clone https://github.com/yourusername/Intro-of-Probability-in-Python.git
cd Intro-of-Probability-in-Python
```

### Launch Jupyter Notebook
```bash
jupyter notebook
```
