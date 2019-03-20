---
title: "certifications"
bg: '#757575'    #defined in _config.yml, can use html color like '#f8f8f8'
color: white  #text color
fa-icon: trophy
---

{% assign certifications = site.data.certifications %}

{% for certification in certifications %}
 * **{{ certification.sponsor }}**: {{ certification.title }}
{% endfor %}
