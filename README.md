# Awesome OR-Tools [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

A curated list of awesome OR-Tools community and official resources.

## Table of Contents

- [Reading](#reading)
  - [Official](#official)
  - [Community](#community)
  - [Research](#research)
- [Watching](#watching) 
- [Samples](#samples)
  - [Basic samples](#basic-samples)
  - [Advanced samples](#advanced-samples)
- [Internal](#internal)
  - [Build systems](#build-systems)
  - [Wrappers](#wrappers)
  - [Algorithms](#algorithms)

### Reading

OR-Tools-related reading materials.

#### Official

Google-produced reading materials:
- [Online Documentation](https://developers.google.com/optimization/).
- [References Documentations](https://google.github.io/or-tools/).
- [or-tools-discuss](https://groups.google.com/g/or-tools-discuss): official mailing list.
- [GitHub Discussion](https://github.com/google/or-tools/discussions) (beta).
- [Discord Channel](https://discord.gg/ENkQrdf): official chat.
- [OR-Tools Blog](https://or-tools.blogspot.com/): unmaintained blog.
- [OR-Tools User's Manual](https://acrogenesis.com/or-tools/documentation/user_manual/index.html): unmaintained manual.

#### Community

Community-produced reading materials:
- [Stack Overflow](https://stackoverflow.com/questions/tagged/or-tools) `[or-tools]` tagged questions.
- [Xiang Chen's Blog](https://www.xiang.dev/tags/#ortools) Mostly CP-SAT related stuff.
- [Activimetrics's Blog](https://activimetrics.com/tags/google-or-tools/) Mostly routing related stuff.
- [freshcodeit.com](https://freshcodeit.com/google-or-tools) General Presentation.
- [medium.com](https://medium.com/google-or-tools/google-or-tools-a-guide-39f439a5cd0f) "Google OR Tools A Guide".
- [oreilly.com](https://www.oreilly.com/library/view/practical-python-ai/9781484234235/) Practical Python AI Projects: Mathematical Models of Optimization Problems with Google OR-Tools.
- [mlabonne.github.io](https://mlabonne.github.io/blog/posts/2022-03-02-Linear_Programming.html) Introduction to Linear Programming in Python.
- [mlabonne.github.io](https://mlabonne.github.io/blog/posts/2022-03-05-Integer_Programming.html) Introduction to Integer Programming in Python.
- [mlabonne.github.io](https://mlabonne.github.io/blog/posts/2022-05-02-Constraint_Programming.html) Introduction to Constraint Programming in Python.
- [Scheduling optimization in blending plants](https://medium.com/total-digital-factory/scheduling-optimization-in-blending-plants-ef53c460f8e0) CP-SAT + ML practical example.
- [kaggle.com](https://www.kaggle.com/jpmiller/application-of-google-or-tools) Assignment and Routing example.
- [Yet Another Math Programming Consultant](http://yetanothermathprogrammingconsultant.blogspot.com/2021/02/2d-bin-packing-with-google-or-tools-cp.html) 2D Bin packing with Google OR-Tools CP-
- Optimization Expert repository (CP-SAT)
  - [Secret Santa](https://github.com/OptimizationExpert/Pyomo/blob/main/Secret_Santa_Circuit_Advanced_CP.ipynb).
  - [Monochrome Rectangle](https://github.com/OptimizationExpert/Pyomo/blob/main/vertex_rectangle.ipynb) 
  - [Optimal Order Picking](https://github.com/OptimizationExpert/Pyomo/blob/main/storage_routing.ipynb) 
  - [Suguru Puzzle](https://github.com/OptimizationExpert/Pyomo/blob/main/Suguru_CP.ipynb) 
  - [Optimal Movie Shooting Sequence](https://github.com/OptimizationExpert/Pyomo/blob/main/Movie_shooting.ipynb) 
  - [Magic square](https://github.com/OptimizationExpert/Pyomo/blob/main/MagicSquare.ipynb)
  - [Linkedin Queen Puzzle](https://github.com/OptimizationExpert/Pyomo/blob/main/Linkedin_CP_Puzzle.ipynb)
- [Philippe Olivier's Blog](https://pedtsr.ca) (CP-SAT examples)
  - [Solving Domino Fit](https://pedtsr.ca/2024/solving-domino-fit-using-constraint-programming.html)
  - [Land Lot Optimization](https://pedtsr.ca/2023/land-lot-optimization.html)
  - [Crossword Generation](https://pedtsr.ca/2023/generating-crossword-grids-using-constraint-programming.html)
  - [MOBA Hero Rotations](https://pedtsr.ca/2023/optimizing-moba-free-hero-rotations.html)

SAT.
- [Prescient Analytics](https://www.prescient.consulting/blogs/post/First-Look-OR-Tools) First Look at OR-Tools.
- [SCM DATA](https://www.supplychaindataanalytics.com/simple-linear-programming-with-google-ortools-in-python/) Simple LP Tutorial.
- [SCM DATA](https://www.supplychaindataanalytics.com/constraint-programming-for-work-scheduling-with-google-or-tools/) Work scheduling using CP-SAT.

#### Research

Research articles using OR-Tools solvers and technologies.

- CP-SAT:
  - Scheduling: [R. Montemanni, M. Dell’Amico, Solving the Parallel Drone Scheduling Traveling Salesman Problem via Constraint Programming. Algorithms 2023, 16 (40). doi: 10.3390/a16010040](https://doi.org/10.3390/a16010040).
  - Cryptography: [E. A. Markatou, F. Falzon, Z. Espiritu, R. Tamassia, Attacks on Encrypted Range Search Schemes in Multiple Dimensions. Proceedings on Privacy Enhancing Technologies 2023(4), 204–223. doi: 10.56553/popets-2023-0106](https://doi.org/10.56553/popets-2023-0106)
  - Scheduling: [S. König, M. Reihn, F. G. Abujamra, A. Novy, B. Vogel‑Heuser, Flexible scheduling of diagnostic tests in automotive manufacturing. Flexible Services and Manufacturing Journal 2023, 35, pp. 320–342. doi: 10.1007/s10696-021-09438-3](https://doi.org/10.1007/s10696-021-09438-3)
  - Assignment: [K. Zhu, N. Gillani, P. Van Hentenryck. Impacts of Differential Privacy on Fostering more Racially and Ethnically Diverse Elementary Schools. International Conference on Computational Social Science 2023](https://arxiv.org/abs/2305.07762)
- Routing:
  - Drone scheduling: [L. Sedov, A. Krasnochub, V. Polishchuk, Modeling quarantine during epidemics and mass-testing using drones. PLOS ONE 2020, 15(6), e0235307. doi: 10.1371/journal.pone.0235307](https://doi.org/10.1371/journal.pone.0235307)
  - Clustering: [K. Abdou, O. Mohammed, G. Eskandar, A. Ibrahim, P.-A. Matt, M. F. Huber, Smart nesting: estimating geometrical compatibility in the nesting problem using graph neural networks. Journal of Intelligent Manufacturing 2023, doi: 10.1007/s10845-023-02179-0](https://doi.org/10.1007/s10845-023-02179-0)
  - Travelling-salesperson problem (TSP): [H. Gao, X. Zhou, X. Xu, Y. Lan, Y. Xiao, AMARL: An Attention-Based Multiagent Reinforcement Learning Approach to the Min-Max Multiple Traveling Salesmen Problem. IEEE Transactions on Neural Networks and Learning Systems 2023, doi: 10.1109/TNNLS.2023.3236629](https://doi.org/10.1109/TNNLS.2023.3236629)
  - Travelling-salesperson problem (TSP): [J. Park, C. Kwon, J. Park, Learn to Solve the Min-max Multiple Traveling Salesmen Problem with Reinforcement Learning. Proceedings of the International Conference on Autonomous Agents and Multiagent Systems 2023, pp. 878-886. doi: 10.5555/3545946.3598725](https://doi.org/10.5555/3545946.3598725)
  - Pickup and delivery (PDP): [F. M. Bergmann, S. M. Wagner, M. Winkenbach, Integrating first-mile pickup and last-mile delivery on shared vehicle routes for efficient urban e-commerce distribution. Transportation Research Part B: Methodological 2020, 131, pp. 26-62. doi: 10.1016/j.trb.2019.09.013](https://doi.org/10.1016/j.trb.2019.09.013)
- Linear solver interface (MPModel):
  - Facility location: [R. B. Lippmann, K. J. Helmstedt, M. T. Gibbs, P. Corry, Optimizing facility location, sizing, and growth time for a cultivated resource: A case study in coral aquaculture. PLOS ONE 2023, 18(3), e0282668. doi: /10.1371/journal.pone.0282668](https://doi.org/10.1371/journal.pone.0282668)
  - Bin packing: [T. Li, Z. Erkin, R. L. Lagendijk, Privacy-Preserving Bin-Packing With Differential Privacy. IEEE Open Journal of Signal Processing 2022, 3, pp. 94-106. doi: 10.1109/OJSP.2022.3153231](https://doi.org/10.1109/OJSP.2022.3153231)
- Graph algorithms:
  - Maximum flow: [Z. Duan, C. Wang, C. Chen, W. Zhou, J. Huang, W. Qian, Match4Match: Enhancing Text-Video Retrieval by Maximum Flow with Minimum Cost. Proceedings of the ACM Web Conference 2023. doi: 10.1145/3543507.3583365](https://doi.org/10.1145/3543507.3583365)

### Watching

#### Official

Google-produced watching materials:
- [OR-tools](https://youtu.be/AJ6LeiMe_PQ) General presentation by Pawel Lichocki.

#### Community

Community-produced watching materials:
- [Primera sesión - "Optimización con Google OR Tools + Python"](https://youtu.be/XPiDrFl5S84): LP, MIP and assignment tutorial (Universidad Libre Columbia).
- [Segunda sesión - "Optimización con Google OR Tools + Python"](https://youtu.be/KxXut49BwUA): routing TSP tutorial (Universidad Libre Columbia).
- [Building AI Solutions with Google OR-Tools - Barry Stahl](https://youtu.be/zZAobExOMB0).
- [OR-Tools を使って数理最適化に触れてみよう](https://www.youtube.com/watch?v=80Gp6wiunkI&t=7726s).
- [SCM DATA](https://youtu.be/QdSJgNG2dGw): job scheduling using CP-SAT.

### Samples

Samples and models from the community.

#### Basic samples

Few canonical samples to advertise basic features of each module, There are usually written in all supported languages.
- [Algorithms samples](https://github.com/google/or-tools/tree/stable/ortools/algorithms/samples).
- [Graph samples](https://github.com/google/or-tools/tree/stable/ortools/graph/samples).
- [Linear Solver samples](https://github.com/google/or-tools/tree/stable/ortools/linear_solver/samples).
- [Constraint Solver samples](https://github.com/google/or-tools/tree/stable/ortools/constraint_solver/samples) Mostly routing samples.
- [CP-SAT samples](https://github.com/google/or-tools/tree/stable/ortools/sat/samples).
- [Glop samples](https://github.com/google/or-tools/tree/main/ortools/glop/samples).

#### Advanced samples

More advanced or complex examples usually merging few concepts and available (i.e. written) in one language.
- [Miscellaneous examples](https://github.com/google/or-tools/tree/stable/examples).
- [Contrib examples](https://github.com/google/or-tools/tree/stable/examples/contrib) Community contributed examples.
- [Hakank's examples](https://github.com/hakank/hakank/tree/main/google_or_tools) Dozens of combinatorial problems and puzzles.
- [MrBenGriffin's examples](https://github.com/MrBenGriffin/or-tools-fun) Models (Delegate Seating) and puzzle solvers.

### Internal

Reading materials related to OR-Tools internals.

#### Build systems

- [CMake Based Build](https://github.com/google/or-tools/blob/main/cmake/README.md).
- [Make based build](https://github.com/google/or-tools/blob/main/makefiles/README.md).
- [Bazel based build](https://github.com/google/or-tools/blob/main/bazel/README.md).

#### Wrappers

- [Python wrapper](https://github.com/google/or-tools/blob/main/ortools/python/README.md).
- [Java wrapper](https://github.com/google/or-tools/blob/main/ortools/java/README.md).
- [.Net wrapper](https://github.com/google/or-tools/blob/main/ortools/dotnet/README.md).

#### Algorithms

- [Search is Dead, Long Live Proof](https://people.eng.unimelb.edu.au/pstuckey/PPDP2013.pdf) ([talk](https://www.youtube.com/watch?v=lxiCHRFNgno)): SAT technology presentation.
- [CPAIOR 2020: CP-SAT](https://youtu.be/lmy1ddn4cyw?t=87): how CP-Sat works internally.
- [CP-SAT Primer](https://github.com/d-krupke/cpsat-primer): A Primer by Dominik Krupke.
- [EWO Seminar 2023: The CP-SAT-LP solver](http://egon.cheme.cmu.edu/ewo/video/CP_SAT_LP_google.mp4): internals of CP-SAT-LP with [slides](http://egon.cheme.cmu.edu/ewo/docs/CP-SAT%20and%20OR-Tools.pdf).
