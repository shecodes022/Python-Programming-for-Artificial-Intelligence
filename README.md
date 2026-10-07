# About this Repository 📌

This repository contains the project I did as a part of the coursework for the module Python Programming for Artificial Intelligence. The assignment consisted of several tasks built around a student "Happiness Dataset", covering data cleaning, custom NumPy functions, statistical analysis, visualisation and a distance-based similarity measure.


# Key Takeaways 🔍

1. Data Understanding: Explored a survey dataset of student attributes (age, height, weight, province, languages, education level, hobbies and happiness score) to identify what may influence happiness.

2. Data Cleaning: Fixed inconsistent IDs, invalid ranges, wrong data types, text/decimal entries and missing values, using NumPy only and replacing unusable values with `np.nan`.

3. Custom Functions: Wrote documented functions such as `sum_with_none`, `mean_with_none` and `std_with_none` that handle `None` and `np.nan` values correctly.

4. Statistics & Visualisation: Computed means and standard deviations, and used Matplotlib to build pie charts and bar graphs for education level, province counts, happiness index and province education rankings.

5. Similarity Measure: Designed a scaled distance function across mixed numeric, boolean and categorical attributes to find the closest people in the dataset, including handling of missing values.


# Stack 🛠️

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)


# Environment 👩🏻‍💻
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white)


# Libraries ⚙️

![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557c?style=for-the-badge&logo=python&logoColor=white)


# Repository Structure 🌲
```text
├── Python_Project.ipynb
├── .gitattributes
└── README.md
```

# Reflection 🪞
This project showed how much of a real AI workflow is spent understanding and cleaning data before any analysis begins. Restricting myself to NumPy made me think carefully about how missing and invalid values propagate through calculations such as means, standard deviations and distances.

Building the similarity function also highlighted the importance of scaling and of choosing sensible attributes when comparing mixed data types. Overall, it strengthened my confidence in writing clean, documented and reusable Python code.
