---
layout: course
title: (Winter 2018) CS 485/585 - Intro to Cryptography
courseid: w18 485/585
desc: w18 485/585
permalink: /teaching/w18_4585_icrypto/
modified: <2018-02-04 Sun>
---
*  **Syllabus**: [PDF]({{base}}/teaching/w18_4585_icrypto/w18syllabus.pdf){:target="_blank"}, and more on the [ADMINISTRATION]({{base}}/teaching/w18_4585_icrypto/admin/) page.
*  **Lectures**: Tu/Th 16:40 - 18:30 @ Fourth Ave Building 10.
*  **Instructor**: [Fang Song]({{base}}/) (fsong
   "AT" pdx.edu). **Office hours**: Tu/Th 10:30 - 11:30am, or by
   appointment @ FAB 120-07.
*  **Teaching assistant**: Nate Launchbury (njl2 "AT"
   pdx.edu). **Office hours**: Monday, 9:30 - 11:00 am. 
*  **Required Text**: [Introduction to Modern
Cryptography](http://www.cs.umd.edu/~jkatz/imc.html){:target="_blank"}
(2nd edition) by [Jonathan
Katz](http://www.cs.umd.edu/~jkatz){:target="_blank"} and [Yehuda
Lindell](http://u.cs.biu.ac.il/~lindell/){:target="_blank"}.  Chapman
and Hall/CRC Press, Nov 2014.
* **Useful materials**: see
  the [RESOURCE]({{base}}/teaching/w18_4585_icrypto/resource/) page.
* Previous offerings: [Winter 2017]({{base}}/teaching/w17_4585_icrypto/){:target="_blank"}

## Announcement
*  <2018-02-04 Sun> Notes for lecture 5 - 8 posted. 
*  <2018-01-25 Thu> Lecture 1 - 5 notes posted. HW2 Problem 1 & 2 typo corrected. 
*  <2018-01-25 Thu> Office hour cancelled due
   to [PSU Winter Symposium 2018](https://www.pdx.edu/academic-affairs/winter-symposium-2018){:target="_blank"}
*  <2018-01-03 Wed> Course page up and running! Check it out~ 

## Schedule (subject to change)

| Week | Date  | Topic | Reading |
|:-----:| :---------: |:----------:|:-----:|
|1| T,01/09  | Syllabus, intro, review of probability and randomized algorithms <br> [Intro slides [PDF]({{base}}/teaching/w18_4585_icrypto/w18_cs4585_intro.pdf){:target="_blank"} 8.7M] | [KatzLindell] Chapter 1,Appendix A; <br> Notes on [discrete probability](https://people.eecs.berkeley.edu/~luca/cs276/notesprob.pdf){:target="_blank"} by Trevisan|
||TR,01/11 |Perfect secrecy, one-time pad, limits; <br> Computational secrecy <br> [Lec2 note: [PDF]({{base}}/teaching/w18_4585_icrypto/w18_cs4585_lec2.pdf){:target="blank"}] | [KL] Sect.2.1,2.2,2.3,3.1|
|2|T,01/16| Stream ciphers, pseudorandom generators <br> proof by reduction <br> [Lec3 note: [PDF]({{base}}/teaching/w18_4585_icrypto/w18_cs4585_lec3.pdf){:target="blank"}] | [KL] 3.2,3.3,6.1; <br> Supplement: [[BonehShoup v0.4](https://crypto.stanford.edu/~dabo/cryptobook/){:target="_blank"}] Chapter 3 |
||TR,01/18| Block ciphers, pseudorandom functions, pseudorandom permutations <br> Q&A <br> [Lec4 note: [PDF]({{base}}/teaching/w18_4585_icrypto/w18_cs4585_lec4.pdf){:target="blank"}] | [KL] 3.5,3.6,6.2 <br> Supplement: [BS] Chapter 4|
|3|T,01/23| Chosen-Plaintext-Attacks <br> **Quiz 1** <br> [Lec5 note: [PDF]({{base}}/teaching/w18_4585_icrypto/w18_cs4585_lec5.pdf){:target="_blank"}] |   [KL] 3.4,3.5 <br> Supplement: [BS] Chapter 5 |
||TR,01/25| CPA constructions <br> Message Authentication Codes <br> [Lec6 note: [PDF]({{base}}/teaching/w18_4585_icrypto/w18_cs4585_lec6.pdf){:target="_blank"}]| [KL] 4.1,4.2,4.3 <br> Supplement: [BS] Chapter 6 |
|4|T,01/30| MAC domain extension <br> Review HW1 & Quiz1 <br> [Lec7 note: [PDF]({{base}}/teaching/w18_4585_icrypto/w18_cs4585_lec7.pdf){:target="_blank"}]|[KL] 4.4 <br> Supplement: [BS] Chapter 6 |
||TR,02/01| Hash functions and applications <br> Q&A <br> [Lec8 note: [PDF]({{base}}/teaching/w18_4585_icrypto/w18_cs4585_lec8.pdf){:target="_blank"}] | [KL] Sect. 5.1-5.4, Appendix A.4 <br> Supplement: [BS] Chapter 8 |
|5|T,02/06| HMAC <br> CCA and authenticated encryption <br> **Quiz 2** <br> [Lec9 note: [PDF]({{base}}/teaching/w18_4585_icrypto/w18_cs4585_lec9.pdf){:target="_blank"}]| [KL] Sect. 3.7.1,4.5.1,4.5.2 <br> Supplement: [BS] Chapter 9 |
||TR,02/08| Theoretical constructions of private-key primitives <br> [Lec10 note: [PDF]({{base}}/teaching/w18_4585_icrypto/w18_cs4585_lec10.pdf){:target="_blank"}]| Sect. 7.1,7.2,7.4,7.5,7.8|
|6|T,02/13| PKC evolution <br> Review HW2&Quiz2  ||
||TR,02/15|PubKey Enc, TDP <br> Q&A ||
|7|T,02/20|Lattices <br> **Quiz 3** | |
||TR,02/22|PKE based on lattices ||
|8|T,02/27|Digital signature 1  <br> Review HW3&Quiz3||
||TR,03/01|DS 2 ||
|9|T,03/06|Crypto in practice: SSL/TLS <br> **Quiz 4**||
||TR,03/08| Crypto in practice: real-world security flaws <br> Final review||
|10|T,03/13| selected topics ||
||TR,03/15| Review HW4,Quiz4,PE ||
||T,03/20 | **Final Exam**: 17:30-19:20 @ FAB 10 | Practice Exam [PDF]|
{:.mbtablestylef}

## Homework 
* [**HW 1** [latex]({{base}}/teaching/w18_4585_icrypto/w18_cs4585_hw1.tex){:target="_blank"} [PDF]({{base}}/teaching/w18_4585_icrypto/w18_cs4585_hw1.pdf){:target="_blank"}] out Tuesday Jan. 09, due **Thursday Jan. 18**.

* [**HW 2** [latex]({{base}}/teaching/w18_4585_icrypto/w18_cs4585_hw2.tex){:target="_blank"} [PDF]({{base}}/teaching/w18_4585_icrypto/w18_cs4585_hw2.pdf){:target="_blank"}] out Thursday Jan. 18, due **Thursday Feb. 1**.

* [**HW 3** [latex]({{base}}/teaching/w18_4585_icrypto/w18_cs4585_hw3.tex){:target="_blank"} [PDF]({{base}}/teaching/w18_4585_icrypto/w18_cs4585_hw3.pdf){:target="_blank"}] out Thursday Feb. 1, due **Thursday Feb. 15**. 

* [**HW 4** [latex]({{base}}/teaching/w18_4585_icrypto/w18_cs4585_hw4.tex) [PDF]({{base}}/teaching/w18_4585_icrypto/w18_cs4585_hw4.pdf){:target="_blank"}] out Thursday Feb. 15, due **Thursday Mar. 1**.
