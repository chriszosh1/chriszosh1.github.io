---
layout: archive
title: ""
permalink: /research/
author_profile: true
---
<h2>Research Areas:</h2>
Micro Theory, Game Theory, Computational Modeling, Organization & Behavior, Learning Models

<h2>Research Papers:</h2>
<b>Job Market Paper:</b><br>
[<b>Agent-Based Econometrics: A Guide and General Method for Estimating Parameters and their Confidence Intervals in Agent-Based Simulations with Stochasticity</b>](https://chriszosh1.github.io/files/Agent-BasedEconometrics_Zosh_et_al.pdf)
<br>with Nency Dhameja,
Yixin Ren, and
<a href="https://www.binghamton.edu/economics/faculty/profile.html?id=apape"> Andreas Pape</a>
<details style="margin-top: -22px;"><summary>Abstract:</summary>
Although many Agent-Based Models (ABMs) traditionally serve to demonstrate proof-of-principle-type findings, it is becoming increasingly common and desirable for such models to be used directly for estimation in many disciplines. Given this, the need for a structured discussion on accessible and econometrically sound methods to estimate these models is of great importance.

Taking the view that ABMs are in many ways analogous to structural equation models, we detail a practical and fairly generalizable approach for bringing nearly any agent-based model to panel data in a manner akin to structural regression. We structure this paper with the aim of being an accessible guide for unfamiliar analysts to pick up and use, covering estimating best-fitting parameters via Simulated Method of Moments (including summarizing and aggregating model output, establishing a fitness function, and choosing an optimization technique), estimating critical values using block-bootstrapping (including how to interpret confidence intervals and hypothesis testing in this context), and using Monte Carlo simulations to establish a number of properties, including whether model parameters are well identified. We also introduce a novel test to distinguish between different sources of estimate imprecision which arise when estimating ABMs. We conclude with an example application in which we bring an ABM of learning agents playing a game to existing lab data to estimate agent learning parameters.
</details>

<b>Working Papers:</b><br>

[<b>Evolving Sustainable Institutions in Agent-Based Simulations with Learning</b>](https://chriszosh1.github.io/files/EvolvingSustainableInstitutions_Zosh_et_al.pdf)
<br>with <a href="https://www.binghamton.edu/economics/faculty/profile.html?id=apape"> Andreas Pape</a>,
<a href="https://www.toddguilfoos.com/"> Todd Guilfoos</a>, and
<a href="https://www.law.northwestern.edu/faculty/profiles/peterdicola/"> Peter DiCola</a> <br>
In revise & resubmit at [JEBO](https://www.sciencedirect.com/journal/journal-of-economic-behavior-and-organization)<br>
<details style="margin-top: -22px;"><summary>Abstract:</summary>
Elinor Ostrom identified eight design principles for the management of common-pool resources across hundreds of case studies. We develop a novel computational model in which learning agents intentionally explore the action space in a common resource game under different policy regimes to test the conditions in which one of Ostrom's design principles, graduated sanctions, emerges. We characterize the long-run policies that emerge top-down via a computational social planner and bottom-up via democracy, modeled as an endogenous self-governance process. 
    
First, we find that graduated sanctions emerge top-down via a social planner who utilizes a fine-based policy without redistribution, but only when agents utilize similarity in their decision-making process. Next, we find that, when policy makers are able to redistribute fines, draconian style sanctions emerge. We also demonstrate that implementing the theoretical solution for rational agents who fully understand the game can forgo substantial potential gains in social welfare. Finally, we observe that, when agents participate in "democracy" (a bottom-up policy selection mechanism via voting for representatives) they are able to solve the commons problem fairly well, though we do not observe graduated sanction emerge in this context.
</details>

<a href="https://arxiv.org/abs/2406.10369"> <b>On the Preservation of Input/Output Directed Graph Informativeness under Crossover</b></a>
<br>with <a href="https://www.binghamton.edu/economics/faculty/profile.html?id=apape"> Andreas Pape</a>,
<a href="https://scholar.google.com/citations?user=pRy5WdkAAAAJ&hl=en"> J. David Schaffer</a>, and
<a href="http://bingdev.binghamton.edu/sayama/"> Hiroki Sayama</a> <br>
Under review at [Complexity](https://onlinelibrary.wiley.com/page/journal/8503/homepage/productinformation.html)<br>
<details style="margin-top: -22px;"><summary>Abstract:</summary>
There exists a broad class of networks that connect inputs to outputs. These networks include chemical transformation networks, electrical circuits, municipal water systems, and neural networks. The goals of this paper are to provide a theoretical foundation for evolutionary crossover on this class of graphs and connect crossover to informativeness, a measure of the connectedness of inputs to outputs. Informativeness is defined as: a partially informative graph has at least one path from an input to some output, a very informative graph has a path from every input to some output, and a fully informative graph has a path from every input to every output. If a neural network with non-zero weights and any number of layers is fully informative. As links are removed (assigned zero weight), it may become very, partially, or not informative. (The complement of informativeness is actionability, which is a measure of how connected outputs are from inputs.)

We define a crossover operation on IOD Graphs in which we find subgraphs with matching sets of forward and backward directed links to "swap." With this operation, IOD Graphs can be subject to evolutionary computation methods. We show that fully informative parents may yield a non-informative child. We also show that under certain conditions, crossover compatible, partially informative parents yield partially informative children, and very informative input parents with partially informative output parents yield very informative children. However, even under these conditions, full informativeness may not be retained. Similar results hold for actionability.
</details>

<b>Selected Works in Progress:</b><br>
[<b>A Case for Simulated Self-Play in Decision Models with Learning</b>](https://chriszosh1.github.io/files/A_Case_for_Simulated_Self_Play_ChrisZosh.pdf)
<details style="margin-top: -22px;"><summary>Abstract:</summary>
While there is an extensive history of bringing decision theories with learning to lab data, such models have been plagued with inadequate assumptions about the information players know before the first round of play. To solve this problem, I discuss the notion of Simulated Self-Play (SSP), in which agents play simulated rounds of the game against themselves to develop intuition about the nature of the game before the first round of play. Although some existing models of artificial intelligence have utilized self-play to achieve high performing solutions to some fairly complex problems (e.g. Alpha Zero playing Chess and Go), its exploration as a cognitive parameter when modeling human behavior has been relatively unexplored. First, I make the case that SSP improves theoretical coherence by discussing a number of common alternative assumptions (uniform / no priors, fitted priors, and burned-in priors), some of their a priori issues, and how Simulated Self-Play addresses many of them in a parsimonious way. Next, I evaluate the empirical value of SSP by implementing a simple learning model using priors formed via SSP and the alternatives and then compare their performance at predicting out-of-sample play in variations of the Beauty Contest game. I find that Simulated Self-Play performs as well or better than all of the aforementioned alternatives.
</details>

<h2>Supporting Documents:</h2>
My <b>Research Statement</b> can be found [here](https://chriszosh1.github.io/files/Research_Statement_ChrisZosh.pdf)