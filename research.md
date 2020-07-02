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

<p><strong>Find me at:</strong></p>
<a href="https://twitter.com/Vivfiona">
            <img src="img/Twitter_Social_Icon.png" alt="twitter icon">
        </a>
        <a href="https://www.linkedin.com/in/vivianguetler/">
            <img src="img/In_icon.png" alt="linkedin icon">
        </a>
        <a href="https://github.com/vguetler">
            <img src="img/GitHub_Mark.png" alt="Github icon">
        </a>
        <a href="https://codepen.io/vguetler/">
            <img src="img/Codepen_icon.png" alt="Codepen icon">
        </a>
        <a href="https://scholar.google.com/citations?hl=en&user=0G8LgsYAAAAJ&view_op=list_works&authuser=1&gmla=AJsN-F4inPXhVAoqjhbLADKcJZ0C6FCbSCyDNQ5ARO_g85PmDg8C_cxDhNn2E1yzB8souySN8xp1zALUKyo1FCkYIISa-iQ9vA">
            <img src="https://img.icons8.com/material-sharp/24/000000/google-scholar.png"/>
        </a>
<div itemscope itemtype="https://schema.org/Person"><a itemprop="sameAs" content="https://orcid.org/0000-0001-5256-0104" href="https://orcid.org/0000-0001-5256-0104" target="orcid.widget" rel="me noopener noreferrer" style="vertical-align:top;"><img src="https://orcid.org/sites/default/files/images/orcid_16x16.png" style="width:1em;margin-right:.5em;" alt="ORCID iD icon">https://orcid.org/0000-0001-5256-0104</a></div>





{% if page.toc %}
    {% assign contentsTitle = page.toc_title | default: 'Contents' %}
    {% include toc.html html=content class='menu-list' h_min=2 h_max=3 contents_title=contentsTitle %}
{% endif %}
<div class="content">
    {{ content }}
</div>