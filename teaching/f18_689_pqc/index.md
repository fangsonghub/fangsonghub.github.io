---
layout: course
title: (Fall 2018) CSCE 689 - Special Topics 
subtitle: Foundations of Post-Quantum Cryptography
courseid: f18 689
desc: f18 689
permalink: /teaching/f18_689_pqc/
modified: <2018-11-07 Wed>
---

## Announcement
*  <2018-09-29 Sat> A LaTeX template for scribe notes
[[TeX]({{base}}/teaching/f18_689_pqc/f18_scribe.tex) [PDF]({{base}}/teaching/f18_689_pqc/f18_scribe.pdf)]. 

*  <2018-09-29 Sat> Information about project available on
[Project]({{base}}/teaching/f18_689_pqc/project/) page.

## About

*  **Prerequisite**: maturity in algorithm analysis and mathematics
   (espeically linear algebra, basic probability thoery and group
   thoery). This course will involve reading and writing lots of
   mathematical proofs. 
*  **Syllabus**:
   [PDF]({{base}}/teaching/f18_689_pqc/CSCE689_PQC_F18_syllabus.pdf){:target="_blank"} 
*  **Instructor**: Prof. [Fang Song]({{base}}/) @ HRBB 427B 
*  **Email**: fang.song "AT" tamu.edu. Start your subject line with "F18-PQC"
*  **Lectures**: T/TR 5:30 – 6:45pm @ HRBB 126
*  **Office hours**: W 10:30 am - 12pm and by appointment
*  **Text**: no required ones. We will primarily follow lecture notes
and read research papers. <!-- See the
**resource** [page]({{base}}/teaching/f18_689_pqc/resource/) for
useful materials. --> 


## Schedule (subject to change)

