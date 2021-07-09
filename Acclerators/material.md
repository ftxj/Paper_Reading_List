Poly Materials

- [Book](#book)
- [People & Lab](#people--lab)
- [Course](#course)
- [Conference](#conference)
- [Acclerator Classification](#acclerator-classification)
- [Company](#company)
- [Big Event Timeline(cite > 100 / Best Paper...)](#big-event-timelinecite--100--best-paper)
- [Papers](#papers)
  - [Acclerator for Deep Learning (without SNN)](#acclerator-for-deep-learning-without-snn)
  - [Acclerator for Machine Learning](#acclerator-for-machine-learning)
  - [Acclerator for Gene](#acclerator-for-gene)
  - [Acclerator for Graph Processing](#acclerator-for-graph-processing)
  - [Acclerator for Sparse/Irregular Data(SpMM, SpGemm, Sparse DNN)](#acclerator-for-sparseirregular-dataspmm-spgemm-sparse-dnn)
  - [Acclerator for General Purpose](#acclerator-for-general-purpose)
  - [Acclerator for Linear System](#acclerator-for-linear-system)
  - [Acclerator for Others](#acclerator-for-others)
  - [Compiler / Runtime / Analysis for Acclerators/CPU](#compiler--runtime--analysis-for-accleratorscpu)
  - [Programming Model](#programming-model)
  - [SW/HW Co-Design](#swhw-co-design)
- [Some Interesting Paper](#some-interesting-paper)

<small><i><a href='http://ecotrust-canada.github.io/markdown-toc/'>Table of contents generated with markdown-toc</a></i></small>

# Book
* [DNN Acclerator, Gatech](https://www.morganclaypool.com/doi/10.2200/S01015ED1V01Y202005CAC052)

# People & Lab
* [Xuehai Qian](http://alchem.usc.edu/portal/index.html)(钱学海) Graph Processing, Machine Learning Accleration
* [Yuan Xie](https://seal.ece.ucsb.edu/), UCSB, PIM, Arch
* [Liang Yun](https://ericlyun.github.io/people/) PKU, EDA & Arch
* [Zhiru Zhang](https://www.csl.cornell.edu/~zhiruz/publications.html), Cornell, HW/SW CO-Design, HLS
* [i-acoma group](http://iacoma.cs.uiuc.edu/josep/torrellas.html), UIUC,
* [Compilers Creating Custom Processors(CCCP) Lab](http://cccp.eecs.umich.edu/), Mich
* [Synergy Lab](https://synergy.ece.gatech.edu/publications/), Gatech. DNN Arch
* [Onur Mutlu](http://people.inf.ethz.ch/omutlu/projects.htm), ETH & CMU. Graph Mining, PIM


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

----

# Company
* Huawei 
  * 2021 [[Ascend]](https://ieeexplore.ieee.org/document/9407221/)
* Facebook 
  * 2021 [[Training Efficiency of Recommendation Modele]](https://arxiv.org/abs/2011.05497)
* Google
  * 2021 [[Framework for Machine Learning Accelerators]](https://ieeexplore.ieee.org/document/9407039)
* IBM
  * 2020 [[Data Compression]](https://conferences.computer.org/isca/pdfs/ISCA2020-4QlDegUf3fKiwUXfV0KdCm/466100a001/466100a001.pdf)

----

# Big Event Timeline(cite > 100 / Best Paper...)
| **Domain** | **2014** | **2015** | **2016** | **2017** |
| --- | --- | --- | --- | --- |
| DL | Diannao |  | Fused CNN Acclerator | | 
| SparseNN |  |  | Eyeriss | SCNN |
| Graph | -- | -- | Graphicionado | |

----


# Papers

## Acclerator for Deep Learning (without SNN)
(num) 2021 = 16,
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
| 2021 HPCA | FuseKNA: Fused Kernel Convolution based Accelerator for Deep Neural Networks [[paper]](https://ieeexplore.ieee.org/abstract/document/9407121/) |   |  |
| 2020 MICRO | SuperNPU: An Extremely Fast Neural Processing Unit Using Superconducting Logic Devices [[paper]](https://www.microarch.org/micro53/papers/738300a058.pdf) [[video]](https://youtu.be/5F8YrPZDlUE) |  超导体加速NN |  |
| 2020 MICRO | Look-Up Table based Energy Efficient Processing in Cache Support for Neural Network Acceleration [[paper]](https://www.microarch.org/micro53/papers/738300a088.pdf) [[video]](https://youtu.be/Wa75USQ7ZWY) |  PIM |  |
| 2020 MICRO | Fast-BCNN: Massive Neuron Skipping in Bayesian Convolutional Neural Networks [[paper]](https://www.microarch.org/micro53/papers/738300a229.pdf) [[video]](https://youtu.be/AvOn96Bnurw) |  |  |
| 2020 MICRO | Non-Blocking Simultaneous Multithreading: Embracing the Resiliency of Deep Neural Networks [[paper]](https://www.microarch.org/micro53/papers/738300a256.pdf) [[video]](https://youtu.be/gQr13rkASlk) |  |  |
| 2020 MICRO | Newton: A DRAM-Maker's Accelerator-in-Memory (AiM) Architecture for Machine Learning [[paper]](https://www.microarch.org/micro53/papers/738300a372.pdf) [[video]](https://youtu.be/cUKR6Y-CjeE) |  |  |
| 2020 MICRO | MOUSE: Inference In Non-volatile Memory for Energy Harvesting Applications [[paper]](https://www.microarch.org/micro53/papers/738300a400.pdf) [[video]](https://youtu.be/nfLkhCAVEYg) |  |  |
| 2020 MICRO | VR-DANN: Real-Time Video Recognition via Decoder-Assisted Neural Network Acceleration [[paper]](https://www.microarch.org/micro53/papers/738300a400.pdf) [[video]](https://youtu.be/nfLkhCAVEYg) |  |  |
| 2020 MICRO | Duplo: Lifting Redundant Memory Accesses of Deep Neural Networks for GPU Tensor Cores [[paper]](https://www.microarch.org/micro53/papers/738300a725.pdf) [[video]](https://youtu.be/hZZlzwxnL0Y) |  |  |
| 2020 MICRO | DUET: Boosting Deep Neural Network Efficiency on Dual-Module Architecture [[paper]](https://www.microarch.org/micro53/papers/738300a738.pdf) [[video]](https://youtu.be/8-3GpbrsmdE) |  |  |
| 2020 MICRO | TFE: Energy-Efficient Transferred Filter-Based Engine to Compress and Accelerate Convolutional Neural Networks [[paper]](https://www.microarch.org/micro53/papers/738300a751.pdf) [[video]](https://youtu.be/2eY_2z_80IA) |  |  |
| 2020 MICRO | GOBO: Quantizing Attention-Based NLP Models for Low Latency and Energy Efficient Inference [[paper]](https://www.microarch.org/micro53/papers/738300a811.pdf) [[video]](https://youtu.be/X1Ojl8yGHCM) | Quantizing |  |
| 2020 ISCA | Think Fast: A Tensor Streaming Processor (TSP) for Accelerating Deep Learning Workloads [[paper]](https://conferences.computer.org/isca/pdfs/ISCA2020-4QlDegUf3fKiwUXfV0KdCm/466100a145/466100a145.pdf)  |  |  |
| 2020 ISCA | uGEMM: Unary Computing Architecture for GEMM Applications [[paper]](https://conferences.computer.org/isca/pdfs/ISCA2020-4QlDegUf3fKiwUXfV0KdCm/466100a377/466100a377.pdf)  |  |  |
| 2020 ISCA | RecNMP: Accelerating Personalized Recommendation with Near-Memory Processing [[paper]](https://conferences.computer.org/isca/pdfs/ISCA2020-4QlDegUf3fKiwUXfV0KdCm/466100a790/466100a790.pdf)  | NDP |  |
| 2020 ISCA | TIMELY: Pushing Data Movements and Interfaces in PIM Accelerators Towards Local and in Time Domain [[paper]](https://conferences.computer.org/isca/pdfs/ISCA2020-4QlDegUf3fKiwUXfV0KdCm/466100a832/466100a832.pdf)  | PIM |  |
| 2020 ISCA | JPEG-ACT: Accelerating Deep Learning via Transform-Based Lossy Compression [[paper]](https://conferences.computer.org/isca/pdfs/ISCA2020-4QlDegUf3fKiwUXfV0KdCm/466100a860/466100a860.pdf)  |  |  |
| 2020 ISCA | A Multi-Neural Network Acceleration Architecture [[paper]](https://conferences.computer.org/isca/pdfs/ISCA2020-4QlDegUf3fKiwUXfV0KdCm/466100a940/466100a940.pdf)  |  |  |
| 2020 ISCA | Centaur: A Chiplet-Based, Hybrid Sparse-Dense Accelerator for Personalized Recommendations [[paper]](https://conferences.computer.org/isca/pdfs/ISCA2020-4QlDegUf3fKiwUXfV0KdCm/466100a968/466100a968.pdf)  | 推荐系统 |  |
| 2020 ISCA | DeepRecSys: A System for Optimizing End-to-End At-Scale Neural Recommendation Inference [[paper]](https://conferences.computer.org/isca/pdfs/ISCA2020-4QlDegUf3fKiwUXfV0KdCm/466100a982/466100a982.pdf)  | 推荐系统 |  |
| 2020 ISCA | DRQ: Dynamic Region-Based Quantization for Deep Neural Network Acceleration [[paper]](https://conferences.computer.org/isca/pdfs/ISCA2020-4QlDegUf3fKiwUXfV0KdCm/466100b010/466100b010.pdf)  |  |  |
| 2020 ASPLOS | DNNGuard: An Elastic Heterogeneous DNN Accelerator Architecture against Adversarial Attacks [[paper]](https://dl.acm.org/doi/pdf/10.1145/3373376.3378532) [[video]](https://www.youtube.com/watch?v=jdicv_HPUKA)  | NN加速器的安全？ |  |
| 2020 ASPLOS | DeepSniffer: A DNN Model Extraction Framework Based on Learning Architectural Hints  |  |  |
| 2020 ASPLOS | Prague: High-Performance Heterogeneity-Aware Asynchronous Decentralized Training  |  |  |
| 2020 ASPLOS | NeuMMU: Architectural Support for Efficient Address Translations in Neural Processing Units  | NPU的TLB |  |
| 2017 ISCA | SCNN: An Accelerator for Compressed-sparse Convolutional Neural Networks  | |  |
| 2016 MICRO | Fused-Layer CNN Accelerators  | CNN中 layer间的fuse。好处是减少全局内存读写，坏处是冗余计算/增加片上缓存需求 |  |

----

## Acclerator for Machine Learning
(num) 2021 = 1,
| **Date** | **Paper** | **Focused On** | **Notes** |
| --- | --- | --- | --- |
| 2021 ASPLOS | Statistical Robustness of Markov Chain Monte Carlo Accelerators [[paper]](https://users.cs.duke.edu/~alvy/papers/robustness_asplos21.pdf)  | 马尔可夫 |  |
| 2020 MICRO | Printed Machine Learning Classifiers [[paper]](https://www.microarch.org/micro53/papers/738300a073.pdf) [[video]](https://youtu.be/RzE-ThPiMxI) | 印刷电子加速机器学习 |  |
| 2020 MICRO | DUAL: Acceleration of Clustering Algorithms using Digital-Based Processing In-Memory [[paper]](https://www.microarch.org/micro53/papers/738300a356.pdf) [[video]](https://youtu.be/PUbRQeRdIsk) | PIM聚类算法 |  |
| 2020 ISCA | Gorgon: Accelerating Machine Learning from Relational Data [[paper]](https://conferences.computer.org/isca/pdfs/ISCA2020-4QlDegUf3fKiwUXfV0KdCm/466100a309/466100a309.pdf) | database ML |  |

----


## Acclerator for Gene
(num) 2021 = 3,
| **Date** | **Paper** | **Focused On** | **Notes** |
| --- | --- | --- | --- |
| 2021 ISCA | Sieve: Scalable In-Situ DRAM-Based Accelerator Designs for Massively Parallel k-mer Matching | NDP |  |
| 2021 ISCA | Accelerated Seeding for Genome Sequence Alignment with Enumerated Radix Trees |  |  |
| 2021 HPCA | EXMA: A Genomics Accelerator for Exact-Matching[[paper]](https://arxiv.org/abs/2101.05314) |  |  |
| 2020 MICRO | SeedEx: A Genome Sequencing Accelerator for Optimal Alignments in Subminimal Space[[paper]](https://www.microarch.org/micro53/papers/738300a937.pdf) [[video]](https://youtu.be/koIkKzE4LCs) |  |  |
| 2020 MICRO | GenASM: A High-Performance, Low-Power Approximate String Matching Acceleration Framework for Genome Sequence Analysis [[paper]](https://www.microarch.org/micro53/papers/738300a951.pdf) [[slides]](https://youtu.be/VeUy4Hh3Moo) |  |  |
| 2020 ISCA | Genesis: A Hardware Acceleration Framework for Genomic Data Analysis [[paper]](https://conferences.computer.org/isca/pdfs/ISCA2020-4QlDegUf3fKiwUXfV0KdCm/466100a254/466100a254.pdf) |  |  |

----

## Acclerator for Graph Processing
(num) 2021 = 6,
| **Date** | **Paper** | **Main Contribute** | **Notes** |
| --- | --- | --- | --- |
| 2021 ISCA | FlexMiner: A Pattern-Aware Accelerator for Graph Pattern Mining |  |  |
| 2021 ISCA | PolyGraph: Exposing the Value of Flexibility for Graph Processing Accelerators |  |  |
| 2021 ISCA | Large-Scale Graph Processing on FPGAs with Caches for Thousands of Simultaneous Misses |  |  |
| 2021 HPCA | DepGraph: A Dependency-Driven Accelerator for Efficient Iterative Graph Processing |  |  |
| 2021 HPCA | P-OPT: Practical Optimal Cache Replacement for Graph Analytics[[paper]](https://brandonlucia.com/pubs/POPT_HPCA21_CameraReady.pdf)[[slides]](https://users.ece.cmu.edu/~vigneshb/files/P-OPT-slides.pdf) |  |  |
| 2021 HPCA | GCNAX: A Flexible and Energy-efficient Accelerator for Graph Convolutional Neural Networks[[paper]](https://ieeexplore.ieee.org/document/9407104)[[slides]](https://users.ece.cmu.edu/~vigneshb/files/P-OPT-slides.pdf) |  |  |
| 2020 MICRO | Pipette: Improving Core Utilization on Irregular Applications through Intra-Core Pipeline Parallelism [[paper]](https://www.microarch.org/micro53/papers/738300a596.pdf)[[slides]](https://youtu.be/AsD2Bzy1A0M) |  |  |
| 2020 MICRO | A Locality-Aware Energy-Efficient Accelerator for Graph Mining Applications [[paper]](https://www.microarch.org/micro53/papers/738300a895.pdf)[[video]](https://youtu.be/UHkB0tn-Sic) | Graph Mining |  |
| 2020 MICRO | GraphPulse: An Event-Driven Hardware Accelerator for Asynchronous Graph Processing [[paper]](https://www.microarch.org/micro53/papers/738300a908.pdf)[[video]](https://youtu.be/olhBDSa7xVE) |  |  |
| 2020 MICRO | AWB-GCN: A Graph Convolutional Network Accelerator with Runtime Workload Rebalancing [[paper]](https://www.microarch.org/micro53/papers/738300a922.pdf)[[video]](https://youtu.be/tkI9wS-mHUk) | GCN |  |
| 2020 ISCA | GraphABCD: Scaling Out Graph Analytics with Asynchronous Block Coordinate Descent [[paper]](https://conferences.computer.org/isca/pdfs/ISCA2020-4QlDegUf3fKiwUXfV0KdCm/466100a419/466100a419.pdf)  |  |  |
| 2020 ISCA | GaaS-X: Graph Analytics Accelerator Supporting Sparse Data Representation Using Crossbar Architectures [[paper]](https://conferences.computer.org/isca/pdfs/ISCA2020-4QlDegUf3fKiwUXfV0KdCm/466100a433/466100a433.pdf)  |  |  |
| 2020 ASPLOS | The TrieJax Architecture: Accelerating Graph Operations Through Relational Joins  |  |  |

----

## Acclerator for Sparse/Irregular Data(SpMM, SpGemm, Sparse DNN)
(num) 2021 = 10,
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
| 2021 HPCA | VIA: A Smart Scratchpad for Vector Units With Application to Sparse Matrix Computations [[paper]](https://ieeexplore.ieee.org/document/9407226/)[[slides]](https://hanlab.mit.edu/projects/spatten/assets/spatten/spatten_slides.pdf)[[website]](https://spatten.mit.edu/)  |  |  |
| 2021 HPCA | FAFNIR: Accelerating Sparse Gathering by Using Efficient Near-Memory Intelligent Reduction [[paper]](http://hparch.gatech.edu/papers/bahar_2021_fafnir.pdf)  |  |  |
| 2020 MICRO | Procrustes: A Dataflow and Accelerator for Sparse Deep Neural Network Training [[paper]](https://www.microarch.org/micro53/papers/738300a711.pdf) [[video]](https://youtu.be/vYslaFsVb_U)  |  |  |
| 2020 MICRO | MatRaptor: A Sparse-Sparse Matrix Multiplication Accelerator Based on Row-Wise Product [[paper]](https://www.microarch.org/micro53/papers/738300a766.pdf) [[video]](https://youtu.be/pXjcavzGqDk)  |  |  |
| 2020 MICRO | TensorDash: Exploiting Sparsity to Accelerate Deep Neural Network Training [[paper]](https://www.microarch.org/micro53/papers/738300a781.pdf) [[video]](https://youtu.be/hMH-cp-EY3Q)  | Sparse Training |  |
| 2020 MICRO | SAVE: Sparsity-Aware Vector Engine for Accelerating DNN Training and Inference on CPUs [[paper]](https://www.microarch.org/micro53/papers/738300a796.pdf) [[video]](https://youtu.be/FatPeRDNhl0)  | Sparse Training |  |
| 2020 ISCA | Commutative Data Reordering: A New Technique to Reduce Data Movement Energy on Sparse Inference Workloads [[paper]](https://conferences.computer.org/isca/pdfs/ISCA2020-4QlDegUf3fKiwUXfV0KdCm/466100b076/466100b076.pdf) | 传输能量 |  |
| 2020 ASPLOS | Batch-Aware Unified Memory Management in GPUs for Irregular Workloads |  |  |



----

## Acclerator for General Purpose
(num) 2021 = 6,
| **Date** | **Paper** | **Focused On** | **Notes** |
| --- | --- | --- | --- |
| 2021 ISCA | Aurochs: An Architecture for Dataflow Threads | |  |
| 2021 ISCA | SNAFU: An Ultra-Low-Power, Energy-Minimal CGRA-Generation Framework and Architecture | |  |
| 2021 ISCA | SARA: Scaling a Reconfigurable Dataflow Accelerator | |  |
| 2021 ASPLOS | DiAG: A Dataflow-Inspired Architecture for General-Purpose Processors [[paper]](https://dl.acm.org/doi/abs/10.1145/3445814.3446703)  | 利用设计加速器的思想加速Dataflow架构 |  |
| 2021 HPCA | Ultra-Elastic CGRAs for Irregular Loop Specialization [[paper]](https://www.csl.cornell.edu/~cbatten/pdfs/torng-uecgra-hpca2021.pdf) [[slides]](https://www.csl.cornell.edu/~cbatten/pdfs/torng-uecgra-slides-hpca2021.pdf) |  |  |
| 2021 HPCA | Analyzing and Leveraging Decoupled L1 Caches in GPUs [[paper]](https://adwaitjog.github.io/docs/pdf/sharedl1-pact20.pdf) [[video]](https://www.youtube.com/watch?v=3YbrS9UpTZ0) |  |  |
| 2020 MICRO | FReaC Cache: Folded-Logic Reconfigurable Computing in the Last Level Cache [[paper]](https://www.microarch.org/micro53/papers/738300a102.pdf) [[video]](https://youtu.be/aJxrIggNOwI) |  |  |
| 2020 ISCA | Hyper-AP: Enhancing Associative Processing Through a Full-Stack Optimization [[paper]](https://conferences.computer.org/isca/pdfs/ISCA2020-4QlDegUf3fKiwUXfV0KdCm/466100a846/466100a846.pdf)  | PIM |  |
| 2020 ASPLOS | Livia: Data-Centric Computing Throughout the Memory Hierarchy |  |  |
| 2020 ASPLOS | A Computational Temporal Logic for Superconducting Accelerators | 超导计算 |  |
| 2020 ASPLOS | CryoCache: A Fast, Large, and Cost-Effective Cache Architecture for Cryogenic Computing | 低温计算? |  |
| 2020 ASPLOS | Fleet: A Framework for Massively Parallel Streaming on FPGAs | FPGA流处理 |  |

----

## Acclerator for Linear System
(num) 2021 = 1,
| **Date** | **Paper** | **Focused On** | **Notes** |
| --- | --- | --- | --- |
| 2021 HPCA | An Analog Preconditioner for Solving Linear Systems [[paper]](https://ieeexplore.ieee.org/abstract/document/9407108) |  |  |

----

## Acclerator for Others
(num) 2021 = 4,
| **Date** | **Paper** | **Domain** | **Notes** |
| --- | --- | --- | --- |
| 2021 ISCA | PipeZK: Accelerating Zero-Knowledge Proof with a Pipelined Architecture | 密码学/区块链 |  |
| 2021 ASPLOS | Robomorphic Computing: A Design Methodology for Domain-Specific Accelerators Parameterized by Robot Morphology [[paper]](https://dl.acm.org/doi/10.1145/3445814.3446746)  | 机器人 |  |
| 2021 HPCA | QEI: Query Acceleration Can be Generic and Efficient in the Cloud [[paper]](https://ieeexplore.ieee.org/document/9407097) [[slides]](https://yifanyuan3.github.io/files/qei.pptx) |  |  |
| 2021 HPCA | Hardware-Based Address-Centric Acceleration of Key-Value Store [[paper]](https://ieeexplore.ieee.org/document/9407194) |  |  |
| 2020 MICRO | AQUOMAN: An Analytic-Query Offloading Machine [[paper]](https://www.microarch.org/micro53/papers/738300a386.pdf) [[slides]](https://youtu.be/WirE_xmM5iQ) |  |  |
| 2020 ISCA | Bonsai: High-Performance Adaptive Merge Tree Sorting [[paper]](https://conferences.computer.org/isca/pdfs/ISCA2020-4QlDegUf3fKiwUXfV0KdCm/466100a282/466100a282.pdf) |  |  |
| 2020 ISCA | A Specialized Architecture for Object Serialization with Applications to Big Data Analytics [[paper]](https://conferences.computer.org/isca/pdfs/ISCA2020-4QlDegUf3fKiwUXfV0KdCm/466100a322/466100a322.pdf) |  |  |
| 2020 ISCA | iPIM: Programmable In-Memory Image Processing Accelerator Using Near-Bank Architecture [[paper]](https://conferences.computer.org/isca/pdfs/ISCA2020-4QlDegUf3fKiwUXfV0KdCm/466100a804/466100a804.pdf) | NDP |  |
| 2020 ISCA | IIU: Specialized Architecture for Inverted Index Search  | 倒排索引 |  |


----

## Compiler / Runtime / Analysis for Acclerators/CPU
(num) 2021 = 2,
| **Date** | **Paper** | **Domain** | **Notes** |
| --- | --- | --- | --- |
| 2021 HPCA | A Computational Stack for Cross-Domain Acceleration [[paper]](https://cseweb.ucsd.edu/~hadi/doc/paper/2021-hpca-polymath.pdf) |  |  |
| 2021 HPCA | Deadline-Aware Offloading for High-Throughput Accelerators [[paper]](https://ieeexplore.ieee.org/document/9407162) [[slides]](https://pages.cs.wisc.edu/~sinclair/presentations/hpca21-longTalk-final.pdf) |  |  |
| 2020 MICRO | FIdelity: Efficient Resilience Analysis Framework for Deep Learning Accelerators [[paper]](https://www.microarch.org/micro53/papers/738300a270.pdf) [[video]](https://youtu.be/jkh4e8dmBSg) |  |  |
| 2020 MICRO | Optimizing the Memory Hierarchy by Compositing Automatic Transformations on Computations and Data [[paper]](https://www.microarch.org/micro53/papers/738300a427.pdf) [[video]](https://youtu.be/fxNpGBcmMy4) |  |  |
| 2020 MICRO | gem5-SALAM: A System Architecture for LLVM-based Accelerator Modeling [[paper]](https://www.microarch.org/micro53/papers/738300a471.pdf) [[video]](https://youtu.be/5c0aI1Rr4r4) |  |  |
| 2020 MICRO | ConfuciuX: Autonomous Hardware Resource Assignment for DNN Accelerators using Reinforcement Learning [[paper]](https://www.microarch.org/micro53/papers/738300a622.pdf) [[video]](https://youtu.be/xS-IGFHv0LU) |  |  |
| 2020 MICRO | Planaria: Dynamic Architecture Fission for Spatial Multi-Tenant Acceleration of Deep Neural Networks [[paper]](https://www.microarch.org/micro53/papers/738300a681.pdf) [[video]](https://youtu.be/cEcqUzU0mos) |  |  |
| 2020 ISCA | DSAGEN: Synthesizing Programmable Spatial Accelerators [[paper]](https://conferences.computer.org/isca/pdfs/ISCA2020-4QlDegUf3fKiwUXfV0KdCm/466100a268/466100a268.pdf) |  |  |
| 2020 ISCA | SOFF: An OpenCL High-Level Synthesis Framework for FPGAs [[paper]](https://conferences.computer.org/isca/pdfs/ISCA2020-4QlDegUf3fKiwUXfV0KdCm/466100a295/466100a295.pdf) |  |  |
| 2020 ISCA | Echo: Compiler-Based GPU Memory Footprint Reduction for LSTM RNN Training [[paper]](https://conferences.computer.org/isca/pdfs/ISCA2020-4QlDegUf3fKiwUXfV0KdCm/466100b089/466100b089.pdf) |  |  |
| 2020 ISCA | SmartExchange: Trading Higher-Cost Memory Storage/Access for Lower-Cost Computation [[paper]](https://conferences.computer.org/isca/pdfs/ISCA2020-4QlDegUf3fKiwUXfV0KdCm/466100a954/466100a954.pdf) |  |  |
| 2020 ISCA | Echo: Compiler-Based GPU Memory Footprint Reduction for LSTM RNN Training [[paper]](https://conferences.computer.org/isca/pdfs/ISCA2020-4QlDegUf3fKiwUXfV0KdCm/466100b089/466100b089.pdf) |  |  |
| 2020 ASPLOS | Noise-Aware Dynamical System Compilation for Analog Devices with Legno [[paper]](https://people.csail.mit.edu/sachour/docs/asplos20-legno.pdf) [[video]](https://www.youtube.com/watch?v=7PU-6cWQQkE&list=PLsLWHLZB96VeVp3IVzvSH58ttVz_Anr7H&index=11&t=0s) |  |  |
| 2020 ASPLOS | FlexAmata: A Universal and Efficient Adaption of Applications to Spatial Automata Processing Accelerators [[paper]](https://www.cs.ucr.edu/~elaheh/papers/ASPLOS2020_FlexAmata.pdf) [[video]](https://www.youtube.com/watch?v=sOV_cz-1CWQ&list=PLsLWHLZB96VeVp3IVzvSH58ttVz_Anr7H&index=10) |  |  |
| 2020 ASPLOS | Accelerating Legacy String Kernels via Bounded Automata Learning [[paper]](http://www-personal.umich.edu/~jeannin/papers/angstadt2020accelerating.pdf) [[video]](https://youtube.com/watch?v=FB_2h5UyH1o&list=PLsLWHLZB96VeVp3IVzvSH58ttVz_Anr7H&index=15&t=0s) |  |  |
| 2020 ASPLOS | Classifying Memory Access Patterns for Prefetching  | 分析访存模式 |  |
| 2020 ASPLOS | AvA: Accelerated Virtualization of Accelerators | 加速器虚拟化 |  |
| 2020 ASPLOS | A Hypervisor for Shared-Memory FPGA Platforms | 多FPGA |  |
| 2020 ASPLOS | Virtualizing FPGAs in the Cloud | FPGA虚拟化 |  |
| 2020 ASPLOS | Chronos: Efficient Speculative Parallelism for Accelerators |  |  |


----


## Programming Model 
| **Date** | **Paper** | **Domain** | **Notes** |
| --- | --- | --- | --- |
| 2021 arxiv |GraphMineSuite: Enabling High-Performance and
Programmable Graph Mining Algorithms with Set Algebra | Graph Mining, Set Alge |  |

----

## SW/HW Co-Design 
(num) 2021 = 11,
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
| 2020 ASPLOS | Interstellar: Using Halide’s Scheduling Language to Analyze DNN Accelerators |  |  |
| 2020 ASPLOS | FirePerf: FPGA-Accelerated Full-System Hardware/Software Performance Profiling and Co-Design | FPGA加速器的分析 |  |
| 2020 ASPLOS | Accelerometer: Understanding Acceleration Opportunities for Data Center Overheads at Hyperscale | 理解什么适合加速器 |  |



----

# Some Interesting Paper
| **Date** | **Paper** | **Domain** | **Notes** |
| --- | --- | --- | --- |
| 2020 ISCA | Focused Value Prediction[[paper]](https://conferences.computer.org/isca/pdfs/ISCA2020-4QlDegUf3fKiwUXfV0KdCm/466100a079/466100a079.pdf) | value locality |  |
| 2020 ISCA | Divide and Conquer Frontend Bottleneck[[paper]](https://conferences.computer.org/isca/pdfs/ISCA2020-4QlDegUf3fKiwUXfV0KdCm/466100a065/466100a065.pdf) |  |  |
| 2020 ISCA | T4: Compiling Sequential Code for Effective Speculative Parallelization in Hardware[[paper]](https://conferences.computer.org/isca/pdfs/ISCA2020-4QlDegUf3fKiwUXfV0KdCm/466100a159/466100a159.pdf) |  |  |


----
