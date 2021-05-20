Poly Materials

- [Book](#book)
- [People & Lab](#people--lab)
- [Course](#course)
- [Conference](#conference)
- [Acclerator Classification](#acclerator-classification)
- [Papers](#papers)
  - [Acclerator for Deep Learning](#acclerator-for-deep-learning)
  - [Acclerator for Machine Learning](#acclerator-for-machine-learning)
  - [Acclerator for Gene](#acclerator-for-gene)
  - [Acclerator for Graph Processing](#acclerator-for-graph-processing)
  - [Acclerator for Sparse Data(SpMM, SpGemm, Sparse DNN)](#acclerator-for-sparse-dataspmm-spgemm-sparse-dnn)
  - [Acclerator for General Purpose](#acclerator-for-general-purpose)
  - [Acclerator for Others](#acclerator-for-others)
  - [Compiler & Runtime Supprot for Acclerators](#compiler--runtime-supprot-for-acclerators)
  - [SW/HW Co-Design](#swhw-co-design)

<small><i><a href='http://ecotrust-canada.github.io/markdown-toc/'>Table of contents generated with markdown-toc</a></i></small>

# Book


# People & Lab
* [Xuehai Qian](http://alchem.usc.edu/portal/index.html)(钱学海) Graph Processing, Machine Learning Accleration
* [Yuan Xie](https://seal.ece.ucsb.edu/)


# Course

# Conference
* MICRO
* ISCA
* ASPLOS
* HPCA

# Acclerator Classification
* ASIC
* FPGA
* NDP
* PIM
* Dataflow
* Spatial

# Papers

## Acclerator for Deep Learning
total paper = 
| **Date** | **Paper** | **Focused On** | **Notes** |
| --- | --- | --- | --- |
| 2021 ISCA | RaPiD: AI Accelerator for Ultra-Low Precision Training and Inference   |  |  |
| 2021 ISCA | REDUCT: Keep It Close, Keep It Cool! - Scaling DNN Inference on Multi-Core CPUs with Near-Cache Compute   |  NDP |  |
| 2021 ISCA | FORMS: Fine-Grained Polarized ReRAM-Based In-Situ Computation for Mixed-Signal DNN Accelerator |  PIM |  |
| 2021 ISCA | Enabling Compute-Communication Overlap in Distributed Deep Learning Training Platforms |   |  |
| 2021 ISCA | SPACE: Locality-Aware Processing in Heterogeneous Memory for Personalized Recommendations |   |  |
| 2021 ISCA | Cambricon-Q: A Hybrid Architecture for Efficient Training |   |  |
| 2021 ISCA | NASA: Accelerating Neural Network Design with a NAS Processor |   |  |
| 2021 ISCA | NN-Baton: DNN Workload Orchestration and Chiplet Granularity Exploration for Multichip Accelerators |   |  |
| 2021 HPCA | Heterogeneous Dataflow Accelerators for Multi-DNN Workloads[[paper]](https://arxiv.org/abs/1909.07437) |   |  |
| 2021 HPCA | Mix and Match: A Novel FPGA-Centric Deep Neural Network Quantization Framework[[paper]](https://arxiv.org/abs/2012.04240)[[video]](https://www.youtube.com/watch?v=kKdnVmcSgmY) |   |  |
| 2021 HPCA | Revisiting HyperDimensional Learning for FPGA and Low-Power Architectures[[paper]](https://ieeexplore.ieee.org/document/9407181)[[video]](https://www.youtube.com/watch?v=kKdnVmcSgmY) |   |  |
| 2021 HPCA | Tensor Casting: Co-Designing Algorithm-Architecture for Personalized Recommendation Training[[paper]](https://arxiv.org/abs/2010.13100)[[video]](https://www.youtube.com/watch?v=KiO6y2z5xjU) |   |  |
| 2021 HPCA | GradPIM: A Practical Processing-in-DRAM Architecture for Gradient Descent[[paper]](https://arxiv.org/abs/2102.07511)[[video]](https://www.youtube.com/watch?v=KiO6y2z5xjU) |   |  |
| 2021 HPCA | LazyBatching: An SLA-aware Batching System for Cloud Machine Learning Inference[[paper]](https://arxiv.org/abs/2010.13103)[[video]](https://www.youtube.com/watch?v=GhWS_K4YIZk) |   |  |
| 2021 HPCA | Efficient Tensor Migration and Allocation on Heterogeneous Memory Systems for Deep Learning[[paper]](http://pasalabs.org/papers/2021/hpca21_sentinel.pdf)[[slides]](http://nvmw.ucsd.edu/nvmw2021-program/nvmw2021-data/nvmw2021-paper62-presentation_slides.pdf) |   |  |

----

## Acclerator for Machine Learning
| **Date** | **Paper** | **Focused On** | **Notes** |
| --- | --- | --- | --- |
| 2021 ASPLOS | Statistical Robustness of Markov Chain Monte Carlo Accelerators [[paper]](https://users.cs.duke.edu/~alvy/papers/robustness_asplos21.pdf)  | 马尔可夫 |  |

----


## Acclerator for Gene
| **Date** | **Paper** | **Focused On** | **Notes** |
| --- | --- | --- | --- |
| 2021 ISCA | Sieve: Scalable In-Situ DRAM-Based Accelerator Designs for Massively Parallel k-mer Matching | NDP |  |
| 2021 ISCA | Accelerated Seeding for Genome Sequence Alignment with Enumerated Radix Trees |  |  |
| 2021 HPCA | EXMA: A Genomics Accelerator for Exact-Matching[[paper]](https://arxiv.org/abs/2101.05314) |  |  |

----

## Acclerator for Graph Processing
| **Date** | **Paper** | **Main Contribute** | **Notes** |
| --- | --- | --- | --- |
| 2021 ISCA | FlexMiner: A Pattern-Aware Accelerator for Graph Pattern Mining |  |  |
| 2021 ISCA | PolyGraph: Exposing the Value of Flexibility for Graph Processing Accelerators |  |  |
| 2021 ISCA | Large-Scale Graph Processing on FPGAs with Caches for Thousands of Simultaneous Misses |  |  |
| 2021 HPCA | DepGraph: A Dependency-Driven Accelerator for Efficient Iterative Graph Processing |  |  |
| 2021 HPCA | P-OPT: Practical Optimal Cache Replacement for Graph Analytics[[paper]](https://brandonlucia.com/pubs/POPT_HPCA21_CameraReady.pdf)[[slides]](https://users.ece.cmu.edu/~vigneshb/files/P-OPT-slides.pdf) |  |  |


----

## Acclerator for Sparse Data(SpMM, SpGemm, Sparse DNN)
| **Date** | **Paper** | **Focused on** | **Notes** |
| --- | --- | --- | --- |
| 2021 ISCA | SpZip: Architectural Support for Effective Data Compression In Irregular Applications |  |  |
| 2021 ISCA | Dual-Side Sparse Tensor Core |  |  |
| 2021 ISCA | RingCNN: Exploiting Algebraically-Sparse Ring Tensors for Energy-Efficient CNN-Based Computational Imaging |  |  |
| 2021 ISCA | GoSPA: An Energy-Efficient High-Performance Globally Optimized SParse Convolutional Neural Network Accelerator |  |  |
| 2021 ASPLOS |Gamma: Leveraging Gustavson’s Algorithm to Accelerate Sparse Matrix Multiplication [[paper]](https://dl.acm.org/doi/abs/10.1145/3445814.3446702)  | SpGEMM |  |
| 2021 HPCA |SPAGHETTI: Streaming Accelerators for Highly Sparse GEMM on FPGAs [[paper]](https://ieeexplore.ieee.org/abstract/document/9407115/)[[code]](https://github.com/sfu-arch/SpGEMM)  | SpGEMM |  |
| 2021 HPCA | SpAtten: Efficient Sparse Attention Architecture with Cascade Token and Head Pruning [[paper]](https://arxiv.org/abs/2012.09852)[[slides]](https://hanlab.mit.edu/projects/spatten/assets/spatten/spatten_slides.pdf)[[website]](https://spatten.mit.edu/)  | Attention |  |
| 2021 HPCA | SpaceA: Sparse Matrix Vector Multiplication on Processing-in-Memory Accelerator [[paper]](https://ieeexplore.ieee.org/abstract/document/9407163/)[[slides]](https://hanlab.mit.edu/projects/spatten/assets/spatten/spatten_slides.pdf)[[website]](https://spatten.mit.edu/)  | Attention |  |



----

## Acclerator for General Purpose
| **Date** | **Paper** | **Focused On** | **Notes** |
| --- | --- | --- | --- |
| 2021 ISCA | Aurochs: An Architecture for Dataflow Threads | |  |
| 2021 ISCA | SNAFU: An Ultra-Low-Power, Energy-Minimal CGRA-Generation Framework and Architecture | |  |
| 2021 ISCA | SARA: Scaling a Reconfigurable Dataflow Accelerator | |  |
| 2021 ASPLOS | DiAG: A Dataflow-Inspired Architecture for General-Purpose Processors [[paper]](https://dl.acm.org/doi/abs/10.1145/3445814.3446703)  | 利用设计加速器的思想加速Dataflow架构 |  |
| 2021 HPCA | Ultra-Elastic CGRAs for Irregular Loop Specialization [[paper]](https://www.csl.cornell.edu/~cbatten/pdfs/torng-uecgra-hpca2021.pdf) [[slides]](https://www.csl.cornell.edu/~cbatten/pdfs/torng-uecgra-slides-hpca2021.pdf) |  |  |
| 2021 HPCA | Analyzing and Leveraging Decoupled L1 Caches in GPUs [[paper]](https://adwaitjog.github.io/docs/pdf/sharedl1-pact20.pdf) [[video]](https://www.youtube.com/watch?v=3YbrS9UpTZ0) |  |  |

----

## Acclerator for Others
| **Date** | **Paper** | **Domain** | **Notes** |
| --- | --- | --- | --- |
| 2021 ISCA | PipeZK: Accelerating Zero-Knowledge Proof with a Pipelined Architecture | 密码学/区块链 |  |
| 2021 ASPLOS | Robomorphic Computing: A Design Methodology for Domain-Specific Accelerators Parameterized by Robot Morphology [[paper]](https://dl.acm.org/doi/10.1145/3445814.3446746)  | 机器人 |  |
| 2021 HPCA | QEI: Query Acceleration Can be Generic and Efficient in the Cloud [[paper]](https://ieeexplore.ieee.org/document/9407097) [[slides]](https://yifanyuan3.github.io/files/qei.pptx) |  |  |

----

## Compiler & Runtime Supprot for Acclerators
| **Date** | **Paper** | **Domain** | **Notes** |
| --- | --- | --- | --- |
| 2021 HPCA | A Computational Stack for Cross-Domain Acceleration [[paper]](https://cseweb.ucsd.edu/~hadi/doc/paper/2021-hpca-polymath.pdf) |  |  |
| 2021 HPCA | Deadline-Aware Offloading for High-Throughput Accelerators [[paper]](https://ieeexplore.ieee.org/document/9407162) [[slides]](https://pages.cs.wisc.edu/~sinclair/presentations/hpca21-longTalk-final.pdf) |  |  |

----


## SW/HW Co-Design 
| **Date** | **Paper** | **Domain** | **Notes** |
| --- | --- | --- | --- |
| 2021 ISCA | Communication Algorithm-Architecture Co-Design for Distributed Deep Learning   |  |  |
| 2021 ISCA | Taming the Zoo: The Unified GraphIt Compiler Framework for Novel Architectures   |  GraphIt |  |
| 2021 ISCA | CoSA: Scheduling by Constrained Optimization for Spatial Accelerators   | Scheduling |  |
| 2021 ISCA | η-LSTM: Co-Designing Highly-Efficient Large LSTM Training via Exploiting Memory-Saving and Architectural Design Opportunities | LSTM |  |
| 2021 ISCA | ELSA: Hardware-Software Co-Design for Efficient, Lightweight Self-Attention Mechanism in Neural Networks | Attention |  |
| 2021 ISCA | TENET: A Framework for Modeling Tensor Dataflow Based on Relation-Centric Notation | |  |
| 2021 ISCA | HASCO: Towards Agile HArdware and Software CO-design for Tensor Computation | |  |
| 2021 ASPLOS | Mind Mappings: Enabling Efficient Algorithm-Accelerator Mapping Space Search [[paper]](https://arxiv.org/abs/2103.01489)  | Algorithm-Accelrator mapping |  |
| 2021 ASPLOS | Analytical Characterization and Design Space Exploration for Optimization of CNNs [[paper]](https://arxiv.org/abs/2101.09808)  | CNN Schedule |  |
| 2021 HPCA | Layerweaver: Maximizing Resource Utilization of Neural Processing Units via Layer-Wise Scheduling [[paper]](https://ieeexplore.ieee.org/document/9407236)  |  |  |
| 2021 HPCA | CSCNN: Algorithm-hardware Co-design for CNN Accelerators using Centrosymmetric Filters [[paper]](https://ieeexplore.ieee.org/document/9407182/)  |  |  |



----
