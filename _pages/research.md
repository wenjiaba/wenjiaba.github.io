---
layout: archive
title: ""
permalink: /research/
author_profile: true
---

Doubly Optimal No-Regret Online Learning in Strongly Monotone Games with Bandit Feedback [[arxiv]](https://arxiv.org/abs/2112.02856)[[html]](https://pubsonline.informs.org/doi/10.1287/opre.2021.0445)
-----
*Operations Research, 2025*

(with [Tianyi Lin](https://tydlin.github.io),[Jiawei Zhang](https://www.stern.nyu.edu/faculty/bio/jiawei-zhang),and  [Zhengyuan Zhou](https://www.stern.nyu.edu/faculty/bio/zhengyuan-zhou) ) 

<details><summary>Abstract</summary><blockquote>
We consider online no-regret learning in unknown games with bandit feedback, where each player can only observe its reward at each time -- determined by all players' current joint action -- rather than its gradient. We focus on the class of smooth and strongly monotone games and study optimal no-regret learning therein. Leveraging self-concordant barrier functions, we first construct a new bandit learning algorithm and show that it achieves the single-agent optimal regret of $\tilde{\Theta}(n\sqrt{T})$ under smooth and strongly concave reward functions ($n \geq 1$ is the problem dimension). We then show that if each player applies this no-regret learning algorithm in strongly monotone games, the joint action converges in the last iterate to the unique Nash equilibrium at a rate of $\tilde{\Theta}(\sqrt{\frac{n^2}{T}})$. Prior to our work, the best-known convergence rate in the same class of games is $\tilde{O}(\sqrt[3]{\frac{n^2}{T}})$ (achieved by a different algorithm), thus leaving open the problem of optimal no-regret learning algorithms (since the known lower bound is $\Omega(\sqrt{\frac{n^2}{T}})$). Our results thus settle this open problem and contribute to the broad landscape of bandit game-theoretical learning by identifying the first doubly optimal bandit learning algorithm, in that it achieves (up to log factors) both optimal regret in the single-agent learning and optimal last-iterate convergence rate in the multi-agent learning. We also present results on several application studies -- Cournot competition, Kelly auctions, and distributed regularized logistic regression -- to demonstrate the efficacy of our algorithm.
</blockquote></details>

Advertising Media and Target Audience Optimization via High-dimensional Bandits [[arxiv]](https://arxiv.org/abs/2209.08403)
-----
*minor revision at Management Science*

(with [J. Michael Harrison](https://www.gsb.stanford.edu/faculty-research/faculty/j-michael-harrison) and [Harikesh S. Nair](https://gsb-faculty.stanford.edu/harikesh-nair/)) 

<details><summary>Abstract</summary><blockquote>
  We present a data-driven algorithm that advertisers can use to automate their digital ad-campaigns at online publishers. The algorithm enables the advertiser to search across available target audiences and ad-media to find the best possible combination for its campaign via online experimentation. The problem of finding the best audience-ad combination is complicated by a number of distinctive challenges, including (a) a need for active exploration to resolve prior uncertainty and to speed the search for profitable combinations, (b) many combinations to choose from, giving rise to high-dimensional search formulations, and (c) very low success probabilities, typically just a fraction of one percent. Our algorithm (designated LRDL, an acronym for Logistic Regression with Debiased Lasso) addresses these challenges by combining four elements: a multiarmed bandit framework for active exploration; a Lasso penalty function to handle high dimensionality; an inbuilt debiasing kernel that handles the regularization bias induced by the Lasso; and a semi-parametric regression model for outcomes that promotes cross-learning across arms. The algorithm is implemented as a Thompson Sampler, and to the best of our knowledge, it is the first that can practically address all of the challenges above. Simulations with real and synthetic data show the method is effective and document its superior performance against several benchmarks from the recent high-dimensional bandit literature.
</blockquote></details>

Consumer Behavior and Algorithmic Price Competition: The Case of Reference Dependence [[SSRN]](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=6388018)
-----

(with [S. Neda Ahmadi Amiri](https://www.linkedin.com/in/neda-ahmadi-amiri/) and [Z. Eddie Ning](https://www.eddiening.com) )

<details><summary>Abstract</summary><blockquote>
  As AI and humans increasingly coexist in the marketplace, it is important to understand how human psychology interacts with algorithmic decision-making. How do consumer behavioral patterns influence algorithmic pricing and the resulting profits and consumer welfare? Should consumer AI agents emulate human psychology or act rationally? While current wisdom suggests removing human biases to maximize efficiency, our paper investigates how consumers' reference dependence, a core human "bias", shapes market outcomes under algorithmic price competition. We show theoretically that reference dependence creates two opposing forces on equilibrium prices: higher demand elasticity disciplines prices downward, while easier collusion raises them. We resolve this tension using simulated experiments in which reinforcement-learning pricing algorithms compete repeatedly for reference-dependent consumers. We find that the disciplining effect dominates: reference dependence paradoxically acts as a competitive safeguard, driving prices down, consumer welfare up, and firm profits down, even as algorithms attempt to collude. These effects persist even when pricing algorithms do not account for behavioral demand features, when consumers are loss-averse, and under alternative assumptions on how consumers form reference prices. Human behavioral biases, while individually non-rational, can collectively discipline pricing and improve consumer outcomes, especially when facing algorithms. We discuss the implications of these findings for the design of consumer AI agents.
</blockquote></details>


Sales Policies of a Virtual Assistant
-----
*manuscript available upon request*

(with [Haim Mendelson](https://www.gsb.stanford.edu/faculty-research/faculty/haim-mendelson) and [Mingxi Zhu](https://sites.google.com/view/mingxizhu/home))

<details><summary>Abstract</summary><blockquote>
We study the implications of selling through a voice-based virtual assistant (VA). The seller has a set of products available and the VA decides on product ranking and pricing, seeking to maximize seller profit, consumer surplus, or total surplus. The consumer is impatient yet rational, seeking to maximize her expected utility. The VA presents the products sequentially. Once a product is presented and priced, the consumer evaluates it and decides whether to purchase it. The consumer's valuation comprises a pre-evaluation value which is common knowledge and a private post-evaluation component. We solve for the equilibria and develop efficient algorithms for implementing the solution. We examine the effects of information asymmetry on the outcomes and study how incentive misalignment depends on the private valuation distributions.
</blockquote></details>

Poisson Limits of Bernoulli Bandits
-----
*in preparation*

(with [Lin Fan](https://linfanf.github.io), [J. Michael Harrison](https://www.gsb.stanford.edu/faculty-research/faculty/j-michael-harrison), and [Peter W. Glynn](https://web.stanford.edu/~glynn/))

<details><summary>Abstract</summary><blockquote>
We study Bernoulli bandits in the ``hard luck'' parameter regime. That is, the probability of success on any given trial is assumed to be small, regardless of what action the experimenter may choose, and regardless of what exogenous context may be observed. Adopting a general model formulation propounded by Kuang and Wager (2023), we prove a limit theorem that justifies approximating a Bernoulli bandit in the hard luck regime by a corresponding Poisson bandit. The latter is a continuous-time treatment selection model in which cumulative reward is driven by one of several possible Poisson processes, depending on the action or treatment selected by the experimenter; each of the Poisson processes has an average success rate that is initially unknown but can be learned through experimentation. Poisson bandits have several advantages over the Bernoulli bandits that they replace or approximate, including both sharper theoretical insights and ease of computation.
To illustrate the computational advantage, we study the use of policy gradient methods to optimize the parameters of randomized treatment selection policies in both Bernoulli bandit and Poisson bandit settings. Our theory and simulation experiments indicate that gradient estimators for Poisson bandit models have much lower variance and yield significantly better policies than those for the Bernoulli bandit models to which they correspond.
</blockquote></details>


 
