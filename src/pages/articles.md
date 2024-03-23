---
title: "Articles"
description: "Articles"
---

<h1>Articles</h1>

<div class="" data-layout="">

 <ul>
  {%- for post in collections.article  -%}
    <li>
      <h3><a href="{{ post.url | url }}">{{ post.data.title }}</a></h3>
     
    </li>
  {%- endfor -%}
</ul>

</div>