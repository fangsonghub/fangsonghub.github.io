---
layout: course
courseid: s19 440/640
desc: Project
permalink: /teaching/s19_4640_qc/project/
title: (Spring 2019) CS 440/640 Quantum Algorithms
subtitle: Project
modified: <2019-02-12 Tue>
---
* Table of Contents
{:toc}

## Instructions

2-3 people group projects. You may go with one (or superposition) of
the following options
*  _literature review_. Pick a topic of interest, and summarize the
state of art of it. The final outcome would be a _survey_ paper
including open problems.
*  _completing "folklore"_. There are ``folklore'' results in the
   filed or missing details in class that are worth spelling out more
   carefully. You will conduct a careful study a dedicated problem and
   give a thorough exposition on it.
*  _original research_. Challenge yourself with some open question in
   the field. You are encouraged to explore the potential of quantum
   computing in your own research area. Be _creative_ and keep a
   _critical_ mind. 
*  _quantum programming_. Implement some quantum algorithms and
   protocols in quantum programming platforms (e.g.,
   [Q#](https://www.microsoft.com/en-us/quantum/development-kit),[Quirky](https://www.quantum-quest.nl/quirky/),[IBM
   QISKIT](https://qiskit.org/),[RigettiForest](https://www.rigetti.com/forest)), and go beyond by optimizing the
   circuit, estimating the cost, and testing variations (e.g.,
   robustness against noise).

### Specs
*  **Proposal**: 1-2 pages consisting of 1) the topic, background,
   context, and motivation; 2) identify a few core papers to be
   studied; and 3) a goal you intend to achieve and a plan.
*  **Oral presentation**: Each group will have about 30mins to present
   your project including Q&A. Your need to demonstrate both _breath_
   and _depth_. Aim for a clear introduction that would **interest**
   the audience, and then explain 1-2 technical ideas in some
   detail. Every group member needs to participate, and your group
   will be graded by other fellow students. You may use slides or
   whiteboard.
*  **Final report**: ~10 pages. This should resemble a research paper:
   1) a short abstract; 2) an introduction that motivates the
   topic/problem and gives an overview of the entire report; 3)
   details including proper preliminary materials (e.g., notations &
   definitions), explaining some main technical results; and finally 4)
   further discussion and open questions.
*  **Report format**: I recommend you to typeset your reports in
   **LaTeX**, and manage your bibliography using BibTeX. The [resource
   page]({{base}}/teaching/s19_4640_qc/resource/) has links to
   materials to pick up LaTeX. You should use single-column,
   single-space (between lines) format on letter-size papers.

### Timeline (Tentative)
*  **Week 1 & 3**: forming groups.
*  **Week 4 & 5**: discussing project ideas.
*  **February 18**: proposal due, 11:59pm anytime on Earth. 
*  **Week 14-15**: in-class presentations. 
*  **May 03**: final report due, 11:59pm anytime on Earth. 

------ 

## Suggested Topics 

