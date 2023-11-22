---
layout: page
title: Team
permalink: /team/
description: 
nav: true
nav_order: 2
display_categories: [work, fun]
horizontal: false
---

{%- for person in site.people %}
<div class="people">
{% include person_horizontal.html %}
</div>
{% endfor %}