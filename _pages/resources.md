---
permalink: /resources/
title: "Resources"
---

This page contains links to software, tools, or websites relating to my work.

My [google scholar profile.](https://scholar.google.co.uk/citations?user=WfvA3zIAAAAJ&hl=en&authuser=1)

## The Immune Dynamics team

Can be found [through this website](https://immunedynamics.io).

We are a collaboration of data scientists (e.g. me), immunologists, and single-cell technology specialists who build technological platforms to advance the study of disease, inflammation and infection through single-cell technologies.

### Spectre

[Spectre is an R package](https://immunedynamics.io/spectre/) 
that provides streamlined workflows for the analysis of single cell sequencing data (including cytometry).

### TrackSOM

[TrackSOM is a temporal cytometry clustering algorithm](https://github.com/ghar1821/TrackSOM) built upon FlowSOM.
The immune response a highly dynamic process resulting from the coordinated actions of many cellular populations.
TrackSOM is a world-leading algorithm that enables integrated analysis of the immune response in these terms.

### ParetoBench

Ever wonder why every cytometry benchmarking study recommends a different algorithm?
It's because different performance metrics interact with different datasets to give biased results towards any given algorithm.
Metrics are not impartial, they emphasise different features of a dataset and an algorithm.
So how are investigators to choose the most appropriate algorithm?

This paper developed Pareto fronts as a framework for providing an unbiased evaluation of clustering algorithms, drawing on many metrics and many datasets simultaneously.
It employs 'wisdom of crowds' (or 'trial by jury') to make better decisions based on many perspectives.
Critically, it is an ability to offer competitive performance on **all datasets and metrics _simultaneously_** that makes for a superior algorithm.
We showed this on high-dimensional cytometry data, but the principles are transferable to any application domain.

Find the [ParetoBench paper here](https://doi.org/10.1093/bioinformatics/btab038)
, and [the GitHub repository here](https://github.com/ghar1821/ParetoBench).

### ChronoClust

The predecessor of TrackSOM.
ChronoClust was our first temporal cytometry analysis algorithm.
It is highly customisable, but this can come at the expense of being difficult to tune, as we discovered in the ParetoBench paper.

[ChronoClust paper here](https://www.sciencedirect.com/science/article/abs/pii/S0950705119300796).
[GitHub repository here]()https://ghar1821.github.io/Chronoclust/.

## GutSim

My simulation of gut microbial community response to diet was featured in [Andrew Holmes’s 2017 Cell Metabolism paper](https://www.sciencedirect.com/science/article/pii/S1550413116305538?via%3Dihub).
The main manuscript describing the simulation work is in final draft, with submission anticipated very soon.
The simulation can be [found through this GitHub repository](https://github.com/marknormanread/GutSim).

## Motilisim: 3D Leukocyte Motility Simulator

In 2016 I published a paper in
[PLOS Computational Biology](https://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1005082)
that proposed a combination of simulation and multi-objective optimisation as a means to determine the search strategies that leukocytes (cells of the immune system) employ.
All software from the paper [can be downloaded here](https://journals.plos.org/ploscompbiol/article/file?type=supplementary&id=info:doi/10.1371/journal.pcbi.1005082.s038).
It includes an implementation of NSGA-II, a multi-objective optimisation engine, that was used to fit motility models to real-world cellular motility data.

A [modified version of this multi-objective optimisation technology](https://github.com/marknormanread/unsga3) was used in my 
[2016 Journal of the Royal Society Interface paper](https://royalsocietypublishing.org/doi/full/10.1098/rsif.2016.0543) on calibration of biological simulations.

I have since [moved MotiliSim to GitHub](https://github.com/marknormanread/motilisim).

## Motility analysis

A Python package that will analyse the motility of a population of agents in 3D space.
The package provides very many statistical analyses, both descriptive of a given dataset and providing statistical significance of difference measures between multiple datasets.

It is [available on GitHub](https://github.com/marknormanread/motility_analysis).

## U-NSGA-III

Universal Non-dominated Sorting Genetic Algorithm III (U-NSGA-III) is an incredibly powerful multi-objective optimisation algorithm.
A number of years ago, there was no publicly available implementation of this algorithm (I suspect perhaps there was a company trying to commercialise it).
I created one, as I was using it in my research to calibrate biological simulations against real-world data.

Included in my implementation was a provision for independently evaluating the quality of the fitted model against independent data.
This is akin to the training-validation separation of data used in supervised machine learning.

My UNSGA-III implementation is [freely available through GitHub](https://github.com/marknormanread/unsga3).

## ARTIMMUS

The Artificial Murine Multiple Sclerosis simulation (ARTIMMUS) [can be downloaded here](https://github.com/marknormanread/artimmus).

There is a supporting information PDF in the repository which provides details on ARTIMMUS's biological underpinning and construction.

This simulation is largely the product of my doctoral research, it is the world’s first agent-based simulation of experimental autoimmune encephalomyelitis (EAE). 
The model of EAE simulated here is a T cell-mediated autoimmune disease in mice, used as a model for multiple sclerosis.
This simulation has lead to a number of publications: Read 13, Greaves 13, Williams 13, Read 11, and others – see my Publications page.

## CoCoRo Underwater Swarm Robotics Project

The CoCoRoSim simulator is an 3D agent-based simulation of the underwater swarm robotic system being developed as part of the CoCoRo project.
One of my responsibilities on the project was to develop and maintain this simulation.

The original website died a few years ago, so [I moved the code over to GitHub](https://github.com/marknormanread/cocorosim).


Statistical Software

The following files provide implementations of statistical tests or distributions that can be difficult to find elsewhere.

Lévy distribution generators. In Java. In Python.
The Vargha-Delaney “A” statistic. Matlab (distributions of equal size), Matlab (distributions of differing size), and Python. You’ll need Cliff’s Delta too.
Empirical cumulative distribution function (Python, you’ll need to unzip this).
 

CoSMoS Project

The CoSMoS website.

The Complex Systems Modelling and Simulation infrastructure (CoSMoS – don’t ask where the ‘i’ went…) project was an EPSRC-funded research project held between the universities of York and Kent. The project aim was to provide capacity in the simulation of complex systems, from both a simulation programming language infrastructure perspective (occam-π, a process oriented langauge), and a more philosophical simulation development angle. The latter culminated in the “CoSMoS process”, a guide to developing simulations of complex systems that are well grounded in their complex system domains. This was achieved through explicit modelling at various stages of simulation conceptualisation and development, and the tracking of assumptions relating the simulation to the domain. A book consolidating the major research output of CoSMoS is currently being written.

AWASS 13 Summer School

The CoCoRoSim simulation, used for development of your chain formation algorithm, can be downloaded here. It’s a ZIP file.

The presentation explaining the problem is available here.

You will need to download NetLogo first (you need 3D, not 2D, but it looks like they are downloaded in the same package). When you have installed that, you can open the simulation in NetLogo, by opening the “CoCoRoSim.nlogo” file in the source zip file available above.

NetLogo documentation is very good. If you google “netlogo dictionary” and “netlogo 3d dictionary”, the first hit is nearly always the code dictionary. Most NetLogo 2D commands work in NetLogo 3D also.

2D dictionary

3D dictionary
