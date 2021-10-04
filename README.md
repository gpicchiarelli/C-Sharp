# The Algorithms - C#
[![Build Status](https://travis-ci.com/TheAlgorithms/C-Sharp.svg?branch=master)](https://travis-ci.com/TheAlgorithms/C-Sharp)
[![Codacy Badge](https://api.codacy.com/project/badge/Grade/6f6c4c370fc04857914dd04b91c5d675)](https://www.codacy.com/app/siriak/C-Sharp?utm_source=github.com&amp;utm_medium=referral&amp;utm_content=TheAlgorithms/C-Sharp&amp;utm_campaign=Badge_Grade)
[![codecov](https://codecov.io/gh/TheAlgorithms/C-Sharp/branch/master/graph/badge.svg)](https://codecov.io/gh/TheAlgorithms/C-Sharp)
[![GuardRails badge](https://badges.guardrails.io/TheAlgorithms/C-Sharp.svg?token=84805208ba243f0931a74c5148883f894cbe9fd97fe54d64d6d0a89852067548)](https://dashboard.guardrails.io/default/gh/TheAlgorithms/C-Sharp)

This repository contains algorithms and data structures implemented in C# for educational purposes.

## Overview

* [Algorithms](./Algorithms)
  * [Data Compression](./Algorithms/DataCompression)
    * [Burrows-Wheeler transform](./Algorithms/DataCompression/BurrowsWheelerTransform.cs)
    * [Huffman Compressor](./Algorithms/DataCompression/HuffmanCompressor.cs)
    * [Shannon-Fano Compressor](./Algorithms/DataCompression/ShannonFanoCompressor.cs)
  * [Encoders](./Algorithms/Encoders)
    * [Caesar](./Algorithms/Encoders/CaesarEncoder.cs)
    * [Vigenere](./Algorithms/Encoders/VigenereEncoder.cs)
    * [Hill](./Algorithms/Encoders/HillEncoder.cs)
    * [NYSIIS](./Algorithms/Encoders/NysiisEncoder.cs)
    * [Soundex](./Algorithms/Encoders/SoundexEncoder.cs)
  * [Graph](./Algorithms/Graph)
    * [BreadthFirstSearch](./Algorithms/Graph/BreadthFirstSearch.cs)
    * [DepthFirstSearch](./Algorithms/Graph/DepthFirstSearch.cs)
  * [Knapsack problem](./Algorithms/Knapsack)
    * [Naive solver](./Algorithms/Knapsack/NaiveKnapsackSolver.cs)
    * [Dynamic Programming solver](./Algorithms/Knapsack/DynamicProgrammingKnapsackSolver.cs)
    * [Branch and bound solver](./Algorithms/Knapsack/BranchAndBoundKnapsackSolver.cs)
  * [Linear Algebra](./Algorithms/LinearAlgebra)
    * [Eigenvalue](./Algorithms/LinearAlgebra/Eigenvalue)
      * [Power Iteration](./Algorithms/LinearAlgebra/Eigenvalue/PowerIteration.cs)
  * [Numeric](./Algorithms/Numeric)
    * [Aliquot Sum Calculator](./Algorithms/Numeric/AliquotSumCalculator.cs)
    * [Decomposition](./Algorithms/Numeric/Decomposition)
      * [LU Decomposition](./Algorithms/Numeric/Decomposition/LU.cs)
      * [Thin Singular Vector Decomposition](./Algorithms/Numeric/Decomposition/ThinSVD.cs)
    * [Greatest Common Divisor](./Algorithms/Numeric/GreatestCommonDivisor)
      * [Euclidean GCD](./Algorithms/Numeric/GreatestCommonDivisor/EuclideanGreatestCommonDivisorFinder.cs)
      * [Binary GCD](./Algorithms/Numeric/GreatestCommonDivisor/BinaryGreatestCommonDivisorFinder.cs)
    * [Factorization](./Algorithms/Numeric/Factorization)
      * [Trial division Factorization](./Algorithms/Numeric/Factorization/TrialDivisionFactorizer.cs)
    * [Series](./Algorithms/Numeric/Series)
      * [Maclaurin Series](./Algorithms/Numeric/Series/Maclaurin.cs)
    * [Gauss-Jordan Elimination](./Algorithms/Numeric/GaussJordanElimination.cs)
    * [Pseudo-Inverse](./Algorithms/Numeric/Pseudoinverse/PseudoInverse.cs)
    * [Narcissistic Number Checker](./Algorithms/Numeric/NarcissisticNumberChecker.cs)
    * [Perfect Number Checker](./Algorithms/Numeric/PerfectNumberChecker.cs)
    * [Perfect Square Checker](./Algorithms/Numeric/PerfectSquareChecker.cs)
    * [Euler Method](./Algorithms/Numeric/EulerMethod.cs)
  * [Searches](./Algorithms/Search)
    * [A-Star](./Algorithms/Search/AStar/)
    * [Binary Search](./Algorithms/Search/BinarySearcher.cs)
    * [Recursive Binary Search](./Algorithms/Search/RecursiveBinarySearcher.cs)
    * [Linear Search](./Algorithms/Search/LinearSearcher.cs)
    * [Fast Search](./Algorithms/Search/FastSearcher.cs)
    * [Jump Search](./Algorithms/Search/JumpSearcher.cs)
  * [Sorts](./Algorithms/Sorters)
    * [Comparison](./Algorithms/Sorters/Comparison)
      * [Binary Insertion Sort](./Algorithms/Sorters/Comparison/BinaryInsertionSorter.cs)
      * [Bogo Sort](./Algorithms/Sorters/Comparison/BogoSorter.cs)
      * [Bubble Sort](./Algorithms/Sorters/Comparison/BubbleSorter.cs)
      * [Cocktail Sort](./Algorithms/Sorters/Comparison/CocktailSorter.cs)
      * [Comb Sort](./Algorithms/Sorters/Comparison/CombSorter.cs)
      * [Cycle Sort](./Algorithms/Sorters/Comparison/CycleSorter.cs)
      * [Heap Sort](./Algorithms/Sorters/Comparison/HeapSorter.cs)
      * [Insertion Sort](./Algorithms/Sorters/Comparison/InsertionSorter.cs)
      * [Merge Sort](./Algorithms/Sorters/Comparison/MergeSorter.cs)
      * [Pancake Sort](./Algorithms/Sorters/Comparison/PancakeSorter.cs)
      * [Quick Sort](./Algorithms/Sorters/Comparison/QuickSorter.cs)
        * [Median of three pivot](./Algorithms/Sorters/Comparison/MedianOfThreeQuickSorter.cs)
        * [Middle point pivot](./Algorithms/Sorters/Comparison/MiddlePointQuickSorter.cs)
        * [Random pivot](./Algorithms/Sorters/Comparison/RandomPivotQuickSorter.cs)
      * [Selection Sort](./Algorithms/Sorters/Comparison/SelectionSorter.cs)
      * [Shell Sort](./Algorithms/Sorters/Comparison/ShellSorter.cs)
    * [External](./Algorithms/Sorters/External)
      * [Merge Sort](./Algorithms/Sorters/External/ExternalMergeSorter.cs)
    * [Integer](./Algorithms/Sorters/Integer)
      * [Counting Sort](./Algorithms/Sorters/Integer/CountingSorter.cs)
      * [Bucket Sort](./Algorithms/Sorters/Integer/BucketSorter.cs)
      * [Radix Sort](./Algorithms/Sorters/Integer/RadixSorter.cs)
    * [String](./Algorithms/Sorters/String)
      * [MSD Radix Sort](./Algorithms/Sorters/String/MsdRadixStringSorter.cs)
      * [Knuth–Morris–Pratt Search](./Algorithms/Strings/KnuthMorrisPrattSearcher.cs)
  * [Sequences](./Algorithms/Sequences)
    * [A000004 Zero](./Algorithms/Sequences/ZeroSequence.cs)
    * [A000005 Count of Divisors](./Algorithms/Sequences/DivisorsCountSequence.cs)
    * [A000027 Natural](./Algorithms/Sequences/NaturalSequence.cs)
    * [A000040 Primes](./Algorithms/Sequences/PrimesSequence.cs)
    * [A000045 Fibonacci](./Algorithms/Sequences/FibonacciSequence.cs)
    * [A000142 Factorial](./Algorithms/Sequences/FactorialSequence.cs)
    * [A007318 Binomial](./Algorithms/Sequences/BinomialSequence.cs)
  * [String](./Algorithms/Strings)
    * [Longest Consecutive Character](./Algorithms/Strings/GeneralStringAlgorithms.cs)
    * [Naive String Search](./Algorithms/Strings/NaiveStringSearch.cs)
    * [Rabin Karp](./Algorithms/Strings/RabinKarp.cs)
    * [Boyer Moore](./Algorithms/Strings/BoyerMoore.cs)
    * [Palindrome Checker](./Algorithms/Strings/palindrome.cs)
  * [Other](./Algorithms/Other)
    * [Fermat Prime Checker](./Algorithms/Other/FermatPrimeChecker.cs)
    * [Sieve of Eratosthenes](./Algorithms/Other/SieveOfEratosthenes.cs)
    * [Luhn](./Algorithms/Other/Luhn.cs)
    * [Mandelbrot](./Algorithms/Other/Mandelbrot.cs)
    * [Koch Snowflake](./Algorithms/Other/KochSnowflake.cs)
    * [RGB-HSV Conversion](./Algorithms/Other/RGBHSVConversion.cs)
    * [Flood Fill](./Algorithms/Other/FloodFill.cs)
  * [Problems](./Algorithms/Problems)
    * [Stable Marriage](./Algorithms/Problems/StableMarriage)
      * [Gale-Shapley](./Algorithms/Problems/StableMarriage/GaleShapley.cs)
    * [N-Queens](./Algorithms/Problems/NQueens)
      * [Backtracking](./Algorithms/Problems/NQueens/BacktrackingNQueensSolver.cs)

* [Data Structures](./DataStructures)
  * [Bit Array](./DataStructures/BitArray.cs)
  * [Timeline](./DataStructures/Timeline.cs)
  * [Segment Trees](./DataStructures/SegmentTrees)
    * [Segment Tree](./DataStructures/SegmentTrees/SegmentTree.cs)
    * [Segment Tree Multiplication](./DataStructures/SegmentTrees/SegmentTreeApply.cs)
    * [Segment Tree Update](./DataStructures/SegmentTrees/SegmentTreeUpdate.cs)
  * [Binary Search Tree](./DataStructures/BinarySearchTree)
  * [AA Tree](./DataStructures/AATree)
  * [Stack](./DataStructures/Stack)
    * [Array-based Stack](./DataStructures/Stack/ArrayBasedStack.cs)
    * [List-based Stack](./DataStructures/Stack/ListBasedStack.cs)
  * [Heap](./DataStructures/Heap)
    * [Min-Max Heap](./DataStructures/Heap/MinMaxHeap.cs)
    * [Binary Heap](./DataStructures/Heap/BinaryHeap.cs)
    * [Fibonacci Heap](./DataStructures/Heap/FibonacciHeap/FibonacciHeap.cs)
  * [Queue](./DataStructures/Queue)
    * [Array-based Queue](./DataStructures/Queue/ArrayBasedQueue.cs)
    * [List-based Queue](./DataStructures/Queue/ListBasedQueue.cs)
    * [Stack-based Queue](./DataStructures/Queue/StackBasedQueue.cs)
  * [Linked List](./DataStructures/LinkedList)
    * [Singly Linked List](./DataStructures/LinkedList/SinglyLinkedList/SinglyLinkedList.cs)
    * [Doubly Linked List](./DataStructures/LinkedList/DoublyLinkedList/DoublyLinkedList.cs)
  * [Graph](./DataStructures/Graph)
    * [Directed Weighted Graph Via Adjacency Matrix](./DataStructures/Graph/DirectedWeightedGraph.cs)
  * [Disjoint Set](./DataStructures/DisjointSet)
  * [SortedList](./DataStructures/SortedList.cs)


## Contributing

You can contribute with pleasure to this repository.
Please orient on the directory structure and overall code style of this repository
and refer to [our contributing guidelines](./CONTRIBUTING.md) for more detail.
If you want to ask a question or suggest something, please open an issue.
