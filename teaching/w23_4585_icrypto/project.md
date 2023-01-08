---
layout: course
title: (Winter 2023) CS 485/585 - Intro to Cryptography
courseid: w23 485/585
subtitle: Course Project
desc: Project
permalink: /teaching/w23_4585_icrypto/project/
modified: <2022-01-05 Thu> 
---

* Table of Contents
{:toc}

## Instructions

{% comment %}
2-3 people group projects. You may choose one (or superposition) of
the options below. 
* **Research project**. Take any route to gain some research
  experience.
  *  _Literature review_. Pick a topic of interest, and summarize the
state of art of it. The final outcome would be a _survey_ paper
including open problems.
  *  _Completing "folklore"_. There are "folklore" results in the
   filed or missing details in class that are worth spelling out
   carefully. You will study a dedicated problem and give a thorough
   exposition on it.
  *  _original research_. Challenge yourself with some open question
   in the field. You are encouraged to explore the potential of
   quantum computing in your own research area. Be _creative_ and keep
   a _critical_ mind.

*  **Programming project**. Sure, why not get your hands dirty, thanks
   to the advances of physical devices and software frameworks (see
   some popular ones below). You may test and optimize quantum
   algorithms and protocols in a platform, or you might want to
   contribute to new features of these tools.
   
*  **Societal-impact project**. Quantum is becoming a buzz word. What
 is the broader implication of quantum technology? What is happening
 in the society to get ready for this technology? Are there ethical
 issues concerning the technology and the workforce development? 

{% endcomment %}
### Milestones

{% comment %}
*  **Proposal**: 1-2 pages consisting of 1) the topic, background,
   context, and motivation; 2) a few core references; and 3)
   your goal and a plan. (10%)
*  **Oral presentation**: Each group will have about 30 minutes to
   present your project including Q&A. Your need to demonstrate both
   _breath_ and _depth_. Aim for a clear introduction that would
   engage the audience, and then explain 1-2 technical ideas in some
   detail. Every group member needs to participate, and your group
   will be graded by fellow students. (20%)
*  **Final report**: <= 10 pages (excluding references). This should
   resemble a research paper: 1) a short abstract; 2) an introduction
   that motivates the topic and offers an overview of the entire
   report; 3) details including proper preliminary materials (e.g.,
   notations & definitions), explaining the main results; and finally
   4) further discussion and open questions. (10%)
*  **Report format**: I recommend you to typeset your reports in
   _LaTeX_, and manage your bibliography using BibTeX. The [resource
   page]({{base}}/teaching/f22_4510_qc/resource/) has links to
   materials to pick up LaTeX. You should use single-column,
   single-space (between lines) format on letter-size papers. You will
   earn extra credit if you typeset your final report in LaTeX.
{% endcomment %} 

### Timeline (Tentative)
{% comment %}
*  **Week 2 - 4**: discussing project ideas and forming groups.
*  **Week 5**: proposal due on xxxx. 
*  **Week 8**: progress check-up meetings.
*  **Week 10**: in-class presentations. 
*  **xx/xx**: final report due. 
{% endcomment %}
------ 

## Suggested topics 

The list below is far from complete, and is only intended as a
starting point for you to explore more options. 


### Societal impact
{% comment %}
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
* The research efforts and focuses of different **regions and
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
* More to be filled by you ...
{% endcomment %}

### Programming 

### Research 

*  Check out the frontier research topics at these venues:
[Crypto](http://www.iacr.org/meetings/crypto/), [Eurocrypt](https://www.iacr.org/meetings/eurocrypt/), [Asiacrypt](https://www.iacr.org/meetings/asiacrypt/), [TCC](https://www.iacr.org/meetings/tcc/),
[Qcrypt](https://2022.qcrypt.net/), and general TCS conferences (e.g.,
[STOC](http://acm-stoc.org/), [FOCS](http://ieee-focs.org/),
[SODA](http://www.siam.org/meetings/archives.php#SODA),
[ITCS](http://itcs-conf.org/),
CCC[https://computationalcomplexity.org/]).

{% comment %}
* **Quantum-safe cryptography**
  *  [[PQC](https://pqcrypto.org/),[ToB18](https://blog.trailofbits.com/2018/10/22/a-guide-to-post-quantum-cryptography/)]
   Securing classical cryptography against quantum attacks, known as
   _post-quantum cryptography_.
  *  [[HMY22](https://arxiv.org/abs/2210.05978)] Trading quantum gravity
     for quantum cryptography?
  *  [[BCMVV18](https://arxiv.org/abs/1804.00640)] Testing quantumness
     and generating certifiable randomness.
  *  [[Zhandry18](https://eprint.iacr.org/2017/1080)] A unique quantum
   primitive, quantum lightning, with applications in quantum
   money. Can you construct it from other problems?
  *  [[DPVR12](https://epubs.siam.org/doi/10.1137/100813683)] Making
   randomness extractors secure against _quantum side information_.
  *  [[MY21](https://arxiv.org/abs/2112.06369)
     [AQY22](https://arxiv.org/abs/2112.10020)] Cryptography from
     quantum pseudorandomness. What is the _minimal_ assumption for
     cryptography?

* **Clearing up the folklore**
  *  [[Cleve11](https://cs.uwaterloo.ca/~cleve/courses/F11CS667/SimonClassicalLB.pdf),[KNP05](https://arxiv.org/abs/quant-ph/0501060)]
   Exact lower bounds for Simon's problem, on probabilistic and
   quantum computers. Bounding the success probability given a fixed
   number of queries.

{% endcomment %}
