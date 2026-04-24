# Data-Driven Analysis of Factors Influencing Graduate Admissions

### Project Overview
This repository contains a dataset and a Jupyter Notebook for analyzing and predicting graduate admission chances for postgraduate programs. The analysis focuses on understanding key factors that influence admission probability, such as standardized test scores, academic performance, recommendation strength, and research experience.

The project is designed from an **Indian perspective** but can be adapted for general graduate admissions worldwide. It also demonstrates how to preprocess data, perform exploratory data analysis (EDA), and optionally build a predictive model for admission chances.

---

### Dataset
The dataset contains several parameters that are commonly considered during Master’s program applications:

- **GRE Scores** (out of 340)  
- **TOEFL Scores** (out of 120)  
- **University Rating** (1–5)  
- **Statement of Purpose (SOP) and Letter of Recommendation (LOR) Strength** (1–5)  
- **Undergraduate GPA** (out of 10)  
- **Research Experience** (0 or 1)  
- **Chance of Admit** (0–1 probability)  
- **Optional:** **IELTS Score** (derived approximately from TOEFL)

The dataset is inspired by the **UCLA Graduate Dataset** and owned by **Mohan S Acharya**.

---

### Purpose
This project helps students and researchers:

- Explore factors that influence graduate admissions  
- Understand the relative importance of GPA, test scores, SOP/LOR, and research experience  
- Learn how to clean, preprocess, and visualize real-world academic datasets  
- Build a predictive model to estimate admission probability

---

### Usage
- The notebook `graduate_admission.ipynb` contains the full analysis, including plots and insights.  
- To reproduce the results, simply open the notebook in Jupyter or Google Colab and run the cells.  

---

### Key Findings & Insights
- CGPA has the strongest positive impact on the Chance of Admit, followed by GRE and TOEFL scores.
- Research experience, SOP strength, and LOR also moderately improve admission chances.
- Most applicants in the dataset have strong GRE, TOEFL, and CGPA scores, suggesting a competitive pool.
- Adding IELTS as a derived feature provides an alternate view of English proficiency.
- Overall, a combination of academic performance and application quality determines admission probability.

---

### Author
- Divya Das
- Data analysis and visualization using Python (Pandas, Seaborn, Matplotlib)
