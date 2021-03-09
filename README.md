# Awesome OR-Tools

A curated list of awesome OR-Tools community and official resources.

## Table of Contents

- [Reading](#reading)
  - [Officials](#official)
  - [Community](#community)
  - [Internal](#internal)
- [Watching](#watching) 
- [Samples](#samples)
  - [Basic samples](#basic-samples)
  - [Advanced samples](#advanced-samples)

### Reading
OR-Tools related reading materials.

#### Official
Google produced reading materials
- [Online Documentation](https://developers.google.com/optimization/).
- [References Documentations](https://google.github.io/or-tools/).
- [or-tools-discuss](https://groups.google.com/g/or-tools-discuss) Official Mailing list.
- [GitHub Discussion](https://github.com/google/or-tools/discussions) (beta).
- [Discord Channel](https://discord.gg/ENkQrdf) Official Chat.
- [OR-Tools Blog](https://or-tools.blogspot.com/) unmaintained blog.
- [OR-Tools User's Manual](https://acrogenesis.com/or-tools/documentation/user_manual/index.html) unmaintained manual.

#### Community
Community produced reading materials
- [Stack Overflow](https://stackoverflow.com/questions/tagged/or-tools) `[or-tools]` tagged questions.
- [Xiang Chen's Blog](https://www.xiang.dev/tags/#ortools) Mostly CP-SAT related stuff.
- [Activimetrics's Blog](https://activimetrics.com/tags/google-or-tools/) Mostly routing related stuff.

#### Internal
Reading materials related to OR-Tools internals.

Build systems:
- [CMake Based Build](https://github.com/google/or-tools/blob/master/cmake/README.md).
- [Make based build](https://github.com/google/or-tools/blob/master/makefiles/README.md).
- [Bazel based build](https://github.com/google/or-tools/blob/master/bazel/README.md).

Wrappers:
- [Python wrapper](https://github.com/google/or-tools/blob/master/ortools/python/README.md)
- [Java wrapper](https://github.com/google/or-tools/blob/master/ortools/java/README.md)
- [.Net wrapper](https://github.com/google/or-tools/blob/master/ortools/dotnet/README.md)

Algorithms:
- [Search is Dead, Long Live Proof](https://people.eng.unimelb.edu.au/pstuckey/PPDP2013.pdf) SAT Technology presentation.

### Watching
Google produced watching materials:
- [OR-tools](https://youtu.be/AJ6LeiMe_PQ) General presentation by Pawel Lichocki.
- [CPAIOR 2020: CP-SAT](https://youtu.be/lmy1ddn4cyw?t=87) How CP-Sat works internally.

### Samples
Samples and models from the community.

#### Basic samples
Few canonical samples to advertise basic features of each module, There are usually written in all supported languages.
- [Algorithms samples](https://github.com/google/or-tools/tree/stable/ortools/algorithms/samples).
- [Graph samples](https://github.com/google/or-tools/tree/stable/ortools/graph/samples).
- [Linear Solver samples](https://github.com/google/or-tools/tree/stable/ortools/linear_solver/samples).
- [Constraint Solver samples](https://github.com/google/or-tools/tree/stable/ortools/constraint_solver/samples) Mostly routing samples.
- [CP-SAT samples](https://github.com/google/or-tools/tree/stable/ortools/sat/samples).
- [Glop samples](https://github.com/google/or-tools/tree/master/ortools/glop/samples).

#### Advanced samples
More advanced or complex examples usually merging few concepts and available (i.e. written) in one language.
- [Miscellaneous examples](https://github.com/google/or-tools/tree/stable/examples).
- [Contrib examples](https://github.com/google/or-tools/tree/stable/examples/contrib) Community contributed examples.
- [Hakank's examples](https://github.com/hakank/hakank/tree/master/google_or_tools) Dozens of combinatorial problems and puzzles.
- [MrBenGriffin's examples](https://github.com/MrBenGriffin/or-tools-fun) Models (Delegate Seating) and puzzle solvers.
