---
layout: archive
title: ""
permalink: /research/
author_profile: true
---
<h2>Research Areas:</h2>
Game Theory, Computational Modeling, Optimization, Learning, and Behavioral Economics

<h2>Research Papers:</h2>
<b>Job Market Paper:</b><br>
[<b>Evolving Sustainable Institutions in Agent-Based Simulations with Learning</b>](https://chriszosh1.github.io/files/EvolvingSustainableInstitutions_Zosh_et_al.pdf)
<br>with <a href="https://www.binghamton.edu/economics/faculty/profile.html?id=apape"> Andreas Pape</a>,
<a href="https://www.toddguilfoos.com/"> Todd Guilfoos</a>, and
<a href="https://www.law.northwestern.edu/faculty/profiles/peterdicola/"> Peter DiCola</a> <br>
In revise & resubmit at [JEBO](https://www.sciencedirect.com/journal/journal-of-economic-behavior-and-organization)<br>
<details style="margin-top: -22px;"><summary>Abstract:</summary>
    Elinor Ostrom identified eight design principles for the management of common-pool resources across hundreds of case studies. We develop a novel computational model in which learning agents intentionally explore the action space in a common resource game under different policy regimes to test the conditions in which one of Ostrom's design principles, graduated sanctions, emerges. We characterize the long-run policies that emerge top-down via a computational social planner and bottom-up via democracy, modeled as an endogenous self-governance process. 
    
    First, we find that graduated sanctions emerge top-down via a social planner who utilizes a fine-based policy without redistribution, but only when agents utilize similarity in their decision-making process. Next, we find that, when policy makers are able to redistribute fines, draconian style sanctions emerge. We also demonstrate that implementing the theoretical solution for rational agents who fully understand the game can forgo substantial potential gains in social welfare. Finally, we observe that, when agents participate in "democracy" (a bottom-up policy selection mechanism via voting for representatives) they are able to solve the commons problem fairly well, though we do not observe graduated sanction emerge in this context.
</details>

<b>Working Papers:</b><br>
[<b>A Guide and General Method for Estimating Parameters and their Confidence Intervals in Agent-Based Simulations with Stochasticity</b>](https://chriszosh1.github.io/files/AGuideAndGeneralMethodForEstimatingParametersAndTheirConfidenceIntervalsInAgentBasedSimulationWithStochasticity_Zosh_et_al.pdf)
<br>with Nency Dhameja,
Yixin Ren, and
<a href="https://www.binghamton.edu/economics/faculty/profile.html?id=apape"> Andreas Pape</a>
<details style="margin-top: -22px;"><summary>Abstract:</summary>
Although many Agent-Based Models (ABMs) traditionally serve to demonstrate proof-of-principle-type findings, it is becoming increasingly common and desirable for such models to be used directly for estimation. Given the increasing prevalence of using computational models for estimation in many disciplines, the need for a structured discussion on accessible and econometrically sound methods to estimate these models is of great importance.

Taking the view that ABMs are in many ways analogous to structural equation models, we detail a practical and fairly generalizable approach for bringing nearly any agent-based model to panel data in a manner akin to structural regression. We structure this paper with the aim of being an accessible guide for unfamiliar analysts to pick up and use, covering finding best fitting parameters (including summarizing and aggregating model output, establishing a fitness function, and choosing an optimization technique), estimating critical values using block-bootstrapping (including how to interpret confidence intervals and hypothesis testing in this context), and using Monte Carlo simulations to establish model/estimator properties. We also introduce a novel test to distinguish between different sources of estimate imprecision. We conclude with an example application in which we bring an ABM of learning agents playing a game to lab data to estimate agent learning parameters.
</details>


<a href="https://arxiv.org/abs/2406.10369"> <b>On the Preservation of Input/Output Directed Graph Informativeness under Crossover</b></a>
<br>with <a href="https://www.binghamton.edu/economics/faculty/profile.html?id=apape"> Andreas Pape</a>,
<a href="https://scholar.google.com/citations?user=pRy5WdkAAAAJ&hl=en"> J. David Schaffer</a>, and
<a href="http://bingdev.binghamton.edu/sayama/"> Hiroki Sayama</a> <br>
Under review<br>
<details style="margin-top: -22px;"><summary>Abstract:</summary>
There is a broad class of networks which connect inputs to outputs. These networks need not be feed-forward, including networks such as chemical transformation networks, electrical circuits, municipal water systems, and neural networks. The goal of this paper is to provide a strong theoretical foundation for a particular evolutionary operation, crossover, across this class of networks and connect crossover to informativeness, a measure of the connectedness of inputs to outputs. 

We define an Input/Output Directed Graph (or IOD Graph) as a graph with a set of nodes N and directed edges E, where N contains a set of "input nodes" I and a set of "output nodes" O. We define a crossover operation on IOD Graphs in which we find subgraphs with matching sets of forward and backward directed links to "swap." With this operation, IOD Graphs can be subject to evolutionary computation methods.

We also define informativeness, which characterizes the degree to which there exist directed paths from the input nodes to the output nodes, and investigate the extent to which the informativeness of parent graphs is preserved in the child graph(s) resulting from this operation. We show that fully informative parents may yield a non-informative child. We also show that under conditions of contiguousness and the no dangling nodes condition, crossover compatible, partially informative parents yield partially informative children, and very informative input parents with partially informative output parents yield very informative children. However, even under these conditions, full informativeness may not be retained.

</details>

<b>Selected Works in Progress:</b><br>
<b>The Problem with Empty-Headedness: Generalizing K-Level Beliefs to Simulate Priors in Models of Learning and Boundedly Rational Response</b>
<details style="margin-top: -22px;"><summary>Abstract:</summary>
While there is an extensive history of bringing decision theories with learning to lab data, such models have been encumbered by the problem of "empty-headedness", which is derived from the common assumption in learning models that agents have no information to go on before the first round of play. To solve this problem, I utilize a method of <em>simulated self-play</em> to generate priors using the features of the game themselves which can be applied to a large class of boundedly rational decision making processes with and without learning. Next, I demonstrate that k-level reasoning exists as a very specific case of this process which utilizes a rational "best response" function and batched updating. Finally, I compare the empirical performance (out of sample prediction) of two common learning models with and without simulated priors as well as K-level reasoning, utilizing lab data of players playing different versions of the Beauty Contest Game.
</details>

<h2>Supporting Documents</h2>
[<b>Research Statement</b>](https://chriszosh1.github.io/files/Research_Statement_ChrisZosh.pdf)