---
title: "Reviews"
description: "Reviews"

---

<h1>Reviews</h1>

<div class="" data-layout="">

 <ul>
  {%- for post in collections.reviews  -%}
    <li>
      <h3><a href="{{ post.url | url }}">{{ post.data.title }}</a></h3> 
    </li>
  {%- endfor -%}
</ul>

</div>




