# STUDY OF CATEGORICAL DATA ANALYSIS USING PYTHON

Name – Falak Jain

Branch – ENTC A3 

PRN – 25070123047

---

## Aim

To study and perform **categorical data analysis using Python and the Pandas library**.

---

## Introduction

Categorical data refers to data that represents **different groups, labels, or categories** rather than numerical quantities. Examples include product categories, gender, payment methods, departments, grades, etc.

In data analysis, categorical variables are widely used to **understand patterns, compare groups, and identify relationships between different categories**. Analyzing such data helps in making informed decisions in fields like business, education, marketing, and research.

Python provides powerful libraries such as **Pandas**, which allow users to easily create datasets, manipulate data, and perform various analytical operations on categorical variables.

---

## Theory

Categorical Data Analysis involves techniques used to **summarize and analyze qualitative data**. Instead of performing mathematical operations such as mean or standard deviation, categorical analysis focuses mainly on **counts, proportions, and relationships between categories**.

One of the most commonly used operations is **frequency count**, which calculates how many times each category appears in a dataset. This helps in understanding the distribution of data.

Another useful operation is **finding unique values**, which identifies all distinct categories present in a column. The function **nunique()** can also be used to determine the number of different categories in a dataset.

**Cross tabulation** is an important method used to analyze the relationship between two categorical variables. It creates a table that displays the frequency of combinations of categories.

**Percentage distribution** helps represent category frequencies as percentages, making it easier to interpret the proportion of each category in the dataset.

Other operations such as **filtering, grouping, and sorting** allow users to extract specific information, analyze category-wise data, and organize the dataset in a structured way.

Using the **Pandas library**, these operations can be performed easily with built-in functions such as `value_counts()`, `unique()`, `nunique()`, `crosstab()`, and `groupby()`.

---

## Procedure

1. Import the **Pandas library** in Python.
2. Create a dataset containing categorical variables such as category, payment method, delivery type, and customer type.
3. Convert the dataset into a **Pandas DataFrame**.
4. Use **value_counts()** to calculate the frequency of different categories.
5. Use **unique()** to display distinct values in the dataset.
6. Use **nunique()** to determine the number of unique categories.
7. Apply **cross tabulation using pd.crosstab()** to analyze relationships between categorical variables.
8. Calculate **percentage distribution** using the normalize option.
9. Filter specific data using conditional statements.
10. Use **groupby()** to analyze grouped categorical data.
11. Sort the dataset using **sort_values()** for better visualization.

---

## Tools / Libraries Used

* Python
* Google Colab / Jupyter Notebook
* Pandas Library

---

## Applications

* Educational data analysis
* Market research
* Business decision making
* Data exploration in data science




---

## Advantages of Categorical Data Analysis

1. **Easy to Understand**
   Categorical data is simple to interpret because it represents data in the form of groups or labels.

2. **Helps in Identifying Patterns**
   It helps in recognizing patterns and relationships between different categories.

3. **Useful for Decision Making**
   Businesses and organizations can analyze categorical data to make better decisions.

4. **Simplifies Data Organization**
   Data can be easily grouped, filtered, and sorted based on categories.

   5. **Widely Used in Different Fields**
   It is used in fields such as marketing, education, healthcare, and business analytics.

---

## Conclusion

Categorical data analysis helps in **understanding the distribution and relationships of qualitative variables** within a dataset. With the help of Python and the Pandas library, categorical datasets can be easily analyzed using operations like **frequency counts, cross tabulation, grouping, and percentage distribution**. This experiment demonstrates how Python simplifies categorical data analysis and makes data interpretation more efficient.






