---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% include base_path %}
**You can also find my articles on my Google Scholar profile**

[**Google Scholar**](https://scholar.google.com/citations?user=UtkbGQcAAAAJ&hl=en)

{% for post in site.publications reversed %}

    {% include archive-single.html %}

{% endfor %}
