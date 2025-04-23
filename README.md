#  SMVSSN
---

## 📂 Table of Contents

- [Dataset](#Dataset)
- [Requirement](#Requirement)


---

## ⚙️ Dataset

Event.db contains the data we compiled from DrugBank 5.1.3 verision. It has 4 tables:
1.drug contains 572 kinds of drugs and their features.
2.event contains the 37264 DDIs between the 572 kinds of drugs.
3.extraction is the process result of NLPProcess. Each interaction is transformed to a tuple: {mechanism, action, drugA, drugB}
4.event_numer lists the kinds of DDI events and their occurence frequency.

