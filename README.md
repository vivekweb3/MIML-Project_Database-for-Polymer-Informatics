# MLMI: Machine Learning-Assisted Exploration of Thermally Conductive Polymers

This project is built as part of an academic exploration into **machine learning-driven materials informatics**. It uses publicly available data from the **PI1M** benchmark database to analyze and predict the thermal conductivity of polymer materials using high-throughput molecular dynamics simulation data and ML models.

---

## 📘 Overview

In recent years, *machine learning-assisted molecular dynamics* (ML-MD) has emerged as a powerful approach to accelerate materials discovery.  
This project reproduces and extends concepts from the research article:

> **Machine Learning-Assisted Exploration of Thermally Conductive Polymers Based on High-Throughput Molecular Dynamics Simulations**  
> *Ruimin Ma and Tengfei Luo, Journal of Chemical Information and Modeling, 2021.*

We utilize the **PI1M dataset**, a large-scale benchmark for polymer informatics, to train and test models for predicting polymer properties such as:
- Density  
- Glass transition temperature (Tg)  
- Melting temperature (Tm)  
- Dielectric constant  
- Synthetic accessibility (SA) score  

---

## 🧠 Objective

The goal of this project is to:
1. Understand how machine learning can be applied to polymer informatics.
2. Implement regression models for predicting key polymer properties.
3. Explore how high-throughput molecular dynamics data can assist in materials design.

---

## 📊 Dataset

### Source
The dataset used in this project is derived from the **[PI1M database](https://github.com/RUIMINMA1996/PI1M)**, which contains approximately **1 million polymer structures** represented in p-SMILES format.

### Format
- **File:** `PI1M_v2.csv`  
- **Columns:** polymer p-SMILES, property values (density, Tg, Tm, dielectric constant), and SA score.

The synthetic accessibility score (SA) is computed using Schuffenhauer’s heuristic scoring approach  
([Reference Paper](https://jcheminf.biomedcentral.com/articles/10.1186/1758-2946-1-8)).

---

## 🧩 Methodology

- **Data Preprocessing:** Cleaning and encoding polymer structures.  
- **Feature Extraction:** Using polymer embedding representations (PE).  
- **Model Training:** Applying regression models (e.g., Random Forest, Gradient Boosting, Neural Networks).  
- **Evaluation:** Comparing predictions for accuracy and interpretability.

---

## 📈 Results

Our analysis reproduces and extends trends reported in the original PI1M study. The ML models successfully predict thermal and structural polymer properties, demonstrating the potential of data-driven polymer design.

---

## 🧪 Tools & Technologies

- Python (NumPy, Pandas, Scikit-learn, Matplotlib)
- Jupyter Notebooks
- Molecular Dynamics data (from original research)
- GitHub for version control

---

## 📚 Reference

If this dataset or research concept benefits your academic or research work, please cite the original publication:

> Ruimin Ma, Tengfei Luo.  
> *PI1M: A Benchmark Database for Polymer Informatics.*  
> Journal of Chemical Information and Modeling (2021).  
> [DOI: 10.1021/acs.jcim.0c00726](https://pubs.acs.org/doi/10.1021/acs.jcim.0c00726)

---

## ⚠️ Note

This repository is for **academic and educational purposes only**.  
All original data and concepts belong to the respective authors of the PI1M database and publication.  
This work extends their dataset for learning and demonstration under fair-use for research.

---

## 👨‍💻 Author

**Vivek Kumar**  
B.Tech, NIT Warangal  
Branch: Biotechnology
RollNumber: 21BTB0A81

**Harsh Hotala
B.tech, NIT Warangal
Branch: Electrical Engineering 
RollNumber: 22EEB0A64

Project: *Machine Learning-Assisted Materials Informatics (MLMI)*  
Year: 2025
