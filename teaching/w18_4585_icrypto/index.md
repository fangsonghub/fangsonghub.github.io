---
layout: course
title: (Winter 2018) CS 485/585 - Intro to Cryptography
courseid: w18 485/585
desc: w18 485/585
permalink: /teaching/w18_4585_icrypto/
modified: <2018-03-14 Wed> 
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
*  <2018-03-14 Wed> Practice exam posted (find below)! Get started to
   prepare for the final exam. 
*  <2018-03-06 Tue> Schedule and lecture notes updated; Quiz 3 solution posted on D2L
*  <2018-02-20 Tue> <i style="color:red;"> Tuesday class cancelled </i> due to inclement
   weather. Stay tuned for further notice. 
*  <2018-02-20 Tue> Lec 11 & 12 notes posted. Thursday lecture
   features talk on Quantum Internet by Prof. Rod Van Meter from Keio
   University at FAB 86-01. 
*  <2018-02-11 Sun> Quiz 2 solution posted on D2L. Lecture notes 9 -
   10, and a summary of private-key crypto posted.
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
||TR,02/08| Theoretical constructions of private-key primitives <br> [Lec10 note: [PDF]({{base}}/teaching/w18_4585_icrypto/w18_cs4585_lec10.pdf){:target="_blank"}] <br> [Priv-key crypto summary: [PDF]({{base}}/teaching/w18_4585_icrypto/w18_cs4585_privksum.pdf){:target="_blank"}]| [KL] 7.1,7.2,7.4,7.5|
|6|T,02/13| Computational indistinguishability <br> PKC evolution <br> Review HW2&Quiz2 <br> [Lec11 note: [PDF]({{base}}/teaching/w18_4585_icrypto/w18_cs4585_lec11.pdf){:target="_blank"}] | [KL] 7.8,8.1,B.1,B.2,10 <br> Notes on [algebra](https://people.eecs.berkeley.edu/~luca/cs276/notesalgebra.pdf){:target="_blank"} by Trevisan <br> History of PKC: [Diffie](http://cr.yp.to/bib/1988/diffie.pdf){:target="_blank"}, [Merkle's Project Proposal](http://www.merkle.com/1974/){:target="_blank"}, [CESG](http://cryptome.org/jya/ellisdoc.htm){:target="_blank"}|
||TR,02/15|Number Theory Review <br> TDP <br> RSA <br> Q&A <br> [Lec12 note: [PDF]({{base}}/teaching/w18_4585_icrypto/w18_cs4585_lec12.pdf){:target="_blank"}]| [KL] 8.2.3,8.2.4,8.3.1,8.3.2; 11.4,11.5.1; 13.1 |
|7|T,02/20|~~Lattice-crypto~~ <br> ~~Hybrid Encryption~~ <br> ~~**Quiz 3**~~ <br> Cancelled due to [SNOW'18](https://alerts.weather.gov/cap/wwacapget.php?x=OR125A92DAB228.WinterStormWarning.125A92E94E00OR.PQRWSWPQR.d0adae4d2387ca50a4c434fe08957ecb){:target="_blank"} | LWE Tutorial by O.Regev [[PDF](https://cims.nyu.edu/~regev/papers/lwesurvey.pdf){:target="_blank"} [PPT](http://www.cims.nyu.edu/~regev/papers/lwesurvey.ppt){:target="_blank"}] <br> [KL: 11.3] |
||TR,02/22| Colloquim by Prof. [Rod Van Meter](http://web.sfc.keio.ac.jp/~rdv/){:target="_blank"} <br>  Title: Designing a Quantum Internet<br> Location: FAB 86-01 ||
|8|T,02/27|Digital signature intro  <br> Review HW3 <br> **Quiz3** <br> [Lec15 short note: [PDF]({{base}}/teaching/w18_4585_icrypto/w18_cs4585_lec15.pdf){:target="_blank"}] | [KL: 12.1,12.2] |
||TR,03/01| Group thoery <br> Diffie-Hellman, ElGamal <br> Hybrid Encryption <br> [Lec13(16) note: [PDF]({{base}}/teaching/w18_4585_icrypto/w18_cs4585_lec13.pdf){:target="_blank"}]|[KL: 8.3.1,8.3.2;11.3,11.4]|
|9|T,03/06| Hash-based Signature <br> Random-oracle <br> PKC with RO: OAEP and FDH <br> [Lec17 note: [PDF]({{base}}/teaching/w18_4585_icrypto/w18_cs4585_lec17.pdf){:target="_blank"}] | [KL: 5.5,11.5.4,12.4.2]|
||TR,03/08| SSL/TLS <br> real-world security flaws <br> **Quiz 4** <br> [Lec18 note: [PDF]({{base}}/teaching/w18_4585_icrypto/w18_cs4585_lec18.pdf){:target="_blank"}]| [KL:12.7,12.8]<br> [KRACK Attacks](https://www.krackattacks.com/){:target="_blank"}: Breaking WPA2 <br> [Heartbleed](http://heartbleed.com/){:target="_blank"}|
|10|T,03/13| selected topics: post-quantum crypto <br> [Slides [PDF]({{base}}/teaching/w18_4585_icrypto/w18_cs4585_pqc.pdf){:target="_blank"} 11.2M] |_Cryptography and Cybersecurity in the Quantum Era_ by Michele Mosca [[Video](https://www.youtube.com/watch?v=vipU_-QGoOg&feature=youtu.be&list=PLUz_4vZOI0H0nfczvYk2C_UbE_BMs8cpY){:target="_blank"}] <br> _Personal view on post-quantum cryptography_ by FS [Slides [PDF]({{base}}/files/talks/201611_fspqcasia.pdf){:target="_blank"}] [[Video](https://www.youtube.com/watch?v=n39-FOmNh5g){:target="_blank"}]|
||TR,03/15| Review HW4,Quiz4,PE ||
||T,03/20 | **Final Exam**: 17:30-19:20 @ FAB 10 | Practice Exam [PDF]({{base}}/teaching/w18_4585_icrypto/w18_cs4585_pe.pdf){:target="_blank"}|
{:.mbtablestylef}

## Homework 
* [**HW 1** [latex]({{base}}/teaching/w18_4585_icrypto/w18_cs4585_hw1.tex){:target="_blank"} [PDF]({{base}}/teaching/w18_4585_icrypto/w18_cs4585_hw1.pdf){:target="_blank"}] out Tuesday Jan. 09, due **Thursday Jan. 18**.

* [**HW 2** [latex]({{base}}/teaching/w18_4585_icrypto/w18_cs4585_hw2.tex){:target="_blank"} [PDF]({{base}}/teaching/w18_4585_icrypto/w18_cs4585_hw2.pdf){:target="_blank"}] out Thursday Jan. 18, due **Thursday Feb. 1**.

* [**HW 3** [latex]({{base}}/teaching/w18_4585_icrypto/w18_cs4585_hw3.tex){:target="_blank"} [PDF]({{base}}/teaching/w18_4585_icrypto/w18_cs4585_hw3.pdf){:target="_blank"}] out Thursday Feb. 1, due **Thursday Feb. 15**. 

* [**HW 4** [latex]({{base}}/teaching/w18_4585_icrypto/w18_cs4585_hw4.tex) [PDF]({{base}}/teaching/w18_4585_icrypto/w18_cs4585_hw4.pdf){:target="_blank"}] out Thursday Feb. 15, due **Thursday Mar. 1**.
