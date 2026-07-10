---
layout: page
title: Projects
permalink: /projects
---

I enjoy building things.

At the moment I'm interested in programming languages, compilers, AI systems & infrastructure, & just re-building interesting tech from scratch.

<div class="projects-grid">
{% assign sorted = site.data.projects | sort: 'order' %}
{% for p in sorted %}
	{% include project-card.html project=p %}
{% endfor %}
</div>