---
title: "education"
bg: '#635FD4'
color: white
fa-icon: graduation-cap
style: center
---

### University of Colorado Boulder

*Bachelor of Science, Business Administration; Marketing*

<br>

### LeaderQuest

*IT Certification, MCITP, MCSE, ITIL, and A+*

<!--
{% assign graduations = site.data.graduations %}

{% for graduation in graduations %}
<div class="row">
  <div class="half column title">

    <h2>
      {{ graduation.title }}
    </h2>
      {{ graduation.date }}
       {% if graduation.concluded %}
        -  {{ graduation.concluded }}
      {% endif %}    

      {% if graduation.lock %}
      <span class="lock" title="locked">-  {{ graduation.lock }}</span>
        
      {% endif %}    

  </div>

  <div class="half column desc">
    <h4>{{ graduation.institution }}</h4>

    {% if graduation.description %}
      {{ graduation.description | markdownify }}
    {% endif %}    
  </div>

</div>
{% endfor %}
-->