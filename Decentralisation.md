Topic: Internet Decentralisation & Distribackup
================================

Diff, Distance & Similarity Algorithms
=========

These solve one of two general problems: 

* Calculating [Edit Distance](https://en.wikipedia.org/wiki/Edit_distance),
  which is the minimum number of changes to turn one string 
  (or other arbitrary sequence of symbols) into another, and
* [Sequence Alignment](https://en.wikipedia.org/wiki/Sequence_alignment),
which calculates what offset between the start of two strings produces the shortest edit distance.

[Needleman-Wunsch](https://en.wikipedia.org/wiki/Needleman%E2%80%93Wunsch_algorithm)
-------

Domain:Bioinformatics.

For aligning protein sequences (RNA or DNA).
Uses Dynamic Programming.

[Smith-Waterman](https://en.wikipedia.org/wiki/Smith%E2%80%93Waterman_algorithm)
-----

Domain:Bioinformatics.

Originally for aligning DNA sequences.
Derived from Needleman-Wunsch.
Uses Dynamic Programming.

[Ukkonen's](https://en.wikipedia.org/wiki/Ukkonen%27s_algorithm)
-----

Domain: Classic Computer Science (data structures & algorithms)

For generating a 'Suffix Tree' of strings. 

[This Stackoverflow question](https://stackoverflow.com/questions/9452701/ukkonens-suffix-tree-algorithm-in-plain-english/9513423#9513423) provides an
explanation of the algorithm.

[Wagner-Fischer](https://en.wikipedia.org/wiki/Wagner%E2%80%93Fischer_algorithm)
-----

Domain: Computer Science

Computes the edit distance between two strings.

[Hirschberg's](https://en.wikipedia.org/wiki/Hirschberg%27s_algorithm)
------

Domain: Computer Science

Finds the optimal sequence alignment between two strings.
"simply described as a more space efficient version of the Needleman–Wunsch algorithm 
that uses divide and conquer."

