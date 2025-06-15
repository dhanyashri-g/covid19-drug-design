# 🧪 Computational Identification of Small Molecule Therapeutics for COVID-19: A Phytochemical and Systems Biology Approach

This repository contains the complete analysis pipeline and results from research project focused on **identifying small molecule antiviral compounds against COVID-19** through phytochemical screening, gene expression prediction, enrichment, druglikeness evaluation, and PPI network analysis.

---

## 📁 Repository Details

**Title**: System Design Analysis - Computational Identification of Small Molecule Therapeutics for COVID-19  
**Author**: Dhanyashri A/P Guruparan  
**Institution**: Management & Science University (MSU), Malaysia  
**Degree**: Bachelor of Bioinformatics (Hons)  
**Year**: 2024    
**Keywords**: covid-19, small-molecules, antiviral, gene-expression, enrichment-analysis, phytochemicals, digep, swissadme, PPI, drug-targets

---

## 🎯 Objectives

- Identify phytochemical compounds with potential antiviral activity against SARS-CoV-2.
- Predict compound-induced gene expression changes using DIGEP-Pred.
- Evaluate overlap between predicted gene sets and known COVID-19-associated genes.
- Assess druglikeness of phytochemicals using SwissADME.
- Perform enrichment and ontology analysis on regulated genes.
- Build protein–protein interaction (PPI) networks and identify top regulatory proteins.
- Validate key genes via virus-host interaction and COVID-19-specific gene set databases.

---

## 🧪 Tools & Databases Used

| Tool / Database | Purpose |
|------------------|---------|
| **SMACC** | Phytochemical compound sourcing |
| **DIGEP-Pred** | Gene expression prediction from SMILES |
| **CTD** | COVID-19-associated gene sets |
| **SwissADME** | Druglikeness screening |
| **Enrichr** | Enrichment analysis (KEGG, GO) |
| **STRING + Cytoscape** | PPI network construction |
| **CytoHubba** | Hub gene identification |
| **P-HIPSTer (Virus-Host PPI)** | Validation of viral gene interactions |

---

## 📌 Highlights

### 🧬 Gene Expression Analysis

- **Total regulated genes**: 55  
  - Upregulated: 40  
  - Downregulated: 17  
- **Overlap with COVID-19 gene set (CTD)**: 53 genes  
- Top biological functions: Immune response, metabolism, apoptosis, oxidative stress, and signal transduction.

---

### 💊 Druglikeness Screening

Out of 35 SMILES entries screened via SwissADME:
- Only **3 passed all druglikeness criteria**:
  - **CHEMBL1324**
  - **CHEMBL1458891**
  - **CHEMBL3818159**

---

### 🧠 Enrichment & Ontology Findings

- **KEGG**: Lipid metabolism, coagulation cascades, inflammation.
- **GO:BP**: Coagulation, immune regulation, vascular remodeling.
- **GO:CC**: Platelet granules, ECM, fibrinolysis.
- **GO:MF**: Enzyme activity, receptor binding.

---

### 🔗 PPI Network & Hub Genes

Top 10 ranked proteins:  
`CTNNB1, REN, LEP, CCL2, TIMP1, ADIPOQ, HMOX1, NFE2L2, PLAU, PLAT`  
- **PLAU** and **ADIPOQ** passed druglikeness analysis and overlap with viral host interaction datasets.

---

## ✅ Conclusion

This pipeline identified **PLAU** and **ADIPOQ** as highly promising small molecule antiviral targets in COVID-19. Their key roles in inflammation, coagulation, and metabolism make them attractive candidates for further **structure-based drug development**.

---

📜 License
This project is licensed under the MIT License. It is freely available for academic and research use only. Attribution to the author and MSU is required in derivative works.

---

| This work is original and solely belongs to the author (Dhanyashri) and MSU. All materials and results are intended for academic and non-commercial research purposes only.
