---
permalink: /
title: "About me"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<br />
　　I am currently an Associate Professor at the Department of Computer Science, Jinan University, Guangzhou, China. I received my B.S. and Ph.D. degrees in the School of Software Engineering from South China University of Technology, China, in 2013 and 2020, respectively, advised by [Prof. Qingyao Wu](https://scholar.google.com.hk/citations?user=n6e_2IgAAAAJ&hl=zh-CN). I worked as a Postdoctoral Research Fellow with the Department of Mathematics, The University of Hong Kong, from 2020 to 2021, advised by [Prof. Michael K. Ng](https://www.math.hkbu.edu.hk/~mng/). My current research interests include transfer learning, hypergraph learning, and their applications in recommendation systems and brain-computer interactions.  


Selected Publications
----------
\[1\]. **Hanrui Wu**, Andy Yip, Jinyi Long, Jia Zhang, Michael K. Ng. Simplicial Complex Neural Networks. IEEE Transactions on Pattern Analysis and Machine Intelligence (**TPAMI**), 2024, 46(1), 561-575.  
\[2\]. **Hanrui Wu**, Yuguang Yan, Michael K. Ng. Hypergraph collaborative network on vertices and hyperedges. IEEE Transactions on Pattern Analysis and Machine Intelligence (**TPAMI**), 2023, 45(3), 3245-3258.  

<div>
  <table>
  {% for post in site.conferences_main reversed %}
    <tr>{% include publication.html %}</tr>
  {% endfor %}
  </table>
  <a href="/conferences/">
    <button class="btn btn--readmore">Read more <font size="1">>></font></button>
  </a>
</div>

<!-- <div margin-bottom:100px>
  <a href="/conferences/">
    <button class="btn btn--readmore">Read more <font size="1">>></font></button>
  </a>
</div>  -->


Journals
----------
<div>
  <table>
  {% for post in site.journals_main reversed %}
    <tr>{% include publication.html %}</tr>
  {% endfor %}
  </table>
   <a href="/journals/">
    <button class="btn btn--readmore">Read more <font size="1">>></font></button>
  </a>
</div>

<!-- <div margin-bottom:100px>
  <a href="/journals/">
    <button class="btn btn--readmore">Read more <font size="1">>></font></button>
  </a>
</div>  -->


Preprint Paper
----------
<div>
  <table>
  {% for post in site.preprints reversed %}
    <tr>{% include publication.html %}</tr>
  {% endfor %}
  </table>
</div>

