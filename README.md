#  SMVSSN
---

## 📂 Table of Contents

- [Dataset](#Dataset)
- [Requirement](#Requirement)
- [Usage](#Usage)


---

## Dataset

The folder 'table' contains the data. It has 9 tables:

1.The eight mat files under the 8anti_mat folder represent the data used in the comparison experiments

2.The 1000.xlsx file is the data used in the new Comparison Experiments section


## Requirement
- numpy (==1.24.3)
- pytorch (==2.3.1)
- spikingjelly
- scikit-learn (==1.4.2)

## Usage
*Example Usage*
Unzip it to see all the .py files
```
    python friendman.py
    python multiview_classification.py
    python ML_Comparison.py 
```
What starts with multi is basically SMVSSN's test and training code, which includes the intermediate products of many iterations of.

The code for the comparison algorithms can be found by using the abbreviations in the corresponding files.
