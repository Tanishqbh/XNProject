## Northeastern University MATH 7243 - Final Project

#### Replicating the Work - Genome‑wide investigation of gene‑cancer associations for the prediction of novel therapeutic targets in oncology - https://doi.org/10.1038/s41598-020-67846-1



#### Group Members: Tanishq Bhatia, Yuyang Cao, Jieying Jin, Jundong Wang, Paul Xi, Jiaming Xu

---

## Description of files

- There are 32 dimensional features generated by applying Diff2Vec on gene interactions data, obtained from BioGRID database. 
  -  Diff2Vec: https://github.com/benedekrozemberczki/diff2vec. Since the code is outdated, modifications were applied.
  -  BioGRID: https://wiki.thebiogrid.org/doku.php/biogridrest
- There are 3 features related to genes - expression, mutation, and essentiality. Obtained from UCSC Xena portal and DepMap.
  - UCSC Xena: https://xena.ucsc.edu 
  - DepMap: https://depmap.org
- The training set was directly aquired from the repository in the literature.
  - CancerTargetPrediction Github: https://github.com/storm-therapeutics/CancerTargetPrediction
 
 ---
 
 ## Machine Learning Models Used in Ths Work
 
 - ANN (Tanishq Bhatia)
 - SVM (Jieying Jin)
 - KNN (Jiaming Xu)
 - LDA/QDA (Jundong Wang)
 - Logistic Regression (Xueqi Xue)
 - Random Forest (Yuyang Cao)

---


