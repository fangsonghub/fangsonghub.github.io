---
layout: course
title: (Winter 2022) CS 485/585 - Intro to Cryptography
courseid: w22 485/585
subtitle: Schedule (subject to change)
desc: Schedule
permalink: /teaching/w22_4585_icrypto/schedule/
modified: <2022-12-13 Mon> 
---

{% comment %}
* Table of Contents
{:toc}
* Zoom link for [office hours](), F 10 - 11am and by appointment.
{% endcomment %}

## General guideline
* [Zoom link]() for joining lectures remotely, TR 14:00 - 15:50. 

## Schedule (subject to change)

| Week | Date  | Topic | Reading & Note |
|:-----:| :---------: |:----------:|:-----:|
|1| T,01/04 | Syllabus, intro, Probability review | **KL** 1,A.1-A.3 <br> Trevisan's Note on probability [PDF](http://theory.stanford.edu/~trevisan/cs276/notesprob.pdf){:target="_blank"} |
||R,01/06 | Perfect secrecy, one-time pad, limits | **KL** 2.1-2.3 |
|2|T,01/11| Computational secrecy, stream ciphers <br> pseudorandom generators, proof by reduction | **KL** 3.1 - 3.3 |
||R,01/13| Block ciphers <br> pseudorandom functions / permutations | **KL** 3.5,3.6,6.2 |
|3|T,01/18| Chosen-Plaintext-Attacks | **KL** 3.4,3.5 <br> Supplement: [BS] Chapter 5 |
||R,01/20 |  | **KL** |
|4|T,01/25 |  | **KL** |
||R,01/27 |  | **KL** |
|5|T,02/01|  | **KL** |
||R,02/03 |  | **KL** |
|6|T,02/08|  | **KL** |
||R,02/10 |  | **KL** |
|7|T,02/15|  | **KL** |
||R,02/17 |  | **KL** |
|8|T,02/22|  | **KL** |
||R,02/24 |  | **KL** |
|9|T,03/01|  | **KL** |
||R,03/03 |  | **KL** |
|10|T,03/08|  | **KL** |
||R,03/10 |  | **KL** |
{:.mbtablestylef}
{% comment %}
|3|T,01/23| Chosen-Plaintext-Attacks | **KL** 3.4,3.5 <br> Supplement: [BS] Chapter 5 |
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
{% endcomment %}


