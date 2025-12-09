# 🎓 **Student Performance – Exam Analysis**

This project focuses on analyzing student exam performance across **Math**, **Reading**, and **Writing** subjects. The goal is to understand overall score distribution and identify statistically significant differences between **male and female students** using descriptive statistics and independent t-tests.

---

## 📌 **Project Overview**

The analysis explores:

* Distribution of exam scores
* Central tendency (mean, median, mode)
* Spread of scores (standard deviation)
* Gender-based score comparison using t-tests
* Key performance insights

No machine learning models were used — the study focuses entirely on **exploratory data analysis (EDA)** and **statistical testing**.

---

## 🗂️ **Repository Structure**

```
student-performance/
│── Student_Performance_Analysis.ipynb
│── dataset/
│── visuals/
│── README.md
```

---

## 🛠️ **Tools Used**

<p align="center">
<img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white"/>
<img src="https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white"/>
<img src="https://img.shields.io/badge/Numpy-013243?style=for-the-badge&logo=numpy&logoColor=white"/>
<img src="https://img.shields.io/badge/Matplotlib-005C97?style=for-the-badge&logo=matplotlib&logoColor=white"/>
<img src="https://img.shields.io/badge/Seaborn-4C72B0?style=for-the-badge&logo=seaborn&logoColor=white"/>
<img src="https://img.shields.io/badge/Statistics-000000?style=for-the-badge&logo=dependabot&logoColor=white"/>
</p>

---

## 📊 **Descriptive Statistics**

### **📘 Mean Scores**

| Subject | Mean Score |
| ------- | ---------- |
| Math    | **66.31**  |
| Reading | **69.36**  |
| Writing | **68.26**  |

---

### **📗 Median Scores**

| Subject | Median Score |
| ------- | ------------ |
| Math    | **66.0**     |
| Reading | **70.0**     |
| Writing | **69.0**     |

---

### **📙 Mode Scores**

| Subject | Mode Score |
| ------- | ---------- |
| Math    | **65.0**   |
| Reading | **72.0**   |
| Writing | **74.0**   |

---

### **📘 Standard Deviation**

| Subject | Std. Deviation |
| ------- | -------------- |
| Math    | **14.75**      |
| Reading | **14.29**      |
| Writing | **14.84**      |

These descriptive statistics provide insights into score behavior:

* **Mean** shows average performance
* **Median** shows central score
* **Mode** highlights most frequent score
* **Standard deviation** shows how spread out the scores are

---

## 📉 **Gender-Based T-Test Results**

Independent t-tests were performed to identify whether score differences between male and female students are statistically significant.

### **Math**

* **t-statistic:** 5.064
* **p-value:** 4.896e-07
* **Conclusion:** Significant difference — **males score higher on average**.

### **Reading**

* **t-statistic:** -8.142
* **p-value:** 1.154e-15
* **Conclusion:** Significant difference — **females score higher on average**.

### **Writing**

* **t-statistic:** -10.004
* **p-value:** 1.616e-22
* **Conclusion:** Strongly significant — **females score higher on average**.

These results indicate that gender plays a measurable role in student performance across subjects.

---

## 📝 **Final Conclusions**

* Students perform best in **Reading**, followed by **Writing**, and lowest in **Math**.
* Variation across subjects is relatively similar (std ≈ 14–15).
* Gender differences are **statistically significant**:

  * **Males excel in Math**
  * **Females excel significantly in Reading and Writing**
* The dataset shows clear performance trends that could help educators understand subject-specific strengths.

---

## 🚀 **Future Enhancements**

* Add visualizations to the `/visuals` folder
* Extend analysis using more demographic factors
* Create a PDF/HTML report summarizing findings

---

## 🙌 **Acknowledgements**

Thanks to open educational datasets and the data analysis community.

---

