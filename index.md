---
layout: default
---

Scientific software teams are typically focused on the creation of a new set of features that will enable the next set of computational experiments. Teams seldom have the time to stop development and focus solely on improving productivity or sustainability. However, teams can incorporate improvements on the way to developing new science capabilities.

The Productivity and Sustainability Improvement Planning (PSIP) process recognizes that productivity and sustainability improvements for scientific software benefit from an incremental, iterative approach.

An ideal place to start learning about PSIP in the PSIP repo would be to start at the online [PSIP user manual/practice guides](/practice-guides/). These guides include a PSIP introduction, practice guides, and PSIP examples. A critical part of a PSIP progress is a Progress Tracking Card (PTC), which contains the goal of the planning activity and a step-by-step list of activities or outcomes to achieve the goal. An invaluable collection of PTC cards can be found in the [PTC Catalog](/ptc-catalog/).

## Recent Activity
{% for post in site.posts %}
<div class="post-preview">
<span class="post-title alignable pull-left">
<a class="post-link underline" href="{{ post.url | prepend: site.baseurl }}">
{{ post.title }}
</a>
</span>
<span class="post-time alignable pull-right">
<time>{{ post.date | date: '%B %d, %Y '}}</time>
</span>
<div style="clear:both"></div>
</div>
{% endfor %}
