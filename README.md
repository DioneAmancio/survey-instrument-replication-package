# Replication Package

This repository contains the replication package associated with the survey study reported in the accompanying manuscript. It provides the research materials, sanitized data, coding artifacts, and statistical analysis outputs used to support the findings presented in the paper.

---

## Associated Paper

A persistent link to the accepted/final version of the paper will be added upon publication.

---

## Repository Structure

```text
├── LICENSE
├── README.md
├── survey_data
│   ├── survey_raw_responses_and_coding.xlsx
│   └── codebook_category_analysis.xlsx
├── statistical_analysis
│   ├── my_data.csv
│   ├── seniority_results.csv
│   ├── usage_results.csv
│   ├── dunn_posthoc_all_results.csv
│   ├── dunn_posthoc_significant_results.csv
│   ├── exploratory_stratified_analysis.csv
│   └── exploratory_stratified_comparisons.png
├── figures
│   └── comparison_related_work.png
```

---

## Artifacts Description

### Survey Data and Qualitative Analysis

The folder **survey_data/** contains the survey instrument, sanitized participant responses, and qualitative coding artifacts used in the study.

* **survey_raw_responses_and_coding.xlsx**
  Contains the complete survey instrument and the corresponding sanitized participant responses. Sensitive or identifying information has been removed to preserve participant anonymity and confidentiality.

* **codebook_category_analysis.xlsx**
  Contains the qualitative coding schema (codebook), category definitions, coding structure, and classification analysis used during the qualitative content analysis process.

---

### Statistical Analysis Materials

The folder **statistical_analysis/** contains the quantitative datasets and statistical outputs used in the inferential and exploratory analyses reported in the manuscript.

* **my_data.csv**
  Cleaned quantitative dataset used as input for the statistical analyses.

* **seniority_results.csv**
  Statistical comparison results for analyses stratified by participant seniority level.

* **usage_results.csv**
  Statistical comparison results for analyses stratified by GenAI usage frequency.

* **dunn_posthoc_all_results.csv**
  Complete results of Dunn’s post-hoc pairwise comparisons performed after omnibus significance testing.

* **dunn_posthoc_significant_results.csv**
  Filtered subset of statistically significant Dunn’s post-hoc comparisons.

* **exploratory_stratified_analysis.csv**
  Results of additional exploratory subgroup and stratified analyses conducted during the study.

* **exploratory_stratified_comparisons.png**
  Visual representation of the exploratory stratified comparisons of composite scores derived from SPACE items, summarizing subgroup differences identified in the quantitative analysis.

---

### Figures and Comparative Analysis

The folder **figures/** contains visual artifacts supporting the comparative analysis between our findings and prior related work.

* **comparison_related_work.png**
  Comparative synthesis of perceived benefits and concerns related to GenAI adoption across our study and prior related work.

---

## Ethical and Legal Statement

All participant data shared in this repository were anonymized and sanitized prior to publication.

No identifying, sensitive, or traceable participant information is included.

---

## Language Notice

The survey was conducted in Brazil with Brazilian software developers. Therefore, the original survey instrument, participant responses, and qualitative materials are provided in **Portuguese**, reflecting the language used during data collection.

---

## Purpose of This Repository

This replication package is provided to:

* Support transparency in the research process
* Facilitate independent verification of the reported findings
* Enable secondary analyses and future replications
* Promote openness and reuse of empirical software engineering research artifacts

---

## License

This repository is distributed under the terms specified in the **LICENSE** file included in this package.
