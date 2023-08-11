# Urine Test Data Analysis Project

The objective of this project is to perform an exploratory data analysis (EDA) on a dataset containing urine test samples. The data consists of cell counts for different organisms, resistance levels for various antibiotics, and the presence of certain resistance genes.

## Table of Contents

- [Dataset Description](#dataset-description)
- [Data Visualization](#data-visualization)
- [Unit Testing](#unit-testing)


## Dataset Description

Each row in the dataset represents a single urine sample and contains the following columns:

- **Cell counts** for 10 different organisms (labeled as `Organism_1` to `Organism_10`).
- **Resistance (R/S)** for 17 different antibiotics (labeled as `Antibiotic_1` to `Antibiotic_17`).
- **Presence (1) or absence (0)** of 5 different resistance genes (labeled as `Gene_1` to `Gene_5`).

## Dataset Visualization

Several visualizations have been generated for a comprehensive understanding of the dataset:

##### Antibiotic Resistance:
Stacked bar plots showing the percentage of samples resistant (R) and sensitive (S) to each antibiotic.

##### Resistance Genes Presence:
Bar plots representing the presence of each resistance gene across the samples.

##### Organism Cell Counts:
Distributions of cell counts for each organism on a logarithmic scale.

## Unit Testing
Unit tests have been written to ensure the accuracy and integrity of data manipulations. The unit tests were written and executed in the jupyter notebook for easy code review. (I'm quite aware that this against convention were unit tests are executed in python files)