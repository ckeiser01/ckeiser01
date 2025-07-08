---
title: About
layout: page
title: About
permalink: /about/
weight: 3
---

# **Overview of Experience**

Hi I am **{{ site.author.name }}**,<br>
Insert information here

<div class="row">
{% include about/skills.html title="Design // Development" source=site.data.Game_Design-skills %}
</div>

<div class="row">
{% include about/skills.html title="Python/Data Skills" source=site.data.data-skills %}
</div>

<div class="row">
{% include about/skills.html title="Programming Languages" source=site.data.other-skills %}
</div>

<div class="row">
{% include about/timeline.html %}
</div>