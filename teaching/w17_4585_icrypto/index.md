---
layout: course
title: (Winter 2017) CS 485/585 - Intro to Cryptography
courseid: w17 485/585
desc: w17 485/585
permalink: /teaching/w17_4585_icrypto/
modified: <2017-03-08 Wed>
---
*  **Syllabus**: [PDF]({{base}}/teaching/w17_4585_icrypto/syllabus.pdf){:target="_blank"}, and more on the [Administratives]({{base}}/teaching/w17_4585_icrypto/admin/) page.
*  **Instructor**: [Fang Song]({{base}}/) @ FAB 120-07. Email: fsong "AT" pdx.edu.
*  **Lectures**: Tu/Th 2:00 - 3:50 pm @ Fourth Ave Building 47.
*  **Office hours**: Tu/W 4 - 5pm, or by appointment. 
*  **Required Text**: [Introduction to Modern
Cryptography](http://www.cs.umd.edu/~jkatz/imc.html){:target="_blank"}
(2nd edition) by [Jonathan
Katz](http://www.cs.umd.edu/~jkatz){:target="_blank"} and [Yehuda
Lindell](http://u.cs.biu.ac.il/~lindell/){:target="_blank"}.  Chapman
and Hall/CRC Press, Nov 2014.
* A **resource** [page]({{base}}/teaching/w17_4585_icrypto/resource/) with useful materials related to the course. 

## Announcement
*  <2017-03-08 Wed> HW 3 & Quiz 4 solutions available on D2L.
*  <2017-02-27 Mon> Quiz 2&3 solutions available on D2L. 
*  <2017-02-21 Thu> HW 4 Problem 4a) typo. Updated the PDF file on webpage. 
*  <2017-02-07 Tue> Quiz 1 solution posted on D2L. HW 3 out.
*  <2017-01-24 Tue> Homework 2 posted. 
*  <2017-01-13 Fri> Jan. 12 lecture cancelled. Schedule, HW1 updated.
*  <2017-01-10 Tue> Slides in Lecture 1, HW1 posted. 
*  <2017-01-04 Wed> Course page up and running! Check it out~ 

## Schedule (subject to change)

<!--
\[KL\]: Katz-Lindell [Introduction to Modern
Cryptography](http://www.cs.umd.edu/~jkatz/imc.html){:target="_blank"} 

\[BS\]: Boneh-Shoup [A Graduate Course on Applied Cryptography](https://crypto.stanford.edu/~dabo/cryptobook/){:target="_blank"}.
-->

<!--
| Date  | Topic | Homework and Reading |
| :---------: |:----------:|:-----:|
| Tue Jan. 10  | Syllabus, intro, math background <br>Perfect secrecy, one-time pad | <br>Homework 1 out [PDF]() (due Tuesday, Jan. 24)  |
|Thu Jan. 12 |Limits of perfect secrecy <br> Private-key crypto |Reading:  |
|<s>Tue Jan. 17</s>| Cancelled due to [QIP'17](https://www.stationq.com/qip-2017/){:target="_blank"}||
|Thu Jan. 19|Quiz <br> Pseudorandom generators and stream ciphers <br> proof by reduction| |
|Tue Jan. 24|CPA, pseudorandom functions and block ciphers <br> CCA | |
|Thu Jan. 26| Message authentication | |
|Tue Jan. 31| MAC continued | |
|Thu Feb. 2| Quiz <br> Hash functions, random oracle model| |
|Tue Feb. 7| Hash function applications <br> block ciphers and stream ciphers in practice||
|Thu Feb. 9| Theoretical constructions of private-key primitives ||
|Tue Feb. 14|Public-key revolution, Diffie-Hellman key exchange <br> number theory review||
|Thu Feb. 16|Mid-term||
|Tue Feb. 21|Public-key encryption, CPA, CCA||
|Thu Feb. 23|PKE examples: RSA, Elgamal, etc. ||
|Tue Feb. 28|Theoretical constructions of PKE||
|Thu Mar. 02|Quiz <br>Digital signatures ||
|Tue Mar. 07|Signature cont'd||
|Thu Mar. 09|Zero-knowledge proofs <br> secure multi-party computation||
|Tue Mar. 14|Lattice and fully homomorphic encryption||
|Thu Mar. 16| Quantum computing and effects on cryptography <br> Review for final exam||
|Mon Mar. 20| Final Exam: 10:15am-12:05pm||
{:.mbtablestylef}
-->

| Date  | Topic | Homework and Reading |
| :---------: |:----------:|:-----:|
| Tue Jan. 10  | Syllabus, intro, math background; <br>Perfect secrecy<br> [Intro slides [PDF]({{base}}/teaching/w17_4585_icrypto/lec1_ppt.pdf){:target="_blank"} 3.8M] | **Reading**: [KL] Chapter 1, Sect. 2.1, Appendix A. <br>[**Homework 1** [PDF]({{base}}/teaching/w17_4585_icrypto/w17_cs4585_hw1.pdf){:target="_blank"}] out (due Tuesday, Jan. 24)<br> <i style="color:red;">HW1 updated due to cancellation on Jan. 12</i> |
|<s>Thu Jan. 12</s>| Cancelled due to [SNOW'17](http://www.opb.org/news/article/snowstorm-portland-region-school-closures-traffic/){:target="_blank"} ||
|Fri Jan. 13 | Catch a lecture at <br> [Quantum & crypto day @ Portland](http://www.fangsong.info/activity/w17qpdx/){:target="_blank"} | [Plan B](#mu)|
|<s>Tue Jan. 17</s>| Cancelled due to [QIP'17](https://www.stationq.com/qip-2017/){:target="_blank"}||
|<s>Thu Jan. 19</s>|Cancelled due to [QIP'17](https://www.stationq.com/qip-2017/){:target="_blank"}||
|Tue Jan. 24 |**Quiz 1** <br> One-time pad, limits of perfect secrecy; <br> Computational secrecy <br> [Lec2 draft note: [PDF]({{base}}/teaching/w17_4585_icrypto/lec2_note.pdf){:target="blank"}] | **Reading**: [KL] Sect. 2.2,2.3,3.1,3.2. <br> HW 1 **due**, [**HW 2** [PDF]({{base}}/teaching/w17_4585_icrypto/w17_cs4585_hw2.pdf){:target="_blank"}] out|
|Thu Jan. 26| Stream ciphers, pseudorandom generators <br> [Lec3 draft note: [PDF]({{base}}/teaching/w17_4585_icrypto/lec3_note.pdf){:target="blank"}] |**Reading**: [KL] 3.3,6.1 <br> Supplement: [[BS](https://crypto.stanford.edu/~dabo/cryptobook/){:target="_blank"} V0.3] Chapter 3 |
|Tue Jan. 31| Block ciphers, pseudorandom functions <br> [Lec4 draft note: [PDF]({{base}}/teaching/w17_4585_icrypto/lec4_note.pdf){:target="blank"}] | **Reading**: [KL] 3.5,3.6,6.2 <br> Supplement: [BS] Chapter 4  |
|Thu Feb. 2| CPA <br> **Quiz 2** <br> [Lec5 draft note: [PDF]({{base}}/teaching/w17_4585_icrypto/lec5_note.pdf){:target="_blank"}]|  **Reading**: [KL] 3.4,3.5 <br> Supplement: [BS] Chapter 5 |
|Tue Feb. 7| Message authentication, domain extension <br> [Lec6 draft note: [PDF]({{base}}/teaching/w17_4585_icrypto/lec6_note.pdf){:target="_blank"}]|**Reading**: [KL] 4.1,4.2,4.3,4.4 <br> Supplement: [BS] Chapter 6  <br> HW 2 **due**, [**HW 3** [PDF]({{base}}/teaching/w17_4585_icrypto/w17_cs4585_hw3.pdf){:target="_blank"}] out |
|Thu Feb. 9| Hash functions, random oracle, applications (MAC) <br> [Lec7 draft note: [PDF]({{base}}/teaching/w17_4585_icrypto/lec7_note.pdf){:target="_blank"}]|**Reading**: [KL] Chapter 5, Appendix A.4 <br> Supplement: [BS] Chapter 8|
|Tue Feb. 14|Theoretical constructions of private-key primitives <br> [Lec8 draft note: [PDF]({{base}}/teaching/w17_4585_icrypto/lec8_note.pdf){:target="_blank"}]|**Reading**: [KL] Chapter 7 <br> Supplement: [BS] Chapter 4.5,4.6; [[Gol00](https://www.amazon.com/Foundations-Cryptography-1-Basic-Tools/dp/0521035368){:target="_blank"}] 2.5,3.4,3.7|
|Thu Feb. 16| Private-key crypto Review  <br> **Quiz 3** <br> [Lec9 draft note: [PDF]({{base}}/teaching/w17_4585_icrypto/lec9_note.pdf){:target="_blank"}]||
|Tue Feb. 21|Public-key revolution, Diffie-Hellman <br> Number theory review <br> [Lec10 draft note: [PDF]({{base}}/teaching/w17_4585_icrypto/lec10_note.pdf){:target="_blank"}]| **Reading**: [KL] 8.1,8.2.1,Appendix B1,B2,Chapter 10 <br> Notes on [algebra](https://people.eecs.berkeley.edu/~luca/cs276/notesalgebra.pdf){:target="_blank"} and number theory ([part I](http://www.cs.nyu.edu/courses/spring12/CSCI-GA.3210-001/out/boneh1.pdf){:target="_blank"}, [Part II](http://www.cs.nyu.edu/courses/spring12/CSCI-GA.3210-001/out/boneh2.pdf){:target="_blank"})<br> Fun reading: [History of PKC](#funpkc) <br> HW 3 **due**, [**HW 4** [PDF]({{base}}/teaching/w17_4585_icrypto/w17_cs4585_hw4.pdf){:target="_blank"}] out |
|Thu Feb. 23| Public-key encryption <br> trapdoor permutations <br> [Lec11 draft note: [PDF]({{base}}/teaching/w17_4585_icrypto/lec11_note.pdf){:target="_blank"}]| **Reading**: [KL] 8.2.3,8.2.4,8.3.1,8.3.2; 11.2,11.5.1,11.5.3|
|Tue Feb. 28| PKE from TDPs in RO <br> factoring & RSA, ElGamal <br> Hybrid encryption, CCA <br> [Lec12 draft note: [PDF]({{base}}/teaching/w17_4585_icrypto/lec12_note.pdf){:target="_blank"}]| **Reading**: [KL] 11.4.1,11.5.4, 11.3,3.7,4.5.4,11.2.3 |
|Thu Mar. 02|Digital signatures, Full-domain-hash <br> **Quiz 4**<br>[Lec13 draft note: [PDF]({{base}}/teaching/w17_4585_icrypto/lec13_note.pdf){:target="_blank"}] | **Reading**: [KL] 12.1-12.4 |
|Tue Mar. 07| DL-based signature <br> hash-based signature <br> SSL/TLS | **Reading**: 12.5.2,12.6,12.8 <br> HW 4 **due**, [**HW 5** [PDF]({{base}}/teaching/w17_4585_icrypto/w17_cs4585_hw5.pdf){:target="_blank"}] out|
|Tue Mar. 09|Lattice and fully homomorphic encryption| **Reading**: Notes by Barak <br> [[Lattice](http://www.boazbarak.org/cs127/chap12_lattices.html){:target="_blank"}, [FHE Part I](http://www.boazbarak.org/cs127/chap15_FHE.html){:target="_blank"}, [FHE Part II](http://www.boazbarak.org/cs127/chap16_FHE_part2.html){:target="_blank"}] <br> CACM [article](https://people.csail.mit.edu/vinodv/6892-Fall2013/GentryCACM.pdf){:target="_blank"} by Gentry|
|Thu Mar. 14|Zero-knowledge proofs <br> secure multi-party computation| **Reading**: Trevisan's note on [ZK](https://people.eecs.berkeley.edu/~luca/cs276/lecture24.pdf){:target="_blank"} <br> Barak's note on [SC](http://www.boazbarak.org/cs127/chap17_SFE.html){:target="_blank"}<br> Vadhan's note on [2PC](http://people.seas.harvard.edu/~salil/cs127/fall06/docs/lec19.pdf){:target="_blank"} |
|Thu Mar. 16| Quantum computing and impacts on cryptography <br> Review for final exam|**Reading**: FS's talk at PQC Asia <br> [Slides [PDF]({{base}}/files/talks/201611_fspqcasia.pdf){:target="_blank"}] [[Video](https://www.youtube.com/watch?v=n39-FOmNh5g){:target="_blank"}] <br> NSA's post-quantum [plan](https://www.iad.gov/iad/programs/iad-initiatives/cnsa-suite.cfm){:target="_blank"} <br> HW 5 **due**|
|Mon Mar. 20| **Final Exam**: 10:15am-12:05pm||
{:.mbtablestylef}

## Supplements

### <a name="mu"></a>**Make-up lectures (Week 2)**
*  Attend at least one of the talks
   at
   [Quantum day @ Portland](http://fangsong.info/activity/w17qpdx/),
   January 13, 2017. 
*  (**Plan B**) If you cannot attend any of the talks on Jan. 13,
   please email me in advance. Upon approval, you have the option of
   watching one of the recorded talks below instead.
   *  Public lecture at [Qcrypt 2016](http://2016.qcrypt.net/){:target="_blank"}:
      _Cryptography and Cybersecurity in the Quantum Era_ by Michele
      Mosca. [Video](https://www.youtube.com/watch?v=vipU_-QGoOg&feature=youtu.be&list=PLUz_4vZOI0H0nfczvYk2C_UbE_BMs8cpY){:target="_blank"}.
   *  One of the tutorials at the [PQCrypto 2016 winter school](https://pqcrypto2016.jp/winter/){:target="_blank"}.	  

### <a name="funpkc"></a>**History of PKC (Feb.21 Lecture)**

*  First ten years of PKC by Whit
   Diffie [PDF](http://cr.yp.to/bib/1988/diffie.pdf){:target="_blank"}
*  1974 CS244 Project Proposal by Ralph
   Merkle [HTML](http://www.merkle.com/1974/){:target="_blank"}
*  Story of non-secret encryption at British Intelligence Agency [HTML](http://cryptome.org/jya/ellisdoc.htm){:target="_blank"}    
