---
layout: course
title: (Fall 2024) CS 483/583 - Intro to Quantum Computer Science
courseid: f24 483/583
subtitle: Course Project
desc: Project
permalink: /teaching/f24_4583_qc/project/
modified: <2024-10-16 Wed>
---

* Table of Contents
{:toc}

## Instructions

2-3 people group projects. You may choose one (or superposition) of
the options below. 
* **Research project**. Take any route to gain some research
  experience.
  *  _Literature review_. Pick a topic of interest, and summarize the
state of art of it. The final outcome would be either a traditional
_survey_ paper or an _expository_ science article that helps explain
the topic to a broader audience (see a [sample
here](https://www.quantamagazine.org/computer-scientists-prove-that-heat-destroys-entanglement-20240828/)).
  *  _Completing "folklore"_. There are "folklore" results in the
   filed or missing details in class that are worth spelling out
   carefully. You will study a dedicated problem and give a thorough
   exposition on it.
  *  _original research_. Challenge yourself with some open question
   in the field. You are encouraged to explore the potential of
   quantum computing in your own research area. Be _creative_ and keep
   a _critical_ mind.

*  **Programming project**. Sure, why not get your hands dirty, thanks
   to the advances of physical device and software frameworks (see
   some popular ones below). You may test and optimize quantum
   algorithms and protocols in a platform, or you might want to
   contribute to new features of these tools.
   
*  **Societal-impact project**. Quantum is becoming a buzz word. What
 is the broader implication of quantum technology? What is happening
 in the society to get ready for this technology? Are there ethical
 issues concerning the technology and the workforce development? 
 
### Milestones
*  **Proposal**: 1-2 pages consisting of 1) the topic, background,
   context, and motivation; 2) a few core references; and 3)
   your goal and a plan. (5%)
*  **Oral presentation**: Each group will have about 30 minutes to
   present your project including Q&A. Your need to demonstrate both
   _breath_ and _depth_. Aim for a clear introduction that would
   engage the audience, and then explain 1-2 technical ideas in some
   detail. Every group member needs to participate, and your group
   will be graded by fellow students. (15%)
*  **Final report**: <= 10 pages (excluding references). This should
   typically resemble a research paper (unless you choose to write an
   expository article mentioned above): 1) a short abstract; 2) an
   introduction that motivates the topic and offers an overview of the
   entire report; 3) details including proper preliminary materials
   (e.g., notations & definitions), explaining the main results; and
   finally 4) further discussion and open questions. (10%)
*  **Report format**: I recommend you to typeset your reports in
   _LaTeX_, and manage your bibliography using BibTeX. The [resource
   page]({{base}}/teaching/f24_4583_qc/resource/) has links to
   materials to pick up LaTeX. You should use single-column,
   single-space (between lines) format on letter-size papers. 

### Timeline (Tentative)
*  **Week 1 - 3**: forming groups.
*  **Week 4**: discussing project ideas.
*  **Week 5 Fri 11/01**: proposal due, 11:59pm anytime on Earth. 
*  **Week 8**: progress check-up meetings.
*  **Week 10**: oral presentations. 
*  **Finals Week Wed 12/11**: final report due, 11:59pm anytime on Earth. 

------ 

## Suggested topics 

The list below is far from complete, and is only intended as a
starting point for you to explore your options. Suggestions on
"societal-impact" and "programming" are especially brief to give your
creativity enough room. Here are a few general readings.

