# EHA

![SBU Logo](index_files/sblogo) ![NSF Logo](index_files/nsf)

## Excitable Hybrid Automata

| [Introduction](http://www.cs.sunysb.edu/%7Eeha/index.htm) | [Documentation](http://www.cs.sunysb.edu/%7Eeha/documentation.htm) | [Download](http://www.cs.sunysb.edu/%7Eeha/download.htm) | [People](http://www.cs.sunysb.edu/%7Eeha/people.htm) | [Sponsors](http://www.cs.sunysb.edu/%7Eeha/sponsors.htm) | [Results](http://www.cs.sunysb.edu/%7Eeha/results.htm) | [Links](http://www.cs.sunysb.edu/%7Eeha/links.htm) |

### Introduction

Systems biology is an emerging multidisciplinary field whose goal is to provide a systems-level understanding of biological systems by uncovering their structure, dynamics and control methods. While many exciting and profound advances have been made in investigating robustness, network structures and dynamics, and application to drug discovery, the field is still in its infancy. An important open problem in systems biology is finding appropriate computational models that scale well for both the simulation and formal analysis of biological processes. Currently, the majority of these models are given in terms of large and complex sets of nonlinear differential equations, describing in painful detail the underlying biological phenomena. Although an invaluable asset for integrating genomics and proteomics data to reveal local interactions, such models are often not amenable to formal analysis and render simulation at the organ or even the cell level impractical. This project seeks to develop a hybrid-automata (HA) approach to modeling and analyzing complex biological systems. Excitable cell networks (heart cells in particular) will be used as an archetype of a complex biological system. Standard modeling methods capture the behavior of such cells using reaction-diffusion PDE systems, with the Hodgkin-Huxley (HH) formalism describing ion channel gating and currents. Initial results indicate that HA models, combining discrete and continuous processes, are able to successfully capture the morphology of the excitation event (action potential) of different cell types, including cardiac cells. They can also reproduce typical excitable cell characteristics, such as refractoriness (period of non-responsiveness to external stimulation) and restitution (adaptation to pacing rates). Multicellular ensembles of HA elements are used to simulate excitation wave propagation, including complex spiral waves underlying pathological conditions in the heart. The resulting simulation framework exhibits significantly improved computational efficiency, and opens the possibility to formal analysis based on HA theory.

Event Driven Simulator: edm.zip

Time-step Integration Simulator: tsim.zip

Simulator Documentation: Documentation.doc or Documentation.pdf

---

Site maintained by [Mike True](mailto:mtrue@cs.sunysb.edu)

---

2025-06-02: Standardized to Markdown.