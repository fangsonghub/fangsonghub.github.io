---
layout: course
title: (Winter 2023) CS 485/585 - Intro to Cryptography
courseid: w23 485/585
subtitle: Course Project
desc: Project
permalink: /teaching/w23_4585_icrypto/project/
modified: <2022-01-25 Wed> 
---

* Table of Contents
{:toc}

## Instructions

2-3 people group projects. You may choose one of the options below.
* **Research project**. Take any route to gain some research
  experience.
  *  _Literature review_. Pick a topic of interest, and summarize the
state of art of it. The final outcome would be a _survey_ paper
including open problems.
  *  _Original research_. Challenge yourself with some open question
   in the field. You are encouraged to explore interdisciplinary
   topics between cryptography and your own research area. Be
   _creative_ and keep a _critical_ mind. You may also choose to
   complete "folklores" in the field, which are results believed true
   but are missing details or careful scrutiny. You will study a
   dedicated problem and give a thorough exposition on it.

*  **Programming project**. Implementing cryptographic systems and
   applications is a risky business. Take this opportunity to learn
   good practices of putting cryptography into real-world use cases.

*  **Societal-impact project**. What is the broader implications of
 cryptography? Are there ethical issues concerning the technology and
 the workforce development?
 
{% comment %} {% endcomment %}

### Milestones

*  **Proposal**: 1-2 pages consisting of 1) the topic, background,
   context, and motivation; 2) a few core references; and 3) your goal
   and a plan. (5%)
*  **Oral presentation**: Each group will have about 30 minutes to
   present your project including Q&A. Your need to demonstrate both
   _breath_ and _depth_. Aim for a clear introduction that would
   engage the audience, and then explain 1-2 technical ideas in some
   detail. Every group member needs to participate, and your group
   will be graded by fellow students. (15%)
*  **Final report**: ~ 10 pages (excluding references). This should
   resemble a research paper containing: 1) a short abstract; 2) an
   introduction that motivates the topic and offers an overview of the
   entire report; 3) details including proper preliminary materials
   (e.g., notations & definitions), explaining the main results; and
   finally 4) further discussion and open questions. (10%)
*  **Report format**: Submit your reports in PDF. I recommend that you
   typeset in _LaTeX_, and manage your bibliography using _BibTeX_.

### Timeline (Tentative)
*  **Week 2 - 4**: discussing project ideas and forming groups.
*  **Week 5**: proposal due on 02/08. 
*  **Week 8**: progress check-up meetings.
*  **Week 10**: in-class presentations. 
*  **03/22**: final report due. 
{% comment %}{% endcomment %}
------ 

## Suggested topics 

The list below is far from complete, and is only intended as a
starting point for you to explore more options. 

### Societal impact
(We need scientists and engineers to advance the field of cryptography
and cybersecurity at large. But what is equally important, if not
more, is to have more people think broadly the implications and proper
actions to take.)

