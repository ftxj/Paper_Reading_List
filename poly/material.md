# Book

* (2001) Optimizing Compilers for Modern Architectures: A Dependence-based Approach [[pdf]](Dependence-Approach-Compiler.pdf)

# Course
* 中科大 https://s4plus.ustc.edu.cn/kjxz/list.htm

| **Date** | **Paper** | **Main Contribute** | **Notes** |
| --- | --- | --- | --- |
| 1991 |Optimizing the Memory Hierarchy by Compositing Automatic Transformations on Computations and Data [[paper]](https://ieeexplore.ieee.org/document/9251965) [[slides]](https://www.di.ens.fr/~zhaojie/micro2020-presentation) | Xin Jie | Micro '20 |
| 1991 | Template Paper Title [[paper]](paper link) [[slides]](/slides/test.pdf) | Your Name | Any Other |
| 2016 CC | Mapping Deviation: A Technique to Adapt or to Guard Loop Transformation Intuitions for Legality [[paper]]((https://dl.acm.org/doi/abs/10.1145/2892208.2892216))  | 多面体模型优化太过于黑盒,没有反馈 |  |

----

## Ploy in Non-affine Type (Sparse Data...)
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
| 2018 IMPACT | Abstractions for Specifying Sparse Matrix Data Transformations[[paper]](http://impact.gforge.inria.fr/impact2018/papers/sparse-abstractions.pdf) |  | |



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
| 2019 | Polyhedral Compilation for Domain Specific Languages[[paper]](https://hal.inria.fr/tel-02385670/document) |  |  |
----
