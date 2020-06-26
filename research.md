---
title: Research
subtitle: My research projects
layout: page
show_sidebar: false
permalink: /research/
hide_footer: true
---

This is another sample page showing how a page can look without a sidebar. 

To hide the sidebar, set the show_sidebar to false in the page's frontmatter


{% if page.toc %}
    {% assign contentsTitle = page.toc_title | default: 'Contents' %}
    {% include toc.html html=content class='menu-list' h_min=2 h_max=3 contents_title=contentsTitle %}
{% endif %}
<div class="content">
    {{ content }}
</div>