* The _Moral Character_ of Cryptographic Work. An insightful essay by
Phil Rogaway
([Paper](https://www.cs.ucdavis.edu/~rogaway/papers/moral-en.pdf)
[Slides](https://www.cs.ucdavis.edu/~rogaway/papers/ac15.pdf) at
Asiacrypt 2015).

*  Cryptography For a Secure, Privacy-Respecting and Fair Society: What
More Can We Do? Invited talk
([Video](https://www.youtube.com/watch?v=23gfTFLp9Is&ab_channel=TheIACR))
at Asiacrypt 2021 by Kazue Sako.

*  Crypto for the People. Invited talk by [Seny
   Kamara](https://cs.brown.edu/~seny/) at Crypto 2020. Check out
   Kamara's research work.

*  Export control on cryptography ([US
   EAR](https://www.bis.doc.gov/index.php/policy-guidance/encryption)). What?
   Why? Impact?

*  E-Voting. Check out research by [Vanessa
   Teague](https://researchers.anu.edu.au/researchers/teague-v) and an
   invited talk
   ([Slides](https://crypto.iacr.org/2021/slides/CRYPTOTeague.pdf)
   [Video](https://www.youtube.com/watch?v=GLQAf6uTExw&ab_channel=TheIACR))
   at Crypto 2021. There was also an earlier talk ([Democracy,
   security and evidence: let's have all
   three](https://asiacrypt.iacr.org/2018/files/SLIDES/WEDNESDAY/Z411/ASIACRYPT2018.pdf))
   at Asiacrypt 2018.

{% comment %} 
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

(Implementing cryptographic algorithms and applications needs to be
exercised with the highest standard. Even the slightest neligence can
be disastrous. Individuals are usually advised against homebrewing
them but to resort to standardized libraries.) 

*  Password Manager (Credit: Dan
   Boneh). [Instructions](https://crypto.stanford.edu/~dabo/courses/cs255_winter22/hw_and_proj/proj1.pdf)
   [Starter code](https://crypto.stanford.edu/~dabo/courses/cs255_winter22/hw_and_proj/proj1.zip).

*  End-to-End encrypted chat client (Credit: Dan
   Boneh). [Instructions](https://crypto.stanford.edu/~dabo/courses/cs255_winter22/hw_and_proj/proj2.pdf)
   [Starter code](https://crypto.stanford.edu/~dabo/courses/cs255_winter22/hw_and_proj/proj2.zip). 
   
*  Comparative study of NIST PQC Finalists. Read the
   [report](https://csrc.nist.gov/publications/detail/nistir/8413/final)
   to get a comprehensive picture about the history and status of this
   standardization process. Then select a few to assess their security
   and performance. Each team typically maitains codes and a project
   website (e.g., [this
   page](https://csrc.nist.gov/Projects/post-quantum-cryptography/selected-algorithms-2022)
   contains the information of the schemes selected to be standadized
   in July 2022, and [this
   page](https://csrc.nist.gov/Projects/post-quantum-cryptography/round-4-submissions)
   lists Round 4 submissions).

*  Build your applications with homomorphic encryption. Some libraries
   to consider
   [SEAL](https://www.microsoft.com/en-us/research/project/microsoft-seal/),
   [openFHE](https://www.openfhe.org/).

*   Playing with [zeor-knowledge proofs](https://zkproof.org/) and
    [SNARKs](https://z.cash/technology/zksnarks/). [This
    workshop](https://rdi.berkeley.edu/zkp-workshop-2022/) provides a
    lot of up-to-date pointers in the theory and practical
    developments of zero-knowledge proofs.


### Research 

*  Check out recent research results at these venues:
[Crypto](http://www.iacr.org/meetings/crypto/),
[Eurocrypt](https://www.iacr.org/meetings/eurocrypt/),
[Asiacrypt](https://www.iacr.org/meetings/asiacrypt/),
[TCC](https://www.iacr.org/meetings/tcc/),
[Qcrypt](https://2022.qcrypt.net/), and general TCS conferences (e.g.,
[STOC](http://acm-stoc.org/), [FOCS](http://ieee-focs.org/),
[SODA](http://www.siam.org/meetings/archives.php#SODA),
[ITCS](http://itcs-conf.org/),
[CCC](https://computationalcomplexity.org/)).

*  **Constructions**
    * [[ETY22](https://eprint.iacr.org/2022/785)] Shorter Hash-and-Sign
    Lattice-Based Signatures.
    *  [[HMR12](https://arxiv.org/abs/1208.1176)] An Enciphering Scheme
     Based on a Card Shuffle.
    * [[BH15](https://link.springer.com/article/10.1007/s00145-013-9169-2)]
    From Non-adaptive to Adaptive Pseudorandom Functions.
    * [[JJ22](https://eprint.iacr.org/2022/1430)] Indistinguishability
    Obfuscation (iO) via Mathematical Proofs of Equivalence.
    * [[SW14](https://eprint.iacr.org/2013/454)] How to Use
    Indistinguishability Obfuscation: Deniable Encryption, and More.
    * [[GSW13](https://eprint.iacr.org/2013/340)] Homomorphic
    Encryption from Learning with Errors: Conceptually-Simpler,
    Asymptotically-Faster, Attribute-Based. (Third-Gen fully
    homomorphic encryption.)

*  **Cryptanalysis**
    * [[Beullens22](https://eprint.iacr.org/2022/214)] Breaking
    _Rainbow_ (an NIST post-quantum cryptography Round-3 finalist)
    Takes a Weekend on a Laptop.
    * [[GLST22](https://eprint.iacr.org/2022/184)] Exploring SAT for
    Cryptanalysis: (Quantum) Collision Attacks against 6-Round SHA-3.

*  **Lower bounds**
    * [[CHM20](https://eprint.iacr.org/2020/687)] How much time and
    memory are needed to invert a function? The solution to this
    simple question is not as simple.
    * [[BHKU22](https://eprint.iacr.org/2022/762)] The Price of
    Verifiability: Lower Bounds for Verifiable Random Functions (VRFs
    are essential in Proof-of-Stake blockchain technology).
    * [[HNY22](https://eprint.iacr.org/2022/178)] Lower Bound on SNARGs
    in the Random Oracle Model. SNARGs are a vital building block in
    ZCash and many more cryptocurrency schemes.
  
* **(Post-) quantum cryptography**
  *  [[MY21](https://arxiv.org/abs/2112.06369)
     [AQY22](https://arxiv.org/abs/2112.10020)
     [AGQY22](https://arxiv.org/abs/2211.01444)] Cryptography from
     quantum pseudorandomness. What is the _minimal_ assumption for
     cryptography?
  *  [[HMY22](https://arxiv.org/abs/2210.05978)] From the Hardness of
     Detecting Superpositions to Cryptography: Quantum Public Key
     Encryption and Commitments.
  *  [[GJMZ22](https://eprint.iacr.org/2022/1358)] Commitments to
     Quantum States.
  *  [[LMQW22](https://eprint.iacr.org/2022/869)] A new set of
     examples demonstrating classical security fails to imply quantum
     security. 

{% comment %}
* **Clearing up the folklore**
{% endcomment %}
