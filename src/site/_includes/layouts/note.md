---
layout: layouts/post.njk
pageClass: notes
templateEngineOverride: njk, md
---

<p class="date">
  Desde mi escritorio en Ambato, el <time datetime="{{ date }}">{{ date | dateDisplay }}</time>
</p>
<main>
  {{ content | safe }}
  <div class="footnote">
    <p>
      Si te es de utilidad este artículo, no olvides citarlo correctamente.
    </p>
  </div>
</main>
