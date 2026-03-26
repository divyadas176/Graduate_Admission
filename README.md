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
- The "Primary Gatekeeper" (CGPA): Correlation analysis identifies CGPA as the most dominant predictor of admission ($R \approx 0.88$). This suggests that while test scores are important, undergraduate academic consistency is the baseline requirement for a competitive application.
- The Research "Lift": Data reveals a distinct advantage for applicants with Research Experience. On average, students with research background show a significantly higher probability of admission (approx. 15-20% higher) than those with similar test scores but no research exposure.
- Diminishing Returns of Test Scores: While GRE and TOEFL scores positively correlate with admission, the data shows a "clustering" effect at the higher end. This implies that once a threshold (e.g., GRE > 315) is met, qualitative factors like SOP and LOR strength become the primary differentiators.
- Holistic Profile Impact: Qualitative metrics (SOP/LOR) show a moderate but steady positive correlation. Specifically, moving from a 3.0 to a 4.5 rating in SOP strength correlates with a measurable jump in admission probability, proving that "soft" factors can compensate for slightly lower numerical scores.
- The "Competitive Ceiling": The distribution of the dataset shows a high concentration of applicants with CGPA > 8.0 and GRE > 310. This confirms that the graduate admission landscape is highly saturated, making unique features (like Research or high-tier University Ratings) essential for standing out.

---

### Author
- Divya Das
- Data analysis and visualization using Python (Pandas, Seaborn, Matplotlib)
