---
layout: course
title: (Winter 2017) CS 485/585 - Intro to Cryptography
courseid: w17 485/585
desc: w17 485/585
permalink: /teaching/w17_4585_icrypto/
modified: <2017-01-05 Thu>
---
*  **Syllabus**: [PDF]({{base}}/teaching/w17_4585_icrypto/syllabus.pdf){:target="_blank"}, and more info. on the [Administratives]({{base}}/teaching/w17_4585_icrypto/admin/) page.
*  **Instructor**: [Fang Song]({{base}}/) @ FAB 120-07. Email: fsong"AT"pdx.edu.
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
*  <2017-01-04 Wed> Course page up and running! Check it out~ 


## Schedule (subject to change)

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
| Tue Jan. 10  | Syllabus, intro, math background; <br>Perfect secrecy | **Reading**: [KL] Chapter 1, Sect. 2.1, Appendix A. <br>**Homework 1** out [PDF]({{base}}/teaching/w17_4585_icrypto/w17_cs4585_hw1.pdf){:target="_blank"} (due Tuesday, Jan. 24) |
|Thu Jan. 12 |One-time pad, limits of perfect secrecy; <br> Computational secrecy |**Reading**: [KL] Sect. 2.2,2.3,3.1,3.2.  |
|Friday Jan. 13 | Catch a lecture at <br> [Quantum & crypto day @ Portland](http://www.fangsong.info/activity/w17qpdx/){:target="_blank"} | [Plan B](#mu)|
|<s>Tue Jan. 17</s>| Cancelled due to [QIP'17](https://www.stationq.com/qip-2017/){:target="_blank"}||
|<s>Thu Jan. 19</s>|Cancelled due to [QIP'17](https://www.stationq.com/qip-2017/){:target="_blank"}||
|Tue Jan. 24|Quiz 1 <br> Pseudorandom generators and stream ciphers <br> proof by reduction| HW 1 due, HW 2 out|
|Thu Jan. 26|CPA, pseudorandom functions and block ciphers <br> CCA | |
|Tue Jan. 31| Message authentication | |
|Thu Feb. 2| Quiz 2 <br>MAC continued | |
|Tue Feb. 7| Hash functions, random oracle model| HW 2 due, HW 3 out |
|Thu Feb. 9| Hash function applications <br> block ciphers and stream ciphers in practice||
|Tue Feb. 14|Theoretical constructions of private-key primitives ||
|Thu Feb. 16| Quiz 3 <br> Public-key revolution, Diffie-Hellman key exchange <br> number theory review||
|Tue Feb. 21|Public-key encryption, CPA, CCA| HW 3 due, HW 4 out|
|Thu Feb. 23|PKE examples: RSA, Elgamal, etc. ||
|Tue Feb. 28|Theoretical constructions of PKE||
|Thu Mar. 02| Quiz 4 <br>Digital signatures ||
|Tue Mar. 07|Signature cont'd| HW 4 due, HW 5 out|
|Thu Mar. 09|Zero-knowledge proofs <br> secure multi-party computation||
|Tue Mar. 14|Lattice and fully homomorphic encryption||
|Thu Mar. 16| Quantum computing and effects on cryptography <br> Review for final exam||
|Mon Mar. 20| Final Exam: 10:15am-12:05pm||
{:.mbtablestylef}


## Supplements

### <a name="mu"></a> **Make-up lectures**
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
