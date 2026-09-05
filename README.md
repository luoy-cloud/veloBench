# Benchmarking RNA velocity methods across 17 independent studies

In this benchmarking study, we tested 15 RNA velocity methods in 17 published datasets, conducting a comprehensive performance evaluation in the dimensions of inference accuracy, algorithm stability, and computational efficiency.For performance evaluation, we used four metrics. Cross-boundary direction correctness (CBDir), intra-cluster coherence (ICCoh), and velocity consistency measure the correctness and coherence of inference at cell level by each method. Then, method agreement A1 & A2 measure the consistency of inference among different methods. We systematically benchmarked the performance of 15 RNA velocity methods in all 17 datasets. In addition, we conducted cellular down-sampling experiments on four representative datasets, selected varying numbers of highly variable genes during preprocessing, and generated simulated datasets covering three distinct developmental topologies to evaluate the stability of these methods. 

![pipeline](https://github.com/luoy-cloud/veloBench/blob/main/pipeline.png) 


## Citation
---
Ya Luo, Jun Ren, Qian Yang, Ying Zhou, Zhiyu You, Qingqing Qin, Qiyuan Li. *Benchmarking RNA velocity methods across 17 independent studies*. *Cell Reports Methods* 6, 101367 (2026). [DOI: 10.1016/j.crmeth.2026.101367](https://doi.org/10.1016/j.crmeth.2026.101367)
