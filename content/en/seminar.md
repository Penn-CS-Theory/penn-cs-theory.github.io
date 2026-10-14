---
title: Theory Seminar (Fall 2026)
linkTitle: Theory Seminar
featured_image: '/images/snow.jpg'
description:
type: page
menu: main

# Fall 2026 schedule, rendered as a table by the seminar-schedule shortcode below.
# Each entry takes: date, speaker, affiliation, url (optional), title (optional), abstract (optional, markdown).
# Use `note` instead of speaker for weeks without a talk.
talks:
  - date: "9/4"
    speaker: Samson Zhou
    affiliation: Texas A&M
    url: https://samsonzhou.github.io/
    title: Adversarial Robustness on Insertion-Deletion Streams
    abstract: |-
      We study adversarially robust sublinear algorithms for insertion-deletion (turnstile) streams, where future updates may depend on past algorithm outputs. While robust algorithms exist for insertion-only streams with only a polylogarithmic overhead in memory over non-robust algorithms, it was widely conjectured that turnstile streams of length polynomial in the universe size n require space linear in n. We refute this conjecture, showing that robustness can be achieved using space which is significantly sublinear in n. Our framework combines multiple linear sketches in a novel estimator-corrector-learner framework (where differential privacy can be used to improve the overall space bounds), yielding the first insertion-deletion algorithms that approximate: (1) the second moment F_2 up to a (1+ε)-factor in polylogarithmic space, (2) any symmetric function F with an O(1)-approximate triangle inequality up to a 2^{O(C)} factor in Õ(n^{1/C}) · S(n) bits of space, where S is the space required to approximate F non-robustly; this includes a broad class of functions such as the L_1-norm, the support size F_0, and non-normed losses such as the M-estimators, and (3) L_2 heavy hitters. For the F_2 moment, our algorithm is optimal up to poly((log n)/ε) factors. Given the recent results of Gribelyuk et al. (STOC, 2025), this shows an exponential separation between linear sketches and non-linear sketches for achieving adversarial robustness in turnstile streams.

  - date: "9/11"
    speaker: Eric Balkanski
    affiliation: Columbia
    url: https://ericbalkanski.com/
    title: Online Selection via Linear Programming
    abstract: |-
      Secretary problems are a fundamental family of online selection problems in which candidates arrive in random order and irrevocable accept-or-reject decisions must be made. In this talk, I will present recent progress on three secretary problems: knapsack secretaries, secretaries with predictions, and truthful secretaries. Our results are obtained using a common two-step approach: we first reduce the original cardinal problem to an ordinal one and then formulate it as a linear program. For the first step, I will present a recent technical tool introduced by Gravin, Sun, and Tang, called order-statistics indistinguishable distributions, which can be used to show that there is no loss in the cardinal-to-ordinal reduction. For the second step, we formulate each ordinal problem as a novel linear program.

      For knapsack secretaries, constant competitive ratios are known, but it was open whether a 1/e competitive ratio is achievable. We show that 1/e is not achievable and give a new algorithm that improves the best-known competitive ratio. For secretaries with predictions, multiple prediction models have been proposed. We present a flexible linear programming framework that captures existing prediction models and use it to obtain improved algorithms and impossibility results, which are in some cases optimal. For truthful secretaries, the best-known truthful mechanism is ¼-competitive, and we show that ¼ is tight for a broad family of mechanisms.

      Joint work with Jason Chatzitheodorou, Dimitris Fotakis, Vasilis Gkatzelis, Xizhi Tan, Thanos Tolias, David Yang, and Cherlin Zhu.

  - date: "9/18"
    speaker: Brian Lee
    affiliation: UC Berkeley
    title: Blackwell Approachability and Gradient Equilibrium are Equivalent
    abstract: |-
      Gradient equilibrium (GEQ) is a recently introduced online optimization framework that generalizes first-order stationarity from offline optimization and subsumes problems like online conformal prediction. While GEQ has curious similarities to existing online learning frameworks, namely regret minimization, prior work has shown that GEQ error and regret are incomparable objectives, leaving open a precise understanding of how GEQ fits into the broader online learning landscape. In this work, we show that GEQ is equivalent to Blackwell approachability in an algorithmic sense. That is, an approachability problem can always be solved using queries to a black-box GEQ oracle, with no asymptotic loss in the oracle's error rate, and vice versa. Combined with well-known equivalences between approachability, regret minimization, and calibration, our results imply that GEQ is equivalent to the latter frameworks, as well.

      Joint work with Nika Haghtalab, Mike Jordan, and Ryan Tibshirani ([arXiv:2606.27315](https://arxiv.org/abs/2606.27315)).

  - date: "9/25"
    speaker: William Pires
    affiliation: Columbia
    title: "Adaptivity does not help: Nearly tight lower bounds for Boolean monotonicity testing"
    abstract: |-
      Monotonicity testing is interested in the following question: given query access to a boolean function f, how many queries does it take to distinguish between (1) the function being monotone and (2) the function being "far" from monotone? For non-adaptive algorithms (when your queries can't depend on the answer to previous queries) the query complexity was pinned down to be n^{1/2}. But can adaptivity help beat the n^{1/2} bound? In this talk we answer in the negative, by proving an almost tight n^{0.5-c} lower bound for adaptive monotonicity testing, for any constant c > 0. Our proof is based on a generalization of the "Talagrand Partitions" used by Belovs and Blais (2014) and Chen, Waingarten and Xie (2017) who respectively showed an n^{1/4} and n^{1/3} lower bound.

      Joint work with Xi Chen (Columbia), Mark Chen (Stanford), Hao Cui (NYU), and Jonah Stockwell (Columbia).

  - date: "10/2"
    speaker: David Wajc
    affiliation: Technion
    url: https://sites.google.com/view/david-wajc
    title: Chasing Submodular Objectives, and Submodular Maximization via Cutting Planes
    abstract: |-
      We introduce the submodular objectives chasing problem, which generalizes many natural and previously-studied problems: a sequence of constrained submodular maximization problems is revealed over time, with both the objective and available ground set changing over time. The goal is to maintain solutions of high approximation and low total recourse (number of changes), compared with exact offline algorithms for the same input sequence. For the central cardinality constraint and partition matroid constraints we provide optimal (1 − 1/e − ε)-approximation in polynomial time, with competitive recourse that is best-possible for any constant-approximation.

      Along the way, we design a new meta-algorithm for (1 − 1/e − ε)-approximately maximizing the multilinear extension under general constraints, which we call approximate-or-separate. The algorithm, whose guarantees are similar to the influential continuous greedy algorithm, can use any cutting plane method and separation oracle for the constraints.

      Based on joint work with Niv Buchbinder and Joseph (Seffi) Naor.

  - date: "10/9"
    note: No talk

  - date: "10/16"
    note: Just lunch (no talk)

  - date: "10/23"
    speaker: Nathan White
    affiliation: Penn
    url: https://www.engineering.upenn.edu/~nathanlw/

  - date: "10/30"
    speaker: Styopa Zharkov
    affiliation: Columbia

  - date: "11/6"
    speaker: Roie Levin
    affiliation: Rutgers
    url: https://roielevin.com/

  - date: "11/13"
    speaker: Chris Gartland
    affiliation: UNC Charlotte
    url: https://chrisgartland.wordpress.com/

  - date: "11/20"
    note: TBD

  - date: "11/27"
    note: Thanksgiving (no talk)

  - date: "12/4"
    note: TBD
---

The theory seminar is back for Fall 2026! Talks are (usually) on **Fridays from 12-1pm** in **Amy Gutmann Hall room 414**, and lunch is provided.
All talks are announced on the theory-group listserv, along with any time/date variances; you can sign up [here](https://lists.seas.upenn.edu/mailman/listinfo/theory-group).

Below is a tentative list of speakers for the semester.

{{< seminar-schedule >}}
