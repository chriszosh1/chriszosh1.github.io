---
layout: archive
title: ""
permalink: /research/
author_profile: true
---

<h2>Working Papers:</h2>
[<b>Evolving Sustainable Institutions in Agent-Based Simulations with Learning</b>](https://chriszosh1.github.io/files/EvolvingSustainableInstitutions_Zosh_et_al.pdf)
<br>with <a href="https://www.binghamton.edu/economics/faculty/profile.html?id=apape"> Andreas Pape</a>,
<a href="https://www.toddguilfoos.com/"> Todd Guilfoos</a>, and
<a href="https://www.law.northwestern.edu/faculty/profiles/peterdicola/"> Peter DiCola</a> <br>
In revise & resubmit at [JEBO](https://www.sciencedirect.com/journal/journal-of-economic-behavior-and-organization)<br>
<details style="margin-top: 0px; padding-top: 0px;"><summary>Abstract</summary>
    Elinor Ostrom identified eight design principles for the management of common-pool resources across hundreds of case studies. We develop a novel computational model in which learning agents intentionally explore the action space in a common resource game under different policy regimes to test the conditions in which one of Ostrom's design principles, graduated sanctions, emerges. We characterize the long-run policies that emerge top-down via a computational social planner and bottom-up via democracy, modeled as an endogenous self-governance process. 
    
    First, we find that graduated sanctions emerge top-down via a social planner who utilizes a fine-based policy without redistribution, but only when agents utilize similarity in their decision-making process. Next, we find that, when policy makers are able to redistribute fines, draconian style sanctions emerge. We also demonstrate that implementing the theoretical solution for rational agents who fully understand the game can forgo substantial potential gains in social welfare. Finally, we observe that, when agents participate in ``democracy'' (a bottom-up policy selection mechanism via voting for representatives) they are able to solve the commons problem fairly well, though we do not observe graduated sanction emerge in this context.
</details>

<a href="https://arxiv.org/abs/2406.10369"> <b>On the Preservation of Input/Output Directed Graph Informativeness under Crossover</b></a>
<br>with <a href="https://www.binghamton.edu/economics/faculty/profile.html?id=apape"> Andreas Pape</a>,
<a href="https://scholar.google.com/citations?user=pRy5WdkAAAAJ&hl=en"> J. David Schaffer</a>, and
<a href="http://bingdev.binghamton.edu/sayama/"> Hiroki Sayama</a> <br>
Under review at [Evolutionary Computation](https://direct.mit.edu/evco) <br>
<details><summary>Abstract:</summary>
There is a broad class of networks which connect inputs to outputs. These networks include chemical transformation networks, electrical circuits, municipal water systems, and neural networks. Evolutionary operations like crossover have been used in all these domains. The goal of this paper is to provide a strong theoretical foundation for crossover across this class of networks and connect crossover to informativeness, a measure of the connectedness of inputs to outputs.
    
We define an \textit{Input/Output Directed Graph} (or \textit{IOD Graph)} as a graph with a set of nodes $N$ and directed edges $E$, where $N$ contains  (a) a set of ``input nodes'' $I \subset N$, where each $i \in I$ has no incoming edges and any number of outgoing edges, and (b) a set of ``output nodes'' $O \subset N$, where each $o \in O$ has no outgoing edges and any number of incoming edges, and $I \cap O = \emptyset$. We define informativeness, which involves the connections via directed paths from the input nodes to the output nodes: A \textit{partially informative IOD Graph} has at least one path from an input to an output, a \textit{very informative IOD Graph} has a path from every input to some output, and a \textit{fully informative IOD Graph} has a path from every input to every output. A perceptron is an example of an IOD Graph. If it has non-zero weights and any number of layers, it is fully informative. As links are removed (assigned zero weight), the perceptron might become very, partially, or not informative.
We define a crossover operation on IOD Graphs in which we find subgraphs with matching sets of forward and backward directed links to ``swap.'' With this operation, IOD Graphs can be subject to evolutionary computation methods. 
We show that fully informative parents may yield a non-informative child. We also show that under conditions of \emph{contiguousness} and the \emph{no dangling nodes} condition, crossover compatible, partially informative parents yield partially informative children, and very informative input parents with partially informative output parents yield very informative children. However, even under these conditions, full informativeness may not be retained.

</details>


[<b>A Guide and General Method for Estimating Parameters and their Confidence Intervals in Agent-Based Simulations with Stochasticity</b>](https://chriszosh1.github.io/files/AGuideAndGeneralMethodForEstimatingParametersAndTheirConfidenceIntervalsInAgentBasedSimulationWithStochasticity_Zosh_et_al.pdf)
<br>with Nency Dhameja,
Yixin Ren, and
<a href="https://www.binghamton.edu/economics/faculty/profile.html?id=apape"> Andreas Pape</a>
<details><summary>Abstract:</summary>
While many Agent-Based Models (ABMs) traditionally serve to demonstrate proof of principle type findings, it is becoming increasingly common and desirable for such models to be used directly for estimation. Given the increasing prevalence of computational models across many disciplines, the need for accessible and econometrically sound methods for estimating these models in one's toolkit has never been greater.
    
Taking the view that ABMs are in many ways analogous to structural equation models, we detail a fairly generalizable estimation framework for bringing nearly any agent-based model to panel data in a manner akin to structural regression. We structure this paper with the aim of being an accessible guide for unfamiliar analysts to pick up and use, covering finding best fitting parameters (including summarizing and aggregating model output, establishing a fitness function, and optimization), estimating critical values using block-bootstrapping (including how to interpret confidence intervals and hypothesis testing in this context), and using Monte-Carlo simulations to establish model/estimator properties (including simulations for determining estimator inaccuracy and bias and decomposing sources of estimator imprecision).

</details>


<b>The Problem with Empty-Headedness: Generalizing K-Level Beliefs to Simulate Priors in Models of Learning and Boundedly Rational Response</b>
<details><summary>Abstract:</summary>

While there is an extensive history of bringing decision theories with learning to lab data, such models have been encumbered by the problem of ''empty-headedness'', which is derived from the common assumption in learning models that agents have no information to go on before the first round of play. To solve this problem, I utilize a method of <em>simulated self-play</em> to generate priors using the features of the game themselves which can be applied to a large class of boundedly rational decision making processes with and without learning. Next, I demonstrate that k-level reasoning exists as a very specific case of this process which utilizes a rational ''best response'' function and batched updating. Finally, I compare the empirical performance (out of sample prediction) of two common learning models with and without simulated priors as well as K-level reasoning, utilizing lab data of players playing different versions of the Beauty Contest Game.
</details>

<h2>Other:</h2>
My <b>Research Statement</b> can be found [here](https://chriszosh1.github.io/files/Research_Statement_ChrisZosh.pdf)