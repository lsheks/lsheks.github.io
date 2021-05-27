---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---


  You can also find my articles on <a href="https://scholar.google.com/citations?user=anBA1CUAAAAJ">my Google Scholar profile</a>.


{% include base_path %}
`int x=1`
{% for post in site.publications reversed %}
  x {% include archive-single.html %}
  `x=x+1`
{% endfor %}
