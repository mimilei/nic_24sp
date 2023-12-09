---
layout: home
title: Home
nav_exclude: true
permalink: /:path/
seo:
  type: Course
  name: Nature-Integrated Computing
---
![splash_img](assets/images/nic_sampler.png)
###### _(Left to Right) Living actuators, plant wearables, printed cyanobacteria, electronic beetle backpack, DNA data storage._
<!-- _(Left to Right) Living actuators, plant wearables, printed cyanobacteria, electronic beetle backpack, DNA data storage._ -->
# CSE 5XX: Nature-Integrated Computing
### Approaches for Engineering, Computing, and Interfacing with Living Materials 
#### University of Washington, Winter 2024
{% assign instructors = site.staffers | where: 'role', 'Instructor' %}
{% for staffer in instructors %}
{{ staffer }}
{% endfor %}

{% assign teaching_assistants = site.staffers | where: 'role', 'Teaching Assistant' %}
{% assign num_teaching_assistants = teaching_assistants | size %}
{% if num_teaching_assistants != 0 %}
{% for staffer in teaching_assistants %}
{{ staffer }}
{% endfor %}
{% endif %}

## Schedule
{% for module in site.modules %}
{{ module }}
{% endfor %}