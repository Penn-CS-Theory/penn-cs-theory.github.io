---
title: "Theory Seminar: Mordecai Golin"
date: 2023-05-05
---

The speaker for this week's theory seminar is [Mordecai Golin](https://www.cse.ust.hk/faculty/golin/) from HKUST. As usual, the talk will take place on Friday 5/5 at 1PM in Levine 307.

**Title**:  AIFV-m Coding and Finding the Cheapest Markov Chain
Mordecai Golin. Hong Kong UST

**Abstract**:
Binary AIFV-m codes are a relatively new method for lossless compression. They encode using an m-tuple of coding trees rather than the single tree used by Huffman coding. Their advantage is better proven redundancy than Huffman codes; their disadvantage is a slight decoding delay.

The compression rate of a binary AIFV-m code is the steady state average “gain” of an associated m-state Markov chain with rewards. Finding a best compression rate AIFV-m code is the problem of finding a minimum-gain Markov chain within an implicitly defined (exponentially large) collection of Markov chains.

Previous algorithms for solving this problem ran in exponential time. We show how to transform the problem to a Linear Programming one (with an exponential number of constraints). This LP problem can then be solved in polynomial time using binary search (for m=2) or the Ellipsoid method (for m >2).  The technique maps all possible Markov chain states to hyperplanes that are then used to define the polytope for the LP problem.  Since this polytope is only a function of the Markov chain structure, with almost no reliance on the original coding problem, the techniques developed might be of interest in other contexts.

This is joint work with Elfarouk Harb and  Albert J.L. Patupat
