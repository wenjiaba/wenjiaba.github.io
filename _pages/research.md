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
*Forthcoming, Management Science*

(with [J. Michael Harrison](https://www.gsb.stanford.edu/faculty-research/faculty/j-michael-harrison) and [Harikesh S. Nair](https://gsb-faculty.stanford.edu/harikesh-nair/)) 

<details><summary>Abstract</summary><blockquote>
  We present a data-driven algorithm that advertisers can use to automate their digital ad-campaigns at online publishers. The algorithm enables the advertiser to search across available target audiences and ad-media to find the best possible combination for its campaign via online experimentation. The problem of finding the best audience-ad combination is complicated by a number of distinctive challenges, including (a) a need for active exploration to resolve prior uncertainty and to speed the search for profitable combinations, (b) many combinations to choose from, giving rise to high-dimensional search formulations, and (c) very low success probabilities, typically just a fraction of one percent. Our algorithm (designated LRDL, an acronym for Logistic Regression with Debiased Lasso) addresses these challenges by combining four elements: a multiarmed bandit framework for active exploration; a Lasso penalty function to handle high dimensionality; an inbuilt debiasing kernel that handles the regularization bias induced by the Lasso; and a semi-parametric regression model for outcomes that promotes cross-learning across arms. The algorithm is implemented as a Thompson Sampler, and to the best of our knowledge, it is the first that can practically address all of the challenges above. Simulations with real and synthetic data show the method is effective and document its superior performance against several benchmarks from the recent high-dimensional bandit literature.
</blockquote></details>

Algorithmic Price Competition with Reference-Dependent Consumers [[SSRN]](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=6388018)
-----

(with [S. Neda Ahmadi Amiri](https://www.linkedin.com/in/neda-ahmadi-amiri/) and [Z. Eddie Ning](https://www.eddiening.com) )

<details><summary>Abstract</summary><blockquote>
As consumers increasingly consult AI systems or delegate purchases to AI agents, their purchasing behavior may change. This shift makes it important to understand how firms' pricing algorithms respond to consumer behavior. We study reference-price dependence, whereby consumers form price expectations from historical prices and respond to deviations from those expectations. Using simulated experiments, we examine how reinforcement-learning pricing algorithms adapt as consumers become more or less reference dependent. Stronger reference dependence lowers prices and profits across our studies and raises consumer welfare in our baseline market. Surprisingly, this pattern persists even when relative collusiveness increases, as measured by the position of learned outcomes between competitive and collusive benchmarks. Whether relative collusiveness increases or decreases depends on market conditions and how much firms value future profits. Benchmark analysis provides economic intuition for these results. Our findings persist under deep reinforcement learning, linear demand, loss aversion, and alternative reference-formation processes. We discuss the implications for the design of consumer AI agents. More broadly, a similar approach can be used to study how other consumer behaviors shape algorithmic competition and welfare. 
</blockquote></details>

Agent-Mediated Commerce: Equilibrium Strategies and Market Outcomes
-----
*manuscript available upon request*

(with [Haim Mendelson](https://www.gsb.stanford.edu/faculty-research/faculty/haim-mendelson) and [Mingxi Zhu](https://sites.google.com/view/mingxizhu/home))

<details><summary>Abstract</summary><blockquote>
Advances in Artificial Intelligence have spawned new classes of electronic agents that facilitate interactions between buyers and sellers. This phenomenon is still evolving, which makes it important to develop a conceptual understanding of how it might affect marketing. We develop a model that examines three alternative, stylized electronic agent designs: a traditional voice assistant (such as the early versions of Amazon's Alexa), a seller agent (such as seller-controlled shopping agents), and a consumer agent (such as consumer-oriented LLM shopping agents). In all three cases, the agent presents products to the consumer and the consumer makes the final purchase decision. We first consider a voice assistant (VA) that aims to maximize the seller's expected profit. The VA dynamically presents sequential offers to the consumer, who evaluates each product presented and is limited by the constraints of the audio interface and her search time. We find that in equilibrium, the VA takes advantage of its inherent interface constraints to push higher-margin products first. Nevertheless, the seller can extract only half of the total surplus, sharing it equally with the consumer. We then examine a seller agent (SA) that controls both price and presentation, aiming to maximize the seller's expected profit while freeing the consumer from the interface constraints of the VA. Unlike the VA, the SA recalls all past offers and allows the consumer to go back to buy a product that she previously passed over. We compare the SA to a consumer agent (CA) which decides what products to present to the consumer for evaluation given the seller's posted prices and aims to maximize the expected consumer utility. In equilibrium, the CA presents items in descending order of their \emph{ex-ante} value minus cost and weakly ascending price-cost margins. We prove that under exponentially distributed private valuations, in spite of the differences between CA and SA, both give rise to exactly the same market outcomes. Numerical experiments confirm that transitioning from a VA to an SA (or, equivalently, CA) improves the seller's expected profit and surplus capture. </blockquote></details>

Poisson Limits of Bernoulli Bandits
-----
*in preparation*

(with [Lin Fan](https://linfanf.github.io), [J. Michael Harrison](https://www.gsb.stanford.edu/faculty-research/faculty/j-michael-harrison), and [Peter W. Glynn](https://web.stanford.edu/~glynn/))

<details><summary>Abstract</summary><blockquote>
We study Bernoulli bandits in the "hard luck" parameter regime. That is, the probability of success on any given trial is assumed to be small, regardless of what action the experimenter may choose, and regardless of what exogenous context may be observed. Adopting a general model formulation propounded by Kuang and Wager (2023), we prove a limit theorem that justifies approximating a Bernoulli bandit in the hard luck regime by a corresponding Poisson bandit. The latter is a continuous-time treatment selection model in which cumulative reward is driven by one of several possible Poisson processes, depending on the action or treatment selected by the experimenter; each of the Poisson processes has an average success rate that is initially unknown but can be learned through experimentation. Poisson bandits have several advantages over the Bernoulli bandits that they replace or approximate, including both sharper theoretical insights and ease of computation.
To illustrate the computational advantage, we study the use of policy gradient methods to optimize the parameters of randomized treatment selection policies in both Bernoulli bandit and Poisson bandit settings. Our theory and simulation experiments indicate that gradient estimators for Poisson bandit models have much lower variance and yield significantly better policies than those for the Bernoulli bandit models to which they correspond.
</blockquote></details>


 
