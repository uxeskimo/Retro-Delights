---
title: "News"
description: "News"
---

<h1>News</h1>

<div class="" data-layout="">

 <ul>
  {%- for post in collections.news  -%}
    <li>
      <h3><a href="{{ post.url | url }}">{{ post.data.title }}{{ post.data.author }}</a></h3>
    </li>
  {%- endfor -%}
</ul>

</div>