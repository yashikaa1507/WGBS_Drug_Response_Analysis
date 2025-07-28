# WGBS_Drug_Response_Analysis
Whole Genome Bisulfite Sequencing pipeline on cancer drug response samples using Galaxy
# 🧬 WGBS-Based Epigenetic Analysis of Drug Response in Cancer Samples

This project demonstrates a complete **Whole Genome Bisulfite Sequencing (WGBS)** analysis pipeline using the **Galaxy platform**, focused on exploring DNA methylation differences between drug-treated and control cancer samples.

---

## 📁 Project Overview

- **Objective**: Identify genome-wide methylation changes in response to drug treatment using WGBS data.
- **Platform**: [Galaxy](https://usegalaxy.org)
- **Techniques**: QC, adapter trimming, alignment (Bismark), methylation extraction, differential methylation analysis.

---

## 🔧 Tools & Workflow Summary

| Step | Tool | Purpose |
|------|------|---------|
| 1️⃣ | **FastQC** | Quality control check of raw FASTQ files |
| 2️⃣ | **Cutadapt** | Trim adapters and low-quality bases |
| 3️⃣ | **Bismark** | Align bisulfite reads to reference genome |
| 4️⃣ | **Bismark Methylation Extractor** | Extract methylation calls |
| 5️⃣ | **Filter & Format** | Prepare data for comparison |
| 6️⃣ | **Differential Methylation Analysis** | Identify DMRs between control and treated groups |
| 7️⃣ | **Visualization** | Heatmaps, genome browser, and summary plots |

---

## 🔬 Dataset

- **Source**: [NCBI GEO / ENA / Zenodo]  
- **Samples**: 2 control and 2 drug-treated cancer WGBS datasets  
- **Reference Genome**: `wildtype.fna`

---

## 🧠 Key Results

- Identified **~1200 DMRs** (Differentially Methylated Regions)
- **Hypomethylation** observed in tumor suppressor gene promoters
- Chromosome 3 showed significant hypermethylation in treated samples

---

## 📊 Visualizations

- Heatmaps of methylation levels across samples
- Gene annotation plots for DMRs
- Bar chart of CpG site coverage

> 📸 Add screenshots of Galaxy steps or plots if possible

---

## 💡 Conclusion

This WGBS pipeline reveals methylation-based epigenetic changes due to drug treatment. The workflow is reproducible using open-source Galaxy tools and demonstrates bioinformatics approaches for precision medicine research.

---



