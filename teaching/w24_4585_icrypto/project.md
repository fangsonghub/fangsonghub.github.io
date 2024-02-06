---
layout: course
title: (Winter 2024) CS 485/585 - Intro to Cryptography
courseid: w24 485/585
subtitle: Course Project 
desc: Project
permalink: /teaching/w24_4585_icrypto/project/
modified: <2024-02-05 Mon> 
---

* Table of Contents
{:toc}

{% comment %}
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
 
{% endcomment %}

## Instructions
### Milestones

*  **Literature review and proposal**: 1-2 pages consisting of 1) the
   topic of your cohice, background, context, and motivation; 2) core
   references; and 3) your goal and a plan. (5%)
*  **Oral presentation**: You need to demonstrate both _breath_ and
   _depth_. Aim for a clear introduction that would engage the
   audience, and then explain a few technical ideas in some
   detail. Every group member needs to participate. (15%)
*  **Final report**: ~ 10 pages (excluding references). This should
   resemble a research paper containing: 1) a short abstract; 2) an
   introduction that motivates the topic and offers an overview of the
   entire report; 3) details including proper preliminary materials
   (e.g., notations & definitions), explaining the main results; and
   finally 4) further discussion, prospects and open questions when
   applicable. (10%)
*  **Report format**: Submit your reports in PDF. I recommend that you
   typeset in _LaTeX_, and manage your bibliography using _BibTeX_.

### Timeline (Tentative)
*  **Week 1 - 5**: team building and discussing project ideas.
*  **Week 6**: proposal due on 02/16. 
*  **Week 8**: progress check-up.
*  **Week 10**: in-class presentations. 
*  **03/22**: final report due. 

------ 

## Suggested topics 

Discuss with me if you intend to choose a topic out of this list.
Keywords appearing in (_kwA_,_kwB_) describe the general category of
the work.

* (_foundation_) [MP23](https://eprint.iacr.org/2023/1451) A (relatively) simple construction of a PRG from a one-way function. 
* (_real-world,foundation_) A lightweight authenticated encryption
  scheme [Ascon](https://ascon.iaik.tugraz.at/) standardized by
  [NIST](https://nvlpubs.nist.gov/nistpubs/ir/2023/NIST.IR.8454.pdf).  
* (_real-world,foundation_) [BHKU22](https://eprint.iacr.org/2022/762)
    The Price of Verifiability: Lower Bounds for Verifiable Random
    Functions (VRFs are essential in Proof-of-Stake blockchain
    technology).
* (_real-world,ethics_) [DB23](https://medium.com/@boneh/using-zk-proofs-to-fight-disinformation-17e7d57fe52f)
  Using zero-knowledge proof systems to fight
  disinformation. ([Slides](https://iacr.org/submit/files/slides/2023/rwc/rwc203/13/slides.pdf) at RWC'2023)
* (_real-world,ethics_) Encrypted Gun Registry [KMPQ21](https://cs.brown.edu/~seny/pubs/gunreg.pdf).
* (_real-world,ethics_) Anonymity: anonymous permutation routing [BKO23](https://eprint.iacr.org/2022/1353)
and anonymous whistlblowing [ACM22](https://eprint.iacr.org/2021/1341.pdf). 
* (_real-world,cryptanalysis_)
  [HSCCS20](https://eprint.iacr.org/2020/1019) A case study of
  Google's Tink library.
* (_real-world,cryptanalysis_) Vulnerability due to weak randomness. A case at [Cisco](https://sec.cloudapps.cisco.com/security/center/content/CiscoSecurityAdvisory/cisco-sa-20190501-asa-ftd-entropy) in 2019 and an [update](https://eprint.iacr.org/2023/912) in 2023. Also see [HDWH12](https://www.usenix.org/system/files/conference/usenixsecurity12/sec12-final228.pdf) an insightful study on weak keys in TLS.
* (_real-world,cryptanalysis_) [sgx.fail](https://sgx.fail/) Vulnerability in Intel's Software Guard Extension (SGX). 

_Caution_: Be critical on the references you find. Below are some
reputable venues on cryptography and security research
[Crypto](http://www.iacr.org/meetings/crypto/),
[Eurocrypt](https://www.iacr.org/meetings/eurocrypt/),
[Asiacrypt](https://www.iacr.org/meetings/asiacrypt/),
[TCC](https://www.iacr.org/meetings/tcc/), list of
[security](https://people.engr.tamu.edu/guofei/sec_conf_stat.htm)
venues (maintained by Guofei Gu), [Qcrypt](https://2022.qcrypt.net/),
and general TCS conferences (e.g., [STOC](http://acm-stoc.org/),
[FOCS](http://ieee-focs.org/).

{% comment %}
### Societal impact
(We need scientists and engineers to advance the field of cryptography
and cybersecurity at large. But what is equally important, if not
more, is to have more people think broadly the implications and proper
actions to take.)

### Programming 


### Research 

{% endcomment %}
