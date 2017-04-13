---
layout: course
courseid: s17 410/510
desc: Project
permalink: /teaching/s17_4510_qc/project/
title: (Spring 2017) CS 410/510 - Intro to Quantum Computing
subtitle: Course Project
modified: 2017-04-11
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
*  **General survey** [[CvD10](https://arxiv.org/abs/0812.0380)]
   _Quantum algorithms for algebraic problems_ by Andrew M. Childs,
   Wim van Dam.
*  **Non-abelian Hidden subgroup probelm** A tough case for HSP, but
   connected with many interesting problems, e.g., graph isomorphism,
   and (unique) shortest vector problem critical in lattice-based
   crypto.
   * [[EK04](http://arxiv.org/abs/quant-ph/0401083)] _The quantum
      query complexity of the hidden subgroup problem is polynomial_
      by M. Ettinger, P. Høyer, E. Knill.
   * [[K03](http://arxiv.org/abs/quant-ph/0302112)] _A
     subexponential-time quantum algorithm for the dihedral hidden
     subgroup problem_ by G. Kuperberg.
*  **(Generalized) hidden shift problem**
   * [[vDHI02](http://arxiv.org/abs/quant-ph/0211140)] _Quantum
     Algorithms for some Hidden Shift Problems_ by W. van Dam,
     S. Hallgren, and L. Ip.  A. Childs and W. van Dam, “Quantum
     algorithm for a generalized hidden shift problem”.
   *  [[CvD05](http://arxiv.org/abs/quant-ph/0507190)] _Quantum
      algorithm for a generalized hidden shift problem_ by A. Childs
      and W. van Dam.
*  **High dimensional continuous abelian HSP**. nice generalization and
   new formalization of HSP on continuous groups with applications in
   sovling basic number theoretic problems and breaking some lattice crypto. 
   *  [[EHKS14](http://fangsong.info/files/pubs/EHKS_STOC14.pdf)] _A
      Quantum Algorithm for Computing the Unit Group of an Arbitrary
      Degree Number Field_ by Kirsten Eisenträger, Sean Hallgren,
      Alexei Kitaev and Fang Song.
   *  [[BS16](http://fangsong.info/files/pubs/BS_SODA16.pdf)]
      _Efficient quantum algorithms for computing class groups and
      solving the principal ideal problem in arbitrary degree number
      fields_ by J. Biasse and F. Song.
*  **Quantum random walk**. An extension of classical random walk to
   the quantum setting. It has become a framework for quantum
   algorithm design that usually achieves polynomial speedup.
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
and possible on a "small" quantum computer with say 50 clean
qubits. Thesre algorithms have wide applications such as machine
learning.
   
*  [[HHL09](https://arxiv.org/abs/0811.3171)] _Quantum algorithm for solving linear systems of equations_ by Aram W. Harrow, Avinatan Hassidim, Seth Lloyd. 
*  [[CKS16](http://arxiv.org/abs/1511.02306)] _Quantum linear systems
      algorithm with exponentially improved dependence on precision_
      by Andrew M. Childs, Robin Kothari, and Rolando D. Somma.
*  [[BCK15](http://arxiv.org/abs/1501.01715)] _Hamiltonian simulation
   with nearly optimal dependence on all parameters_ by Dominic W. Berry, Andrew M. Childs, and Robin Kothari.   
*  Application in quantum machine learning. ML, of course... but be
   critical 
   * A survey. [[AW17](https://arxiv.org/abs/1701.06806)] _A Survey of Quantum
     Learning Theory_ by S. Arunachalam, R. de Wolf.
   * [[KP16](https://arxiv.org/abs/1603.08675)] _Quantum Recommendation Systems_ by I. Kerenidis, A. Prakash.  
*  **Quantum supremacy**. Recent advances in physical implementation
has brought up the hot topic on demonstrating: on a _small_
(special-purpose) quantum device, is there a clear quantum speedup for
some task, motivated by the goal of overturning the Extended
Church-Turing Thesis as confidently as possible.
   * [[AC16](https://arxiv.org/abs/1612.05903)] _Complexity-Theoretic
     Foundations of Quantum Supremacy Experiments_ by S. Aaronson and
     L. Chen.
	 
### Quantum Information Theory  

*  Broad survey on **Quantum
   entanglement** [[HHHH08](https://arxiv.org/abs/quant-ph/0702225)]
   _Quantum entanglement_ by R. Horodecki, P. Horodecki, M. Horodecki,
   K. Horodecki.
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
*  **Quantum Shannon theory**. It deals with communicating information
    via noisy channel. Many surprsing and distinct features in the
    quantum generaliztion.
   * [[BDH+09](https://arxiv.org/abs/0912.5537)] _Quantum Reverse
     Shannon Theorem_ by C.H. Bennett et al.
   * [[HOW05](http://arxiv.org/abs/quant-ph/0505062)] _Quantum
     information can be negative_ by M. Horodecki, J. Oppenheim,
     A. Winter.
   * [[SY08](http://arxiv.org/abs/0807.4935)] _Quantum Communication
     With Zero-Capacity Channels_ by G. Smith, J. Yard.
*  Quantum information and **black holes**. 
   *  Lecture
      notes. [[A16](http://www.scottaaronson.com/barbados-2016.pdf)]
      _From quantum money to balck holes_ by S. Aaronson.
   *  [[HP07](https://arxiv.org/abs/0708.4025)] _Black holes as
      mirrors: quantum information in random subsystems_ by Patrick
      Hayden, John Preskill.
   *  [[HP13](https://arxiv.org/abs/1301.4504)] _Quantum computation vs. firewalls_ by D. Harlow and P. Hayden.  

### Quantum Computational Complexity  
There is a large body of research that explores abstractly the power and the limits of quantum computing.  

*  **General survey** [[W09](http://arxiv.org/abs/0804.3401)] _Quantum
   Computational Complexity_ by J. Watrous.
*  Quantum **interactive proofs** 
   * Survey. [[VW16](https://arxiv.org/abs/1610.01664)] _Quantum
     Proofs_ by Thomas Vidick, John Watrous.
   * [[JJUW09](https://arxiv.org/abs/0907.4737)] _QIP = PSPACE_ by Rahul Jain, Zhengfeng Ji, Sarvagya Upadhyay, John Watrous   
   * Verifying a quantum computer
     classically? [[ABOE08](https://arxiv.org/abs/0810.5375)]
     _Interactive Proofs For Quantum Computations_ by Dorit Aharonov,
     Michael Ben-Or, Elad Eban.
*  **Non-local** games. Introduced for the purpose of testing quantum
   theory, it turns out to be far more influential and connets to many
   areas such as interactive proofs, operator theory, cryptography,
   etc.
   *  [[V13](https://arxiv.org/abs/1302.1242)] _Three-player entangled
      XOR games are NP-hard to approximate_ by Thomas Vidick.
   *  Recent
      **breakthrough** [[S16](https://arxiv.org/abs/1606.03140)]
      _Tsirelson's problem and an embedding theorem for groups arising
      from non-local games_ by William Slofstra.	  
*  **Hamiltonian Complexity** How difficult is it to determin the
   ground energy of a physical system?
   * [[AN02](https://arxiv.org/abs/quant-ph/0210077)] _Quantum NP - A
     Survey_ by Dorit Aharonov, Tomer Naveh. 
   * [[GN13](https://arxiv.org/abs/1302.0290)] _Quantum 3-SAT is
     QMA1-complete_ by David Gosset, Daniel Nagaj.
   * [[LVV13](https://arxiv.org/abs/1307.5143)] _A polynomial-time
      algorithm for the ground state of 1D gapped local Hamiltonians_
      by Zeph Landau, Umesh Vazirani, Thomas Vidick.

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

* **Query lower bound** 
  *  Polynomial
     method. [[BBCMW98](https://arxiv.org/abs/quant-ph/9802049)]
     _Quantum Lower Bounds by Polynomials_ by R. Beals et al.
  *  Adversarial
     method. [[A00](https://arxiv.org/abs/quant-ph/0002066)] _Quantum
     lower bounds by quantum arguments_ by Andris Ambainis.
  *  [[HLS07](https://arxiv.org/abs/quant-ph/0611054)] _Negative
     weights make adversaries stronger_ P. Hoyer T. Lee, R. Spalek.
  *  [[R09](https://arxiv.org/abs/0904.2759)] _Span programs and
     quantum query complexity: The general adversary bound is nearly
     tight for every boolean function_ by Ben W. Reichardt.

### Quantum and crypto
*  **Post-quantum crypto** cope with quantum _codebreakers_
   *  [[R04](https://arxiv.org/abs/cs/0304005)] _Quantum Computation
      and Lattice Problems_ by Oded Regev.
   *  [[Z12](http://eprint.iacr.org/2012/182)] _How to Construct
      Quantum Random Functions_ by Mark Zhandry.  
   *  [[Z13](http://eprint.iacr.org/2012/606)] _Quantum-Secure Message
      Authentication Codes_ by Dan Boneh and Mark Zhandry.
   * [[S14](https://arxiv.org/abs/1409.2187)] _A Note on Quantum
     Security for Post-Quantum Cryptography_ by F. Song.
   * [[HHS11](https://arxiv.org/abs/1507.01625)] _Classical
     Cryptographic Protocols in a Quantum World_ by Sean Hallgren,
     Adam Smith, Fang Song.
   * [[BDF+11](https://arxiv.org/abs/1008.0931)] _Random Oracles in a
     Quantum World_, by Dan Boneh et al.
   *  [[KLLNP16](https://arxiv.org/abs/1602.05973)] _Breaking
      Symmetric Cryptosystems using Quantum Period Finding_ by Marc
      Kaplan, Gaëtan Leurent, Anthony Leverrier, María Naya-Plasencia.
*  **Quantum cryptograpy** equip _codemakers_ with quantum information
   processing
   * **Survey**. [[BS15](https://arxiv.org/abs/1510.06120)] _Quantum
     Cryptography Beyond Quantum Key Distribution_ Anne Broadbent,
     Christian Schaffner.
   * **QKD** [[R05](https://arxiv.org/abs/quant-ph/0512258)] _Security
     of Quantum Key Distribution_ by Renato Renner.
   * Quantum key exchange a la
     **Merkle** [[BHK+11](http://arxiv.org/abs/1108.2316)] _Merkle
     Puzzles in a Quantum World_ by G. Brassard, P. Hoyer, K. Kalach,
     M. Kaplan, S. Laplante, L. Salvail.
   * [[BCG+02](https://arxiv.org/abs/quant-ph/0205128)]
     _Authentication of Quantum Messages_ by Howard Barnum et al.
   * **Quantum Money** [[AC12](https://arxiv.org/abs/1203.4740)]
     _Quantum Money from Hidden Subspaces_ by Scott Aaronson, Paul
     Christiano.
   * **Quantum homomorphic
     encryption** [[DSS16](https://arxiv.org/abs/1603.09717)] _Quantum
     homomorphic encryption for polynomial-sized circuits_ by Yfke
     Dulek, Christian Schaffner, Florian Speelman.
   * [[U13](http://eprint.iacr.org/2013/606)] _Revocable quantum
     timed-release encryption_ by Dominique Unruh.
*  **Device-independence, randomness amplification** What if your devices for cryptography cannot be trusted (recall what [NSA](https://en.wikipedia.org/wiki/Dual_EC_DRBG) did)? Quantum non-locality enables certified security and a lot many fanscinating tasks.  
   *  [[MS14](https://arxiv.org/abs/1402.0489)] _Robust protocols for
      securely expanding randomness and distributing keys using
      untrusted quantum devices_ by Carl A. Miller, Yaoyun Shi.
   *  [[CSW14](https://arxiv.org/abs/1402.4797v3)] _Physical
      Randomness Extractors: Generating Random Numbers with Minimal
      Assumptions_ by Kai-Min Chung, Yaoyun Shi, Xiaodi Wu.

### Other models of quantum computation
*  **Adiabetic quantum computation** [[AvDK+04](https://arxiv.org/abs/quant-ph/0405098)] _Adiabatic Quantum Computation is Equivalent to Standard Quantum Computation_ by D. Aharonov et al. 
*  **Topological quantum computation** [[K97](https://arxiv.org/abs/quant-ph/9707021)] _Fault-tolerant quantum computation by anyons_ by A. Yu. Kitaev. 
*  **Measurement-based** [[RB01](https://journals.aps.org/prl/abstract/10.1103/PhysRevLett.86.5188)] _A One-Way Quantum Computer_ by Robert Raussendorf and Hans J. Briegel. 
*  A non-univeral model concerning **bonson
   sampling**. [[AA11](https://arxiv.org/abs/1011.3245)] _The
   Computational Complexity of Linear Optics_ by S. Aaronson and
   A. Arkhipov.

### Quantum software and logic

*  Universal quantum gates. Quantum computer is digital!
   * Survey. [[DN05](https://arxiv.org/abs/quant-ph/0505030)]_The
   Solovay-Kitaev algorithm_ by Christopher M. Dawson, Michael
   A. Nielsen.
   * [[S03](https://arxiv.org/abs/quant-ph/0205115)] _Both Toffoli and
     Controlled-NOT need little help to do universal quantum
     computation_ by Y. Shi.
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

### Quantum-inspired proofs for classical theorems

The techniques and formalism in quantum information processing have
inspired proofs for mathematical theorems that seem to have nothing to
do with Quantum.

*  [[DW11](https://arxiv.org/abs/0910.3376)] _Quantum Proofs for
   Classical Theorems_ by Andrew Drucker, Ronald de Wolf.
* [[FMP+11](http://arxiv.org/abs/1111.0837)] _Linear vs. “Semidefinite
Extended Formulations: Exponential Separation and Strong Lower Bounds_
by S. Fiorini, S. Massar, S. Pokutta, H. R. Tiwary, R. de Wolf.
* [[A11](https://arxiv.org/abs/1109.1674)] _A Linear-Optical Proof
   that the Permanent is #P-Hard_ by Scott Aaronson.
