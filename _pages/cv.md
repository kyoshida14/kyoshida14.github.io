---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

<body>
    <iframe src="/files/Yoshida_CV.pdf" width="100%" height="700px" marginwidth="0">
    </iframe>
     <i>Updated on September 23, 2025</i> 
</body>

{% for post in site.CV %}
  {% include archive-single.html %}
{% endfor %}
