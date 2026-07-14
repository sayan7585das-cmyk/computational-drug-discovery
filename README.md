# 🧬 Alzheimer's Virtual Screening Pipeline

> An integrated computational drug discovery workflow for virtual screening of natural compounds against Alzheimer's disease using molecular docking, Python-based data analysis, and pharmacokinetic prediction.

![Python](https://img.shields.io/badge/Python-3.10+-blue)
![Bioinformatics](https://img.shields.io/badge/Bioinformatics-Computational-green)
![AutoDock Vina](https://img.shields.io/badge/Molecular%20Docking-AutoDock%20Vina-orange)
![License](https://img.shields.io/badge/License-MIT-yellow)

---

## 📖 Project Overview

Alzheimer's disease (AD) is a progressive neurodegenerative disorder and one of the leading causes of dementia worldwide. Acetylcholinesterase (AChE) is an established therapeutic target for symptomatic treatment of AD.

This project presents an **integrated computational pipeline** to identify and prioritize natural compounds with potential inhibitory activity against human acetylcholinesterase (PDB ID: **4EY7**). The workflow combines molecular docking, cheminformatics, Python-based data analysis, drug-likeness evaluation, and ADMET prediction to support early-stage lead identification.

> **Note:** This study is entirely computational. The results represent in silico predictions and require experimental validation.

---

## 🎯 Objectives

- Perform virtual screening of natural compounds against human AChE.
- Predict protein–ligand binding affinity using AutoDock Vina.
- Analyze molecular descriptors with Python.
- Evaluate drug-likeness using Lipinski's Rule of Five.
- Predict pharmacokinetic properties using SwissADME.
- Prioritize promising lead compounds for future investigation.

---

## 🔬 Workflow

```
Literature Survey
        │
        ▼
Ligand Selection (41 Natural Compounds)
        │
        ▼
Protein Preparation (PDB: 4EY7)
        │
        ▼
Molecular Docking (AutoDock Vina)
        │
        ▼
Python Data Analysis
        │
        ├── Molecular Descriptors
        ├── Statistical Analysis
        ├── Data Visualization
        ▼
Protein–Ligand Interaction Analysis
        │
        ▼
Lipinski Rule of Five
        │
        ▼
SwissADME Prediction
        │
        ▼
Lead Compound Prioritization
```

---

## 🛠 Tools & Technologies

| Category | Software / Library |
|-----------|--------------------|
| Programming | Python |
| Environment | Google Colab |
| Molecular Docking | AutoDock Vina |
| Docking GUI | PyRx |
| Cheminformatics | RDKit |
| Data Retrieval | PubChemPy |
| Data Analysis | Pandas, NumPy |
| Visualization | Matplotlib |
| Interaction Analysis | BIOVIA Discovery Studio |
| ADMET Prediction | SwissADME |

---

## 📊 Project Highlights

- Screened **41 natural compounds** against human acetylcholinesterase.
- Used **Donepezil** as the reference inhibitor.
- Integrated molecular docking with Python-based statistical analysis.
- Evaluated molecular descriptors and physicochemical properties.
- Predicted pharmacokinetic profiles using SwissADME.
- Prioritized lead compounds based on multiple computational criteria.

---

## 🏆 Key Findings

- **Epigallocatechin Gallate (EGCG)** showed the strongest predicted binding affinity in docking simulations.
- **Demethoxycurcumin**, **Curcumin**, and **Bisdemethoxycurcumin** demonstrated favorable docking scores with comparatively balanced predicted drug-like properties.
- Integrating docking with molecular descriptors and pharmacokinetic prediction provided a more comprehensive framework for lead prioritization.


---

## 📈 Data Analysis

The Python workflow includes:

- Data preprocessing
- Molecular descriptor retrieval
- Descriptive statistics
- Correlation analysis
- Exploratory Data Analysis (EDA)
- Publication-quality visualizations

---

## 📌 Future Improvements

- Molecular Dynamics (MD) simulations
- MM/PBSA or MM/GBSA binding free-energy calculations
- Machine learning-based virtual screening
- Expanded natural product library
- Experimental validation (in vitro and in vivo)

---

## 📚 References

Key databases and tools:

- Protein Data Bank (PDB)
- PubChem
- AutoDock Vina
- SwissADME
- BIOVIA Discovery Studio

Complete references are available in the project report.

---

## ⚠ Disclaimer

This project is intended for educational and research purposes only. All findings are based on computational predictions and should not be interpreted as evidence of biological activity or therapeutic efficacy without experimental validation.

---

## 👨‍💻 Author

**Sayan Das**

Computational Biology • Bioinformatics • Molecular Docking • Python • Data Analysis

- GitHub: https://github.com/sayan7585das-cmyk/sayan7585das-cmyk
- LinkedIn: www.linkedin.com/in/sayan-das-19660340a
  

---

⭐ **If you found this project interesting, consider giving the repository a star!**
