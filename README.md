Download Link : https://programming.engineering/product/ve477-homework-5/

# VE477-Homework-5
VE477 Homework 5

Questions preceded by a * are optional. Although they can be skipped without any deduction, it is important to know and understand the results they contain.

Ex. 1 — The partition problem

    1. Explain what the linear partition problem is and where it arises.

        A simple strategy consists in computing the average size of a partition and then insert a divider close to this average. Is this a good solution? Explain, or provide a counter example.

Let n be the number of elements and k be the number of ranges. We denote by M(n, k) the minimum cost over all the partitioning of the n elements into k ranges, where the cost is the largest sum of elements in one of its parts.

    Provide a recursive algorithm to compute M(n, k). Its detailed pseudocode is not required here.

    What is the complexity of the previous algorithm?

    What quantities could be stored and not recomputed over and over again?

    Provide the pseudocode of a dynamic programming algorithm solving the partition problem.

    Prove the correctness of this new algorithm.

    Show that the complexity is now O(kn2).

    As knowing the minimal cost is often useless in practice, we desire to reconstruct the path such as to know where to set the dividers. Explain how this can be achieved by a simple subroutine.

Ex. 2 — Critical thinking

Given a black box B which returns a random integer in the range 0 – 4, create a random number generator whose output is a random integer in the range 0 – 7. Extend this idea and write an algorithm which given an integer n, uses B to generate random integers in the range 0 – n. Is there any restriction on n? All the random number generators are expected to follow the uniform distribution.

Ex. 3 — Bellman-Ford algorithm

In the lectures, Bellman-Ford algorithm (3.17|3.153) expects a weighted graph with no negative cycle.

Write an algorithm to determine whether or not a given graph features a negative cycle.

    Ex. 4 — Augmenting path

Complete the proof of lemma (4.13|4.179).

Ex. 5 — Wifi network

On campus there are k internet hostspots. Their positions are known and defined as simple planar coordinates. They also feature a range parameter r within which a user can connect, and a load l defining the maximum number of users the base can serve. Design a polynomial time algorithm which given r , l, the location of the k hotspots, and the position of n clients decides whether they can all connect to internet. Provide the pseudocode for the algorithm, proof its correctness, and complexity.
