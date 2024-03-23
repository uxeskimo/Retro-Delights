---
title: "Games"
description: "Games"
---

<h1>Games</h1>

<div class="" data-layout="">
 <ul>
  {%- for post in collections.games  -%}
    <li>
      <h3><a href="{{ post.url | url }}">{{ post.data.title }}</a></h3>
     
    </li>
  {%- endfor -%}
</ul>

</div>
