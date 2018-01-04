---
layout: course
courseid: s16uwpqc
desc: S16-QIC 891
homeurl: /s16_uw_pqc/
permalink: /teaching/s16_uw_pqc/
title: QIC891 Topics in Quantum Safe Cryptography (Spring 2016)
subtitle: "Module 1: Post-Quantum Cryptography"
modified: Tue May 17 20:41:53 EDT 2016
---

* Table of Contents
{:toc}

## News

*   <span class="timestamp-wrapper"><span class="timestamp"><2016-05-20 Fri></span></span> Lecture 1 note posted, finally.
*   <span class="timestamp-wrapper"><span class="timestamp"><2016-05-20 Fri></span></span> Homework, lecture 4 note & slides posted!
*   <span class="timestamp-wrapper"><span class="timestamp"><2016-05-17 Tue></span></span> Lecture 3 handout & draft note, reading materials for lecture 1 - 3 postded.
*   <span class="timestamp-wrapper"><span class="timestamp"><2016-05-12 Thu></span></span> Lecture 2 handout and draft note posted.
*   <span class="timestamp-wrapper"><span class="timestamp"><2016-05-10 Tue></span></span> Lecture 1 introductory slides, handout on central problems posted! Lecture note will come soon.
*   <span class="timestamp-wrapper"><span class="timestamp"><2016-05-06 Fri></span></span> Resourse page is up and continues to grow!
*   <span class="timestamp-wrapper"><span class="timestamp"><2016-05-05 Thu></span></span> Course webpage is up!

## Course Info

*   **Meeting**: 10:30-12:00 on May 10, 12, 17, 19\. All at **QNC 1201** (attention: differs from initial announcement).
*   **Instructor**: [Fang Song]({{base}}/) (fang.song AT uwaterloo DOT ca)

### About this module

Cryptography is facing devastating challenges in an era of quantum
computing. Many public-key cryptosystems widely deployed on the
Internet will be broken by quantum attackers due to efficient quantum
algorithms such as Shor's factoring algorithm. This calls for
designing cryptosystems that (hopefully) can resist quantum attacks,
a.k.a. _post-quantum cryptography_ (PQC).

This module will give an overview of a few candidate directions on PQC. We will use public-key signature and encryption schemes as running examples. Instead of going over various constructions, I will take a unified approach by outlining general frameworks for cryptographic designs and showing how to instantiate them from each candidate direction. Quantum security of these new proposals will be discussed, which includes (quantum) hardness of underlying computational problems as well as formal security analyses in the presence of quantum adversaries (which have not received enough emphasis in the literature).

Check out the tentative [schedule](#tentative-schedule) below.

* * *

## Resources


*   A (non-exhaustive & growing) **[list]({{base}}/teaching/s16_uw_pqc/resource/)** of study materials & references on post-qantum cryptography.
*   Relevant readings will be specified for each lecture.


* * *


## Policy


### For academic credit

A short homework assignment will be handed out after the last lecture, which will be (typically) due two weeks after the end of the module.

In order to complete QIC 891 for academic credit, students must complete 3 modules and a project. You may only register in QIC 891 if you intend on completing 3 modules and associated homework and project by August 2016\.

Permission numbers are required to enroll in this course. Please contact [Monica Dey](https://services.iqc.uwaterloo.ca/people/profile/mdey/). Find more information [here](https://cryptoworks21.uwaterloo.ca/training/2016modules/).


### For CryptoWorks21 qualification

Students in the CryptoWorks21 training program may complete any eligible modules order to prepare for a CryptoWorks21 technical skills qualification exam on the module topic. Technical skills qualification exams will take place at the end of each module.

Students may also count these modules, including assignments and final project, towards academic credit as part of QIC 891.

**This module is eligible for technical skill qualification**. An exam (format TBD) will be given at a later point.

* * *

## Tentative schedule

### Tu May 10: Intro

[handout pqc candidate
problems: [pdf]({{ base }}/teaching/s16_uw_pqc/ccp.pdf)] - [Lec 1 Part
I intro
slides:
[pdf]({{base}}/teaching/s16_uw_pqc/qic891_pqc_intro.pdf)] - [Lec1 part
II note: [pdf]({{base}}/teaching/s16_uw_pqc/qic891_pqc_lec1.pdf)]

*   Setting the scene: threats to cryptography from quantum attacks. Two major aspects: 1) underlying hard problems are broken and 2) classical framework for security analysis falls apart.
*   Introduce main proposals to resist quantum attacks based on: 1) point lattices; 2) coding theory; 3) multivariate polynomials; and 4) signature schemes using cryptographic hash functions.
*   Central candidate problems for building PQC, e.g. SIS&LWE (lattice-based), syndrome decoding (code-based), multivariate equations (MQ-based).

