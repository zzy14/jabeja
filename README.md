
JabeJa: Distributed Balanced Graph Partitioning

Link to the paper: http://www.sics.se/~fatemeh/files/papers/jabeja.pdf

The implementation of JabeJa on GraphChi consists of the following files:
1. JabeJa.java: the main algorithm of JabeJa.
2. JabeJaWeighted.java: this is JabeJa for weighted graphs.
3. MessageRelay.java: this is the file that implements the "mail" API, i.e., "send" and "get".
4. PartitionAnalysis.java: this file writes the final partitions into different output files.


Furthermore, there are a few other java files that GraphChi might need, if they are not already included. These files are listed below:
Multimap.java
Multimaps.java
HashMultimap.java
IntArrayConverter.java
