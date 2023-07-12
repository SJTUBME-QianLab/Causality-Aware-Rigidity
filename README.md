# Causality-Aware-Rigidity

This repository holds the code for the paper

**A Causality-Aware Graph Convolutional Network Framework for Rigidity Assessment in Parkinsonians**

All the materials released in this library can ONLY be used for RESEARCH purposes and not for commercial use.

The authors' institution (Biomedical Image and Health Informatics Lab, School of Biomedical Engineering, Shanghai Jiao Tong University) preserve the copyright and all legal rights of these codes.

# Author List

Xinlu Tang, Chencheng Zhang, Rui Guo, Xinling Yang, and Xiaohua Qian\*

# Abstract

Rigidity is one of the common motor disorders in Parkinson's disease (PD), which lead to life quality deterioration. The widely-used rating-scale-based approach for rigidity assessment still depends on the availability of experienced neurologists and is limited by rating subjectivity. Given the recent successful applications of quantitative susceptibility mapping (QSM) in auxiliary PD diagnosis, automated assessment of PD rigidity can be essentially achieved through QSM analysis. However, a major challenge is the performance instability due to the confounding factors (e.g., noise and distribution shift) which conceal the truly-causal features. Therefore, we propose a causality-aware graph convolutional network (GCN) framework, where causal feature selection is combined with causal invariance to ensure that causality-informed model decisions are reached. Firstly, a GCN model that integrates causal feature selection is systematically constructed at three graph levels: node, structure, and representation. In this model, a causal diagram is learned to extract a subgraph with truly-causal information. Secondly, a non-causal perturbation strategy is developed along with an invariance constraint to ensure the stability of the assessment results under different distributions, and thus avoid spurious correlations caused by distribution shifts. The superiority of the proposed method is shown by extensive experiments and the clinical value is revealed by the direct relevance of selected brain regions to rigidity in PD. Besides, its extensibility is verified on other two tasks: PD bradykinesia and mental state for Alzheimer's disease. Overall, we provide a clinically-potential tool for automated and stable assessment of PD rigidity. Our source code will be available at https://github.com/SJTUBME-QianLab/Causality-Aware-Rigidity.

