---
title: "Theory Seminar: Kate Donahue"
date: 2023-09-08
---

This week's theory seminar speaker is Kate Donahue of Cornell University. As usual, the talk will take place in Room 401B, 3401 Walnut Street on Friday 12-1 PM. Talk and speaker details are included below

**Title:** Stability, Optimality, and Fairness in Federated Learning

**Abstract:** Federated learning is a distributed learning paradigm where multiple agents, each only with access to local data, jointly learn a global model. There has recently been an explosion of research aiming not only to improve the accuracy rates of federated learning, but also provide certain guarantees around social good properties such as total error or fairness. In this talk, I describe three papers analyzing federated learning through the lens of cooperative game theory, all joint with Jon Kleinberg (https://arxiv.org/abs/2010.00753, https://arxiv.org/abs/2106.09580, https://arxiv.org/abs/2112.00818)

In the first paper, we discuss fairness in federated learning, which relates to how error rates differ between federating agents. In this work, we consider two notions of fairness: egalitarian fairness (which aims to bound how dissimilar error rates can be) and proportional fairness (which aims to reward players for contributing more data). For egalitarian fairness, we obtain a tight multiplicative bound on how widely error rates can diverge between agents federating together. For proportional fairness, we show that sub-proportional error (relative to the number of data points contributed) is guaranteed for any individually rational federating coalition. The second paper explores optimality in federated learning with respect to an objective of minimizing the average error rate among federating agents. In this work, we provide and prove the correctness of an efficient algorithm to calculate an optimal (error minimizing) arrangement of players. This paper builds on our prior work on stability in federated learning, and allows us to give the first constant-factor bound on the performance gap between stability and optimality, proving that the total error of the worst stable solution can be no higher than 9 times the total error of an optimal solution (Price of Anarchy bound of 9).

**Bio:** Kate Donahue is a fifth year computer science PhD candidate at Cornell advised by Jon Kleinberg. She works on algorithmic problems relating to the societal impact of AI such as fairness, human/AI collaboration and game-theoretic models of federated learning. Her work has been supported by an NSF fellowship and recognized by a FAccT Best Paper award. During her PhD, she has interned at Microsoft Research, Amazon, and Google.


