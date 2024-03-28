---
title: Arcanum
subtitle: Sitio de Fernando Mayorga para compartir historias, mitos, arte y literatura del mundo antiguo y no tan antiguo.
layout: layouts/base.njk
---

## Abril 2024

<div class="intro">

Es oficial, una nueva temporada de eclipses está en marcha y este mes presenciaremos un eclipse solar total, el anterior fue el 4 de diciembre de 2021 y pudo ser visto sólo desde la Antártida.  
<br/>
Etimológicamente abril viene del vocablo latín "Aprilis", nombre del segundo mes en el antiguo calendario romano; a su vez también existe la teoría que vincula "abril" con la palabra griega *"aphrós"* en referencia a la diosa Afrodita, deidad directamente relacionada con la Primavera. Este mes estaba consagrado a la diosa Afrodita o Venus (para los romanos).

</div>

**Data de almanaques y medios digitales:**

- El lunes 8 de abril tenemos el primer eclipse solar del año, será un **eclipse total** visto desde México, la zona central y noreste de EE.UU. y parte de Canadá; **será parcial** en Hawai, Galápagos, Centroamérica y El Caribe. El eclipse se transmitirá en directo desde el sitio oficial de la NASA en [YouTube](https://www.youtube.com/live/2MJY_ptQW1o?si=gSLYPRVcPlkEJWgs) a las 12h00 tiempo de Ecuador (GMT -5). Este eclipse solar coincide con la Luna Nueva de abril.
- El sábado 13 de abril, en Ecuador, celebramos el **Día del Maestro** en homenaje al gran escritor y pensador Ambateño *Juan Montalvo Fiallos*, nacido en esta fecha en el año 1832.  
- El ocaso del lunes 22 da inicio a la **Pascua Judía** *(Passover)* o celebración de la libertad, esta festividad concluye el martes 30 de abril. El pueblo hebreo conmemora la salida de Egipto hacia la Tierra Prometida y el fin de la esclavitud liderados por Moisés.
- El 25 de abril es el día de **San Marcos Evangelista** autor del segundo evangelio canónico, evangelio escrito entre los años 65 y 75 donde recoge las enseñanzas de Jesús como las contaría San Pedro, de quien Marcos era compañero y discípulo. San Marcos es el santo patrón de Venecia, ciudad donde reposan sus reliquias desde el siglo IX, según cuenta la tradición de esta ciudad.
- En las tradiciones del hemisferio norte (América y Europa), a la luna llena de abril se la denomina LUNA DEL CRECIMIENTO / LUNA DE HIERBA y representa el crecimiento salvaje de la vegetación, los nuevos comienzos que trae la Primavera. Debido a que en esta época del año florece el Flox musgoso *Phlox subulata*, una planta nativa del este de Norteamérica, esta luna también se la conoce como LUNA ROSA.
- En este mes tendremos una **luna llena en escorpio**, se cree que esta luna es muy potente y transformadora a nivel espiritual.
- Se esperan las siguientes fases lunares hora de Ecuador (GMT -5) según [Lunarium](https://www.lunarium.co.uk) :

<br/>  

| Fase lunar              | Fecha 	| Hora |
| :---------------- | :------  	| :---- |
| Menguante        |   Lunes 01.04.2024   	| 22:14 |
| Nueva           |   Lunes 08.04.2024   	| 13:20 |
| Creciente    |  Lunes 15.04.2024   	| 14:12 |
| Llena |  Martes 23.04.2024   	| 18:48 |  

<br/>  

- Concluyo abril recordando un hecho histórico para nuestra nación, el 21 de abril de 1822 sucedió la **Batalla de Tapi** o Batalla de Riobamba; en consecuencia, debido al triunfo de las tropas libertadoras, para esta fecha se conmemora la **Independencia de Riobamba**.

  
### Revisa los meses anteriores:

{% for page in collections.note %}
  <p><a href="{{ page.url }}"><strong>{{ page.data.title }}</strong></a><br/>
	<small> {{ page.data.excerpt }}</small></p>

{% endfor %}


<br/>  
<div class="ocre-river">

<h2>Artículos destacados</h2><p><small>Este es el último año de nuestra vida tal como la conocíamos</small></p>

{% for page in collections.article | reverse %}

<div class="cards">
  <h2><a href="{{ page.url }}">{{ page.data.title }}</a></h2>
	<img src=" {{ page.data.image }}"/>
  <p> <time datetime="{{ page.date }}"><b>{{ page.date | dateDisplay("LLLL d, y") }}</b></time><br/>
{{ page.data.description }} </br><small> {{ page.data.excerpt }}</small></p>
</div>

{% endfor %}
</div>

<div class="meta-river">
<h2><a href="/2024">Artículos anteriores 2024</a></h2><p><small>Otra vez en línea, escribiendo para aprender.</small><p>

<ul class="listing">
{%- for page in collections.post | reverse -%}
  <li>
    <a class="ptsans" href="{{ page.url }}">{{ page.data.title }}</a> -
    <time datetime="{{ page.date }}">{{ page.date | dateDisplay("LLLL d, y") }}</time>
  </li>
  <p class="descriptor">{{ page.data.description }}</p>
{%- endfor -%}
</ul>
</div>


## Guayaquil 1929 por Carlos Endara A.  

<div class="full-width">
<img class="wide" src="https://res.cloudinary.com/magnvs/image/upload/v1569034596/wzsgteeuryfsesmxjcig.png"/>
</div>

<div class="nakedLink">
<div style="width:50px;display:block;float:left;margin:0;">

  [![Youtube icon](/images/youtube-red.svg)](https://youtu.be/noyqmW9v8Gw?si=I5DZJxCM_bRPccV_)

</div>
</div>

<div style="clear:both;margin-bottom:2em;">  

Primera parte de la película filmada por el fotógrafo y artista Carlos Endara Andrade en donde detalla su visita a Guayaquil en 1929, esta es la versión ampliada de la descripción histórica de la ciudad con la contribución de Melvin Hoyos G. La película fue rescatada por la Universidad Andina Simón Bolívar - Sede Ecuador - con el aporte de la M. I. Municipalidad de Guayaquil en el año 2019. La restauración y rescate de la película la realizó el cineasta Álex Schlenker.

</div>  

<iframe allow="autoplay *; encrypted-media *; fullscreen *; clipboard-write" frameborder="0" height="175" style="width:100%;max-width:660px;overflow:hidden;border-radius:10px;" sandbox="allow-forms allow-popups allow-same-origin allow-scripts allow-storage-access-by-user-activation allow-top-navigation-by-user-activation" src="https://embed.podcasts.apple.com/ec/podcast/ecuador-1929-de-carlos-endara/id1477126077?i=1000451314315"></iframe>

<div class="pearl-river">

## RECOMENDACIÓN DEL MES

<figure>
<img class="fit" src="https://res.cloudinary.com/magnvs/image/upload/v1708998841/IMG_20240226_201628_rckbtx.jpg"/>
</figure>

Esto no es publicidad pagada, simplemente me parece justo recomendar un buen producto que tiene un precio razonable y además estamos colaborando con una buena causa. 

Si te gusta un café de acidez ligera, con aroma y sabor achocolatado, deberías probar CAFÉ CAIMÁN - House Blend, el cual dice en su etiqueta: *"... se cultiva en las mismas tierras que el Centro de Rescate San Isidro, un refugio que alberga fauna silvestre rescatada del tráfico y la tenencia ilegal"*.

Pude averiguar que este centro de rescate esta ubicado en el cantón Isidro Ayora de la provincia del Guayas, desafortunadamente no he podido encontrar alguna otra información de ellos mismo en internet, sólo esta nota del diario [Metro de Ecuador](https://www.metroecuador.com.ec/ec/noticias/2020/01/13/guayas-centro-de-rescate-animal-san-isidro-ecuador.html).

<small>El Café Caimán lo encontré en la cafetería El Español, el paquete de 340 g cuesta USD$ 7.00 </small>
</div>  

<figure>
<img src="https://res.cloudinary.com/magnvs/image/upload/v1707487188/IMG_20180710_111505986_ny6glq.jpg"/>
<figcaption> Despidiéndome del Viejo Napo (2019). Museo Municipal de Guayaquil.</figcaption>
</figure>

<div class="fleuron">&#10086;</div>
