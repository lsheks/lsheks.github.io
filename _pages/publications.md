---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---


  You can also find my articles on <a href="https://scholar.google.com/citations?user=anBA1CUAAAAJ">my Google Scholar profile</a>.


<ol reversed>{% include base_path %}
{% for post in site.publications reversed %}
   {% include archive-single.html %}
{% endfor %}</ol>
