# k-shortest-path
http://www.ics.uci.edu/~eppstein/pubs/Epp-SJC-98.pdf

This paper presents an algorithm that finds multiple short paths connecting two terminals in a graph (allowing repeated vertices and edges in the paths) in constant time per path after a preprocessing stage dominated by a single-source shortest path computation. The paths it finds are the k shortest in the graph, where k is a parameter given as input to the algorithm.

The k shortest paths problem has many important applications for finding alternative solutions to geographic path planning problems, network routing, hypothesis generation in computational linguistics, and sequence alignment and metabolic pathway finding in bioinformatics. Although there have been many papers on the k shortest paths problem before and after this one, it has become frequently cited in those application areas. Additionally, it marks a boundary in the theoretical study of the problem: prior theoretical work largely concerned how quickly the problem could be solved, a line of research that was closed off by the optimal time bounds of this paper. Subsequent work has focused instead on devising efficient algorithms for more complex alternative formulations of the problem that avoid the repeated vertices and other shortcomings of the alternative paths produced by this formulation.

Install-Package Eppstein -Version 1.0.0
