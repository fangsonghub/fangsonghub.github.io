---
layout: course
courseid: s17 410/510
desc: Project
permalink: /teaching/s17_4510_qc/project/
title: (Spring 2017) CS 410/510 - Intro to Quantum Computing
subtitle: Course Project
modified: 2017-04-11
---
<!--<p style="text-align: center;"> <a href="{{base}}/teaching/s17_4510_qc/project.pdf" target="_blank">PDF</a></p> -->

## Instructions
2-3 people group projects. You may choose to do a _literature review_
project or (more exciting) _original research_. For literature review,
you'd read a few papers around a topic, understand the connection of
this topic to the general field of quantum computing as well as the of
various works under this topic. The final outcome would be a _survey_
paper including interesting open problems. For research project,
identify clearly a problem (e.g., designing/improving an algorithm for
a specific task) and let your _creativity_ guide you while maintaining
reasonable _precision_! You are not requried to completely solve a
problem (big congrats if you do!).

### Specs
*  **Proposal**: 1-2 pages consisting of 1) the topic, background,
   context, motivation; 2) brief summary of the relevant works and
   core papers to be studied; and 3) a goal you intend to achieve and
   a plan.
*  **Mid-term report**: ~5 pages. After more reading and group discussion, your mid-term report should have a polished and expanded version of your proposal. You also need to demonstrate the progress you've made since the proposal.  
*  **Oral presentation**: Each group will have about 20mins to present your project, demonstrating both _breath_ and _depth_: you should aim for a clear introdution of your topic with sufficient background and motivation that would  **interest** the audience; and then you may choose to explain 1-2 techincal ideas in a little detail. Every group member needs to participate, and your group will be graded by other fellow students. You may give your the presentaion on board or with slides.  
*  **Final report**: ~10 pages. This should resemble a real research
   paper: a short abstract; 2) an introduction that motivates the
   topic/problem and gives an overview of the entire paper; 3) details
   including proper preliminary materials (e.g., notations &
   defintions), explaning some main technical results; and finally 4)
   further discussion and open questions.
