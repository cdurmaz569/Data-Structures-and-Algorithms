# Data-Structures-and-Algorithms
Data Structures &amp; Algorithms Course at Weill Cornell Fall 2020

This repository contains completed homework assignments for the Data Structures and Algorithms Course in Fall, 2020 at Weill Cornell Medicine. 

Graduate course addresses fundamental data structures and algorithms that are applied to modern computational biology. Course focused on how to design and apply data structures and algorithms to state-of-the-art biology problems such as large-scale biomolecular sequence analysis. Topics covered in the course include: runtime analysis and big O notation, complexity and NP-completeness, greedy algorithms, sequence alignment, Knuth-Morris-Pratt algorithm, Boyer-Moore algorithm, hash function, suffix tree and suffix arrays, Burrows-Wheeler Transformation and FM-index, inexact matching, hash-based short read alignments, graph theory, De Bruijn graphs, Eulerian Graphs, basics of HMM and parameters, Viterbi algorithm, and forward/backward algorithms. 

Homework 1: Graph Class
    * Implement weighted directed graph class 
    * Implement function that searches some paths between two vertices, outputs edges in the path and distance 
    * Implement algorithm that outputs all directed triangles in the graph and find its complexity
    * Implement function that checks if an input graph is a DAG. Output topological sort of the vertices is graph is DAG. 
    * Implement DeleteEdge, VertexCount, EdgeCount functions, making sure that VertexCount() and EdgeCount() are O(1) time. 

Homework 2: Consists of 3 parts
    * Wildcard KMP: Describe a modification of Knuth-Morris-Pratt (KMP) algorithm
    * Cyclic rotation alignment: Implement an algorithm where, given strings *s* and *t*, finds the best local alignment of any cyclic rotation of *t* to any cyclic rotation of *s*
    * Read mapping: Implement an algorithm where, given the reference file in FASTA format, reads file and aligns reads to the reference. Uses Burrows-Wheeler Transformation and FM-index for alignment 

Homework 3: De Bruijn Graph
    * Build condensed De Bruijn Graph that 1) outputs edges in fasta-file, 2) counts average kmer coverage for each edge, and 3) outputs .dot file where each edge is labeled with its length and average coverage 
    * Graph simplification: implement a graph simplification algorithm for basic erroneous edge removal 

Final Assignment: 
    * Implements a 2-state HMM for detecting G+C-rich regions in the fasta sequence
    * Uses Viterbi training to find improved parameter estimates for the transition probabilities, holding the emission and initiation probabilities fixed at specified values
    * Output: 1) name and first line of the .fna file, 2) model information (i.e. number of states and segments, and new probability values) for each of the 10 iterations, and 3) the list of G+C rich segments after the final round of Viterbi training, sorted by genomic position 
    
*** All code written in python
