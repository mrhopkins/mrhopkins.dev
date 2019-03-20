---
title: "experience"
bg: '#3B84CF'  #defined in _config.yml, can use html color like '#0fbfcf'
color: white   #text color
fa-icon: briefcase
---

{% assign experiences = site.data.experiences %}

{% for experience in experiences %}
<div class="row">
  <div class="small column">
    <h3>
      {{ experience.company }}
      <span class="heading-font-size">{{ experience.job }}</span>
      <span class="heading-font-size">{{ experience.date }}</span>
    </h3>
  </div>
  <div class="big column">
    {{ experience.description | markdownify }}

  </div>
</div>
{% endfor %}
