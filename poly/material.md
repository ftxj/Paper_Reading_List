# Book

* (2001) Optimizing Compilers for Modern Architectures: A Dependence-based Approach [[pdf]](Dependence-Approach-Compiler.pdf)

# Course
* 中科大 https://s4plus.ustc.edu.cn/kjxz/list.htm

# Conference
* IMPACT: International Workshop on Polyhedral Compilation Techniques[[website]](https://acohen.gitlabpages.inria.fr/impact/)
  * 2011 年开始，每年一届，接收work-in-process的文章。每届10篇以内。

| **Date** | **Paper** | **Main Contribute** | **Notes** |
| --- | --- | --- | --- |
| 1991 |Optimizing the Memory Hierarchy by Compositing Automatic Transformations on Computations and Data [[paper]](https://ieeexplore.ieee.org/document/9251965) [[slides]](https://www.di.ens.fr/~zhaojie/micro2020-presentation) | Xin Jie | Micro '20 |
| 1991 | Template Paper Title [[paper]](paper link) [[slides]](/slides/test.pdf) | Your Name | Any Other |
| 2016 CC | Mapping Deviation: A Technique to Adapt or to Guard Loop Transformation Intuitions for Legality [[paper]]((https://dl.acm.org/doi/abs/10.1145/2892208.2892216))  | 多面体模型优化太过于黑盒,没有反馈 |  |

----

## Ploy for Irregular/Non-affine(Sparse/Recurisive...)
| **Date** | **Paper** | **Main Contribute** | **Notes** |
| --- | --- | --- | --- |
| 2013 | Compilers for Regular and Irregular Stencils: Some Shared Problems and Solutions[[paper]](http://cgi.cs.arizona.edu/~mstrout/Papers/Papers13/WOSC2013-strout.pdf) | Stencil中的非规则 | |
| 2014 CGO |Non-affine Extensions to Polyhedral Code Generation [[paper]](https://dl.acm.org/doi/abs/10.1145/2544137.2544141) | 第一个在Polyhedral模型中应用到Sparse数据结构上 | 分析loop bound, Trans |
| 2015 PLDI | Tree dependence analysis[[paper]](https://dl.acm.org/doi/abs/10.1145/2737924.2737972)[[slides]](https://pldi15.sigplan.org/details/pldi2015-papers/1/Tree-Dependence-Analysis) |  | |
| 2015 PLDI | Loop and Data Transformations for Sparse Matrix Code [[paper]](https://dl.acm.org/doi/10.1145/2737924.2738003) [[slides]](https://pldi15.sigplan.org/details/pldi2015-papers/65/Loop-and-Data-Transformations-for-Sparse-Matrix-Code) | 从稠密矩阵模式生成稀疏矩阵.抽象转化原语 | make_dense |
| 2015 TACO | The Polyhedral Model of Nonlinear Loops[[paper]]([](https://dl.acm.org/doi/10.1145/2737924.2738003)) | 非线性bound, memory access |  |
| 2016 PARCO | An approach for code generation in the Sparse Polyhedral Framework[[paper]](https://www.sciencedirect.com/science/article/pii/S0167819116000557) |  |  |
| 2016 | Compiler Transformation to Generate Hybrid Sparse Computations[[paper]](https://ieeexplore.ieee.org/abstract/document/7833301) |  | |
| 2016 | AN INTEGRATED COMPILER AND RUNTIME FRAMEWORK FOR SPARSE MATRIX CODES[[paper]](https://core.ac.uk/download/pdf/276262611.pdf) | 学位论文 | |
| 2016 | Automated Optimization of Numerical Methods for Partial Differential Equations[[paper]](https://spiral.imperial.ac.uk/bitstream/10044/1/44726/1/Luporini-F-2017-PhD-Thesis.pdf) | 学位论文&科学计算| |
| 2016 LCPC | Optimizing LOBPCG: Sparse Matrix Loop and Data Transformations in Action[[paper]](https://link.springer.com/chapter/10.1007/978-3-319-52709-3_17) |  | |
| 2016 SC | Automating Wavefront Parallelization for Sparse Matrix Computations[[paper]](https://ieeexplore.ieee.org/document/7877119) | 稀疏数据 |  |
| 2017 SC | Sympiler: Transforming Sparse Matrix Codes by Decoupling Symbolic Analysis[[paper]](https://dl.acm.org/doi/abs/10.1145/3126908.3126936)[[slides]](https://www.sympiler.com/index_files/Sympiler_SC17_TALK.pdf)[[project]](https://www.sympiler.com/) | Domain-Specific-Compiler for Sparse Matrix | 一个做了很多年的系统 |
| 2018 | The Sparse Polyhedral Framework: Composing Compiler-Generated Inspector-Executor Code[[paper]](https://ieeexplore.ieee.org/abstract/document/8436444) |  | |
| 2018 IMPACT | Abstractions for Specifying Sparse Matrix Data Transformations[[paper]](http://impact.gforge.inria.fr/impact2018/papers/sparse-abstractions.pdf)[[slides]](https://acohen.gitlabpages.inria.fr/impact/impact2018/papers/sparse-abstractions-slides.pdf) |  | |
| 2018 IMPACT | Load Balancing with Polygonal Partitions[[paper]](https://acohen.gitlabpages.inria.fr/impact/impact2018/papers/polygonal-partitions.pdf)[[slides]](https://acohen.gitlabpages.inria.fr/impact/impact2018/papers/polygonal-partitions-slides.pdf) | load-balance的分块 | |
| 2018 IMPACT | Polyhedral Modeling of Immutable Sparse Matrices[[paper]](https://acohen.gitlabpages.inria.fr/impact/impact2018/papers/modeling-immutable-sparsemat.pdf)[[slides]](https://acohen.gitlabpages.inria.fr/impact/impact2018/papers/modeling-immutable-sparsemat-slides.pdf) | 稀疏矩阵 | |
| 2019 IMPACT | The Polyhedral Model Beyond Loops - Recursion Optimization and Parallelization Through Polyhedral Modeling[[paper]](https://acohen.gitlabpages.inria.fr/impact/impact2019/papers/IMPACT_2019_paper_5.pdf)[[slides]](https://acohen.gitlabpages.inria.fr/impact/impact2019/slides/IMPACT_2019_slides_5.pdf) | Recursion | |
| 2021 IMPACT | Representing Non-Affine Parallel Algorithms by means of Recursive Polyhedral Equations[[paper]](https://acohen.gitlabpages.inria.fr/impact/impact2021/papers/IMPACT_2021_paper_3.pdf) [[slides]](https://acohen.gitlabpages.inria.fr/impact/impact2021/slides/IMPACT_2021_slides_3.pdf) |  Recursive程序 | |


## Poly in weak-dependence(Reduce...)
| **Date** | **Paper** | **Main Contribute** | **Notes** |
| --- | --- | --- | --- |
| 2015 IMPACT | Polly’s Polyhedral Scheduling in the Presence of Reductions[[paper]](https://arxiv.org/pdf/1505.07716.pdf)[[slides]](http://impact.gforge.inria.fr/impact2015/papers/impact2015-doerfert-slides.pdf) | reduce_sum类型的应用不需要强依赖关系 |  |
| 2016 PACT | Reduction Drawing: Language Constructs and Polyhedral Compilation for Reductions on GPUs [[paper]](https://hal.inria.fr/hal-01425750/document) | 也是reduce |  |


----



## Poly for communication avoiding
| **Date** | **Paper** | **Main Contribute** | **Notes** |
| --- | --- | --- | --- |
| 2015 PACT | Communication Avoiding Algorithms: Analysis and Code Generation for Parallel Systems[[paper]](https://ieeexplore.ieee.org/abstract/document/7429302) |  |  |

----


## Poly for Domain-Specific-Compiler
| **Date** | **Paper** | **Main Contribute** | **Notes** |
| --- | --- | --- | --- |
| 2014 IMPACT | Presentation: Domain-specific languages and optimizers[[slides]](https://acohen.gitlabpages.inria.fr/impact/impact2014/papers/impact2014-bondhugula-slides.pdf) |  |  |
| 2019 | Polyhedral Compilation for Domain Specific Languages[[paper]](https://hal.inria.fr/tel-02385670/document) |  |  |
----

## Poly for Hardware/HLS
| **Date** | **Paper** | **Main Contribute** | **Notes** |
| --- | --- | --- | --- |
| 2014 FPGA | Theory and algorithm for generalized memory partitioning in high-level synthesis [[paper]](https://dl.acm.org/doi/10.1145/2554688.2554780)  | FPGA HLS |  |
| 2014 IMPACT | Throughput Optimization for High-Level Synthesis Using Resource Constraints [[no paper]]() [[sldies]](https://acohen.gitlabpages.inria.fr/impact/impact2014/papers/impact2014-li-slides.pdf) | FPGA HLS |  |
| 2015 DATE | Interplay of loop unrolling and multidimensional memory partitioning in HLS [[paper]](https://ieeexplore.ieee.org/abstract/document/7092376)  | FPGA HLS |  |
| 2015 FCCM | Offline Synthesis of Online Dependence Testing: Parametric Loop Pipelining for HLS[[paper]](https://ieeexplore.ieee.org/abstract/document/7160061) | FPGA HLS |  |
| 2015 ICCAD | A polyhedral-based SystemC modeling and generation framework for effective low-power design space exploration[[paper]](https://ieeexplore.ieee.org/abstract/document/7372592) | FPGA HLS |  |
| 2016 IMPACT | Towards Scalable and Efficient FPGA Stencil Accelerators[[paper]](https://acohen.gitlabpages.inria.fr/impact/impact2016/papers/impact2016-deest.pdf) [[sldies]](https://acohen.gitlabpages.inria.fr/impact/impact2016/papers/impact2016-deest-slides.pdf) | FPGA HLS |  |
| 2016 FCCM | Loop Splitting for Efficient Pipelining in High-Level Synthesis[[paper]](https://ieeexplore.ieee.org/abstract/document/7544750) | FPGA HLS |  |
| 2017 TCAD | Efficient Memory Partitioning for Parallel Data Access in FPGA via Data Reuse[[paper]](https://ieeexplore.ieee.org/abstract/document/7807209) | Memory Partitioning |  |
| 2017 FPL | Tile size selection for optimized memory reuse in high-level synthesis[[paper]](https://ieeexplore.ieee.org/abstract/document/8056810) | FPGA HLS |  |
| 2018 TCAD | Polyhedral-Based Dynamic Loop Pipelining for High-Level Synthesis[[paper]](https://ieeexplore.ieee.org/abstract/document/8207646) | FPGA HLS Pipeline |  |
| 2019 DAC | Graph-Morphing: Exploiting Hidden Parallelism of Non-Stencil Computation in High-Level Synthesis[[paper]](https://dl.acm.org/doi/abs/10.1145/3316781.3317834) | FPGA HLS Pipeline |  |
| 2020 IMPACT | TC-CIM: Empowering Tensor Comprehensions for Computing In-Memory[[paper]](https://acohen.gitlabpages.inria.fr/impact/impact2020/papers/IMPACT_2020_paper_2.pdf) [[sldies]](https://acohen.gitlabpages.inria.fr/impact/impact2020/slides/IMPACT_2020_slides_2.pdf) | ReRAM Compiler |  |
| 2020 IMPACT | Generating SIMD Instructions for Cerebras CS-1 using Polyhedral Compilation Techniques[[paper]](https://acohen.gitlabpages.inria.fr/impact/impact2020/papers/IMPACT_2020_paper_3.pdf) [[sldies]](https://acohen.gitlabpages.inria.fr/impact/impact2020/slides/IMPACT_2020_slides_3.pdf) | ReRAM Compiler | AI Chip |
| 2020 IMPACT | Bounded Stream Scheduling in Polyhedral OpenStream[[paper]](https://acohen.gitlabpages.inria.fr/impact/impact2020/papers/IMPACT_2020_paper_4_new.pdf) [[sldies]](https://acohen.gitlabpages.inria.fr/impact/impact2020/slides/IMPACT_2020_slides_4.pdf) | Dataflow Compiler |  |
| 2021 IMPACT | Hardware Abstractions for targeting EDDO Architectures with the Polyhedral Model[[paper]](https://acohen.gitlabpages.inria.fr/impact/impact2021/papers/IMPACT_2021_paper_6.pdf) [[sldies]](https://acohen.gitlabpages.inria.fr/impact/impact2021/slides/IMPACT_2021_slides_6.pdf) |  |  |
----


## Poly Tools
| **Date** | **Paper** | **Main Contribute** | **Notes** |
| --- | --- | --- | --- |
| 2015 IMPACT | Manipulating visualization, not codes[[paper]](https://acohen.gitlabpages.inria.fr/impact/impact2015/papers/impact2015-zinenko.pdf) [[sldies]](https://acohen.gitlabpages.inria.fr/impact/impact2015/papers/impact2015-zinenko-slides.pdf)[[code]](https://github.com/ftynse/clint) | Poly模型可视化 | 没有发布 |
| 2020 IMPACT | Farkas Lemma made easy Tool Demo[[paper]](https://acohen.gitlabpages.inria.fr/impact/impact2020/papers/IMPACT_2020_paper_1.pdf) [[sldies]](https://acohen.gitlabpages.inria.fr/impact/impact2020/slides/IMPACT_2020_slides_1.pdf)[[website]](https://foobar.ens-lyon.fr/fkcc/index.php) | Farkas |  |



## Poly on multi-cpu/gpu
| **Date** | **Paper** | **Main Contribute** | **Notes** |
| --- | --- | --- | --- |
| 2020 IMPACT | md_poly: A Performance-Portable Polyhedral Compiler based on Multi-Dimensional Homomorphisms[[paper]](https://acohen.gitlabpages.inria.fr/impact/impact2020/papers/IMPACT_2020_paper_5.pdf) [[sldies]](https://acohen.gitlabpages.inria.fr/impact/impact2020/slides/IMPACT_2020_slides_5.pdf) | multi-cpu/gpu |  |


## Poly for Pipeline
| **Date** | **Paper** | **Main Contribute** | **Notes** |
| --- | --- | --- | --- |
| 2020 IMPACT | Pipelined Multithreading Generation in a Polyhedral Compiler[[paper]](https://acohen.gitlabpages.inria.fr/impact/impact2020/papers/IMPACT_2020_paper_8.pdf) [[sldies]](https://acohen.gitlabpages.inria.fr/impact/impact2020/slides/IMPACT_2020_slides_8.pdf) | multi-thread pipeline |  |


## Poly for datalayout
| **Date** | **Paper** | **Main Contribute** | **Notes** |
| --- | --- | --- | --- |
| 2019 IMPACT | Integrating Data Layout Transformations with the Polyhedral Model[[paper]](https://acohen.gitlabpages.inria.fr/impact/impact2019/papers/IMPACT_2019_paper_8.pdf) [[sldies]](https://acohen.gitlabpages.inria.fr/impact/impact2019/slides/IMPACT_2019_slides_8.pdf) |  |  |

## Poly for Tiling
| **Date** | **Paper** | **Main Contribute** | **Notes** |
| --- | --- | --- | --- |
| 2014 IMPACT | Constant Aspect Ratio Tiling[[paper]](https://acohen.gitlabpages.inria.fr/impact/impact2014/papers/impact2014-iooss.pdf) [[sldies]](https://acohen.gitlabpages.inria.fr/impact/impact2014/papers/impact2014-iooss-slides.pdf) |  |  |
| 2014 IMPACT | Parametric Tiling with Inter-Tile Data Reuse[[paper]](https://acohen.gitlabpages.inria.fr/impact/impact2014/papers/impact2014-darte.pdf) [[sldies]](https://acohen.gitlabpages.inria.fr/impact/impact2014/papers/impact2014-darte-slides.pdf) |  |  |
| 2014 IMPACT | Tiling for Dynamic Scheduling[[paper]](https://acohen.gitlabpages.inria.fr/impact/impact2014/papers/impact2014-mullapudi.pdf) [[sldies]](https://acohen.gitlabpages.inria.fr/impact/impact2014/papers/impact2014-mullapudi-slides.pdf) |  |  |

## Poly for Scheduling and Optimization
| **Date** | **Paper** | **Main Contribute** | **Notes** |
| --- | --- | --- | --- |
| 2014 IMPACT | Schedule Trees [[paper]](https://acohen.gitlabpages.inria.fr/impact/impact2014/papers/impact2014-verdoolaege.pdf)[[slides]](https://acohen.gitlabpages.inria.fr/impact/impact2014/papers/impact2014-verdoolaege-slides.pdf)  | |  |
| 2018 IMPACT | Optimization Through Recomputation in the Polyhedral Model[[paper]](https://acohen.gitlabpages.inria.fr/impact/impact2018/papers/recomputation.pdf) [[sldies]](https://acohen.gitlabpages.inria.fr/impact/impact2018/papers/recomputation-slides.pdf) | DL应用Recomputation |  |