*  **Report Format**: follow the 2017 [ACM Article Template](https://www.acm.org/publications/proceedings-template){:target="_blank"} "**ACM Small**" format. Here is a sample [TeX]({{base}}/teaching/s17_4510_qc/sample-acmsmall.tex){:target="_blank"} and its [PDF]({{base}}/teaching/s17_4510_qc/sample-acmsmall.pdf){:target="_blank"}. MS Word templates and samples are available on [ACM's website](https://www.acm.org/publications/proceedings-template){:target="_blank"}. 

### Timeline 
*  **Week 1 & 2**: forming groups.  
*  **Week 3 & 4**: meeting and discussing project ideas.
*  **April 27**: proposal due.
*  **May 18**: mid-term report due.
*  **Week 10**: in-class presentations. 
*  **June 15**: final report due. 

------ 

## Suggested Topics 

Also available in ([PDF]({{base}}/teaching/s17_4510_qc/project.pdf){:target="_blank"}). Feel free to pursue a project not on this list. Good venues to look for inspirations: [QIP](https://qipconference.org/), [Qcrypt](http://2016.qcrypt.net/previous-conferences/) and more general TCS conferences (e.g., [STOC](http://acm-stoc.org/), [FOCS](http://ieee-focs.org/), [Crypto](http://www.iacr.org/meetings/crypto/)). 

### Quantum Algorithms   
*  A survey. [[CvD10](https://arxiv.org/abs/0812.0380)] _Quantum
   algorithms for algebraic problems_ by Andrew M. Childs, Wim van
   Dam.
*  **Hidden subgroup probelm and friends** 
   *  **Hidden shift problem** 
   *  Non-abelian and dihedral HSP
   *  Query model efficient solvable 
   *  high dimensional abelian HSP
 
*  **Quantum random walk**. An extension of classical random walk to the
   quantum setting. It has become a framework for quantum algorithm
   design that usually achieves polynomial speedup. 
   *  Survey papers
      *   [[K03](http://arxiv.org/abs/quant-ph/0303081)] _Quantum random
      walks – an introductory overview_ by J. Kempe.
      *  [[A04](http://arxiv.org/abs/quant-ph/0403120)] _Quantum walks and
      their algorithmic applications_ by A. Ambainis.
	  *   [[MNRS06](http://arxiv.org/abs/quant-ph/0608026)] _Search
          via Quantum Walk_ by F. Magniez, A. Nayak, J. Roland, and
          M. Santha.
   *  [[HK16](https://arxiv.org/abs/1612.08958)] _Efficient quantum
      walk on the grid with multiple marked elements_ by Peter Hoyer,
      Mojtaba Komeili.
   *  **Continuous-time** quantum
      walk. [[C08](http://arxiv.org/abs/0806.1972)] _Universal
      computation by quantum walk_ by A. M. Childs.

### Quantum simulation related algorithms

Original motivation of quantum computers. They are already meaningful
and possible on a "small" quantum computer with say 50 clean qubits. 

*  [[HHL09](https://arxiv.org/abs/0811.3171)] _Quantum algorithm for solving linear systems of equations_ by Aram W. Harrow, Avinatan Hassidim, Seth Lloyd. 
*  [[CKS16](http://arxiv.org/abs/1511.02306)] _Quantum linear systems
      algorithm with exponentially improved dependence on precision_
      by Andrew M. Childs, Robin Kothari, and Rolando D. Somma.
*  [[BCK15](http://arxiv.org/abs/1501.01715)] _Hamiltonian simulation
   with nearly optimal dependence on all parameters_ by Dominic W. Berry, Andrew M. Childs, and Robin Kothari.   

### Quantum Information Theory  

*  **Quantum error correcting**. We only scratch the surface of QECC
   in class. **Project idea**: a summary of the genearl error
   correcting theory and the stablizer formalism, and discussing a
   particular code (e.g. surface code).
   *  A survey. [[B15](https://arxiv.org/abs/1302.3428)] _Quantum
      Error Correction for Quantum Memories_ by Barbara M. Terhal.
   *  [[FMMC12](https://arxiv.org/abs/1208.0928)] _Surface codes:
      Towards practical large-scale quantum computation_ by Austin
      G. Fowler, Matteo Mariantoni, John M. Martinis, Andrew
      N. Cleland.

*  **Thoery of quantum fault-tolerant computing**. Fault-tolerance is
   critical for physical implementation of a quantum
   computer. **Project idea**: a gerenal overview and explaining some
   of the key compenents in detail would be suitable for a course
   project. 
   * [[ABO99](http://arxiv.org/abs/quant-ph/9906129)] _Fault-Tolerant
     Quantum Computation with Constant Error Rate_ by D. Aharonov and M. Ben-Or.  
   * [[G13](https://arxiv.org/pdf/1310.2984.pdf)] _Fault-Tolerant Quantum
     Computation with Constant Overhead_ by Daniel Gottesman.

### Quantum Computational Complexity  

### Quantum Query & Communication Complexity 
*  [[MW13](https://arxiv.org/abs/1310.2035)] _A Survey of Quantum Property Testing_ by Ashley Montanaro, Ronald de Wolf.  
*  [[G01](https://arxiv.org/abs/quant-ph/0101005)] _Quantum Communication Complexity (A Survey)_ by Gilles Brassard.
*  Recent developments
   *  [[ABDK16](https://arxiv.org/abs/1511.01937)] _Separations in query complexity using cheat sheets_ by
      Scott Aaronson, Shalev Ben-David, and Robin Kothari. 
   *  [[ABBD+16](http://arxiv.org/abs/1605.01142)] _Separations in communication complexity using
cheat sheets and information complexity_ by Anurag Anshu et al.

* **Query lower bound** 
  *  Polynomial
     method. [[BBCMW98](https://arxiv.org/abs/quant-ph/9802049)]
     _Quantum Lower Bounds by Polynomials_ by R. Beals et al.
  *  Adversarial
     method. [[A00](https://arxiv.org/abs/quant-ph/0002066)] _Quantum
     lower bounds by quantum arguments_ by Andris Ambainis.

### Quantum and Crypto
*  Lattice problems & quantum computing 
*  Quantum homomorphic encryption 
*  Device-independence, randomness amplification
*  Quantum Money

### Other models of quantum computation
*  **Adiabetic quantum computation** [[AvDK+04](https://arxiv.org/abs/quant-ph/0405098)] _Adiabatic Quantum Computation is Equivalent to Standard Quantum Computation_ by D. Aharonov et al. 
*  **Topological quantum computation** [[K97](https://arxiv.org/abs/quant-ph/9707021)] _Fault-tolerant quantum computation by anyons_ by A. Yu. Kitaev. 
*  **Measurement-based** [[RB01](https://journals.aps.org/prl/abstract/10.1103/PhysRevLett.86.5188)] _A One-Way Quantum Computer_ by Robert Raussendorf and Hans J. Briegel. 

### Quantum software and logic

*  [[SHT16](https://arxiv.org/abs/1612.08091)] _ProjectQ: An Open Source Software Framework for Quantum
   Computing_ by Damian S. Steiger, Thomas Häner, Matthias Troyer. More info. on their project [website](https://projectq.ch/){:target="_blank"}.  
*  [[WS14](https://www.microsoft.com/en-us/research/publication/liqui-a-software-design-architecture-and-domain-specific-language-for-quantum-computing/?from=http%3A%2F%2Fresearch.microsoft.com%2Fpubs%2F209634%2F1402.4467.pdf)]
   _LIQUi|>: A Software Design Architecture and Domain-Specific
   Language for Quantum Computing_ by QuArC @ Microsoft
   Research. [Github](https://github.com/StationQ/Liquid).  
*  [[GLRSV13](https://arxiv.org/abs/1304.3390)] _Quipper: A Scalable
   Quantum Programming Language_ by A. S. Green et al. [Project website](http://www.mathstat.dal.ca/~selinger/quipper/).
*  [[PRZ17](https://www.cis.upenn.edu/~rrand/qwire.pdf)] _QWIRE: A
Core Language for Quantum Circuits_ by Jennifer Paykin Robert Rand
Steve Zdancewic.
*  [[YYW17](https://ix.cs.uoregon.edu/~xiaodiwu/papers/popl17.pdf)]
   _Invariants of Quantum Programs: Characterisations and Generation_
   by M. Ying, S. Ying and X. Wu.
