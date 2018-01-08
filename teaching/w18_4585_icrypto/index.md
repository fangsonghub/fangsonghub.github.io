---
layout: course
title: (Winter 2018) CS 485/585 - Intro to Cryptography
courseid: w18 485/585
desc: w18 485/585
permalink: /teaching/w18_4585_icrypto/
modified: <2018-01-03 Wed>
---
*  **Syllabus**: [PDF]({{base}}/teaching/w18_4585_icrypto/w18syllabus.pdf){:target="_blank"}, and more on the [ADMINISTRATION]({{base}}/teaching/w18_4585_icrypto/admin/) page.
*  **Lectures**: Tu/Th 16:40 - 18:30 @ Fourth Ave Building 10.
*  **Instructor**: [Fang Song]({{base}}/) (fsong
   "AT" pdx.edu). **Office hours**: Tu/Th 10:30 - 11:30am, or by
   appointment @ FAB 120-07.
*  **Teaching assistant**: Nate Launchbury (njl2 "AT"
   pdx.edu). **Office hours**: TBD
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
*  <2018-01-03 Wed> Course page up and running! Check it out~ 

## Schedule (subject to change)

| Week | Date  | Topic | Reading |
|:-----:| :---------: |:----------:|:-----:|
|1| T,01/09  | Syllabus, intro, review of probability and randomized algorithms <br> [Intro slides [PDF]({{base}}/teaching/w18_4585_icrypto/intro_ppt.pdf){:target="_blank"}] | [KatzLindell] Chapter 1,Appendix A; <br> Notes on [discrete probability](https://people.eecs.berkeley.edu/~luca/cs276/notesprob.pdf){:target="_blank"} by Trevisan|
||TR,01/11 |Perfect secrecy, one-time pad, limits; <br> Computational secrecy <!--<br> [Lec2 draft note: [PDF]({{base}}/teaching/w18_4585_icrypto/lec2_note.pdf){:target="blank"}]--> | [KL] Sect.2.1,2.2,2.3,3.1|
|2|T,01/16| Stream ciphers, pseudorandom generators <br> proof by reduction <!-- <br> [Lec3 draft note: [PDF]({{base}}/teaching/w18_4585_icrypto/lec3_note.pdf){:target="blank"}] --> | [KL] 3.2,3.3,6.1; <br> Supplement: [[BonehShoup v0.4](https://crypto.stanford.edu/~dabo/cryptobook/){:target="_blank"}] Chapter 3 |
||TR,01/18| Block ciphers, pseudorandom functions, pseudorandom permutations <br> Q&A <!--<br> [Lec4 draft note: [PDF]({{base}}/teaching/w18_4585_icrypto/lec4_note.pdf){:target="blank"}]--> | [KL] 3.5,3.6,6.2 <br> Supplement: [BS] Chapter 4|
|3|T,01/23| Chosen-Plaintext-Attacks <br> **Quiz 1** <br> <!--[Lec5 draft note: [PDF]({{base}}/teaching/w18_4585_icrypto/lec5_note.pdf){:target="_blank"}] -->|   [KL] 3.4,3.5 <br> Supplement: [BS] Chapter 5 |
||TR,01/25| MAC 1 <br> <!--[Lec6 draft note: [PDF]({{base}}/teaching/w18_4585_icrypto/lec6_note.pdf){:target="_blank"}] --> | [KL] 4.1,4.2,4.3,4.4 <br> Supplement: [BS] Chapter 6 |
|4|T,01/30| MAC 2 domain extension <br> Review HW1 & Quiz1 <!--<br> [Lec7 draft note: [PDF]({{base}}/teaching/w18_4585_icrypto/lec7_note.pdf){:target="_blank"}]-->| [KL] Chapter 5, Appendix A.4 <br> Supplement: [BS] Chapter 8|
||TR,02/01| Hash functions, random oracle, applications <br> Q&A | |
|5|T,02/06| Theoretical constructions of private-key primitives <br> **Quiz 2** | |
||TR,02/08| PKC evolution ||
|6|T,02/13| PubKey Enc, TDP <br> Review HW2&Quiz2 ||
||TR,02/15| Lattices | |
|7|T,02/20| PKE based on lattices <br> **Quiz 3**||
||TR,02/22| Digital signature 1||
|8|T,02/27| DS 2 <br> Review HW3&Quiz3 ||
||TR,03/01| DS 3 <br> Q&A||
|9|T,03/06|Crypto in practice: SSL/TLS <br> **Quiz 4**||
||TR,03/08| Crypto in practice: real-world security flaws <br> Final review||
|10|T,03/13| selected topics ||
||TR,03/15| Review HW4,Quiz4,PE ||
||T,03/20 | **Final Exam**: 17:30-19:20 @ FAB 10 | Practice Exam [PDF]|
{:.mbtablestylef}
## Homework 
* [**HW 1** [latex]() [PDF]({{base}}/teaching/w18_4585_icrypto/w18_cs4585_hw1.pdf){:target="_blank"}] out Tuesday Jan. 09, due **Thursday Jan. 18**.
* [**HW 2** [latex]() [PDF]({{base}}/teaching/w18_4585_icrypto/w18_cs4585_hw2.pdf){:target="_blank"}] out Thursday Jan. 18, due **Thursday Feb. 1**.
* [**HW 3** [latex]() [PDF]({{base}}/teaching/w18_4585_icrypto/w18_cs4585_hw3.pdf){:target="_blank"}] out Thursday Feb. 1, due **Thursday Feb. 15**. 
* [**HW 4** [latex]() [PDF]({{base}}/teaching/w18_4585_icrypto/w18_cs4585_hw3.pdf){:target="_blank"}] out Thursday Feb. 15, due **Thursday Mar. 1**.

<!--
||Theoretical constructions of private-key primitives <br> [Lec8 draft note: [PDF]({{base}}/teaching/w17_4585_icrypto/lec8_note.pdf){:target="_blank"}]|**Reading**: [KL] Chapter 7 <br> Supplement: [BS] Chapter 4.5,4.6; [[Gol00](https://www.amazon.com/Foundations-Cryptography-1-Basic-Tools/dp/0521035368){:target="_blank"}] 2.5,3.4,3.7|
|Thu Feb. 16| Private-key crypto Review  <br> **Quiz 3** <br> [Lec9 draft note: [PDF]({{base}}/teaching/w17_4585_icrypto/lec9_note.pdf){:target="_blank"}]||
|Tue Feb. 21|Public-key revolution, Diffie-Hellman <br> Number theory review <br> [Lec10 draft note: [PDF]({{base}}/teaching/w17_4585_icrypto/lec10_note.pdf){:target="_blank"}]| **Reading**: [KL] 8.1,8.2.1,Appendix B1,B2,Chapter 10 <br> Notes on [algebra](https://people.eecs.berkeley.edu/~luca/cs276/notesalgebra.pdf){:target="_blank"} and number theory ([part I](http://www.cs.nyu.edu/courses/spring12/CSCI-GA.3210-001/out/boneh1.pdf){:target="_blank"}, [Part II](http://www.cs.nyu.edu/courses/spring12/CSCI-GA.3210-001/out/boneh2.pdf){:target="_blank"})<br> Fun reading: [History of PKC](#funpkc) <br> HW 3 **due**, [**HW 4** [PDF]({{base}}/teaching/w17_4585_icrypto/w17_cs4585_hw4.pdf){:target="_blank"}] out |
|Thu Feb. 23| Public-key encryption <br> trapdoor permutations <br> [Lec11 draft note: [PDF]({{base}}/teaching/w17_4585_icrypto/lec11_note.pdf){:target="_blank"}]| **Reading**: [KL] 8.2.3,8.2.4,8.3.1,8.3.2; 11.2,11.5.1,11.5.3|
|Tue Feb. 28| PKE from TDPs in RO <br> factoring & RSA, ElGamal <br> Hybrid encryption, CCA <br> [Lec12 draft note: [PDF]({{base}}/teaching/w17_4585_icrypto/lec12_note.pdf){:target="_blank"}]| **Reading**: [KL] 11.4.1,11.5.4, 11.3,3.7,4.5.4,11.2.3 |
|Thu Mar. 02|Digital signatures, Full-domain-hash <br> **Quiz 4**<br>[Lec13 draft note: [PDF]({{base}}/teaching/w17_4585_icrypto/lec13_note.pdf){:target="_blank"}] | **Reading**: [KL] 12.1-12.4 |
|Tue Mar. 07| DL-based signature <br> hash-based signature <br> SSL/TLS <br> [Lec14 draft note: [PDF]({{base}}/teaching/w17_4585_icrypto/lec14_note.pdf){:target="_blank"}] | **Reading**: 12.5.2,12.6,12.8 <br> HW 4 **due**, [**HW 5** [PDF]({{base}}/teaching/w17_4585_icrypto/w17_cs4585_hw5.pdf){:target="_blank"}] out|
|Tue Mar. 09|Lattice based crypto <br> fully homomorphic encryption| **Reading**: Notes by Barak <br> [[Lattice](http://www.boazbarak.org/cs127/chap12_lattices.html){:target="_blank"}, [FHE Part I](http://www.boazbarak.org/cs127/chap15_FHE.html){:target="_blank"}, [FHE Part II](http://www.boazbarak.org/cs127/chap16_FHE_part2.html){:target="_blank"}] <br> CACM [article](https://people.csail.mit.edu/vinodv/6892-Fall2013/GentryCACM.pdf){:target="_blank"} by Gentry|
|Thu Mar. 14|Zero-knowledge proofs <br> secure multi-party computation| **Reading**: Trevisan's note on [ZK](https://people.eecs.berkeley.edu/~luca/cs276/lecture24.pdf){:target="_blank"} <br> Barak's note on [SC](http://www.boazbarak.org/cs127/chap17_SFE.html){:target="_blank"}<br> Vadhan's note on [2PC](http://people.seas.harvard.edu/~salil/cs127/fall06/docs/lec19.pdf){:target="_blank"} |
|Thu Mar. 16| Quantum computing and impacts on cryptography <br> Review for final exam|**Reading**: FS's talk at PQC Asia <br> [Slides [PDF]({{base}}/files/talks/201611_fspqcasia.pdf){:target="_blank"}] [[Video](https://www.youtube.com/watch?v=n39-FOmNh5g){:target="_blank"}] <br> NSA's post-quantum [plan](https://www.iad.gov/iad/programs/iad-initiatives/cnsa-suite.cfm){:target="_blank"} <br> HW 5 **due**|
|Mon Mar. 20| **Final Exam**: 10:15am-12:05pm @ FAB 47| Practice exam [PDF]({{base}}/teaching/w17_4585_icrypto/w17_4585_pe.pdf){:target="_blank"} |
{:.mbtablestylef}
-->


