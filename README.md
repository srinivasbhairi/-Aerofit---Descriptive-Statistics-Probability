![image](https://github.com/user-attachments/assets/689dac7a-eb45-4db3-98fa-82ed42efa1cc)

SRINIVAS BHAIRI | Data Scientist Aspirant

[Connect me on LinkedIn](https://www.linkedin.com/in/srinivas-bhairi)

## 🏋️‍♂️ AeroFit Treadmill Customer Segmentation & Analysis

### 📌 About AeroFit

**AeroFit** is a leading brand in the fitness equipment industry, offering a wide range of products including treadmills, exercise bikes, gym equipment, and fitness accessories. Their product portfolio is designed to meet the fitness needs of all categories of customers, from beginners to professional athletes.

---

### 🎯 Business Objective

The **Market Research Team** at AeroFit aims to identify the target audience characteristics for each type of treadmill. The goal is to improve product recommendations for new customers by analyzing if different treadmill models appeal to different customer profiles.

---

### 📝 Project Goals

Perform **Descriptive Analytics** to create a **customer profile** for each AeroFit treadmill product using:

* Summary statistics & visualizations
* Two-way contingency tables
* Marginal and conditional probability computations
* Customer profiling insights and recommendations

---

### 🧾 Dataset Description

| Feature               | Description                                            |
| --------------------- | ------------------------------------------------------ |
| **Product Purchased** | Type of treadmill purchased: `KP281`, `KP481`, `KP781` |
| **Age**               | Age of customer (in years)                             |
| **Gender**            | `Male` or `Female`                                     |
| **Education**         | Number of years of education                           |
| **MaritalStatus**     | `Single` or `Partnered`                                |
| **Usage**             | Avg. times per week customer plans to use treadmill    |
| **Income**            | Annual income in USD                                   |
| **Fitness**           | Self-rated fitness level (1 = Poor, 5 = Excellent)     |
| **Miles**             | Avg. miles expected to walk/run per week               |

---

### 🏷️ Treadmill Product Portfolio

| Product   | Price (USD) | Description                              |
| --------- | ----------- | ---------------------------------------- |
| **KP281** | \$1,500     | Entry-level treadmill                    |
| **KP481** | \$1,750     | Mid-range treadmill for regular runners  |
| **KP781** | \$2,500     | Premium treadmill with advanced features |

---

### 📊 Analytical Approach

1. **Initial Data Exploration**

   * Dataset loading, structure analysis, and data types
   * Summary statistics using `.describe()` and `.info()`

2. **Outlier Detection**

   * Using boxplots and statistical metrics (mean vs median)

3. **Visual Analysis**

   * Histograms and boxplots by product type
   * Count plots for categorical variables like `Gender`, `MaritalStatus`

4. **Customer Behavior Analysis**

   * Investigate how `Age`, `Income`, `Fitness`, and `Usage` relate to product choice
   * Use of group-by aggregations and comparative bar charts

5. **Contingency Tables & Probability Analysis**

   * Marginal Probability: Percentage distribution of products purchased
   * Conditional Probability: e.g., Probability of a male customer buying KP781
   * Two-way tables with `pd.crosstab()` and percentage breakdowns

6. **Correlation Analysis**

   * Heatmaps and pair plots to identify significant relationships among variables

---

### 📈 Expected Deliverables

* **Customer Profiles** per product category
* **Marginal & Conditional Probability** insights
* **Visualizations** that tell a story
* **Business Recommendations** such as:

  * Which product suits which customer segment?
  * What characteristics define a KP781 buyer?
  * How does fitness level or income influence product choice?

---

### 🧠 Example Questions Answered

* What is the **probability of a male customer** buying the **KP781** treadmill?
* Does **marital status** influence treadmill preference?
* What are the most **important factors** for premium product buyers?

---

### 📌 Tools & Technologies

* Python (Pandas, Matplotlib, Seaborn, NumPy)
* Jupyter Notebook
* Markdown for documentation

---

### 📢 Actionable Insights

Based on the analysis, this project provides **data-driven recommendations** to AeroFit’s marketing team, enabling them to:

* Personalize customer recommendations
* Optimize marketing campaigns by demographic groups
* Forecast product demand more accurately