| Week | Date  | Topic | Reading |
|:-----:| :---------: |:----------:|:-----:|
|1| Tu,08/28  | Syllabus, intro, qubit |Aaronson Lec9 [HTML](http://www.scottaaronson.com/democritus/lec9.html){:target="_blank"} <br> Watrous Lec1 [PDF](https://cs.uwaterloo.ca/~watrous/CPSC519/LectureNotes/01.pdf){:target="_blank"} |
|| Th,08/30 | Aggie GameDay, Class Cancelled |
|2| Tu,09/04| tensor product, dirac notation | Watrous Lec2 [PDF](https://cs.uwaterloo.ca/~watrous/CPSC519/LectureNotes/02.pdf){:target="_blank"}|
|| Th,09/06| quantum circuit model, Deutsch's algorithm| Watrous Lec3 [PDF](https://cs.uwaterloo.ca/~watrous/CPSC519/LectureNotes/03.pdf){:target="_blank"}, Lec4 [PDF](https://cs.uwaterloo.ca/~watrous/CPSC519/LectureNotes/04.pdf){:target="_blank"} |
|3| Tu,09/11| Simon's algorithm | Self-study Deutsch-Josza (Watrous Lec5 [PDF](https://cs.uwaterloo.ca/~watrous/CPSC519/LectureNotes/05.pdf){:target="_blank"}) <br>  Watrous Lec6 [PDF](https://cs.uwaterloo.ca/~watrous/CPSC519/LectureNotes/06.pdf){:target="_blank"}|
|| Th,09/13 | Grover's algorithm | Watrous Lec12 [PDF](https://cs.uwaterloo.ca/~watrous/CPSC519/LectureNotes/12.pdf){:target="_blank"}, Lec13 [PDF](https://cs.uwaterloo.ca/~watrous/CPSC519/LectureNotes/13.pdf){:target="_blank"} |
| 4 |Tu,09/18 | Overview of quantum-safe crypto | [Son'PQC14](https://eprint.iacr.org/2014/709){:target="_blank"} <br> Video: [Son16@AsiaPQC](https://www.youtube.com/watch?v=n39-FOmNh5g){:target="_blank"}|
|| Th,09/20| Case study: PRF/PRP <br> Superposition attack on Luby-Rackoff | Trevison Notes [[5](https://people.eecs.berkeley.edu/~luca/cs276/lecture05.pdf){:target="_blank"}, [6](https://people.eecs.berkeley.edu/~luca/cs276/lecture06.pdf){:target="_blank"}, [15](https://people.eecs.berkeley.edu/~luca/cs276/lecture15.pdf){:target="_blank"}]<br> [KM'ISIT10](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=5513654){:target="_blank"} |
|5| Tu,09/25| Superpositon attacks cont'd <br> Quantum-secure PRF | [Zhandry'FOCS12](https://eprint.iacr.org/2012/182){:target="_blank"} <br> Supp: [Zhandry'ePrint16](https://eprint.iacr.org/2016/1076){:target="_blank"} | 
||Th,09/27| Small-range distribution <br> QPRF cont'd <br> | [Zhandry'FOCS12](https://eprint.iacr.org/2012/182){:target="_blank"} |
|6|Tu,10/02|Oracle Indist. <br> GGM PRF from PRG | [Zhandry'FOCS12](https://eprint.iacr.org/2012/182){:target="_blank"} <br> Trevison note [14](https://people.eecs.berkeley.edu/~luca/cs276/lecture14.pdf){:target="_blank"}|
||Th,10/04| Quantum query complexity | [BBBV97](https://arxiv.org/pdf/quant-ph/9701001.pdf){:target="_blank"} <br> Supp.: [Son17](https://arxiv.org/abs/1709.01236){:target="_blank"} |
|7| Tu,10/09| Polynomial method | [Childs LN 13](https://www.cs.umd.edu/~amchilds/teaching/w13/l14.pdf){:target="_blank"} <br> [Thm.3.1,3.2 [Zhandry'Crypto12](https://eprint.iacr.org/2012/076){:target="_blank"}]|
||Th,10/11|Case study: Hash functions <br> Generic security | [8.1,8.3 [Boneh-Shoup v0.4](https://crypto.stanford.edu/~dabo/cryptobook/){:target="_blank"}]|
|8| Tu,10/16| Hash functions: quantum security | [HRS'PKC16](https://eprint.iacr.org/2015/1256){:target="_blank"}|
||Th,10/18| More on hash functions <br> Collision finding | [Zhandry'QIC15](https://arxiv.org/abs/1312.1027){:target="_blank"} <br> |
|9|Tu,10/23| Iterated hash <br> Random Oracle model | [8.4,8.10.2 [Boneh-Shoup v0.4](https://crypto.stanford.edu/~dabo/cryptobook/){:target="_blank"}] <br> [BDF+'Asiacrypt11](https://eprint.iacr.org/2010/428){:target="_blank"} <br> Supp: M.Green [Blog posts](https://blog.cryptographyengineering.com/2011/09/29/what-is-random-oracle-model-and-why-3/){:target="_blank"} |
||Th,10/25| Case study: Full-Domain-Hash Signature| Trevisan note [22](https://people.eecs.berkeley.edu/~luca/cs276/lecture22.pdf){:target="_blank"} <br> [Sect.5.3 [Zhandry'Crypto12](https://eprint.iacr.org/2012/076){:target="_blank"}]|
|10|Tu,10/30|Techniqes for Quantum RO | [Lemma1,31[Unruh'JACM15](https://eprint.iacr.org/2013/606){:target="_blank"}] <br> [Lemma5 [ES'TQC15](https://eprint.iacr.org/2015/878){:target="_blank"}] <br> Supp: [AHU'ePrint18](https://eprint.iacr.org/2018/904){:target="_blank"} |
||Th,11/01|More on QRO ||
|11|Tu,11/06|||
||Th,11/08|||
|12|Tu,11/13|||
||Th,11/15|||
|13|Tu,11/20|Project Presentation||
||Th,11/22| no class <br> Thanksgiving holiday||
|14| Tu,11/27| Project Presentation||
||Th,11/29| Project Presentation ||
|15 | Tu,12/05| Redefined day <br> Thursday class||
{:.mbtablestylef}

## Homwork and Exercise 

* Exercise 1 [[PDF]({{base}}/teaching/f18_689_pqc/f18_pqc_ex1.pdf){:target="_blank"} [TeX]({{base}}/teaching/f18_689_pqc/f18_pqc_ex1.tex){:target="_blank"}]
* Homework 1 [[PDF]({{base}}/teaching/f18_689_pqc/f18_689_hw1.pdf){:target="_blank"} [TeX]({{base}}/teaching/f18_689_pqc/f18_689_hw1.tex){:target="_blank"}]


