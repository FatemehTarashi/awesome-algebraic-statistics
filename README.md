# Awesome Algebraic Statistics [![Awesome](https://awesome.re/badge.svg)](https://github.com/sindresorhus/awesome)

A curated list of Algebraic Statistics tools and resources.

Algebraic statistics uses techniques from algebraic geometry, commutative algebra, combinatorics, and computational algebra to study statistical models and their applications.

If you know of any other tools or resources, feel free to fork/PR or open a new issue.

## Contents

<!--lint disable no-missing-blank-lines alphabetize-lists list-item-punctuation-->

- [Theory](#theory)
  - [Books](#books)
  - [Articles](#articles)
- [Tools](#tools)
  - [C++](#c)
  - [Julia / OSCAR](#julia--oscar)
  - [Macaulay2](#macaulay2)
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

### Articles

- [Algebraic Algorithms for Sampling from Conditional Distributions](https://projecteuclid.org/journals/annals-of-statistics/volume-26/issue-1/Algebraic-algorithms-for-sampling-from-conditional-distributions/10.1214/aos/1030563990.full) - Diaconis, and Sturmfels.
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
- [The Maximum Likelihood Degree of a Very Affine Variety](https://arxiv.org/abs/1207.0553) - Huh.
- [Thesis: The Algebraic Statistics of Sampling, Likelihood, and Regression](https://orlandomarigliano.com/thesis.pdf) - Marigliano.

## Tools

### C++

- [4ti2](https://4ti2.github.io/) - A software package for algebraic, geometric, and combinatorial problems on linear spaces.

### Julia / OSCAR

- [Algebraic Statistics in OSCAR](https://docs.oscar-system.org/stable/Experimental/AlgebraicStatistics/introduction/) - Experimental OSCAR functionality for common algebraic statistical models.
- [AlgebraicStatistics.jl](https://github.com/bkholler/AlgebraicStatistics.jl) - A Julia / OSCAR package for algebraic statistics.

### Macaulay2

- [AllMarkovBases](https://macaulay2.com/doc/Macaulay2/share/doc/Macaulay2/AllMarkovBases/html/index.html) - Computing all minimal Markov bases of a configuration matrix.
- [FourTiTwo](https://macaulay2.com/doc/Macaulay2/share/doc/Macaulay2/FourTiTwo/html/index.html) - Macaulay2 interface to 4ti2.
- [GraphicalModels](https://macaulay2.com/doc/Macaulay2/share/doc/Macaulay2/GraphicalModels/html/index.html) - Discrete and Gaussian graphical models.
- [GraphicalModelsMLE](https://macaulay2.com/doc/Macaulay2/share/doc/Macaulay2/GraphicalModelsMLE/html/index.html) - Maximum likelihood estimates for graphical statistical models.
- [Markov](https://macaulay2.com/doc/Macaulay2/share/doc/Macaulay2/Markov/html/index.html) - Markov ideals arising from Bayesian networks in statistics.
- [MultigradedImplicitization](https://macaulay2.com/doc/Macaulay2/share/doc/Macaulay2/MultigradedImplicitization/html/index.html) - Implicitization problems using multigradings.
- [PhylogeneticTrees](https://macaulay2.com/doc/Macaulay2/share/doc/Macaulay2/PhylogeneticTrees/html/index.html) - Invariants for group-based phylogenetic models.
- [StatGraphs](https://macaulay2.com/doc/Macaulay2/share/doc/Macaulay2/StatGraphs/html/index.html) - Graphs specific for algebraic statistics.

### R

- [algstat](https://github.com/dkahle/algstat) - An R package for algebraic statistics.
- [latte](https://cran.r-project.org/package=latte) - R interface to LattE and 4ti2.
- [m2r](https://github.com/dkahle/m2r) - R interface to Macaulay2.

## Useful Links

- [Algebraic Statistics Community Homepage](https://www.algebraicstatistics.org/) - Community homepage with journal, mailing list, and events.
- [Algebraic Statistics Online Seminar](https://sites.google.com/view/algstatsonline/home) - Online seminar series in algebraic statistics.
- [Journal of Algebraic Statistics](https://msp.org/astat/) - Community-run journal published by MSP.
- [Discontinued Journal of Algebraic Statistics](https://www.jalgstat.org/) - Archive and information for the discontinued journal.
- [Seth Sullivant: Activities](https://sethsullivant.wordpress.ncsu.edu/activities/) - Events, workshops, and activities related to algebraic statistics and applied algebraic geometry.

## Events

### Upcoming Events

#### 2027

- [Algebraic Statistics 2027](https://www.algebraicstatistics.org/2027/index.html) - Otto von Guericke University Magdeburg, Germany, March 1-5, 2027.
- [Algebraic Distance Optimization](https://icerm.brown.edu/program/semester_program_workshop/sp-s27-w1) - ICERM, Brown University, US, February 15-19, 2027.

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
