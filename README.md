# 📚 NYC Public Schools SAT Performance Analysis

## 📌 Project Overview

Every year, thousands of American high school students take the **SAT**, a standardized exam used in college admissions. The SAT measures student performance across three core sections:

* **Reading** (800 max)
* **Math** (800 max)
* **Writing** (800 max)

This project explores the SAT performance of **New York City public schools** using Python and Pandas to answer three key business questions:

1. Which NYC schools have the best math results?
2. What are the top 10 performing schools based on combined SAT scores?
3. Which borough has the largest variation in SAT performance?

---

## 🛠️ Tools & Technologies Used

* **Python**
* **Pandas**
* **Jupyter Notebook**

---

## 📂 Dataset

The dataset used is:

`schools.csv`

It contains SAT score data for NYC public schools, including:

* School Name
* Borough
* Average Math Score
* Average Reading Score
* Average Writing Score

---

## 🔍 Project Tasks & Analysis

---

## 1️⃣ Best Performing Schools in Math

To identify elite-performing schools in Mathematics, a benchmark of **80% of the maximum SAT Math score** was used:

[
800 \times 0.8 = 640
]

Schools scoring **640 and above** were selected.

### 🏆 Top Math Schools

| Rank | School Name                                          | Math Score |
| ---- | ---------------------------------------------------- | ---------- |
| 1    | Stuyvesant High School                               | 754        |
| 2    | Bronx High School of Science                         | 714        |
| 3    | Staten Island Technical High School                  | 711        |
| 4    | Queens High School for the Sciences at York College  | 701        |
| 5    | High School for Mathematics, Science and Engineering | 683        |

### 📌 Insight

Specialized science and technology schools dominate mathematics rankings, showing the strong academic competitiveness of NYC selective schools.

---

## 2️⃣ Top 10 Schools by Total SAT Score

The total SAT score was calculated as:

[
\text{Total SAT} = Math + Reading + Writing
]

### 🏆 Top 10 NYC Schools

| Rank | School Name                                          | Total SAT |
| ---- | ---------------------------------------------------- | --------- |
| 1    | Stuyvesant High School                               | 2144      |
| 2    | Staten Island Technical High School                  | 2041      |
| 3    | Bronx High School of Science                         | 2041      |
| 4    | High School of American Studies at Lehman College    | 2013      |
| 5    | Townsend Harris High School                          | 1981      |
| 6    | Queens High School for the Sciences at York College  | 1947      |
| 7    | Brooklyn Technical High School                       | 1896      |
| 8    | High School for Mathematics, Science and Engineering | 1889      |
| 9    | Eleanor Roosevelt High School                        | 1889      |


### 📌 Insight

Top-performing schools consistently belong to NYC’s specialized or academically selective institutions.

---

## 3️⃣ Borough with Highest SAT Score Variation

Standard deviation was used to measure score spread across boroughs.

### 🏆 Borough Result

| Borough   | Number of Schools | Average SAT | Standard Deviation |
| --------- | ----------------- | ----------- | ------------------ |
| Manhattan | 89                | 1340.13     | 230.29             |

### 📌 Insight

**Manhattan** has the highest SAT score variation, meaning it contains both:

* Extremely high-performing schools
* Lower-performing schools

This suggests educational inequality and a wide performance gap within the borough.

---

# 📈 Key Business Insights

## 🎯 Education Stakeholders Can Use This To:

### For Parents

Identify top-performing schools for admission planning.

### For Policymakers

Target boroughs with high score disparities for intervention.

### For Researchers

Study performance patterns across socioeconomic regions.

### For Schools

Benchmark against leading institutions.

---


---

# 💻 Code Snippet

```python
school['total_SAT'] = (
    school['average_math'] +
    school['average_reading'] +
    school['average_writing']
)
```

---

# 🚀 Final Conclusion

This analysis reveals that **specialized NYC schools consistently outperform others**, particularly in math and total SAT performance.

It also highlights **Manhattan as the borough with the greatest score disparity**, signaling opportunities for targeted educational improvement.

---


---

# 🙌 Connect With Me

If you found this project helpful, feel free to ⭐ the repository and connect with me on LinkedIn.