#### Reading

*   Watch tutorial videos from PQCrypto 2014 [Summer School](https://www.youtube.com/playlist?list=PLBRgytHojT9ahsYZQ5FyCY_UO6tWz8FVA) & PQCrypt 2016 [Winter School](https://pqcrypto2016.jp/winter/).

### Th May 12: Signature

[handout pqsign schemes: [pdf]({{base}}/teaching/s16_uw_pqc/pqcsign.pdf)] - [Lec2 note: [pdf]({{base}}/teaching/s16_uw_pqc/qic891_pqc_lec2.pdf)]

*   Hash-based signature: Lamport one-time signature (OTS) & Merkle-tree construction. Recent developments for efficiency improvements, e.g., Winternitz OTS.
*   Hash+: signatures from collision resistant hash function with homomorphic property (H).
    *   hard problems to H.
    *   H to identification (ID) schemes: Stern (code), Lyubashevsky (lattice).
    *   ID to signature: Fiat-Shamir transformation.
*   **Next Time** Full domain hash in the random-oracle model using a trapdoor one-way permutation and instantiations: GPV (lattice) and CFS (code).

#### Reading

*   Chapter 3 (generic construction from OWFs) & 8 (identification & Fiat-Shamir) of monograph on Digital Signatures by Jon Katz [Springer](http://link.springer.com/book/10.1007/978-0-387-27712-7) (access it via library)
*   Lattice identification schemes [[LyuPKC08](http://www.di.ens.fr/~lyubash/papers/idlatticeconf.pdf), [LyuAC09](http://www.di.ens.fr/~lyubash/papers/FSAbortAsiacryptconf.pdf), [Lyu12](http://www.di.ens.fr/~lyubash/papers/LatticeSignature.pdf)]
*   Code identification [[Stern96](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.51.9793&rep=rep1&type=pdf)]

### Tu May 17: Public-key encryption

[handout pq pke schemes: [pdf]({{base}}/teaching/s16_uw_pqc/pqencsum.pdf)] - [Lec3 note: [pdf]({{base}}/teaching/s16_uw_pqc/qic891_pqc_lec3.pdf)]

*   Trapdoor one-way functions: plain-text RSA and its siblings in the post-quantum setting: GGH/NTRU (lattice), McEliece/Niederreiter (code), HFE (MQ).
*   Generic techniques to get CPA/CCA secure encryption in the random-oracle model:
    *   BR93
    *   Efficiency improvement: OAEP
    *   From weaker assummptions: Pointcheval, Fujisaki-Okamoto …
*   **Reading** Direct constructions based on lattices
    *   Regev's LWE encryption
    *   Fancy stuff: fully-homomorphic encryption, etc.

#### Reading

*   Chapter 7 (FDH) of Digital Signatures by Jon Katz [Springer](http://link.springer.com/book/10.1007/978-0-387-27712-7) (access it via library)
*   Lattice trapdoors, signature & PKE [[GPV08](http://web.eecs.umich.edu/~cpeikert/pubs/trap_lattice.pdf), [Regev09](http://www.cims.nyu.edu/~regev/papers/qcrypto.pdf), [MP12](http://web.eecs.umich.edu/~cpeikert/pubs/efftrap.pdf)]
*   Random oracles, OAEP & more: [[BR93](https://cseweb.ucsd.edu/~mihir/papers/ro.pdf), [BR94](https://cseweb.ucsd.edu/~mihir/papers/oae.pdf), [FO13](http://link.springer.com/article/10.1007/s00145-011-9114-1)]

### Th May 19: Are they quantum-secure?

[homework: [pdf]({{base}}/teaching/s16_uw_pqc/qic891_pqc_hw.pdf), [tex]({{base}}/teaching/s16_uw_pqc/qic891_pqc_hw.tex)] - [Lec4 part I note: [pdf]({{base}}/teaching/s16_uw_pqc/qic891_pqc_lec4.pdf)] - [Lec4 part II slides: [pdf]({{base}}/teaching/s16_uw_pqc/qic891_pqc_outro.pdf)]

*   Hardness of the candidate computational problems against quantum algorithms. Worst-case to average-case reductions for lattice problems.
*   Analyzing security in the presence of quantum adversaries. Challenges and techniques to deal with
    *   quantum random-oracle model.
    *   quantum rewinding (affects e.g., identification schemes).

