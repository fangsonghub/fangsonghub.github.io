---
layout: page
title: Home
excerpt: "Academic homepage of Fang Song"
modified: 
logo: true
---

--- 
I joined the Department of [Computer Science and Engineering](https://engineering.tamu.edu/cse/index.html) at [Texas A&M University](https://www.tamu.edu/) in Fall 2018. I was an Assistant Professor in the [Computer Science Department](http://www.pdx.edu/computer-science/) at the [Portland State University](http://www.pdx.edu/) since Fall 2016. During 2013 to 2016, I was a postdoctoral fellow at the [Institute for Quantum Computing](http://iqc.uwaterloo.ca) and the [Department of Combinatorics and Optimization](http://math.uwaterloo.ca/combinatorics-and-optimization/) at the [University of Waterloo](http://uwaterloo.ca). I completed my PhD in 2013 in [Computer Science and Engineering](http://www.cse.psu.edu/) at the [Pennsylvania State University](http://www.psu.edu), under the supervision of Prof. [Sean Hallgren](http://www.cse.psu.edu/~hallgren). Prior to that, I received my bachelor's degree from [University of Science & Technology of China](http://en.ustc.edu.cn/) in 2008.

My research interests lie in cryptography, especially
provable-security in the presence of quantum attacks, quantum
algorithms, computational complexity and theoretical computer science
broadly. I'm grateful to the [National Science Foundation](https://www.nsf.gov/){:target="_blank"} for funding my
research.

--- 

## News

{% comment %}
{% assign news = site.documents | where: "title", "news" %}
{{ news.content }}
{{ news.content |strip_html | truncatewords:200 }}
{% assign news = site.pages | where: "title", "News" | first%}
{{ news.excerpt }}
{% endcomment %}

*  <2019-12-21 Sat> I will serve on the program committee of [Crypto
   2020](https://crypto.iacr.org/2020/callforpapers.html){:target="_blank"}. Submit
   your best papers by **February 11 2020**.
*  <2019-08-28 Wed> Slides of the tutorial at the [9th International
   Conference on Quantum Cryptography](http://2019.qcrypt.net/), now
   available under [Research]({{base}}/research/#other-talks) Explore
   **Zero-knowledge proofs** in a quantum world, and solve the open
   questions.
* Read [more]({{base}}/news/) ...



