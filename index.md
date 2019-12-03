---
# You don't need to edit this file, it's empty on purpose.
# Edit theme's home layout instead if you wanna make some changes
# See: https://jekyllrb.com/docs/themes/#overriding-theme-defaults
layout: default
---
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
