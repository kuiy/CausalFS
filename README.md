# CausalFS: An open-source package of causal feature selection and causal (Bayesian network) structure learning (C++ version)

The CausalFS package provides a comprehensive open-source library for use in C/C++ that implements the state-of-the-art local causal structure learning approaches to feature selection and was developed in Linux systems. The package is designed to facilitate the development of new algorithms in this exciting research direction and make it easy to compare new feature selection methods and existing ones.

The CausalFS package implements 28 representative local causal structure learning methods for feature selection. Specifically, it consists of 24 methods using conditional independence tests (i.e., 16 single Markov boundary (MB) learning algorithms, 2 multiple MB learning algorithms, and 6 PC (parents and children) learning algorithms), and 4 score-based MB and PC learning approaches. 

Constraint-based MB learning methods:

GSMB, IAMB, Inter-IAMB, Fast-IAMB, LRH, BAMB, EEMB, FBED,
MMMB, PCMB, HITON-MB, Semi-HITON-MB, IPCMB, STMB, CCMB

Multiple MB learning methods:

KIAMB, TIE*

Constraint-based PC learning methods:

PC-simple, MBtoPC, HITON-PC, Semi-HITON-PC, GetPC, MMPC

score-based MB learning methods:

SLL, S^2TMB

score-based PC learning methods:

SLL-PC, S^2TMB-PC

Furthermore, by applying the MB and PC learning algorithms, using the CausalFS package, users can easily generate different local-to-global structure learning methods. Then the CausalFS toolbox not only supports feature selection for supervised classification, but also is able to do local-to-global BN structure learning. For example, using the MMMB algorithm, we can generate MMMB based local-to-global structure learning algorithm. 

All implementation details please read the manual documentation. 


References for citation:

-Kui Yu, Xianjie Guo, Lin Liu, Jiuyong Li, Hao Wang, Zhaolong Ling, and Xindong Wu. Causality-based Feature Selection: Methods and Evaluations. ACM Computing Surveys (CSUR) 53, no. 5 (2020): 1-36.

-Kui Yu, Lin Liu, and Jiuyong Li. A unified View of Causal and Non-causal Feature Selection. ACM Transactions on Knowledge Discovery from Data, in press (2020).
