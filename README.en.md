# MAC5865 — Data Science and Engineering

[Português](README.md) | **English**

Repository with the assignments developed for **MAC5865 — Data Science and Engineering** (*Ciência e Engenharia de Dados*), a graduate course in Computer Science at the Institute of Mathematics and Statistics of the University of São Paulo (IME-USP).

**Instructor:** Prof. Dr. Roberto Hirata Junior

**Professor:** Roberto Hirata Junior

## Objectives

To understand the fundamentals of data science and engineering through the topics covered in the course, such as techniques for manipulating, representing, analyzing, modeling, and validating large datasets.

## Content

The ease of data collection achieved by today's society poses a major challenge: storing, representing, analyzing, and modeling what is commonly known as the “data deluge”. The education of graduate students in Computer Science cannot do without the fundamentals and techniques provided by this course.

Topics covered:

- Importance of the field and its applications
- Knowledge discovery in databases (KDD)
- Cleaning, representation, and quality assessment of large volumes of data
- Data warehouses and multidimensional models
- Indexing and retrieval of large volumes of data
- Graphs in databases
- Exploratory data analysis (cluster analysis and association analysis)
- Knowledge modeling (classifiers, classification rules, examples)
- Development and use of software for KDD
- Exercises with simulated and real data

## Assignments

### EP1 — Exploratory Data Analysis: Used Cars (Cars.com, April 2023)

Exploratory analysis of 762,091 used-vehicle listings published on Cars.com. The work covers a data-quality audit, documented data-preparation decisions, the price distribution, model diversity by manufacturer, the share of electric vehicles by model year, relationships between price, model year and mileage, and an investigation of unusual observations. The notebook is written in Portuguese.

| File | Description |
|---|---|
| [`EP1/Hirata_DataScienceEP1_completo_final1.ipynb`](EP1/Hirata_DataScienceEP1_completo_final1.ipynb) | Notebook with the full analysis |
| [`EP1/cars.csv.gz`](EP1/cars.csv.gz) | Gzip-compressed dataset (the original CSV is 145 MB, above GitHub's 100 MB file limit) |

**How to run:** open the notebook in Google Colab using the link below and run all cells. If `cars.csv` is not present in the session, the notebook automatically downloads and decompresses it from this repository.

[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/rodrigobarbozadias/MAC5865---Ci-ncia-e-Engenharia-de-Dados/blob/main/EP1/Hirata_DataScienceEP1_completo_final1.ipynb)

**Data integrity:** SHA-256 of the decompressed `cars.csv`: `b66592aefd315e73fe84e984f92198c50707d4963a369b7c793ad21e1d455b07`

**Data source:** [Used Cars Dataset — Andrei Novikov (Kaggle)](https://www.kaggle.com/datasets/andreinovikov/used-cars-dataset)

**Authors (Group 5):** Rafael Guimarães Dias · Rodrigo Barboza Dias

## Bibliography

1. Inmon, W. H. *Building the Data Warehouse*. Wiley, 2005.
2. Kantardzic, M. *Data Mining: Concepts, Models, Methods, and Algorithms*. 3rd ed. Wiley-IEEE Press, 2019.
3. Ross, M.; Kimball, R. *The Data Warehouse Toolkit: The Definitive Guide to Dimensional Modeling*. 3rd ed. Wiley, 2013.
4. Baeza-Yates, R.; Ribeiro-Neto, B. *Modern Information Retrieval: The Concepts and Technology behind Search*. 2nd ed. ACM Press Books, 2011.
5. Snodgrass, R. T. *Developing Time-Oriented Database Applications in SQL*. Morgan Kaufmann, 2000.
6. Tan, P.-N.; Steinbach, M.; Kumar, V. *Introdução ao Data Mining* (Portuguese edition of *Introduction to Data Mining*). Ciência Moderna, 2009.
7. Torgo, L. *Data Mining with R: Learning with Case Studies*. Chapman & Hall/CRC Data Mining and Knowledge Discovery Series, 2020.
8. Witten, I.; Frank, E.; Hall, M.; Pal, C. *Data Mining: Practical Machine Learning Tools and Techniques*. Morgan Kaufmann, 2016.
9. Dominich, S. *The Modern Algebra of Information Retrieval*. The Information Retrieval Series. Springer, 2010.
10. Huyen, C. *Designing Machine Learning Systems: An Iterative Process for Production-Ready Applications*. O'Reilly Media, 2022.
11. Robinson, I.; Webber, J.; Eifrem, E. *Graph Databases*. O'Reilly Media, 2015.
12. Wilson, B. *Machine Learning Engineering in Action*. Manning, 2022.
13. Schwabish, J. *Better Data Visualizations: A Guide for Scholars, Researchers, and Wonks*. Columbia University Press, 2021.
