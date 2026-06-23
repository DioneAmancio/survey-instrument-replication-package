# Replication Package

This repository contains the replication package associated with the survey study reported in the accompanying manuscript. It provides the research materials, sanitized data, qualitative coding artifacts, reliability assessment materials, statistical analysis outputs, and literature review artifacts used in the study.

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
│   ├── codebook_category_analysis.xlsx
│   └── interrater_reliability
│       ├── coding_assignments.csv
│       ├── coding_labels.csv
│       └── interrater_reliability_results.csv
├── statistical_analysis
│   ├── my_data.csv
│   ├── data_with_space_scores.csv
│   ├── seniority_results.csv
│   ├── usage_results.csv
│   ├── dunn_posthoc_all_results.csv
│   ├── dunn_posthoc_significant_results.csv
│   ├── exploratory_stratified_analysis.csv
│   ├── Script.docx
│   └── cronbach_alpha
│       ├── Cronbach Alpha.xlsx
│       └── Script.docx
├── related_work
│   └── related_work.pdf
```

---

## Artifacts Description

### Survey Data and Qualitative Analysis

The folder **survey_data/** contains the survey instrument, sanitized participant responses, and qualitative coding artifacts used in the study.

* **survey_raw_responses_and_coding.xlsx**  
  Contains the complete survey instrument and the corresponding sanitized participant responses. Sensitive or identifying information has been removed to preserve participant anonymity and confidentiality.

* **codebook_category_analysis.xlsx**  
  Contains the qualitative coding schema (codebook), category definitions, coding structure, category consolidation process, and classification analysis used during the qualitative content analysis.

---

### Inter-Rater Reliability

The folder **survey_data/interrater_reliability/** contains the materials used to assess coding agreement before the consensus meetings.

* **coding_assignments.csv**  
  Contains the independent coding assignments produced by the two researchers and used as input for the inter-rater reliability analysis.

* **coding_labels.csv**  
  Contains the mapping between code identifiers and their corresponding qualitative code descriptions.

* **interrater_reliability_results.csv**  
  Contains the inter-rater reliability statistics, including Percent Agreement, Scott’s Pi, Cohen’s Kappa, Krippendorff’s Alpha, number of agreements, and number of disagreements.

The agreement analysis was performed before the consensus meetings and yielded a Cohen’s Kappa of 0.81, indicating substantial agreement between coders.

---

### Statistical Analysis Materials

The folder **statistical_analysis/** contains the quantitative datasets, statistical outputs, and analysis scripts used in the study.

* **my_data.csv**  
  Cleaned quantitative dataset used as input for the statistical analyses.

* **data_with_space_scores.csv**  
  Dataset including the calculated SPACE composite scores used in the inferential and exploratory analyses.

* **seniority_results.csv**  
  Statistical comparison results for analyses stratified by participant seniority level.

* **usage_results.csv**  
  Statistical comparison results for analyses stratified by GenAI usage frequency.

* **dunn_posthoc_all_results.csv**  
  Complete results of Dunn’s post-hoc pairwise comparisons performed after omnibus significance testing.

* **dunn_posthoc_significant_results.csv**  
  Filtered subset containing only statistically significant Dunn’s post-hoc comparisons.

* **exploratory_stratified_analysis.csv**  
  Results of additional exploratory subgroup and stratified analyses conducted during the study.

* **Script.docx**  
  Statistical analysis script used to generate descriptive statistics, SPACE composite scores, inferential tests, and post-hoc analyses.

---

### Internal Consistency Analysis

The folder **statistical_analysis/cronbach_alpha/** contains the materials used to assess the internal consistency of the composite constructs reported in the manuscript.

* **Cronbach Alpha.xlsx**  
  Contains the survey items, participant responses, construct composition, and reliability analysis outputs used to calculate Cronbach’s alpha coefficients for the composite measures reported in the study.

* **Script.docx**  
  Contains the analysis procedure and script used to calculate Cronbach’s alpha coefficients.

The materials in this folder provide the reliability assessment for all composite constructs reported in Table 9 of the manuscript.

---

### Related Work

The folder **related_work/** contains supporting material related to the literature review conducted in this study.

* **related_work.pdf**  
  Contains the review and synthesis of prior studies on Generative AI adoption in software engineering considered during the development of this research.

---

## Ethical and Legal Statement

All participant data shared in this repository were anonymized and sanitized prior to publication.

No identifying, sensitive, or traceable participant information is included.

---

## Language Notice

The survey was conducted in Brazil with Brazilian software developers. Therefore, the original survey instrument, participant responses, coding artifacts, and qualitative materials are provided in **Portuguese**, reflecting the language used during data collection.

---

## Purpose of This Repository

This replication package is provided to:

* Support transparency in the research process
* Facilitate independent verification of the reported findings
* Provide access to qualitative coding artifacts, inter-rater reliability assessments, and quantitative analysis outputs
* Enable secondary analyses and future replications
* Promote openness and reuse of empirical software engineering research artifacts

---

## License

This repository is distributed under the terms specified in the **LICENSE** file included in this package.
