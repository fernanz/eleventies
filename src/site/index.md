---
title: SinNombre
subtitle: Sitio de Fernando Mayorga para compartir historias, mitos, arte y curiosidades del mundo antiguo.
layout: layouts/base.njk
---


## En este mes

Datos obtenidos de almanaques y medios digitales:

- [Eleventy](https://11ty.io) with a skeleton site
- A date format filter for Nunjucks based on [Luxon](https://moment.github.io/luxon)
- A tiny CSS pipeline with PostCSS
- A tiny inline JS pipeline. (<a href="#" class="btn-log">Test a console.log message</a>)
- JS [search index](/search.json) generator
- [Netlify Dev](https://www.netlify.com/products/dev) for testing [Netlify redirects](https://netlify.com/docs/redirects/)
- Serverless (FaaS) development pipeline with [Netlify Dev](https://www.netlify.com/products/dev) and [Netlify Functions](https://www.netlify.com/products/functions)

| Item              | In Stock 	| Price |
| :---------------- | :------  	| :---- |
| Python Hat        |   True   	| 23.99 |
| SQL Hat           |   True   	| 23.99 |
| Codecademy Tee    |  False   	| 19.99 |
| Codecademy Hoodie |  False   	| 42.99 |

## Recientes artículos

Otra vez en línea, escribiendo para aprender.

<ul class="listing">
{%- for page in collections.post | reverse -%}
  <li>
    <a class="ptsans" href="{{ page.url }}">{{ page.data.title }}</a> -
    <time datetime="{{ page.date }}">{{ page.date | dateDisplay("LLLL d, y") }}</time>
  </li>
  <p class="descriptor">{{ page.data.description }}</p>
{%- endfor -%}
</ul>

<div class="full-width">
<img class="wide" src="https://res.cloudinary.com/magnvs/image/upload/v1569034596/wzsgteeuryfsesmxjcig.png"/>
</div>

## Sitios recomendados

- [Node and NPM](https://nodejs.org/)

## Para leer

A serverless functions pipeline is included via Netlify Dev. By running `netlify dev` you'll be able to execute any of your serverless functions directly like this:

- [/.netlify/functions/hello](/.netlify/functions/hello)
- [/.netlify/functions/fetch-joke](/.netlify/functions/fetch-joke)





