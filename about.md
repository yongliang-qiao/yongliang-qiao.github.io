---
permalink: /
title: ""
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<span id="Biography" class="section-subheading">Biography</span>
<!-- ====== -->

Yongliang Qiao (Senior Member, IEEE) is a Professor and Ph.D. Supervisor at the [College of Biological and Agricultural Engineering, Jilin University](https://cbae.jlu.edu.cn/info/1130/8619.htm), China. He previously worked at the Australian Institute for Machine Learning (AIML), The University of Adelaide, and the Australian Centre for Field Robotics (ACFR), The University of Sydney. He received his Ph.D. degree from the University of Burgundy-Franche-Comté, France, in 2017. His research focuses on agricultural robotics, autonomous field operations, intelligent perception and multimodal fusion, and AI-based decision-making and control for smart agricultural machinery. He chairs the IEEE RAS Technical Committee on Agricultural Robotics and Automation and serves as an Associate Editor for *Computers and Electronics in Agriculture* and *Frontiers in Plant Science*.

{% include education.html %}

<span id="News" class="section-subheading">News</span>
{% include News.html %}

<span id="Publications" class="section-subheading">Publications</span>
  <ul>
  {% assign recent_publications = site.publications | where: "recent", true | sort: "date" | reverse %}
  {% for post in recent_publications %}
    {% include archive-single-cv.html %}
  {% endfor %}
  {% for post in site.publications reversed %}
    {% unless post.recent or post.legacy_duplicate %}
      {% include archive-single-cv.html %}
    {% endunless %}
  {% endfor %}
  </ul>

<span id="Talks" class="section-subheading">Talks and presentations</span>

  <ul>
  {% for post in site.talks reversed %}
    {% include archive-single-talk.html %}
  {% endfor %}
  </ul>


<span id="Patent" class="section-subheading">Patent</span>
  <ul>
  {% for post in site.patent reversed %}
    {% include archive-single-patent.html %}
  {% endfor %}
  </ul>

<span id="Honour" class="section-subheading">Honour</span>
  <ul>
  {% for post in site.honour reversed %}
    {% include archive-single-honour.html %}
  {% endfor %}
  </ul>

<span id="Services"></span>
  {% include service.html %}

<span id="Contact" class="section-subheading"></span>
  {% include Contact.html %}


<!-- Talks
======
  <ul>
  {% for post in site.talks %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}
  </ul>


Teaching
======
  <ul>
  {% for post in site.teaching %}
    {% include archive-single-cv.html %}
  {% endfor %}
  </ul>


Service and leadership
======
* Currently signed in to 43 different slack teams -->

<!-- 个人Github信息小卡片 -->
<!-- ![Christmas's GitHub stats](https://github-readme-stats.vercel.app/api?username=Shunli-W&show_icons=true&theme=tokyonight) -->

<!-- 个人主页各个国家的访问人数 -->
<!-- <a href="https://flagcounter.me/details/doX"><img src="https://flagcounter.me/doX/" alt="Flag Counter"></a> -->

<!-- 主页访问人数 -->
<!-- ![Visitor Count](https://profile-counter.glitch.me/qiao19981314/count.svg)
![Visitor Count](https://komarev.com/ghpvc/?username=qiao19981314&label=PROFILE+VIEWS) -->
