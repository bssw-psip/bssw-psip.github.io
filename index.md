---
layout: default
---

Scientific software teams are typically focused on the creation of a new set of features that will enable the next set of computational experiments. Teams seldom have the time to stop development and focus solely on improving productivity or sustainability. However, teams can incorporate improvements on the way to developing new science capabilities.

The Productivity and Sustainability Improvement Planning (PSIP) process recognizes that productivity and sustainability improvements for scientific software benefit from an incremental, iterative approach.

## Get Started with PSIP

- Visit [RateYourProject](https://rateyourproject.org). This is a self-assessment tool to help identify practices which could be improved.
- [PSIP user manual and practice guides](/practice-guides/). These guides include a PSIP introduction, practice guides, and PSIP examples. 
- Browse the [PTC Catalog](/ptc-catalog/catalog). Progress Tracking Cards (PTCs) contain the goal of the planning activity and a numbered list of outcomes.
- Chat with PSIP team [Gitter](https://gitter.im/bssw-psip/community)

## Recent Activity
<ul>
{% for post in site.posts %}
<div class="post-preview">
    <li>
        <span class="post-title alignable pull-left">
            <a class="post-link underline" href="{{ post.url | prepend: site.baseurl }}">
            {{ post.title }}
            </a>
        </span>
        <span class="post-time alignable pull-right">
            <time>{{ post.date | date: '%B %d, %Y '}}</time>
        </span>
    </li>
    <div style="clear:both"></div>
</div>
{% endfor %}
</ul>
