---
layout: course
courseid: s18 410/510
desc: Project
permalink: /teaching/s18_4510_qc/project/
title: (Spring 2018) CS 410/510 - Intro to Quantum Computing
subtitle: Course Project
modified: 2018-04-01
---

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
   paper: 1) a short abstract; 2) an introduction that motivates the
   topic/problem and gives an overview of the entire report; 3) details
   including proper preliminary materials (e.g., notations &
   defintions), explaning some main technical results; and finally 4)
   further discussion and open questions. 
*  **Report format**: you are **required** to typeset all your reports in **LaTeX**. BibTeX is recommaned to manage bibliograpy. The [resource page]({{base}}/teaching/s18_4510_qc/resource/) has links to materials to pick up LaTeX. You should use single-column, single-space (between lines) format on letter-size papers. Here is a barebone [[TeX]({{base}}/teaching/s17_4510_qc/sample-quantum.tex){:target="_blank"} [PDF]({{base}}/teaching/s17_4510_qc/sample-quantum.pdf){:target="_blank"}] template. You may also follow a suitable [ACM Article Template](https://www.acm.org/publications/proceedings-template){:target="_blank"} (e.g., _ACM Small_ format). Many LaTeX templates are availabe there. There are online TeX editors available if you don't want to install a local engine, e.g., [Overleaf](https://www.overleaf.com/){:target="_blank"}. 

### Timeline (Tentative)
*  **Week 1 & 2**: forming groups.
*  **Week 3 & 4**: meeting and discussing project ideas.
*  **April 27**: proposal due.
*  **May 14**: mid-term report due. 
*  **Week 10**: in-class presentations. 
*  **June 14**: final report due. 

------ 

## Suggested Topics 

<!--Also available in ([PDF]({{base}}/teaching/s18_4510_qc/project.pdf){:target="_blank"}). --> Feel free to pursue a project not on this list. I'm happy to meet with your group and discuss about your ideas. 

A few venues to look for inspirations: 

*  [QIP](https://qipconference.org/)
*  [Qcrypt](http://2016.qcrypt.net/previous-conferences/) 
*  General TCS conferences (e.g., [STOC](http://acm-stoc.org/), [FOCS](http://ieee-focs.org/), [SODA](), [Crypto](http://www.iacr.org/meetings/crypto/)). 

### Quantum algorithms for algebraic problems

Shor's quantum factorization problems is a notable example of solving algebraic problems faster, sometimes with exponential speedup, on a quantum computer than best known classical algorithms. 

*  **General survey** [[CvD10](https://arxiv.org/abs/0812.0380)]
   _Quantum algorithms for algebraic problems_ by Andrew M. Childs,
   Wim van Dam.
* [[W01](http://arxiv.org/abs/quant-ph/0011023)]
_Quantum algorithms for solvable groups_ by J. Watrous. 
*  **(Generalized) hidden shift problem**
    * [[vDHI02](http://arxiv.org/abs/quant-ph/0211140)] _Quantum
     Algorithms for some Hidden Shift Problems_ by W. van Dam,
     S. Hallgren, and L. Ip. A. Childs and W. van Dam, “Quantum
     algorithm for a generalized hidden shift problem”.
    * [[CvD05](http://arxiv.org/abs/quant-ph/0507190)] _Quantum
      algorithm for a generalized hidden shift problem_ by A. Childs
      and W. van Dam.
*  **Non-abelian** hidden subgroup problem 
    * [[EK04](http://arxiv.org/abs/quant-ph/0401083)] _The quantum
      query complexity of the hidden subgroup problem is polynomial_
      by M. Ettinger, P. Høyer, E. Knill.
    * [[K03](http://arxiv.org/abs/quant-ph/0302112)] _A
     subexponential-time quantum algorithm for the dihedral hidden
     subgroup problem_ by G. Kuperberg.

### Quantum random walk 

An extension of classical random walk to the quantum setting. It has become a framework for quantum algorithm design that usually achieves polynomial speedup. Grover's quantum search algorithm can be viewed as a special case of quantum random walk. 

*  Survey papers
    *  [[K03](http://arxiv.org/abs/quant-ph/0303081)] _Quantum random walks – an introductory overview_ by J. Kempe.
    *  [[A04](http://arxiv.org/abs/quant-ph/0403120)] _Quantum walks and their algorithmic applications_ by A. Ambainis.
*  **Amplitute amplification**: simple generalization of Grover's search algorithm.
    *  [[BHMT02](https://arxiv.org/abs/quant-ph/0005055)] _Quantum Amplitude Amplification and Estimation_ by Gilles Brassard, Peter Hoyer, Michele Mosca, Alain Tapp. 
	*  **Oblivious** amplitute amplification. [BCC+14] _Exponential improvement in precision for simulating sparse Hamiltonians_ by D. W. Berry, A. M. Childs, R. Cleve, R. Kothari, R. D. Somma. 
*   [[MNRS06](http://arxiv.org/abs/quant-ph/0608026)] _Search
          via Quantum Walk_ by F. Magniez, A. Nayak, J. Roland, and
          M. Santha.
*  [[HK16](https://arxiv.org/abs/1612.08958)] _Efficient quantum
      walk on the grid with multiple marked elements_ by Peter Hoyer,
      Mojtaba Komeili.
*  **Continuous-time** quantum walk. [[C08](http://arxiv.org/abs/0806.1972)] _Universal computation by quantum walk_ by A. M. Childs.

### Quantum simulation related algorithms

Original motivation of quantum computers proposed by
R. Feynman. Closely related to quantum algorithms for linear
systems. They might already be meaningful on near-term quantum
processors (~100 noisy qubits). Machine learning is a potential
application.

*  [[HHL09](https://arxiv.org/abs/0811.3171)] _Quantum algorithm for solving linear systems of equations_ by Aram W. Harrow, Avinatan Hassidim, Seth Lloyd. 
*  [[CKS16](http://arxiv.org/abs/1511.02306)] _Quantum linear systems
      algorithm with exponentially improved dependence on precision_
      by Andrew M. Childs, Robin Kothari, and Rolando D. Somma.
*  [[BCK15](http://arxiv.org/abs/1501.01715)] _Hamiltonian simulation
   with nearly optimal dependence on all parameters_ by Dominic
   W. Berry, Andrew M. Childs, and Robin Kothari.
*  Application in quantum **machine learning**. ML, of course... but be critical about what you see.
    * A survey. [[AW17](https://arxiv.org/abs/1701.06806)] _A Survey of Quantum
     Learning Theory_ by S. Arunachalam, R. de Wolf.
    * [[LMR14](https://arxiv.org/abs/1307.0401)] _Quantum principal component analysis_ by Seth Lloyd, Masoud Mohseni, Patrick Rebentrost.

### Quantum Information Theory

*  **Quantum error correcting** and **fault-tolerence**. We only scratch the surface of this topic in class. Quantum information is prone to noise, and to transmit quantum information reliably and build a robust quantum computer, we need to correct errors and further make all computation fault-tolerant. These techniques have also found critical in quantum cryptography.
    *  [[FMMC12](https://arxiv.org/abs/1208.0928)] _Surface codes:
      Towards practical large-scale quantum computation_ by Austin
      G. Fowler, Matteo Mariantoni, John M. Martinis, Andrew
      N. Cleland.
    * [[ABO99](http://arxiv.org/abs/quant-ph/9906129)] _Fault-Tolerant
     Quantum Computation with Constant Error Rate_ by D. Aharonov and
     M. Ben-Or.
    *  [Reichart] ?
*  **Quantum Shannon Theory** Quantum information shows distinct features than what Shannon's theory about classical information describes.  
    * [[HOW05](http://arxiv.org/abs/quant-ph/0505062)] _Quantum
     information can be negative_ by M. Horodecki, J. Oppenheim,
     A. Winter.
    * [[SY08](http://arxiv.org/abs/0807.4935)] _Quantum Communication
     With Zero-Capacity Channels_ by G. Smith, J. Yard.
*  Quantum information and **black holes**. There is some fancinating connection to the theory of black holes. 
    *  [[A16 Chapter 6](http://www.scottaaronson.com/barbados-2016.pdf)]
      _From quantum money to balck holes_ by S. Aaronson.

### Quantum Computational Complexity

There is a large body of research that explores abstractly the strengths and the limits of quantum computing.

*  **General survey** [[W09](http://arxiv.org/abs/0804.3401)] _Quantum Computational Complexity_ by J. Watrous.
*  Quantum **interactive proofs** What problems can you compute by interacting with a ``powerful'' guru? 
    * A comprehensive survey. [[VW16](https://arxiv.org/abs/1610.01664)] _Quantum
     Proofs_ by Thomas Vidick, John Watrous.
    * [[JJUW09](https://arxiv.org/abs/0907.4737)] _QIP = PSPACE_ by
      Rahul Jain, Zhengfeng Ji, Sarvagya Upadhyay, John Watrous
* Can you verify a quantum computer by a classical computer? Someone claims a quantum computer at hand, can you trust him/her? 
    *  [[M18](https://arxiv.org/abs/1804.01082)] _Classical Verification of Quantum Computations_
by Urmila Mahadev. 
*  **Hamiltonian Complexity** How difficult is it to determin the ground energy of a physical system?
    * [[AN02](https://arxiv.org/abs/quant-ph/0210077)] _Quantum NP - A
     Survey_ by Dorit Aharonov, Tomer Naveh.

### Quantum Query & Communication Complexity 

*  [[MW13](https://arxiv.org/abs/1310.2035)] _A Survey of Quantum Property Testing_ by Ashley Montanaro, Ronald de Wolf.
*  [[G01](https://arxiv.org/abs/quant-ph/0101005)] _Quantum
   Communication Complexity (A Survey)_ by Gilles Brassard.
*  Separations of classical/quantum complexity 
    *  [[ABDK16](https://arxiv.org/abs/1511.01937)] _Separations in
      query complexity using cheat sheets_ by Scott Aaronson, Shalev
      Ben-David, and Robin Kothari.
    *  [[ABBD+16](http://arxiv.org/abs/1605.01142)] _Separations in
      communication complexity using cheat sheets and information
      complexity_ by Anurag Anshu et al.
*  [[ATYY16](https://arxiv.org/abs/1611.08946)] _Exponential
      Separation of Quantum Communication and Classical Information_
      by Anurag Anshu, Dave Touchette, Penghui Yao, Nengkun Yu.

### Quantum and crypto
*  **Post-quantum crypto** cope with quantum _codebreakers_
    *  [[Z12](http://eprint.iacr.org/2012/182)] _How to Construct
      Quantum Random Functions_ by Mark Zhandry.
    *  [[Z13](http://eprint.iacr.org/2012/606)] _Quantum-Secure Message
      Authentication Codes_ by Dan Boneh and Mark Zhandry.
    * [[S14](https://arxiv.org/abs/1409.2187)] _A Note on Quantum
     Security for Post-Quantum Cryptography_ by F. Song.
    * [[BDF+11](https://arxiv.org/abs/1008.0931)] _Random Oracles in a
     Quantum World_, by Dan Boneh et al.
    *  [[KLLNP16](https://arxiv.org/abs/1602.05973)] _Breaking
      Symmetric Cryptosystems using Quantum Period Finding_ by Marc
      Kaplan, Gaëtan Leurent, Anthony Leverrier, María Naya-Plasencia.
	*  [[SY17]()] NMAC  . A positive message, proving several security constructions, in regard to the above attack. 
*  **Quantum cryptograpy** equip _codemakers_ with quantum information
   processing
    * **Survey**. [[BS15](https://arxiv.org/abs/1510.06120)] _Quantum
     Cryptography Beyond Quantum Key Distribution_ by Anne Broadbent,
     Christian Schaffner.
    * Quantum key exchange a la
     **Merkle** [[BHK+11](http://arxiv.org/abs/1108.2316)] _Merkle
     Puzzles in a Quantum World_ by G. Brassard, P. Hoyer, K. Kalach,
     M. Kaplan, S. Laplante, L. Salvail.
    * **Quantum Money** [[AC12](https://arxiv.org/abs/1203.4740)]
     _Quantum Money from Hidden Subspaces_ by Scott Aaronson, Paul
     Christiano. [[A16 Chapter 8,9](http://www.scottaaronson.com/barbados-2016.pdf)]
      _From quantum money to balck holes_ by S. Aaronson.
    * **Quantum homomorphic encryption** [[DSS16](https://arxiv.org/abs/1603.09717)] _Quantum
     homomorphic encryption for polynomial-sized circuits_ by Yfke
     Dulek, Christian Schaffner, Florian Speelman.
*  **Device-independence, randomness amplification** What if your
   devices for cryptography cannot be trusted (recall
   what [NSA](https://en.wikipedia.org/wiki/Dual_EC_DRBG) did)?
   Quantum non-locality enables certified security.
    * [[BCMVV18](https://arxiv.org/abs/1804.00640)] _Certifiable Randomness from a Single Quantum Device_ by Z. Brakerski, P. Christiano, U. Mahadev, U. Vazirani, T. Vidick. 

### Other models of quantum computation

*  **Adiabetic quantum computation** [[AvDK+04](https://arxiv.org/abs/quant-ph/0405098)] _Adiabatic Quantum Computation is Equivalent to Standard Quantum Computation_ by D. Aharonov et al. 
*  **Measurement-based** [[Jozsa05](http://arxiv.org/abs/quant-ph/0508124)] _An introduction to measurement based quantum computation_ by R. Jozsa.
*  **Topological quantum computation**: Microsoft is pursing this direction. A beautiful idea that would make noises much easier to deal with. [[K97](https://arxiv.org/abs/quant-ph/9707021)] _Fault-tolerant quantum computation by anyons_ by A. Yu. Kitaev. 
*  A **non-univeral** model concerning **bonson
   sampling**, which is also a promising approach to demonstrate **quantum supremacy**.
    *  [[AA11](https://arxiv.org/abs/1011.3245)] _The
   Computational Complexity of Linear Optics_ by S. Aaronson and
   A. Arkhipov.
    *  quantum supremacy [V18]
*  Qubit is precious, be
   conservative. [[KL98](https://arxiv.org/abs/quant-ph/9802037)] _On
   the Power of One Bit of Quantum Information_ by E. Knill,
   R. Laflamme.

### Quantum software and logic

*  **Universal quantum gates**. Quantum computer is digital! How come one can implement a continuous space of unitary operations by a constant-size gate set?
    * Survey. [[DN05](https://arxiv.org/abs/quant-ph/0505030)]_The
   Solovay-Kitaev algorithm_ by Christopher M. Dawson, Michael
   A. Nielsen.
    * [[S03](https://arxiv.org/abs/quant-ph/0205115)] _Both Toffoli
     and Controlled-NOT need little help to do universal quantum
     computation_ by Y. Shi.
*  **Quantum software (and hardware) platforms**. Project idea: survey some popular platforms, and write quantum programs to simulate selected quantum algorithms on some backends (classical simulator or actual quantum processor). 
    *  [[IBM18](https://www.research.ibm.com/ibm-q/)] IBM Q Experience and Quantum information software Kit [QISKit(https://nbviewer.jupyter.org/github/QISKit/qiskit-tutorial/blob/stable/index.ipynb)]. 
    *  [[SHT16](https://arxiv.org/abs/1612.08091)] _ProjectQ: An Open
   Source Software Framework for Quantum Computing_ by Damian
   S. Steiger, Thomas Häner, Matthias Troyer. More info. on their
   project [website](https://projectq.ch/){:target="_blank"}.
    *  [[WS14](https://www.microsoft.com/en-us/research/publication/liqui-a-software-design-architecture-and-domain-specific-language-for-quantum-computing/?from=http%3A%2F%2Fresearch.microsoft.com%2Fpubs%2F209634%2F1402.4467.pdf)]
   _LIQUi|>: A Software Design Architecture and Domain-Specific
   Language for Quantum Computing_ by QuArC @ Microsoft
   Research. [Github](https://github.com/StationQ/Liquid).
    *  [[GLRSV13](https://arxiv.org/abs/1304.3390)] _Quipper: A Scalable
   Quantum Programming Language_ by A. S. Green et al. [Project website](http://www.mathstat.dal.ca/~selinger/quipper/).
*  Thoery of quantum programing. [[LY18](https://popl18.sigplan.org/event/popl-2018-papers-algorithmic-analysis-of-termination-problems-for-quantum-programs)] by Y. Li, M. Ying.