* [[CCC17](https://cra.org/ccc/wp-content/uploads/sites/2/2018/11/Next-Steps-in-Quantum-Computing.pdf)]
Next Steps in Quantum Computing: Computer Science’s Role.
* [[NAP19](https://www.nap.edu/catalog/25196/quantum-computing-progress-and-prospects)] Quantum Computing: Progress and Prospects. 
* [[Quantum software – beneath the quantum hype](https://www.factbasedinsight.com/quantum-software-beneath-the-quantum-hype/#zp-ID-139100-2488567-SQFNRLQ9)] Reflections on NISQ era.
* [[National Quantum Initiative Act](https://www.quantum.gov/people/)] by the US goverment. 

### Societal impact
(We need scientists and engineers to advance the field of quantum
  computing. But what is equally important, if not more, is to have
  more people think broadly the implications and proper actions to
  take.)
  
* **Misinformation** in mass media.  Are we doing a good job so far to
  deliver the idea of quantum computing to the general audience? Some
  popular sites: [[Phys.org](https://m.phys.org/),
  [Quantamagazine](https://www.quantamagazine.org/tag/quantum-computing/),
  [MIT Tech
  Review](https://www.technologyreview.com/topic/computing/quantum-computing/)]. An
  ebook by Graves on _Deciding what's true_ is available via [Library
  eLink](https://search.library.pdx.edu/primo-explore/fulldisplay?docid=CP71268037550001451&vid=PSU&search_scope=all&tab=default_tab&lang=en_US&context=L).
* Research efforts and focuses of different **regions and
  countries**. For instance, look at the [Quantum Internet](http://quantum-internet.team/) effort in EU. [US National Strategic Overview](https://www.whitehouse.gov/wp-content/uploads/2018/09/National-Strategic-Overview-for-Quantum-Information-Science.pdf). Where is the US government's funding going? How is it influencing the gap between resources to different institutes? 
* Impact on **labor market**. How many patents are being filed? How
  much investiment is being injected in quantum startup companies?
  Are we going to see jobs in quantum? This [report on
  AI](https://web.stanford.edu/~mww/webb_jmp.pdf) might help.
* Impact on **education**. Are there sufficient resource to pick up
  quantum computing (e.g., MOOC at various levels)? Shall we update
  the curriculum in college (or even in high school)? Some teasers:
  [[IHE](https://www.insidehighered.com/digital-learning/blogs/online-trending-now/quantum-leap-future-education), [Fermilab](https://arxiv.org/pdf/2004.07206.pdf)]. 
* **Ethical** issues. Can quantum technology help alleviate pressing
  social crisis? Or is it possibly exacerbating problems such as
  global warming and inequality? An APS interview titled "[Should We Build Quantum Computers at All?
](https://www.aps.org/publications/apsnews/202209/build-quantum.cfm)".
* The debate on **Quatnum Internet**. For starters: [Talk by
  Lukens](https://2024.qcrypt.net/sessions/tutorial_lukens/), [NSA's
  position](https://www.nsa.gov/Cybersecurity/Quantum-Key-Distribution-QKD-and-Quantum-Cryptography-QC/),
  and [response](https://arxiv.org/abs/2307.15116) by some
  researchers.
* More to be filled by you ...

### Programming 

* Popular quantum programming platforms (some with hardware too): IBM
  [Qiskit](https://qiskit.org/), Microsoft [Q# development
  kit](https://www.microsoft.com/en-us/quantum/development-kit),
  Google [Cirq](https://cirq.readthedocs.io/en/stable/index.html),
  Rigetti [Forrest SDK](http://docs.rigetti.com/en/stable/). You may
  conduct a _comparative_ study on the qualities of their physical
  device, as well as features of the software kits. Here is an
  introduction to [benchmarking quantum
  computers](https://qiskit.org/textbook/ch-quantum-hardware/randomized-benchmarking.html),
  and a report on benchmarking an [11-qubit quantum
  computer](https://www.nature.com/articles/s41467-019-13534-2).
*  [[HM17](https://arxiv.org/abs/1809.07442),[FH16](https://arxiv.org/abs/1602.07674),[CZH+18](https://arxiv.org/abs/1805.01450),[QWE19](https://arxiv.org/abs/1902.02359)]
   Test (on a small scale) proposals for "quantum advantage", and
   compare with simulations on classical computers.
*  [[KLLNP16](https://arxiv.org/abs/1602.05973),[GM19](https://scirate.com/arxiv/1902.02332)]
   Simon's algorithm can break some symmetric-key cryptosystems. Can
   you demonstrate some toy example? 
*  Extensions to consider for implementation and simulation of quantum
   algorithms: optimize the circuit, estimate the cost, test
   variations (e.g., robustness against noise), etc.  Tools on
   optimizing reversible/quantum circuit:
   [[RevKit](https://msoeken.github.io/revkit.html),[Feynman](https://github.com/meamy/feynman),[ZX-Calculus](https://arxiv.org/abs/1902.03178)]
*  Develop a **quantum computer game**? Here is an example [quantum
   battleship](https://medium.com/@decodoku/quantum-battleships-the-first-multiplayer-game-for-a-quantum-computer-e4d600ccb3f3).

### Research 

*  [SciRate](https://scirate.com/) is quantum researchers' instagram,
where new papers are posted, rated and discussed. 
*  Major venues for disseminating quantum research:
[QIP](https://qipconference.org/), [TQC](https://tqc-conference.org/),
[QCRYPT](https://2024.qcrypt.net/), and general TCS conferences (e.g.,
[STOC](http://acm-stoc.org/), [FOCS](http://ieee-focs.org/),
[Crypto](http://www.iacr.org/meetings/crypto/)).

* **Quantum algorithms and complexity**
  * [[YLC14](https://arxiv.org/abs/1409.3305)] Fixed-point quantum search. 
  * [[AR19](https://arxiv.org/abs/1908.10846)] Quantum Approximate Counting, Simplified.
  * [[CSZJ20](https://arxiv.org/abs/2004.01372)] Variational Quantum
    State Eigensolver. An algorithmic framework suitable for near-term
    quantum devices.
  * [[GSLW18](https://arxiv.org/abs/1806.01838)] Introduces _singular
  value transformation_, a cute framework unifying several quantum
  algorithmic techniques. 
  * [[CK24](https://arxiv.org/abs/2402.13863)] Fault-tolerance with
    _local_ operations. 
  
* **Quantum information theory**
  * [[HHL04](https://arxiv.org/abs/quant-ph/0307221)] Superdense
    coding of quantum states.
  * [[HOW05](http://arxiv.org/abs/quant-ph/0505062),[SY08](http://arxiv.org/abs/0807.4935)] Some weirdness about quantum information, such as _negative_ information and communicating with _zero-capacity_ channels.

* **Quantum cryptography & learning**
  *  [[B23](https://arxiv.org/abs/2211.05491)] Trading quantum gravity
     for quantum cryptography?
  *  [[Zhandry18](https://eprint.iacr.org/2017/1080)] A unique quantum
   primitive, quantum lightning, with applications in quantum
   money. Can you construct it from other problems?
  *  [[MY21](https://arxiv.org/abs/2112.06369)
     [AQY22](https://arxiv.org/abs/2112.10020)] Cryptography from
     quantum pseudorandomness. What is the _minimal_ assumption for
     cryptography? A lot of exciting recent development to catch up.
  *  [CHINS23](https://arxiv.org/abs/2306.04843) How can a classical
     user reliably delegate learning tasks to a quantum server? 
  *  [[BLMT](https://arxiv.org/abs/2310.02243)] _Learning quantum
     Hamiltonians_ at any temperature in polynomial time.

* **Clearing up the folklore**
  *  [[Cleve11](https://cs.uwaterloo.ca/~cleve/courses/F11CS667/SimonClassicalLB.pdf),[KNP05](https://arxiv.org/abs/quant-ph/0501060)]
   Exact lower bounds for Simon's problem, on probabilistic and
   quantum computers. Bounding the success probability given a fixed
   number of queries.
  *  [[BSS03](https://www.computer.org/csdl/proceedings/ccc/2003/1879/00/18790179.pdf)]
   Workspace in a quantum query algorithm. Does more space give you
   more power?
