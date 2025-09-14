# NSAID Hepatotoxicity Analysis: Unsupervised Chemoinformatics Approach

An exploratory analysis of hepatotoxicity patterns in Non-Steroidal Anti-Inflammatory Drugs (NSAIDs) using unsupervised machine learning methods.

---

## Overview
This project analyzes **30 NSAIDs** from the **FDA DILIst database** using molecular descriptors and fingerprints.  
Due to extreme class imbalance (**96.7% hepatotoxic vs 3.3% non-hepatotoxic**), we applied unsupervised methods including **PCA**, **t-SNE**, and **k-means clustering**.

---

## Key Finding
Non-hepatotoxic NSAIDs cluster with hepatotoxic compounds rather than forming separate groups, suggesting that **gross structural features alone do not determine hepatotoxicity** within the NSAID class.

---


---

## Results Summary

- **Dataset:** 30 NSAIDs (29 hepatotoxic, 1 non-hepatotoxic)  
- **PCA:** First 2 components explain **33.6%** of variance  
- **Clustering:** Optimal **k=2 clusters** (silhouette score = **0.318**)  
- **Molecular Features:** LogP, TPSA, HBD, HBA, MW + **1024-bit Morgan fingerprints**




## Limitations

- Small dataset (n=30)
- Extreme class imbalance
- Single non-hepatotoxic compound
- Exploratory analysis only

Contact
Favour Igwezeke - beingfave@gmail.com
University of Nigeria