The list below is necessarily incomplete, and you are welcome to
choose a topic not on the list. A few venues to look for inspirations:
[QIP](https://qipconference.org/),
[Qcrypt](http://2018.qcrypt.net/previous-next-conferences/), and
general TCS conferences (e.g., [STOC](http://acm-stoc.org/),
[FOCS](http://ieee-focs.org/),
[SODA](http://www.siam.org/meetings/archives.php#SODA),
[Crypto](http://www.iacr.org/meetings/crypto/)).

### More quantum algorithms

* [[CvD07](https://arxiv.org/abs/quant-ph/0507190),[IPS18](https://arxiv.org/abs/1806.09660)]
  Generalized hidden-shift problem via various techniques (e.g.,
  _pretty-good-measurement_).
* [[BKL+18](https://arxiv.org/abs/1710.02581),[AG18](https://arxiv.org/abs/1804.05058)]
  Quantum algorithms for solving semi-definite programs, a central
  problem in convex optimization.
* [[GSLW18](https://arxiv.org/abs/1806.01838)] Introduces _singular
  value transformation_, a nice framework unifying several quantum
  algorithmic techniques.
* [[CKS15](https://arxiv.org/abs/1511.02306)] Improves HHL's quantum
  algorithms for solving linear systems.
* [[FG14](https://arxiv.org/abs/1411.4028)] _Quantum Approximate Optimization Algorithm_ (QAOA).
* [[AW17](https://arxiv.org/abs/1701.06806),[LMR14](https://arxiv.org/abs/1307.0401)]
  Quantum algorithms for machine learning, e.g., _principal component
  analysis_.
* [[Tang18](https://arxiv.org/abs/1807.04271),[CLLW19](https://arxiv.org/abs/1901.03254)]
  Tang's novel idea enables efficient classical algorithms (in a
  non-standard model) for recommendation systems and other problems,
  inspired by quantum algorithms.
* [[LGNR18](https://arxiv.org/abs/1810.10838)] Quantum advantage in distributed computing. 

### Quantum complexity

* [[KSdW05](https://epubs.siam.org/doi/10.1137/05063235X)] Time‐Space
Tradeoffs for quantum query complexity. Any implication in
Proof-of-work or Proof-of-Space in blockchain designs in the presence
of quantum attacks?
* [[BBCMW01](https://dl.acm.org/citation.cfm?doid=502090.502097),[ABP17](https://arxiv.org/abs/1711.07285)]
  One central quantum lower-bound technique: _polynomial method_.
* [[HLS07](https://arxiv.org/abs/quant-ph/0611054),[Reichardt11](https://arxiv.org/abs/1005.1601)]
  Another central quantum lower-bound technique: _adversary method_. 
* [[JJUW09](https://arxiv.org/abs/0907.4737)] QIP = PSPACE
  (=IP). Quantum interactive proof systems turn out to assume the same
  power of classical IP, but still with unique properties.
  
### Quantum information theory

* [[CBTW15](https://arxiv.org/abs/1511.04857)] Uncertainty relation, a
unique feature in quantum theory, in the language of entropy.
* [[FMMC12](https://arxiv.org/abs/1208.0928),[CR17a](https://arxiv.org/abs/1705.02329),[CR17b](https://arxiv.org/abs/1705.05365),[FGL18](https://arxiv.org/abs/1808.03821)]
      Recent advances on quantum error-correction and fault-tolerance,
      e.g. _Surface codes_ and FT with _constant_ overhead.
* [[HOW05](http://arxiv.org/abs/quant-ph/0505062),[SY08](http://arxiv.org/abs/0807.4935)] Some weirdness about quantum information, such as _negative_ information and communicating with _zero-capacity_ channels.
*  [[HH13](https://arxiv.org/abs/1301.4504),[A16 Chapter 6](http://www.scottaaronson.com/barbados-2016.pdf)]
   Some fascinating connection of quantum information to the theory of
   **black holes**.

### Quantum-safe cryptography 
*  [[PQC](https://pqcrypto.org/),[ToB18](https://blog.trailofbits.com/2018/10/22/a-guide-to-post-quantum-cryptography/)]
   Securing classical cryptography against quantum attacks, known as
   _post-quantum cryptography_.
*  [[Urmila18](https://arxiv.org/abs/1708.02130)] Homomorphic
   encryption that admit evaluation of quantum circuits. A novel idea
   that also lead to breakthrough results by the same author. 
*  [[Zhandry18](https://eprint.iacr.org/2017/1080)] A unique quantum
   primitive, quantum lightening, with applications in quantum
   money. Can you construct it from other problems?
*  [[DPVR12](https://epubs.siam.org/doi/10.1137/100813683)] Making
   randomness extractors secure against _quantum side information_.

### Programming and simulating quantum computers
*  [[Urmila18](https://arxiv.org/abs/1804.01082)] Implement a protocol
   for verifying a server's _quantumness_. Optimize the quantum
   circuit by some tool for circuit synthesis
   (Cf. [MM16](https://iopscience.iop.org/article/10.1088/2058-9565/1/1/015003/meta)).
*  [[HM17](https://arxiv.org/abs/1809.07442),[FH16](https://arxiv.org/abs/1602.07674),[CZH+18](https://arxiv.org/abs/1805.01450),[QWE19](https://arxiv.org/abs/1902.02359)]
   Test (on a small scale) proposals for "quantum supremacy", and
   compare with simulations on classical computers.
*  [[KLLNP16](https://arxiv.org/abs/1602.05973),[GM19](https://scirate.com/arxiv/1902.02332)]
   Simon's algorithm can break some symmetric-key cryptosystems. Can
   you demonstrate some toy example? 
*  Some tools on optimizing reversible/quantum circuit: [[RevKit](https://msoeken.github.io/revkit.html),[Feynman](https://github.com/meamy/feynman)]

### Clearing up the folklore 
*  [[Shor97](https://epubs.siam.org/doi/10.1137/S0097539795293172),[Childs](https://www.cs.umd.edu/~amchilds/teaching/w13/l04.pdf)]
   Shor's algorithm can be seen as period finding over $$\mathbb{Z}$$.
   Can you extend to high dimensions, i.e., $$\mathbb{Z}^n$$ by
   reducing it to the one-dimensional case?  Note that period finding
   over $$\mathbb{Z}^n$$ can also be solved as a special case of a
   more general problem in
   [EHKS14](https://dl.acm.org/citation.cfm?id=2591860).
*  [[Cleve11](https://cs.uwaterloo.ca/~cleve/courses/F11CS667/SimonClassicalLB.pdf),[KNP05](https://arxiv.org/abs/quant-ph/0501060)]
   Exact lower bounds for Simon's problem, on probabilistic and
   quantum computers. Bounding the success probability given a fixed
   number of queries.
*  [[BSS03](https://www.computer.org/csdl/proceedings/ccc/2003/1879/00/18790179.pdf)]
   Workspace in a quantum query algorithm. Does more space give you
   more power?
*  More to come ... 
