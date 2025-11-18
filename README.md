# ⚗️ Delaney Solubility Prediction (ML Models)

A Machine Learning project comparing **Linear Regression** and **Random Forest** algorithms to predict the aqueous solubility of chemical compounds based on their molecular descriptors.

![Python](https://img.shields.io/badge/Python-3.x-blue)
![Scikit-Learn](https://img.shields.io/badge/Library-Scikit--Learn-orange)
![Pandas](https://img.shields.io/badge/Library-Pandas-green)

## 📖 Overview

Solubility is a critical physicochemical property in drug discovery and chemistry. This project utilizes the **Delaney Solubility with Descriptors** dataset to train and evaluate regression models. The goal is to predict the `logS` (log of aqueous solubility) value using molecular features.

## 📂 Dataset

The dataset is sourced from the [Data Professor GitHub](https://github.com/dataprofessor/data/blob/master/delaney_solubility_with_descriptors.csv).

* **Total Instances:** 1,144 rows
* **Target Variable:** `logS` (Log Solubility)

### Feature Set (X)
| Feature Name | Description |
| :--- | :--- |
| **MolLogP** | Octanol-water partition coefficient (hydrophobicity). |
| **MolWt** | Molecular Weight. |
| **NumRotatableBonds** | Number of rotatable bonds in the molecule. |
| **AromaticProportion** | Ratio of heavy atoms in aromatic rings to total heavy atoms. |

## 🛠️ Installation & Requirements

To run this notebook locally, you will need Python installed along with the following libraries:

```bash
pip install pandas scikit-learn matplotlib
