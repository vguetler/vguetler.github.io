---
title: CV
#subtitle: 
layout: page
show_sidebar: false #show sidebar to true otherwise
permalink: /cv/
hide_footer: true
---


<p><strong>Share</strong></p>
<div class="buttons {% if include.centered %} is-centered {% endif %}">
    <a class="button is-medium is-facebook"
       onclick="window.open('https://www.facebook.com/share.php?u={{ site.url }}{{ page.url | prepend: site.baseurl }}');">
        <span class="icon"><i class="fab fa-facebook fa-lg"></i></span>
    </a>
    <a class="button is-medium is-twitter"
       onclick="window.open('https://twitter.com/intent/tweet?text={{ site.url }}{{ page.url | prepend: site.baseurl }}');">
        <span class="icon"><i class="fab fa-twitter fa-lg"></i></span>
    </a>
    <a class="button is-medium is-linkedin"
       onclick="window.open('https://www.linkedin.com/shareArticle?mini=true&url={{ site.url }}{{ page.url | prepend: site.baseurl }}&title={{ page.title | url_encode }}&summary=&source=');">
        <span class="icon"><i class="fab fa-linkedin fa-lg"></i></span>
    </a>
    <a class="button is-medium is-reddit"
       onclick="window.open('https://reddit.com/submit?url={{ site.url }}{{ page.url | prepend: site.baseurl }}');">
        <span class="icon"><i class="fab fa-reddit fa-lg"></i></span>
    </a>
</div>









This is another sample page showing how a page can look without a sidebar. 

To hide the sidebar, set the show_sidebar to false in the page's frontmatter

```yml
title: Page without sidebar
subtitle: Demo page without the sidebar
layout: page
show_sidebar: false
```