---
layout: page
title: Home
excerpt: "Academic homepage of Fang Song"
modified: 
logo: true
---

--- 

I am an Assistant Professor in the [Computer Science
Department](http://www.pdx.edu/computer-science/) at the [Portland
State University](http://www.pdx.edu/). During 2013 to 2016, I was a
postdoctoral fellow at the [Institute for Quantum
Computing](http://iqc.uwaterloo.ca) and the [Department of
Combinatorics and
Optimization](http://math.uwaterloo.ca/combinatorics-and-optimization/)
at the [University of Waterloo](http://uwaterloo.ca). I completed my
PhD in 2013 in [Computer Science and
Engineering](http://www.cse.psu.edu/) at the [Pennsylvania State
University](http://www.psu.edu), under the supervision of Prof. [Sean
Hallgren](http://www.cse.psu.edu/~hallgren). Prior to that, I received
my bachelor's degree from [University of Science & Technology of
China](http://en.ustc.edu.cn/) in 2008.

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

*  <2021-10-04 Mon> Our department has multiple faculty positions available this year, and **Theory** is a focus area. See details [here](https://www.pdx.edu/computer-science/open-faculty-positions){:target="_blank"}, and send in your strong applications!
*  <2021-02-22 Mon> I have a postdoc position available. Find out more [here]({{base}}/files/docs/recruit_fangsong.pdf){:target="_blank"}. 
* Read [more]({{base}}/news/) ...



