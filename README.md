# EDAB2724 Assignment 1: Bayesian Network Analysis of Shopper Purchase Intention

## Overview

This project explores the factors associated with retail shopper purchase intention using Exploratory Data Analysis (EDA) and Bayesian Networks. It was completed as part of the EDAB2724 Business and Financial Analytics module at the University of the Free State.

The project uses a retail dataset to investigate relationships between selected variables, construct and compare Directed Acyclic Graphs (DAGs), and apply probabilistic inference to understand how different conditions relate to purchase intention.

## Objectives

- Perform Exploratory Data Analysis using a correlation heatmap.
- Examine relationships between variables using Pearson correlation coefficients and p-values.
- Select nine representative variables for the Bayesian Network.
- Construct an expert-defined DAG and learn a DAG structure from data.
- Compare the two DAG structures using a suitable evaluation metric and visualisation.
- Build a Bayesian Network by learning its parameters from data.
- Perform probabilistic inference and interpret the results for different combinations of variables and purchase intention.

## Tools and Technologies

- Python
- Google Colab
- Pandas and NumPy
- SciPy
- Matplotlib and Seaborn
- NetworkX
- pgmpy

## Project Workflow

### 1. Exploratory Data Analysis

The dataset is explored to understand relationships between variables. A Pearson correlation heatmap is used to examine correlation strength, with p-values included to support statistical interpretation and variable selection.

### 2. Variable Selection

Nine variables are selected from the dataset's categories for inclusion in the Bayesian Network. The selection is justified using the heatmap and the expected insights each variable may provide.

### 3. Bayesian Network Structure Learning

Two DAG structures are developed:

- **Expert-defined DAG:** A manually designed structure based on the expected relationships between variables.
- **Data-driven DAG:** A structure learned from the dataset using a selected structure-learning technique.

The structures are compared to evaluate their similarities, differences, advantages, and limitations.

### 4. Bayesian Network Construction

The expert-defined DAG is used as the network structure, and its parameters are learned from the data to construct the Bayesian Network.

### 5. Probabilistic Inference

The completed network is used to investigate how evidence involving selected variables relates to purchase intention. Six combinations of variables are analysed, with the results interpreted in terms of their potential implications for retail decision-making.

## Key Learning Outcomes

This project develops practical skills in:

- Exploratory data analysis and data visualisation.
- Correlation analysis and statistical interpretation.
- Selecting variables for probabilistic models.
- Designing and evaluating DAG structures.
- Bayesian Network construction and parameter learning.
- Probabilistic inference and evidence-based interpretation.
- Documenting analytical workflows in Python notebooks.

## Repository Contents

- `README.md`: Project overview, objectives, methodology, and tools.
- `*.ipynb`: Google Colab notebook containing the analysis, code, visualisations, and interpretations.

## Conclusion

This project applies data analysis and probabilistic modelling techniques to investigate factors associated with retail shopper purchase intention. By combining statistical exploration, DAG structure learning, Bayesian Network construction, and inference, the analysis demonstrates how data can support a more structured understanding of shopper behaviour.
