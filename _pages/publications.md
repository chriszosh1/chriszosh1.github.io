---
layout: archive
title: ""
permalink: /research/
author_profile: true
---
<h2>Research Areas:</h2>
Computational Modeling, Behavioral Game Theory, Microeconomic Theory, Complex Systems, Learning Models and Optimization

<h2>Research Papers:</h2>
<b>Job Market Paper:</b><br>

[<b>Monte-Carlo Tests for Identification and Validation of Stochastic Agent-Based Models</b>](https://chriszosh1.github.io/files/Agent-BasedEconometrics_MC_Zosh_et_al.pdf)
<br>with Nency Dhameja,
Yixin Ren, and
<a href="https://www.binghamton.edu/economics/faculty/profile.html?id=apape"> Andreas Pape</a><br>
<details style="margin-top: -22px;"><summary>Abstract:</summary>
Agent-based models (ABMs) are increasingly used for formal estimation and inference, but their complexity and algorithmic nature pose persistent challenges for the formal assessment of estimator properties.

This paper highlights the indispensable role that Monte Carlo simulations (MCS) can play in addressing these challenges. We show that MCS can systematically evaluate whether parameters of an ABM can be reliably estimated, how estimate accuracy and precision depend on factors such as search algorithm choice and the number of model runs conducted, and can even speak to model validity in some cases. We also introduce a novel Monte Carlo test that disentangles imprecision due to the stochasticity of the model and estimation process itself versus that sourced by sampling variation.

We apply these techniques to two example applications: first, a repeated prisoner's dilemma model with learning agents and second, a model of information diffusion over a network. Our results demonstrate that, while the parameters of these models can be identified in principle, estimator performance can be highly sensitive to choice of fitness function, search method used in the estimation process, and to features of the model itself, so establishing if a particular specification works for a particular problem is vital. These findings underscore the practical importance of applying MCS-based diagnostics before drawing substantive conclusions from estimated ABM parameters.
</details>

<b>Working Papers:</b><br>

[<b>Evolving Sustainable Institutions in Agent-Based Simulations with Learning</b>](https://chriszosh1.github.io/files/EvolvingSustainableInstitutions_Zosh_et_al.pdf)
<br>with <a href="https://www.binghamton.edu/economics/faculty/profile.html?id=apape"> Andreas Pape</a>,
<a href="https://www.toddguilfoos.com/"> Todd Guilfoos</a>, and
<a href="https://www.law.northwestern.edu/faculty/profiles/peterdicola/"> Peter DiCola</a> <br>
*Conditionally accepted at [JEBO](https://www.sciencedirect.com/journal/journal-of-economic-behavior-and-organization) - a leading journal in the behavioral economics subfield*<br>
<details style="margin-top: -22px;"><summary>Abstract:</summary>
We develop a novel, game-theoretic computational model in which learning agents explore how much to consume from a common resource. These agents live under three different political regimes: private provision, a benevolent and powerful social planner, and competitive direct democracy over vectors of (Pigouvian) fines. Both agent consumption and voting decisions are guided by a single process: reinforcement learning with action similarity. The model produces panel data of fine vectors for each regime and setting. 

We find the benevolent social planner’s fines have significant welfare gains over uncoordinated private action, and that competitive direct democracy’s fines can nearly achieve the same gains. We also find that learning changes the optimal solution: that is, the fine vector found by the	benevolent social planner is both distinct from and performs better than the socially optimal fine vector analytically derived from this setting, were it populated with rational, fully-informed agents.
    
Elinor Ostrom empirically identified eight “design principles” common to social structures of communities which successfully cultivate a common resource. One of these principles is ”graduated sanctions,” in which punishment accumulates at an accelerating rate as the degree of offense increases. We find that graduated sanctions only emerges when the agents use similarity in decision-making. We also find that, if fines generate revenue which can be costlessly redistributed, draconian (not graduated) sanctions emerge.
</details>


[<b>On the Preservation of Input/Output Directed Graph Informativeness under Crossover</b>](https://chriszosh1.github.io/files/SNNCrossover.pdf)
<br>with <a href="https://www.binghamton.edu/economics/faculty/profile.html?id=apape"> Andreas Pape</a>,
<a href="https://scholar.google.com/citations?user=pRy5WdkAAAAJ&hl=en"> J. David Schaffer</a>, and
<a href="http://bingdev.binghamton.edu/sayama/"> Hiroki Sayama</a> <br>
*In revise & resubmit at [Complexity](https://onlinelibrary.wiley.com/page/journal/8503/homepage/productinformation.html) - the leading interdisciplinary journal in complex systems research*<br>
<details style="margin-top: -22px;"><summary>Abstract:</summary>
There exists a broad class of networks that connect inputs to outputs. These networks include chemical transformation networks, electrical circuits, municipal water systems, and neural networks. The goals of this paper are to provide a theoretical foundation for evolutionary crossover on this class of graphs and connect crossover to informativeness, a measure of the connectedness of inputs to outputs. Informativeness is defined as: a partially informative graph has at least one path from an input to some output, a very informative graph has a path from every input to some output, and a fully informative graph has a path from every input to every output. If a neural network with non-zero weights and any number of layers is fully informative. As links are removed (assigned zero weight), it may become very, partially, or not informative. (The complement of informativeness is actionability, which is a measure of how connected outputs are from inputs.)

We define a crossover operation on IOD Graphs in which we find subgraphs with matching sets of forward and backward directed links to "swap." With this operation, IOD Graphs can be subject to evolutionary computation methods. We show that fully informative parents may yield a non-informative child. We also show that under certain conditions, crossover compatible, partially informative parents yield partially informative children, and very informative input parents with partially informative output parents yield very informative children. However, even under these conditions, full informativeness may not be retained. Similar results hold for actionability.
</details>

[<b>Social Context Matters: How Large Language Model Agents Reproduce Real-World Segregation Patterns in the Schelling Model</b>](https://chriszosh1.github.io/files/Social_Context_and_LLM_Segregation.pdf)
<br>with Mohammed Mahinur Alam, Nency Dhameja, Srikanth Iyer, <a href="https://www.binghamton.edu/anthropology/faculty/profile.html?id=clipo"> Carl Lipo</a>, and <a href="https://www.binghamton.edu/economics/faculty/profile.html?id=apape"> Andreas Pape</a><br>
<details style="margin-top: -22px;"><summary>Abstract:</summary>
We extend the classic Schelling segregation model by replacing its traditional, rule-based agents with Large Language Model (LLM) agents that make residential decisions using natural language reasoning grounded in social context. While LLMs have been incorporated into agent-based models before, to our knowledge this is the first application that substitutes the mechanical agents of the Schelling model with LLM-driven agents. We compare LLM agent behavior across five social contexts: a neutral baseline (red/blue teams), racial (White/Black), ethnic (Asian/Hispanic), economic (high/low income), and political (liberal/conservative) scenarios. Our results reveal dramatic differences in segregation patterns based solely on social framing. Political contexts produce the most extreme segregation (ghetto rate: 61.6, segregation share: 0.928), while economic contexts show minimal clustering (ghetto rate: 5.0, share: 0.543). Racial and ethnic scenarios fall between these extremes, reproducing some well-documented real-world patterns. All scenarios differ significantly from baseline ($p < 0.001$), with political segregation showing 12.3 times higher ghetto formation than economic segregation. These findings demonstrate that LLMs can capture culturally-embedded preferences and biases, producing segregation dynamics that vary realistically with social context. This has important implications for using LLM agents to model social phenomena and test policy interventions.
</details>

[<b>A Case for Simulated Self-Play in Decision Models with Learning</b>](https://chriszosh1.github.io/files/A_Case_for_Simulated_Self_Play_ChrisZosh.pdf)<br>
<details style="margin-top: -22px;"><summary>Abstract:</summary>
While there is an extensive history of bringing decision theories with learning to lab data, such models have been plagued with inadequate assumptions about the information players know before the first round of play. To solve this problem, I discuss the notion of Simulated Self-Play (SSP), in which agents play simulated rounds of the game against themselves to develop intuition about the nature of the game before the first round of play. Although some existing models of artificial intelligence have utilized self-play to achieve high performing solutions to some fairly complex problems (e.g. Alpha Zero playing Chess and Go), its exploration as a cognitive parameter when modeling human behavior has been relatively unexplored. First, I make the case that SSP improves theoretical coherence by discussing a number of common alternative assumptions (uniform / no priors, fitted priors, and burned-in priors), some of their a priori issues, and how Simulated Self-Play addresses many of them in a parsimonious way. Next, I evaluate the empirical value of SSP by implementing a simple learning model using priors formed via SSP and the alternatives and then compare their performance at predicting out-of-sample play in variations of the Beauty Contest game. I find that Simulated Self-Play performs as well or better than all of the aforementioned alternatives.
</details>

[<b>A Guide for Estimating Agent-Based Model Parameters, their Confidence Intervals, and Establishing Estimator Properties using AgentCarlo</b>](https://chriszosh1.github.io/files/Agent-BasedEconometrics_SP_Zosh_et_al.pdf)
<br>with Nency Dhameja,
Yixin Ren, and
<a href="https://www.binghamton.edu/economics/faculty/profile.html?id=apape"> Andreas Pape</a><br>
<details style="margin-top: -22px;"><summary>Abstract:</summary>
Although many Agent-Based Models (ABMs) traditionally serve to demonstrate proof-of-principle-type findings, it is becoming increasingly common and desirable for such models to be used directly for estimation in many disciplines. Given this, the need for a structured discussion on accessible and econometrically sound methods to estimate these models is of great importance.

Taking the view that ABMs are in many ways analogous to structural equation models, we detail a practical and fairly generalizable approach for bringing nearly any agent-based model to panel data in a manner akin to structural regression. We structure this paper with the aim of being an accessible guide for unfamiliar analysts to pick up and use, covering estimating best-fitting parameters via Simulated Method of Moments (including summarizing and aggregating model output, establishing a fitness function, and choosing an optimization technique), estimating critical values using block-bootstrapping (including how to interpret confidence intervals and hypothesis testing in this context), and using Monte Carlo simulations to establish a number of properties, including whether model parameters are well identified. We also introduce a novel test to distinguish between different sources of estimate imprecision which arise when estimating ABMs. We conclude with an example application in which we bring an ABM of learning agents playing a game to existing lab data to estimate agent learning parameters.
</details>

<h2>Supporting Documents:</h2>
My <b>Research Statement</b> can be found [here](https://chriszosh1.github.io/files/Research_Statement_ChrisZosh.pdf).
