# Awesome Algebraic Statistics [![Awesome](https://awesome.re/badge.svg)](https://github.com/sindresorhus/awesome)

A curated list of Algebraic Statistics tools and resources.

Algebraic statistics uses techniques from algebraic geometry, commutative algebra, combinatorics, and computational algebra to study statistical models and their applications.

If you know of any other tools or resources, read the [Contribution Guidelines](contributing.md) and feel free to fork/PR or open a new issue.

## Contents

<!--lint disable no-missing-blank-lines alphabetize-lists list-item-punctuation-->

- [Theory](#theory)
  - [Books](#books)
  - [Articles](#articles)
- [Tools](#tools)
  - [C++](#c)
  - [Julia / OSCAR](#julia--oscar)
  - [Macaulay2](#macaulay2)
  - [Python](#python)
  - [R](#r)
- [Useful Links](#useful-links)
- [Events](#events)
  - [Upcoming Events](#upcoming-events)
  - [Past Events](#past-events)

<!--lint enable no-missing-blank-lines alphabetize-lists list-item-punctuation-->

## Theory

### Books

- [Algebraic Statistics](https://www.ams.org/books/gsm/194/) - Sullivant.
- [Algebraic Statistics](https://tore.tuhh.de/bitstream/11420/1271/1/book.pdf) - Zimmermann.
- [Algebraic Statistics for Computational Biology](https://www.cambridge.org/core/books/algebraic-statistics-for-computational-biology/2E5CCE6BB6751EB7423EE3D2BF40EBFF) - Pachter, and Sturmfels.
- [An Introduction to Algebraic Statistics](https://www3.diism.unisi.it/~chiantini/did/00Book.pdf) - Bocci, Chiantini, and Geramita.
- [Lectures on Algebraic Statistics](https://link.springer.com/book/10.1007/978-3-7643-8905-5) - Drton, Sturmfels, and Sullivant.
- [Metric Algebraic Geometry](https://link.springer.com/book/10.1007/978-3-031-51462-3) - Breiding, Kohn, and Sturmfels.

### Articles

- [Algebraic Algorithms for Sampling from Conditional Distributions](https://projecteuclid.org/journals/annals-of-statistics/volume-26/issue-1/Algebraic-algorithms-for-sampling-from-conditional-distributions/10.1214/aos/1030563990.full) - Diaconis, and Sturmfels.
- [Algebraic Optimization Degree](https://doi.org/10.1145/3427218.3427222) - Härkönen, Hollering, Tarashi Kashani, and Rodriguez.
- [Algebraic Statistics](https://math.uchicago.edu/~may/REU2020/REUPapers/Mi,Sabrina.pdf) - Mi.
- [Algebraic Statistics and Contingency Table Problems: Log-Linear Models, Likelihood Estimation, and Disclosure Limitation](https://www.stat.cmu.edu/~arinaldo/papers/IMA_final.pdf) - Dobra, Fienberg, Rinaldo, Slavkovic, and Zhou.
- [Algebraic Statistics in Model Selection](https://arxiv.org/pdf/1207.4112.pdf) - Garcia.
- [Algebraic Statistics in OSCAR](https://arxiv.org/abs/2601.15807) - Boege, Della Vecchia, Garrote López, and Hollering.
- [Algebraic Statistics in Practice: Applications to Networks](https://arxiv.org/abs/1906.09537) - Casanellas, Petrović, and Uhler.
- [Algebraic statistical models](https://www3.stat.sinica.edu.tw/statistica/oldpdf/A17n41.pdf) - Drton, and Sullivant.
- [Algebraic statistics, tables, and networks: The Fienberg advantage](https://arxiv.org/pdf/1910.01692.pdf) - Gross, Karwa, and Petrovic.
- [Geometry of Maximum Likelihood Estimation in Gaussian Graphical Models](https://arxiv.org/abs/1012.2643) - Uhler.
- [Introductory Notes to Algebraic Statistics](https://www.openstarts.units.it/bitstream/10077/4141/1/HostenRuffaRendMat37.pdf) - Hoşten, and Ruffa.
- [Likelihood Geometry](https://web.math.princeton.edu/~huh/LikelihoodGeometry.pdf) - Huh, and Sturmfels.
- [Markov Bases: A 25 Year Update](https://arxiv.org/abs/2306.06270) - Almendra-Hernández, De Loera, and Petrović.
- [New Directions in Algebraic Statistics: Three Challenges from 2023](https://arxiv.org/pdf/2402.13961) - Alexandr, Bakenhus, Curiel, Deshpande, Gross, Gu, Hill, Johnson, Kagy, Karwa, Li, Lyu, Petrović, and Rodriguez.
- [Open Problems in Algebraic Statistics](https://arxiv.org/pdf/0707.4558.pdf) - Sturmfels.
- [TAPAS of Algebraic Statistics](https://upcommons.upc.edu/bitstream/handle/2117/121825/AMS_AlgStat_edited.pdf?sequence=1) - Endola, Casanellas, and Puente.
- [Tensors in Algebraic Statistics](https://arxiv.org/abs/2411.14080) - Casanellas, Sierra, and Zwiernik.
- [The Maximum Likelihood Degree of a Very Affine Variety](https://arxiv.org/abs/1207.0553) - Huh.
- [Thesis: The Algebraic Statistics of Sampling, Likelihood, and Regression](https://orlandomarigliano.com/thesis.pdf) - Marigliano.
- [Schur multipliers, vanishing minors and Gaussian conditional independence](https://arxiv.org/abs/2611.20982) - Leonelli

## Tools

### C++

- [4ti2](https://4ti2.github.io/) - A software package for algebraic, geometric, and combinatorial problems on linear spaces.
- [Bertini](https://bertini.nd.edu/) - Software for numerical algebraic geometry and homotopy continuation.
- [LattE Integrale](https://www.math.ucdavis.edu/~latte/) - Software for lattice point enumeration and integration over convex polytopes.
- [Normaliz](https://www.normaliz.uni-osnabrueck.de/) - A software tool for computations in affine monoids, vector configurations, lattice polytopes, and rational cones.
- [polymake](https://polymake.org/) - Open-source software for research in polyhedral geometry and tropical geometry.

### Julia / OSCAR

- [Algebraic Statistics in OSCAR](https://docs.oscar-system.org/stable/Experimental/AlgebraicStatistics/introduction/) - Experimental OSCAR functionality for common algebraic statistical models.
- [AlgebraicStatistics.jl](https://github.com/bkholler/AlgebraicStatistics.jl) - A Julia / OSCAR package for algebraic statistics.
- [HomotopyContinuation.jl](https://www.juliahomotopycontinuation.org/) - Solving systems of polynomials via numerical homotopy continuation, widely used for computing ML degrees.
- [OSCAR](https://oscar-system.org/) - Comprehensive open-source computer algebra system in Julia with dedicated AlgebraicStatistics functionality.

### Macaulay2

- [AlgebraicOptimization](https://github.com/Macaulay2/Workshop-2020-Cleveland/tree/master/alg-stat/AlgebraicOptimization) - Methods for determining the algebraic degree of an optimization problem, including Euclidean distance degrees and maximum likelihood degrees ([paper](https://doi.org/10.1145/3427218.3427222)).
- [AllMarkovBases](https://macaulay2.com/doc/Macaulay2/share/doc/Macaulay2/AllMarkovBases/html/index.html) - Computing all minimal Markov bases of a configuration matrix.
- [BinomialEdgeIdeals](https://macaulay2.com/doc/Macaulay2/share/doc/Macaulay2/BinomialEdgeIdeals/html/index.html) - Binomial edge ideals of graphs arising in conditional independence and graphical models.
- [EuclideanDistanceDegree](https://macaulay2.com/doc/Macaulay2/share/doc/Macaulay2/EuclideanDistanceDegree/html/index.html) - Euclidean distance degrees of algebraic varieties.
- [FourTiTwo](https://macaulay2.com/doc/Macaulay2/share/doc/Macaulay2/FourTiTwo/html/index.html) - Macaulay2 interface to 4ti2.
- [GraphicalModels](https://macaulay2.com/doc/Macaulay2/share/doc/Macaulay2/GraphicalModels/html/index.html) - Discrete and Gaussian graphical models.
- [GraphicalModelsMLE](https://macaulay2.com/doc/Macaulay2/share/doc/Macaulay2/GraphicalModelsMLE/html/index.html) - Maximum likelihood estimates for graphical statistical models.
- [LikelihoodGeometry](https://macaulay2.com/doc/Macaulay2/share/doc/Macaulay2/LikelihoodGeometry/html/index.html) - Likelihood correspondences and likelihood ideals for discrete algebraic statistical models.
- [Markov](https://macaulay2.com/doc/Macaulay2/share/doc/Macaulay2/Markov/html/index.html) - Markov ideals arising from Bayesian networks in statistics.
- [MultigradedImplicitization](https://macaulay2.com/doc/Macaulay2/share/doc/Macaulay2/MultigradedImplicitization/html/index.html) - Implicitization problems using multigradings.
- [PhylogeneticTrees](https://macaulay2.com/doc/Macaulay2/share/doc/Macaulay2/PhylogeneticTrees/html/index.html) - Invariants for group-based phylogenetic models.
- [Probability](https://macaulay2.com/doc/Macaulay2/share/doc/Macaulay2/Probability/html/index.html) - Probability distributions and random variate generation in Macaulay2.
- [StatGraphs](https://macaulay2.com/doc/Macaulay2/share/doc/Macaulay2/StatGraphs/html/index.html) - Graphs specific for algebraic statistics.

### Python

- [pgmpy](https://pgmpy.org/) - Python library for probabilistic graphical models, Bayesian networks, and causal inference.
- [PyNormaliz](https://github.com/Normaliz/PyNormaliz) - Python interface to Normaliz for computing Hilbert bases, lattice points, and Markov/Graver bases of toric ideals.
- [SageMath](https://www.sagemath.org/) - Open-source mathematics software system supporting algebraic geometry, toric ideals, polyhedral geometry, and interfaces to 4ti2 and Macaulay2.
- [SymPy](https://www.sympy.org/) - Python library for symbolic mathematics, including polynomial manipulation and Gröbner bases for algebraic statistical modeling.

### R

- [algstat](https://github.com/dkahle/algstat) - An R package for algebraic statistics.
- [latte](https://cran.r-project.org/package=latte) - R interface to LattE and 4ti2.
- [m2r](https://github.com/dkahle/m2r) - R interface to Macaulay2.
- [mpoly](https://cran.r-project.org/package=mpoly) - Symbolic multivariate polynomials and Gröbner bases in R, foundational dependency for algstat.

## Useful Links

- [Algebraic Statistics Community Homepage](https://www.algebraicstatistics.org/) - Community homepage with journal, mailing list, and events.
- [Algebraic Statistics Online Seminar](https://sites.google.com/view/algstatsonline/home) - Online seminar series in algebraic statistics.
- [Journal of Algebraic Statistics](https://msp.org/astat/) - Community-run journal published by MSP.
- [Discontinued Journal of Algebraic Statistics](https://www.jalgstat.org/) - Archive and information for the discontinued journal.
- [Markov Bases Database](https://markov-bases.de/) - Curated online database of precomputed Markov bases for statistical models in 4ti2 format.
- [MathRepo](https://mathrepo.mis.mpg.de/) - Mathematical research data and code repository from MPI MiS.
- [Seth Sullivant: Activities](https://sethsullivant.wordpress.ncsu.edu/activities/) - Events, workshops, and activities related to algebraic statistics and applied algebraic geometry.
- [SIAM Journal on Applied Algebra and Geometry (SIAGA)](https://www.siam.org/publications/journals/siam-journal-on-applied-algebra-and-geometry-siaga) - Major journal publishing algebraic statistics and applied algebraic geometry.

## Events

### Upcoming Events

#### 2027

- [Algebraic Statistics 2027](https://www.algebraicstatistics.org/2027/index.html) - Otto von Guericke University Magdeburg, Germany, March 1-5, 2027.
- [Algebraic Distance Optimization](https://icerm.brown.edu/program/semester_program_workshop/sp-s27-w1) - ICERM, Brown University, US, February 15-19, 2027.
- [ATMCS 13 (Algebraic Topology: Methods, Computation and Science)](https://appliedtopology.org/) - KTH, Stockholm, Sweden, June 28 - July 2, 2027.
- [SIAM Conference on Applied Algebraic Geometry (AG27)](https://www.siam.org/conferences-events/siam-conferences/ag27/) - Osnabrück, Germany, July 19-23, 2027.

### Past Events

#### 2026

- [EWM 2026 General Meeting](https://sites.google.com/europeanwomeninmaths.org/ewm2026warwick/home) - University of Warwick, UK, August 31-September 4, 2026. Includes an Algebraic Statistics minisymposium.
- [Combinatorics in Algebraic Statistics and Game Theory](https://www.combinatorial-synergies.de/activities/) - MPI CBG Dresden, Germany, August 10-September 18, 2026.
- [SIAM Annual Meeting, Minisymposium on Algebraic Statistics](https://sethsullivant.wordpress.ncsu.edu/activities/) - Cleveland, Ohio, US, July 6-10, 2026.
- [Algebraic Statistics at NORDSTAT 2026](https://www.helsinki.fi/en/conferences/nordstat-2026/programme-0) - Helsinki, Finland, June 1-4, 2026.
- [Rigid Structures in Algebraic Combinatorics and Algebraic Statistics](https://icms.ac.uk/activities/workshop/rigid_structures_in_algebraic_combinatorics_algebraic_statistics/apply/) - ICMS, Edinburgh, UK, May 18-22, 2026.
- [Gröbner Free Methods and Their Applications](https://www.ub.edu/arcades/gfm2026.html) - University of Barcelona, Spain, April 13-15, 2026.
- [AlgStat - Lille 2026](https://www.mathconf.org/algstat2026) - University of Lille, France, March 12-13, 2026.

#### 2025

- [Algebraic Statistics 2025](https://sites.google.com/view/algstat2025/home) - Technical University of Munich, Germany, March 24-28, 2025.
- [Algebraic Statistics and the Study of Multistate Models: Theory and Applications](https://www.kaiekubjas.com/algstatmsm/) - Aalto University and the University of Helsinki, Finland, April 1-4, 2025.
- [SIAM Conference on Applied Algebraic Geometry (AG25)](https://www.siam.org/conferences-events/siam-conferences/ag25/) - University of Wisconsin-Madison, US, July 7-11, 2025.
- [New Directions in Algebraic Statistics](https://www.imsi.institute/activities/new-directions-in-algebraic-statistics/) - Institute for Mathematical and Statistical Innovation, US, July 21-25, 2025.
