# Book

* (2001) Optimizing Compilers for Modern Architectures: A Dependence-based Approach [[pdf]](Dependence-Approach-Compiler.pdf)

# Course
* 中科大 https://s4plus.ustc.edu.cn/kjxz/list.htm

| **Date** | **Paper** | **Main Contribute** | **Notes** |
| --- | --- | --- | --- |
| 1991 |Optimizing the Memory Hierarchy by Compositing Automatic Transformations on Computations and Data [[paper]](https://ieeexplore.ieee.org/document/9251965) [[slides]](https://www.di.ens.fr/~zhaojie/micro2020-presentation) | Xin Jie | Micro '20 |
| 1991 | Template Paper Title [[paper]](paper link) [[slides]](/slides/test.pdf) | Your Name | Any Other |

----

## Ploy in Non-affine
| **Date** | **Paper** | **Main Contribute** | **Notes** |
| --- | --- | --- | --- |
| 2014 CGO |Non-affine Extensions to Polyhedral Code Generation [[paper]](https://dl.acm.org/doi/abs/10.1145/2544137.2544141) | 第一个在Polyhedral模型中应用到Sparse数据结构上 | 分析loop bound, Trans |
| 2015 PLDI | Loop and Data Transformations for Sparse Matrix Code [[paper]](https://dl.acm.org/doi/10.1145/2737924.2738003) [[slides]](https://pldi15.sigplan.org/details/pldi2015-papers/65/Loop-and-Data-Transformations-for-Sparse-Matrix-Code) | 从稠密矩阵模式生成稀疏矩阵.抽象转化原语 | make_dense |
| 2015 TACO | The Polyhedral Model of Nonlinear Loops[[paper]]([](https://dl.acm.org/doi/10.1145/2737924.2738003)) | 非线性bound, memory access |  |
| 2016 PARCO | An approach for code generation in the Sparse Polyhedral Framework[[paper]](https://www.sciencedirect.com/science/article/pii/S0167819116000557) |  |  |
| 2016 SC | Automating Wavefront Parallelization for Sparse Matrix Computations[[paper]](https://ieeexplore.ieee.org/document/7877119) | 稀疏数据 |  |
| 2017 SC | Sympiler: Transforming Sparse Matrix Codes by Decoupling Symbolic Analysis[[paper]](https://dl.acm.org/doi/abs/10.1145/3126908.3126936)[[slides]](https://www.sympiler.com/index_files/Sympiler_SC17_TALK.pdf)[[project]](https://www.sympiler.com/) | Domain-Specific-Compiler for Sparse Matrix | 一个做了很多年的系统 |

## Poly in weak-dependence
| **Date** | **Paper** | **Main Contribute** | **Notes** |
| --- | --- | --- | --- |
| 2015 IMPACT | Polly’s Polyhedral Scheduling in the Presence of Reductions[[paper]](https://arxiv.org/pdf/1505.07716.pdf)[[slides]](http://impact.gforge.inria.fr/impact2015/papers/impact2015-doerfert-slides.pdf) | reduce_sum类型的应用不需要强依赖关系 |  |
| 2016 PACT | Reduction Drawing: Language Constructs and Polyhedral Compilation for Reductions on GPUs [[paper]](https://hal.inria.fr/hal-01425750/document) | 也是reduce |  |
----