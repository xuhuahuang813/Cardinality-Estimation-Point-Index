# Cardinality-Estimation-Point-Index

[TOC]

:sunflower:This repository collects a set of papers on cardinality estimation, with key ideas distilled for my own learning and writing. While primarily intended for personal study, I hope it also proves helpful for your work in this area. Please feel free to use anything you find helpful.

### Traditional CardEst

#### Histogram

1. [Equi-Depth Histograms For Estimating Selectivity Factors For Multi-Dimensional Queries](https://dl.acm.org/doi/pdf/10.1145/971701.50205) [None 87]
2. [Optimal Histograms for Limiting Worst-Case Error Propagation in the Size of Join Results](https://dl.acm.org/doi/pdf/10.1145/169725.169708) [ACM Transactions on Database Systems 93]
3. [Improved histograms for selectivity estimation of range predicates](https://dl.acm.org/doi/pdf/10.1145/233269.233342)[SIGMOD 96]
4. [Selectivity Estimation Without the  Attribute Value Independence Assumption](https://www.madgik.di.uoa.gr/sites/default/files/2018-06/vldb97_pp486-495.pdf) (**MHIST**) [SIGMOD 97]
5. [On Rectangular Partitionings in Two Dimensions: Algorithms, Complexity, and Applications](https://link.springer.com/chapter/10.1007/3-540-49257-7_16) [ICDT 99]
6. [Approximating multi-dimensional aggregate range queries over real attributes](https://dl.acm.org/doi/pdf/10.1145/335191.335448) (**GENHIST**) [SIGMOD 00]
7. [Independence is good: Dependency-based histogram synopses for high-dimensional data](https://dl.acm.org/doi/pdf/10.1145/376284.375685) (**DBHist**) [SIGMOD 01]
8. [STHoles: a multidimensional workload-aware histogram](http://www.cs.columbia.edu/~gravano/Papers/2001/sigmod01b.pdf) (**STHoles**)[SIGMOD 01]
9. [Selectivity Estimation using Probabilistic Models](https://dl.acm.org/doi/pdf/10.1145/375663.375727)[SIGMOD 01]
10. [A multi-dimensional histogram for selectivity estimation and fast approximate query answering](https://dl.acm.org/doi/pdf/10.5555/961322.961374) [CASCON 03]
11. [The history of histograms (abridged)](https://www.vldb.org/conf/2003/papers/S02P01.pdf) [VLDB 03]
12. [SASH: A Self-Adaptive Histogram Set for Dynamically Changing Workloads](https://www.ittc.ku.edu/~jsv/Papers/LWV03.sash.pdf)(**SASH**)[VLDB 03]
13. [Selectivity estimators for multidimensional range queries over real attributes](https://cs.gmu.edu/~carlotta/publications/vldb090.pdf) (**GENHIST**) [VLDB 03]
14. [ISOMER: Consistent histogram construction using query feedback](https://citeseerx.ist.psu.edu/document?repid=rep1&type=pdf&doi=55708905fb9ecd1ffa2f41638410f672147ccdaa) (**ISOMER**)[ICDE 06]
15. [Join Over Histograms](http://www.adellera.it/static_html/investigations/join_over_histograms/JoinOverHistograms.pdf) [Alberto Dell'Era 07]
16. [Consistent Histograms In The Presence of Distinct Value Counts](https://dl.acm.org/doi/pdf/10.14778/1687627.1687723) [VLDB 08]
17. [Lightweight Graphical Models for Selectivity Estimation Without Independence Assumptions](https://dl.acm.org/doi/pdf/10.14778/3402707.3402724) [VLDB 11]
18. [Efficiently adapting graphical models for selectivity estimation](https://www.cl.cam.ac.uk/~ey204/teaching/ACS/R244_2020_2021/papers/tzoumas_VLDB_2013.pdf) [VLDB 13]
19. [Improving Accuracy and Robustness of Self-Tuning Histograms by Subspace Clustering](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=7067401) [TKDE 15]

#### Sampling

1. [Two-Level Sampling for Join Size Estimation](https://15721.courses.cs.cmu.edu/spring2023/papers/18-costmodels/p759-chen.pdf) [SIGMOD 17]
2. [Combining Aggregation and Sampling (Nearly) Optimally for Approximate Query Processing](https://arxiv.org/pdf/2103.15994.pdf) [SIGMOD 21]

#### Others

1. [Access path selection in a relational database management system](https://courses.cs.duke.edu/compsci516/cps216/spring03/papers/selinger-etal-1979.pdf) [SIGMOD 79]
2. [Plan Bouquets: Query Processing without Selectivity Estimation](https://dsl.cds.iisc.ac.in/~course/DBMS/papers/planBouquet.pdf) [SIGMOD 14]
3. [Exact Cardinality Query Optimization with Bounded Execution Cost](https://dl.acm.org/doi/pdf/10.1145/3299869.3300087) [SIGMOD 19]
4. [JoinSketch: A Sketch Algorithm for Accurate and Unbiased Inner-Product Estimation](https://yangtonghome.github.io/uploads/JoinSketch_2023.pdf) [SIGMOD 23]
5. [Efficient and Effective Cardinality Estimation for Skyline Family](https://dl.acm.org/doi/abs/10.1145/3588958) [SIGMOD 23]
6. [Cardinality Estimation for Having-Clauses](https://www.vldb.org/pvldb/vol18/p28-moerkotte.pdf) [VLDB 25]
7. [Faper: Join Tree with Uncertainty Awareness for Faster, More Precise and Robust Cardinality Estimation](https://link.springer.com/chapter/10.1007/978-981-96-8170-9_33) [PAKDD 25]

#### Survey

1. [Synopses for Massive Data: Samples, Histograms, Wavelets, Sketches](https://dsf.berkeley.edu/cs286/papers/synopses-fntdb2012.pdf) [A detailed book published in 2012]
2. [Preventing bad plans by bounding the impact of cardinality estimation errors](https://citeseerx.ist.psu.edu/document?repid=rep1&type=pdf&doi=986d26dd8fa2355e9356ab2740b76e691cb22a15) [VLDB 09]
3. [Analyzing the Impact of Cardinality Estimation on Execution Plans in Microsof SQL Server](https://www.vldb.org/pvldb/vol16/p2871-dutt.pdf) [VLDB 23]

#### Special Case

1. [Selectivity Estimation for Queries Containing Predicates over Set-Valued Attributes](https://dl.acm.org/doi/pdf/10.1145/3626755) [SIGMOD 24]



### Machine Learning

1. [Self-Tuning, GPU-Accelerated Kernel Density Models for Multidimensional Selectivity Estimation](https://dl.acm.org/doi/pdf/10.1145/2723372.2749438) [SIGMOD 15]
2. [Estimating Join Selectivities using  Bandwidth-Optimized Kernel Density Models](https://www.vldb.org/pvldb/vol10/p2085-kiefer.pdf) [VLDB 17]
3. [QuickSel: Quick Selectivity Learning  with Mixture Models](https://dl.acm.org/doi/pdf/10.1145/3318464.3389727) [SIGMOD 20]
4. [LHist: Towards Learning Multidimensional Histogram for Massive Spatial Data](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9458896) [ICDE 21]



### Learned  CardEst

#### Query-Driven

##### Single-Table

1. [Selectivity estimation for range predicates using lightweight models](http://www.vldb.org/pvldb/vol12/p1044-dutt.pdf) [VLDB 19]
2. [Deep learning models for selectivity estimation of multiattribute queries](https://dl.acm.org/doi/abs/10.1145/3318464.3389741) [SIGMOD 20]

##### Multi-Tables

1. [Towards a Learning Optimizer for Shared Clouds](https://www.vldb.org/pvldb/vol12/p210-wu.pdf) [VLDB 18]
2. [Learned Cardinalities: Estimating Correlated Joins with Deep Learning](https://arxiv.org/pdf/1809.00677.pdf) [CIDR 2019]
3. [An End-to-End Learning-based Cost Estimator](http://www.vldb.org/VLDB/vol13/p307-sun.pdf) [VLDB 19] [![](https://img.shields.io/github/stars/greatji/Learning-based-cost-estimator?style=social&label=Code+Stars)](https://github.com/greatji/Learning-based-cost-estimator)
4. [Flow-Loss: Learning Cardinality Estimates That Matter](https://people.csail.mit.edu/tatbul/publications/flowloss_vldb21.pdf) [VLDB 21]  
5. [Warper: Efficiently Adapting Learned Cardinality Estimators to Data and Workload Drifts](https://yao.lu/warper.pdf) [SIGMOD 22]  
6. [Selectivity Functions of Range Queries are Learnable](https://dl.acm.org/doi/pdf/10.1145/3514221.3517896)[SIGMOD 22] [![](https://img.shields.io/github/stars/huxiao2010/Selectivity?style=social&label=Code+Stars)](https://github.com/huxiao2010/Selectivity)
7. [Speeding Up End-to-end Query Execution via Learning-based Progressive Cardinality Estimation](https://www4.comp.polyu.edu.hk/~csmlyiu/conf/SIGMOD23_LPCE.pdf) [SIGMOD 23] [![](https://img.shields.io/github/stars/Eilowangfang/LPCE?style=social&label=Code+Stars)](https://github.com/Eilowangfang/LPCE)  
8. [Robust Query Driven Cardinality Estimation under Changing Workloads](https://www.vldb.org/pvldb/vol16/p1520-negi.pdf)[[VLDB 23](https://github.com/learnedsystems/CEB)]  
9. [Enhanced Featurization of Queries with Mixed Combinations of Predicates for ML-based Cardinality Estimation](https://openproceedings.org/2023/conf/edbt/paper-1.pdf) [EDBT 23]  
10. [AutoCE: An Accurate and Efficient Model Advisor for Learned Cardinality Estimation](https://dbgroup.cs.tsinghua.edu.cn/ligl/papers/AutoCE_camera_ready_ICDE2023.pdf) [ICDE 23]  
11. [Asm: Harmonizing autoregressive model, sampling, and multi-dimensional statistics merging for cardinality estimation](https://dl.acm.org/doi/pdf/10.1145/3639300) [SIGMOD 24]  
12. [Adding Domain Knowledge to Query-Driven Learned Databases](https://arxiv.org/pdf/2312.01025) [arXiv 24]  
13. [Sample-Efficient Cardinality Estimation Using Geometric Deep Learning](https://dl.acm.org/doi/10.14778/3636218.3636229) [VLDB 24] 
14. [A Practical Theory of Generalization in Selectivity Learning](https://arxiv.org/pdf/2409.07014) [VLDB 25]

#### Data-Driven

##### Single-Table

1. [Self-tuning, gpu-accelerated kernel density models for multidimensional selectivity estimation](https://dl.acm.org/doi/10.1145/2723372.2749438) [SIGMOD 15]
2. [Deep Unsupervised Cardinality Estimation](http://www.vldb.org/VLDB/vol13/p279-yang.pdf) [VLDB 19] [![](https://img.shields.io/github/stars/naru-project/naru?style=social&label=Code+Stars)](https://github.com/naru-project/naru)
3. [Quicksel: Quick selectivity learning with mixture models](https://arxiv.org/pdf/1812.10568.pdf) [SIGMOD 20]  [![](https://img.shields.io/github/stars/illinoisdata/quicksel?style=social&label=Code+Stars)](https://github.com/illinoisdata/quicksel) 
4. [Pre-training Summarization Models of Structured Datasets for Cardinality Estimation](http://yao.lu/iris.pdf) [VLDB 22] [![](https://img.shields.io/github/stars/tjluyao/iris_demo?style=social&label=Code+Stars)]( https://github.com/tjluyao/iris_demo) 

##### Multi-Tables

1. [DeepDB: Learn from Data, not from Queries!](https://dl.acm.org/doi/pdf/10.14778/3384345.3384349) [VLDB 20] [![](https://img.shields.io/github/stars/DataManagementLab/deepdb-public?style=social&label=Code+Stars)](https://github.com/DataManagementLab/deepdb-public) 
2. [NeuroCard: One Cardinality Estimator for All Tables](https://vldb.org/VLDB/vol14/p61-yang.pdf) [VLDB 21]  [![](https://img.shields.io/github/stars/neurocard/neurocard?style=social&label=Code+Stars)](https://github.com/neurocard/neurocard) 
3. [FLAT: Fast, Lightweight and Accurate Method for Cardinality Estimation](http://www.vldb.org/VLDB/vol14/p1489-zhu.pdf) [VLDB 21]
4. [BayesCard: Revitilizing Bayesian Frameworks for Cardinality Estimation](https://arxiv.org/pdf/2012.14743.pdf) [aiXiv 21] [![](https://img.shields.io/github/stars/wuziniu/BayesCard?style=social&label=Code+Stars)](https://github.com/wuziniu/BayesCard) 
5. [Glue: Adaptively Merging Single Table Cardinality to Estimate Join Query Size](https://arxiv.org/pdf/2112.03458.pdf)  [aiXiv 21]
6. [Fauce: fast and accurate deep ensembles with uncertainty for cardinality estimation](http://vldb.org/pvldb/vol14/p1950-liu.pdf) [VLDB 21]
7. [FACE: a normalizing flow based cardinality estimator](https://dbgroup.cs.tsinghua.edu.cn/ligl/papers/vldb22-flow-card.pdf) [VLDB 22]  [![](https://img.shields.io/github/stars/for0nething/FACE-A-Normalizing-Flow-based-Cardinality-Estimator?style=social&label=Code+Stars)](https://github.com/for0nething/FACE-A-Normalizing-Flow-based-Cardinality-Estimator/) 
8. [FactorJoin: A New Cardinality Estimation Framework for Join Queries](https://arxiv.org/pdf/2212.05526.pdf) [SIGMOD 22]
9. [Cardinality estimation using normalizing flow](https://link.springer.com/article/10.1007/s00778-023-00808-x) [VLDBJ 23]
10. [CEDA: Learned Cardinality Estimation with Domain Adaptation](https://dl.acm.org/doi/abs/10.14778/3611540.3611589) [VLDB 23]
11. [LPLM: A Neural Language Model for Cardinality Estimation of LIKE-Queries](https://dl.acm.org/doi/pdf/10.1145/3639309) [SIGMOD 24]
12. [Cardinality Estimation of LIKE Predicate Queries using Deep Learning](https://dl.acm.org/doi/pdf/10.1145/3709670) [SIGMOD 25]
13. [Grid-AR: A Grid–based Booster for Learned Cardinality Estimation and Range Joins](https://arxiv.org/pdf/2410.07895) [arXiv 25]
14. [Updateable Data-Driven Cardinality Estimator with Bounded Q-error](https://arxiv.org/pdf/2408.17209) [arXiv 25]
15. [SPACE: Cardinality Estimation for Path Queries Using Cardinality-Aware Sequence-based Learning](https://dl.acm.org/doi/pdf/10.1145/3725355) [SIGMOD 25]
16. [Data-Agnostic Cardinality Learning from Imperfect Workloads](https://www.arxiv.org/pdf/2506.16007#page=10.34) [VLDB 25]

#### Hybrid

1. [A Unified Deep Model of Learning from both Data and Queries for Cardinality Estimation](https://arxiv.org/pdf/2107.12295.pdf) [SIGMOD 21]  [![](https://img.shields.io/github/stars/pagegitss/UAE?style=social&label=Code+Stars)](https://github.com/pagegitss/UAE) 
2. [ALECE: An Attention-based Learned Cardinality Estimator for SPJ Queries on Dynamic Workloads](https://dl.acm.org/doi/pdf/10.14778/3626292.3626302) [VLDB 23] [![](https://img.shields.io/github/stars/pfl-cs/ALECE?style=social&label=Code+Stars)](https://github.com/pfl-cs/ALECE)
3. [A Unified Model for Cardinality Estimation by Learning from Data and Queries via Sum-Product Networks](https://arxiv.org/pdf/2505.08318) [arXiv 25]  [![](https://img.shields.io/github/stars/rucjrliu/QSPN_code?style=social&label=Code+Stars)](https://github.com/rucjrliu/QSPN_code) 

#### Pretrain

1. [PRICE: A Pretrained Model for Cross-Database Cardinality Estimation](https://www.vldb.org/pvldb/vol18/p637-zhu.pdf) [VLDB 25]
2. [PLM4NDV：Minimizing Data Access for Number of Distinct Values Estimation with Pre-trained Language Models](https://arxiv.org/pdf/2504.00608) [SIGMOD 25]

#### Survey

1. [Cardinality Estimation: An Experimental Survey](https://www.vldb.org/VLDB/vol11/p499-harmouch.pdf) [VLDB 17]
2. [Are We Ready For Learned Cardinality Estimation?](https://arxiv.org/pdf/2012.06743.pdf) [VLDB 21]
3. [Cardinality Estimation in DBMS: A Comprehensive Benchmark Evaluation](https://kai-zeng.github.io/papers/benchmark_vldb_2021.pdf) [VLDB 21]
4. [Learned cardinality estimation: A design space exploration and a comparative evaluation](https://dbgroup.cs.tsinghua.edu.cn/ligl/papers/vldb22-card-exp.pdf) [VLDB 22]
5. [Learned Cardinality Estimation: An In-depth Study](https://dl.acm.org/doi/10.1145/3514221.3526154) [SIGMOD 22] [![](https://img.shields.io/github/stars/postechdblab/learned-cardinality-estimation?style=social&label=Code+Stars)](https://github.com/postechdblab/learned-cardinality-estimation?tab=readme-ov-file)

