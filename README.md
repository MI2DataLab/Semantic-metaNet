# SeFNet: Bridging Tabular Datasets with Semantic Feature Nets

This repository contains code and resources that can be used to reproduce the results presented in the "SeFNet: Bridging Tabular Datasets with Semantic Feature Nets".

## Reproducting results
### 0. Annotating datasets <br>
The annotation of datasets' features is a tedious process, so the annotations we made manually have been made available in the 'annotations' directory. Every annotation file is in .csv format and it consists of two columns: column_name (original feature name) and term_id (SNOMED-CT term id).

### 1. Calculating similarity between terms <br>
bla bla bla

### 2. Calculating DOSS matrix <br>
bla bla bla 

## Repository structure
```
├── annotations - directory containing datasets annotations
├── calculate-term-similarities
│   ├── src/main/java
│   │   ├── AllTermsSimilarity.java - calculate semantic similarity between all annotated terms (term_similarities.csv)
│   │   ├── Dataset2DatasetSimilarity.java - calculate semantic similarity between terms in two datasets
│   │   ├── SingleTermSimilarity.java - calculate semantic similarity between two terms
│   ├── pom.xml
├── datasets - directory containing datasets which could be shared
├── DOSS.py - python script which creates DOSS_matrix.csv
├── DOSS_matrix.csv
├── README.md
├── annotations.csv - annotations of all used terms
└── term_similarities.csv - semantic similarity between all annotated terms calculated in AllTermsSimilarity.java
```

## Citation
```
TBC
```
