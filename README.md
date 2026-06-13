# Advanced Algorithms Project: Chasing Convex Bodies

This repository contains the presentation slides and materials for the **"Chasing Convex Bodies"** problem, a fundamental challenge in Online Algorithms and Computational Geometry.

## Overview
Online learning involves an algorithm making decisions sequentially without knowing future data points. This project specifically analyzes the "Chasing Convex Bodies" problem, where a player must pick a point within a continuously revealing sequence of convex bodies while trying to minimize the total movement cost.

## Contents
The presentation breaks down the problem and analyzes three distinct algorithmic approaches:

1. **Online Learning and Online Algorithms:** An introduction to sequential decision-making environments.
2. **The Chasing Convex Bodies Problem:** Mathematical formulation, including the objective of minimizing the competitive ratio and real-world applications like Load Balancing in Cloud Computing.
3. **Naive Centroid Approach:** Moving to the centroid of the given convex body at each timestep, and a proof of why this intuitive approach is not competitive.
4. **Recursive Greedy Method:** Analysis of the first $f(d)$-competitive algorithm for Chasing Nested Convex Bodies, which operates in phases and subproblems in lower dimensions. 
5. **Steiner Point Method:** A memoryless algorithm that selects the Steiner point $s(K)$ by averaging extremal points across all directions, achieving a competitive ratio of $O(d)$.

## References
* Nikhil Bansal, Martin Böhm, Marek Eliáš, Grigorios Koumoutsos, Seeun William Umboh (2017). *Nested Convex Bodies are Chaseable*. [arXiv:1707.05527](https://arxiv.org/abs/1707.05527)
* Sébastien Bubeck, Bo'az Klartag Yin Tat Lee, Yuanzhi Li, Mark Sellke (2018). *Chasing Nested Convex Bodies Nearly Optimally*. [arXiv:1811.00999](https://arxiv.org/abs/1811.00999)
