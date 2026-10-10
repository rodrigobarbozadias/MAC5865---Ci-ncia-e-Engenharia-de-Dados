# MAC5865 — Ciência e Engenharia de Dados

**Português** | [English](README.en.md)

Repositório com os trabalhos desenvolvidos na disciplina **MAC5865 — Ciência e Engenharia de Dados**, do programa de pós-graduação em Ciência da Computação do Instituto de Matemática e Estatística da Universidade de São Paulo (IME-USP).

**Docente:** Prof. Dr. Roberto Hirata Junior

**Professor:** Roberto Hirata Junior

## Objetivos

Compreender fundamentos de ciência e engenharia de dados através dos tópicos abordados na disciplina, como: técnicas para manipulação, representação, análise, modelagem e validação de grandes conjuntos de dados.

## Conteúdo

A facilidade de coleta de dados alcançada pela civilização atual nos impõe um grande desafio: armazenar, representar, analisar e modelar o que usualmente é conhecido como “avalanche de dados”. A formação dos pós-graduandos em Ciência da Computação não pode dispensar o conhecimento dos referidos fundamentos e técnicas proporcionados por esta disciplina.

Tópicos abordados:

- Importância da área e de suas aplicações
- Processo de descoberta do conhecimento (KDD) em conjuntos de dados
- Tratamento, representação e qualificação de grandes volumes de dados
- Armazém de dados e modelos multidimensionais
- Indexação e recuperação de grandes volumes de dados
- Grafos em bancos de dados
- Análise exploratória de dados (análise de agrupamentos e associações de dados)
- Modelagem de conhecimento (classificadores, regras de classificação, exemplos)
- Desenvolvimento e uso de software para KDD
- Exercícios com utilização de dados simulados e reais

## Trabalhos

### EP1 — Análise Exploratória de Dados: Used Cars (Cars.com, abril de 2023)

Análise exploratória de 762.091 anúncios de veículos usados publicados na plataforma Cars.com. O trabalho cobre auditoria da qualidade dos dados, decisões de preparação documentadas, distribuição de preços, diversidade de modelos por fabricante, participação de veículos elétricos por ano-modelo, relações entre preço, ano-modelo e quilometragem, e investigação de observações incomuns.

| Arquivo | Descrição |
|---|---|
| [`EP1/Hirata_DataScienceEP1_completo_final1.ipynb`](EP1/Hirata_DataScienceEP1_completo_final1.ipynb) | Notebook com a análise completa |
| [`EP1/cars.csv.gz`](EP1/cars.csv.gz) | Dataset compactado em gzip (o CSV original tem 145 MB, acima do limite de 100 MB do GitHub) |

**Como executar:** abra o notebook no Google Colab pelo link abaixo e execute todas as células. Se o `cars.csv` não estiver na sessão, o notebook baixa e descompacta o arquivo deste repositório automaticamente.

[![Abrir no Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/rodrigobarbozadias/MAC5865---Ci-ncia-e-Engenharia-de-Dados/blob/main/EP1/Hirata_DataScienceEP1_completo_final1.ipynb)

**Integridade dos dados:** SHA-256 do `cars.csv` descompactado: `b66592aefd315e73fe84e984f92198c50707d4963a369b7c793ad21e1d455b07`

**Fonte dos dados:** [Used Cars Dataset — Andrei Novikov (Kaggle)](https://www.kaggle.com/datasets/andreinovikov/used-cars-dataset)

**Autores (Grupo 5):** Rafael Guimarães Dias · Rodrigo Barboza Dias

## Bibliografia

1. Inmon, W. H. *Building the Data Warehouse*. Wiley, 2005.
2. Kantardzic, M. *Data Mining: Concepts, Models, Methods, and Algorithms*. 3rd ed. Wiley-IEEE Press, 2019.
3. Ross, M.; Kimball, R. *The Data Warehouse Toolkit: The Definitive Guide to Dimensional Modeling*. 3rd ed. Wiley, 2013.
4. Baeza-Yates, R.; Ribeiro-Neto, B. *Modern Information Retrieval: The Concepts and Technology behind Search*. 2nd ed. ACM Press Books, 2011.
5. Snodgrass, R. T. *Developing Time-Oriented Database Applications in SQL*. Morgan Kaufmann, 2000.
6. Tan, P.-N.; Steinbach, M.; Kumar, V. *Introdução ao Data Mining*. Ciência Moderna, 2009.
7. Torgo, L. *Data Mining with R: Learning with Case Studies*. Chapman & Hall/CRC Data Mining and Knowledge Discovery Series, 2020.
8. Witten, I.; Frank, E.; Hall, M.; Pal, C. *Data Mining: Practical Machine Learning Tools and Techniques*. Morgan Kaufmann, 2016.
9. Dominich, S. *The Modern Algebra of Information Retrieval*. The Information Retrieval Series. Springer, 2010.
10. Huyen, C. *Designing Machine Learning Systems: An Iterative Process for Production-Ready Applications*. O'Reilly Media, 2022.
11. Robinson, I.; Webber, J.; Eifrem, E. *Graph Databases*. O'Reilly Media, 2015.
12. Wilson, B. *Machine Learning Engineering in Action*. Manning, 2022.
13. Schwabish, J. *Better Data Visualizations: A Guide for Scholars, Researchers, and Wonks*. Columbia University Press, 2021.
