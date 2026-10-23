---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

<!-- {% if author.googlescholar %}
  You can also find my articles on <u><a href="https://scholar.google.it/citations?user=xlV8QE0AAAAJ&hl=en">my Google Scholar profile</a>.</u>
{% endif %} -->

<!-- {% include base_path %} -->

{% assign recent_publications = site.publications | where: "recent", true | sort: "date" | reverse %}
{% for post in recent_publications %}
  {% include archive-single.html %}
{% endfor %}
{% for post in site.publications reversed %}
  {% unless post.recent or post.legacy_duplicate %}
    {% include archive-single.html %}
  {% endunless %}
{% endfor %}

<!-- 该页面没有用到 -->