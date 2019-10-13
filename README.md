# awesome-TDA

A curated list of [TDA](https://en.wikipedia.org/wiki/Topological_data_analysis) resources and links. In applied mathematics, topological data analysis (TDA) is an approach to the analysis of datasets using techniques from topology. under development!

## Contents

<!--lint disable no-missing-blank-lines alphabetize-lists list-item-punctuation-->

- [Theory](#theory)
  - [Algorithms](#algorithms) 
  - [Books](#books)
  - [Articles](#articles)
  - [Courses](#courses)
  - [Other lists](#other-lists)
- [Tools](#tools)
  - [TdaToolbox](#tdatoolbox)
  - [TTk](#ttk)
- [Frameworks and Libs](#frameworks-and-libs)
  - [C++](#c++)
    - [Ctl](#ctl)
    - [Dionysus](#dionysus)
    - [GUDHI](#gudhi)
    - [PHAT](#phat)
    - [RIVET](#rivet)
    - [TDA](#tda)
  - [Haskell](#haskell)
    - [Persistence](#persistence)
  - [Java](#java)
    - [JavaPlex](#javaplex)
  - [Python](#python)
    - [KeplerMapper](#keplermapper)
    - [kohonen](#kohonen)
    - [Mapper implementation TDA](#mapper-implementation-tda)
    - [mogutda](#mogutda)
    - [openTDA](#opentdpdfa)
    - [Python Mapper](#python-mapper)
    - [Scikit-TDA](#scikit-tda)
    - [scTDA](#sctda)
  - [R](#r)
    - [TDAmapper](#tdamapper)
    - [TDAstats](#tdastats)
  - [Spark](#spark)
    - [Spark Mapper](#spark-mapper)
    - [Spark-tda](#spark-tda)
- [Useful Links](#useful-links)
  - [A concrete application of Topological Data Analysis](#a-concrete-application-of-topological-data-analysis)
  - [Computing Homology](#computing-homology)
  - [Persistent Homology](#persistent-homology)
  - [TDA and Data Professionals](#tda-and-data-professionals)
  - [TDA and Deep Learning](#tda-and-deep-learning)
  - [TDA and Machine Learning](#tda-and-machine-learning)
- [License](#license)

<!--lint enable no-missing-blank-lines alphabetize-lists list-item-punctuation-->

- - -

## Theory

### Algorithms
* Morse-Smale complex
* Persistent homology computation
* Persistent cohomology computation
* Reeb graph
* Vineyards
* Zigzag persistent homology
* Topological Domains in Mammalian Genomes Identified by Analysis of Chromatin Interactions
  
### Books
   
* A Short Course in Computational Geometry and Topology - Edelsbrunner, Herbert [springer link](https://www.springer.com/gp/book/9783319059563)

* Persistence Theory: From Quiver Representations to Data Analysis - Steve Y. Oudot [Online](https://bookstore.ams.org/surv-209/) [PDF](https://geometrica.saclay.inria.fr/team/Steve.Oudot/books/o-pt-fqrtda-15/surv-209.pdf)
F
* Topological and Statistical Methods for Complex Data: Tackling Large-Scale, High-Dimensional, and Multivariate Data Spaces -  Bennett, Janine, Vivodtzev, Fabien, Pascucci, Valerio (Eds.) [springer link](https://www.springer.com/gp/book/9783662448991)  
  
* Topological Data Analysis for Scientific Visualization - Tierny, Julien [springer link](https://www.springer.com/gp/book/9783319715063) 

* Topological Methods in Data Analysis and Visualization: Theory, Algorithms, and Applications - Pascucci, V., Tricoche, X., Hagen, H., Tierny, J. (Eds.) [springer link](https://www.springer.com/gp/book/9783642150135)
   
* Topological Methods in Data Analysis and Visualization-II: Theory, Algorithms, and Applications - Peikert, R., Hauser, H., Carr, H., Fuchs, R. (Eds.) [springer link](https://www.springer.com/gp/book/9783642231742) 
 
* Topological Methods in Data Analysis and Visualization-III: Theory, Algorithms, and Applications - Bremer, P.-T., Hotz, I., Pascucci, V., Peikert, R. (Eds.) [springer link](https://www.springer.com/gp/book/9783319040981) 
  
* Topological Methods in Data Analysis and Visualization-IV: Theory, Algorithms, and Applications - Carr, Hamish, Garth, Christoph, Weinkauf, Tino (Eds.) [springer link](https://www.springer.com/gp/book/9783319446820)
  
* Topology-based Methods in Visualization-  Hauser, Helwig, Hagen, Hans, Theisel, Holger (Eds.) [springer link](https://www.springer.com/gp/book/9783540708223)
  
### Articles

* A Fuzzy Clustering Algorithm for the Mode Seeking Framework - Bonis, Oudot [arxiv](https://arxiv.org/abs/1406.7130)

* A User’s Guide to Topological Data Analysis - Elizabeth Munch [read online](https://learning-analytics.info/journals/index.php/JLA/article/view/5196/6089) 
  
* An introduction to Topological Data Analysis:  fundamental and practical aspects for data scientists - Chazal, Michel [arxiv](https://arxiv.org/abs/1710.04019) 

* Computing Persistent Homology (Discrete and Computational Geometry) - Zomorodian, Carlsson [PDF](https://geometry.stanford.edu/papers/zc-cph-05/zc-cph-05.pdf)

* Introduction to the R package TDA - Fasy, Jisu Kim, Lecci, Clément Maria, Millman, Rouvreau] [PDF](cran.r-project.org/web/packages/TDA/vignettes/article.pdf)
  
* Homological Algebra and Data - Robert Ghrist [PDF](https://www.math.upenn.edu/~ghrist/preprints/HAD.pdf)
  
* Large Scale computation of Means and Clusters for Persistence Diagrams using Optimal Transport -  Lacombe, Cuturi, OUDOT [arxiv](https://arxiv.org/abs/1805.08331)
  
* Topological Data Analysis - Larry Wasserman [arxiv](https://arxiv.org/abs/1609.08227) 

* Topological Data Analysis for Object Data - Patrangenaru, Bubenik, Paige, Osborne [arxiv](https://arxiv.org/abs/1804.10255) 

* Two-Tier Mapper: a user-independent clustering method for global gene expression analysis based on topology [arxiv](https://arxiv.org/abs/1801.01841) 

### Courses
- [Computational Topology and Data Analysis](http://web.cse.ohio-state.edu/~dey.8/course/CTDA/CTDA.html) A course is not active, but the course notes are useful

- [Topological Data Analysis](http://www.enseignement.polytechnique.fr/informatique/INF556/#Synopsis) A course is not active, but the course notes are useful

- [Topological Data Analysis](https://people.clas.ufl.edu/peterbubenik/intro-to-tda/)

### Other lists

## Tools
### TdaToolbox
[TdaToolbox](https://github.com/Coricos/TdaToolbox)
  - [3DShape] - This notebook gives a simple example of how to handle three-dimensional shapes. The whole example is based on the height as filtration function, so not invariant in space. However, it gives a pretty good idea of what the output of a topological analysis may give.
  - [ToMaTo Clustering] - This notebook rather focus on a specific strength of TDA: its robustness to detect centroids in dataset, along with its ability to record the relationships between each point, enabling us to retrace the whole structure of the centroids. Examples are provided in the notebook.

### TTK
[TTk](https://topology-tool-kit.github.io/index.html) - The Topology ToolKit is an open-source library and software collection for topological data analysis in scientific visualization. TTK can handle scalar data defined either on regular grids or triangulations, either in 2D or in 3D. It provides a substantial collection of generic, efficient and robust implementations of key algorithms in topological data analysis.

For more information you can read ["Topological Data Analysis Made Easy with the Topology ToolKit"](https://arxiv.org/pdf/1806.08126.pdf) article.

## Frameworks and Libs

### C++
#### ctl
[Ctl](https://github.com/appliedtopology/ctl) - This C++11 library provides a set of generic tools for:
  - Building Neighborhood Graphs
  - Building Cellular Complexes
  - Computing [persistent] homology over finite fields
  - Parallel algorithm(s) for homology
  
#### Dionysus
[Dionysus](http://mrzv.org/software/dionysus/) - Dionysus is a C++ library for computing persistent homology. It provides implementations of the following algorithms:
  - Persistent homology computation 
  - Vineyards (C++ only)
  - Persistent cohomology computation 
  - Zigzag persistent homology 

#### GUDHI
[GUDHI](http://gudhi.gforge.inria.fr/) - The GUDHI library is a generic open source C++ library, with a Python interface, for Topological Data Analysis (TDA) and Higher Dimensional Geometry Understanding. The library offers state-of-the-art data structures and algorithms to construct simplicial complexes and compute persistent homology.

####  PHAT
[phat](https://bitbucket.org/phat-code/phat) - This software library contains methods for computing the persistence pairs of a filtered cell complex represented by an ordered boundary matrix with Z<sub>2</sub> coefficients. For an introduction to persistent homology, see the textbook. This software package contains code for several algorithmic variants:
  - The "standard" algorithm 
  - The "row" algorithm 
  - The "twist" algorithm
  - The "chunk" algorithm 
  - The "spectral sequence" algorithm 
  
#### RIVET
[RIVET](https://github.com/rivetTDA/rivet) - for the visualization and analysis of two-parameter persistent homology. RIVET is made available under the under the terms of the GNU General Public License. The RIVET documentation lives [here](https://rivet.readthedocs.io).
  
#### TDA
[TDA](https://cran.r-project.org/web/packages/TDA/) - tools for the statistical analysis of persistent homology and for density clustering. For that, this package provides an R interface for the efficient algorithms of the C++ libraries [GUDHI](http://gudhi.gforge.inria.fr/), [Dionysus](http://www.mrzv.org/software/dionysus/), and [PHAT](https://bitbucket.org/phat-code/phat/). This package also implements the methods in Fasy et al. [(2014)](doi:10.1214/14-AOS1252) and Chazal et al. [(2014)](doi:10.1145/2582112.2582128) for analyzing the statistical significance of persistent homology features.


### Haskell 
#### Persistence
[Persistence](https://hackage.haskell.org/package/Persistence) - A topological data analysis library motivated by flexibility when it comes to the type of data being analyzed. If your data comes with a meaningful binary function into an ordered set, you can use Persistence to analyze your data. The library also provides functions for analyzing directed/undirected, weighted/unweighted graphs. See the README for resources on learning about topological data anlysis.


### Java
#### JavaPlex
[JavaPlex](https://github.com/appliedtopology/javaplex) - Persistent Homology and Topological Data Analysis Library - The JavaPlex library implements persistent homology and related techniques from computational and applied topology, in a library designed for ease of use, ease of access from Matlab and java-based systems, and ease of extensions for further research projects and approaches. JavaPlex is mainly developed by the Computational Topology workgroup at Stanford University, and is based on previous similar packages from the same group.

### Python
#### KeplerMapper
[KeplerMapper](https://github.com/MLWave/kepler-mapper) - This is a Python implementation of the TDA Mapper algorithm for visualization of high-dimensional data. For complete documentation, see https://kepler-mapper.scikit-tda.org.
KeplerMapper employs approaches based on the Mapper algorithm (Singh et al.) as first described in the paper "Topological Methods for the Analysis of High Dimensional Data Sets and 3D Object Recognition".
KeplerMapper can make use of Scikit-Learn API compatible cluster and scaling algorithms.

#### kohonen
[kohonen](https://github.com/lmjohns3/kohonen) - This module contains some basic implementations of Kohonen-style vector quantizers: Self-Organizing Map (SOM), Neural Gas, and Growing Neural Gas. Kohonen-style vector quantizers use some sort of explicitly specified topology to encourage good separation among prototype "neurons".

#### Mapper implementation TDA
[Mapper implementation](https://github.com/ksanjeevan/mapper-tda) - Topological Data Analysis for high dimensional dataset exploration

#### mogutda
[mogutda](https://github.com/stephenhky/MoguTDA) - mogutda contains Python codes that demonstrate the numerical calculation of algebraic topology in an application to topological data analysis (TDA). Its core code is the numerical methods concerning implicial complex, and the estimation of homology and Betti numbers. mogutda runs in Python 2.7, 3.5, and 3.6.

#### openTDA
[openTDA](https://github.com/outlace/OpenTDA) - Open source Python library for topological data analysis (TDA)

#### Python Mapper
[Python Mapper](http://danifold.net/mapper/introduction.html) - Python Mapper is a realization of this toolchain, written by Daniel Müllner and Aravindakshan Babu. It is open source software and is released under the GNU GPLv3 license. 
There is also a company, Ayasdi, which was founded by Gurjeet Singh, Gunnar Carlsson and Harlan Sexton and whose main product, the [Ayasdi Iris software](https://www.ayasdi.com/solutions/clinical-variation-management/), has the Mapper algorithm at its core. Ayasdi also issues academic trial licenses.

#### Scikit-TDA
[Scikit-TDA](https://scikit-tda.org/) - Scikit-TDA is a home for compatible TDA Python libraries intended for non-topologists. This project aims to provide a curated library of TDA Python tools that are widely usable and easily approachable.
It is structured so that each package can stand alone or be used as part of the scikit-tda bundle.
Current packages available:
  - [Ripser] - Data to diagrams in one line
  - [Persim] - Easy Persistence Images
  - [UMAP] - Mathematically justified dimensionality reduction
  - [Kepler Mapper] - Mapper framework integrated into sklearn
  - [TaDAsets] - Constructors for common data sets for demonstrating TDa.

#### scTDA
[scTDA](https://github.com/CamaraLab/scTDA) - scTDA is an object oriented python library for topological data analysis of high-throughput single-cell RNA-seq data. It includes tools for the preprocessing, analysis, and exploration of single-cell RNA-seq data based on topological representations.

### R
#### TDAmapper
[TDAmapper](https://github.com/paultpearson/TDAmapper/) - Topological Data Analysis using Mapper - An R package for using discrete Morse theory to analyze a data set using the Mapper algorithm described in G. Singh, F. Memoli, G. Carlsson (2007)

#### TDAstats
[TDAstats](https://github.com/rrrlw/TDAstats) - TDAstats is an R pipeline for computing persistent homology in topological data analysis.

### Spark
#### Spark Mapper
[Spark Mapper](https://github.com/log0ymxm/spark-mapper) - Mapper is a topological data anlysis technique for estimating a lower dimensional simplicial complex from a dataset. It was initially described in the paper "Topological Methods for the Analysis of High Dimensional Data Sets and 3D Object Recognition."

#### spark-tda
[spark-tda](https://github.com/ognis1205/spark-tda) - The scalable topological data analysis package for Apache Spark. This project aims to implement the following features:
  - [ Scalable Mapper Implemented as Reeb Diagrams, i.e., Reeb Cosheaves]
  - [Scalable Mapper Implementation]
  - [Scalable Multiscale Mapper Implementation]
  - [Scalable Tower Computation for Multiscale Mapper]
  - [Scalable Persistent Homology Computation on Top of Apache Spark]
  
 For more information you can read ["Sparse-TDA: Sparse Realization of Topological Data Analysis for Multi-Way Classification"](https://arxiv.org/pdf/1701.03212.pdf) article.
  
## Useful Links

### A concrete application of Topological Data Analysis
- [A concrete application of Topological Data Analysis](https://towardsdatascience.com/a-concrete-application-of-topological-data-analysis-86b89aa27586)

### Computing Homology
- [Computing Homology](https://jeremykun.com/2013/04/10/computing-homology/)

### Persistent Homology
- [A roadmap for the computation of persistent homology](https://epjdatascience.springeropen.com/articles/10.1140/epjds/s13688-017-0109-5#Sec34)

- [Practical Guide to Persistent Homology](http://www.mrzv.org/software/dionysus2/tutorial/index.html)

### TDA and Data Professionals
- [Topological Data Analysis for Data Professionals](https://www.kdnuggets.com/2018/01/topological-data-analysis.html)

### TDA and Deep Learning
- [From Topological Data Analysis to Deep Learning: No Pain No Gain](https://towardsdatascience.com/from-tda-to-dl-d06f234f51d)

- [On Characterizing the Capacity of Neural Networks Using Algebraic Topology](https://openreview.net/forum?id=H11lAfbCW)

- [Using Topological Data Analysis to Understand the Behavior of Convolutional Neural Networks](https://www.ayasdi.com/blog/artificial-intelligence/using-topological-data-analysis-understand-behavior-convolutional-neural-networks/)

### TDA and Machine Learning
- [How TDA and Machine Learning Enhance Each Other](https://www.ayasdi.com/blog/bigdata/how-tda-and-machine-learning-enhance-each-other/)

- [Topological Machine Learning](https://www.sthu.org/research/topmachinelearning/)


## License

`awesome-TDA by [@FatemehTarashi](https://github.com/FatemehTarashi) is licensed under the
GNU General Public License v3.0
