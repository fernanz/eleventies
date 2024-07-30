---
title: picker
layout: layouts/about.njk
subtitle: Uso privado.
---


<ul class="listing">
{%- for page in collections.post | reverse -%}
  <li>
    <a class="ptsans" href="{{ page.url }}">{{ page.data.title }}</a> -
    <time datetime="{{ page.date }}">{{ page.date | dateDisplay("LLLL d, y") }}</time>
  </li>
  <p class="descriptor">{{ page.data.description }}</p>
{%- endfor -%}
</ul>