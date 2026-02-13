# 📘 LLMs_for_SPM — Replication Package for Large Language Models in Software Project Management: A Two-phase Systematic Literature Review

This repository contains all replication materials for the systematic literature review (SLR) paper titled **"Large Language Models in Software Project Management: A Two-phase Systematic Literature Review"**. It includes SPARK-based implementation code, dataset files, screening and annotations files, and scripts for computing agreements. This will help to reproduce the experiments and results presented in the paper.

## 📁 Repository Structure
```
LLMs_for_SPM/
├── Phase-I/
│   ├── Dataset/
│   ├── SLR_selected_for_data_extraction/
│   ├── SPARK_Implementation_Code/
│   ├── computing_agreements/
│   ├── evaluating_primary_studies_from_phase-I_SLR/
│   ├── manual_filtration_of_titles_and_abstracts/
│   └── quality_assessment/
├── Phase-II/
│   ├── Dataset/
│   ├── SPARK_Implementation_Code/
│   ├── computing_agreements/
│   ├── manual_screening_of_titles_and_abstracts/
│   ├── primary_studies_selected_for_data_extraction/
│   └── quality_assessment/
└── README.md
```


---

## 📦 Phase-I: Tertiary Study

The *Phase-I* materials support the **tertiary study**, including search aggregation, screening, filtration, and quality evaluation.

### 📁 Phase-I Contents

| Folder | Description |
|--------|-------------|
| `Dataset/` | Original raw search results from databases (Scopus, Web of Science, etc.) |
| `SLR_selected_for_data_extraction/` | Records selected after screening and deduplication |
| `SPARK_Implementation_Code/` | Code (Spark-based) used for parsing, filtering, and extraction |
| `computing_agreements/` | Annotator agreement calculations (e.g., Cohen’s kappa) |
| `evaluating_primary_studies_from_phase-I_SLR/` | Scripts & outputs for study scoring and relevance evaluation |
| `manual_filtration_of_titles_and_abstracts/` | Sheets/outputs from manual filtering |
| `quality_assessment/` | Files documenting the quality assessment of Phase-I candidates |

---

## 📊 Phase-II: SLR

The *Phase-II* materials enable replication of the **Systematic Literature Review**, which also includes search aggregation, screening, filtration, and quality evaluation.

### 📁 Phase-II Contents

| Folder | Description |
|--------|-------------|
| `Dataset/` | Curated dataset of primary studies |
| `SPARK_Implementation_Code/` | Code used for Phase-II SPARK implementation |
| `computing_agreements/` | Agreement scores for Phase-II annotations |
| `manual_screening_of_titles_and_abstracts/` | Screening results for Phase-II screening |
| `primary_studies_selected_for_data_extraction/` | Final set of primary studies annotated for data extraction |
| `quality_assessment/` | Detailed quality assessment documents for Phase-II |

---

## 🧠 How to Use These Materials

### 🔹 Reproducing Phase-I

1. Load raw search results from `Phase-I/Dataset/`.
2. Run the filters in `SPARK_Implementation_Code/` to dedupe and clean.
3. Use spreadsheets in `manual_filtration_of_titles_and_abstracts/` for human screening validation.
4. Compute inter-annotator agreements with `computing_agreements/`.
5. Evaluate and finalize included studies using the quality assessment workflow.

### 🔹 Reproducing Phase-II

1. Load datasets from `Phase-II/Dataset/`.
2. Recreate annotation steps using the code in `SPARK_Implementation_Code/`.
3. Validate annotations with `computing_agreements/`.
4. Follow the manuals in `manual_screening_of_titles_and_abstracts/`.
5. Extract study features and perform quality assessment using respective folders.

---

## 📝 Authors

Muhammad Saad Amin, Emilia Mendes, Adam Alami, and Ricardo Britto 
