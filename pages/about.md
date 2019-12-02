---
layout: page
title: About
permalink: /about/
weight: 3
---

# **About Me**

Hi I'm **{{ site.author.name }}**,<br>
I am a coder, gamer and an aspiring data scientist

<div class="rMow">
{% include about/skills.html title="Programming Skills" source=site.data.programming-skills %}
{% include about/skills.html title="Other Skills" source=site.data.other-skills %}
</div>

<div class="row">
{% include about/timeline.html %}
</div>