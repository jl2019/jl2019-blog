---
layout: default
---
<article class="post">

  <header class="post-header">
    <h1 class="post-title">{{ page.title | escape }}</h1>
    {% if page.date %}
    Last Modified: {{ page.date | date: "%b %d, %Y" }}
    {% endif %}
  </header>

  <div class="post-content">
    {{ content }}
  </div>

</article>
