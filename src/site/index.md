---
title: Arcanum
subtitle: Sitio de Fernando Mayorga para compartir historias, mitos, arte y literatura del mundo antiguo y no tan antiguo.
layout: layouts/base.njk
---


## Marzo 2024

<div class="intro">

Marzo nos trae un cambio de estación gracias a su equinoccio, en el hemisferio norte marca el inicio de la Primavera, en el sur el Otoño; además, este equinoccio también marca el inicio del calendario andino y, en la tradición religiosa cristiana, este equinoccio sirve para determinar la fecha de la **Pascua de Resurrección** puesto que esta debe celebrarse el domingo posterior a la primera luna llena después del equinoccio (*Concilio de Nicea -año 325-*).  
Este era el primer mes del calendario romano el cual estaba consagrado al dios MARTE, de allí su nombre: **"martius"**; Marte era el protector del pueblo romano, padre de Rómulo y Remo fundadores de Roma. 
</div>

**Data de almanaques y medios digitales:**

- El 8 de Marzo *(este año es viernes)*, al igual que en muchos países, conmemoramos el **"Día Internacional de las Mujeres"**; proclamado en 1977 por la [Asamblea General de la ONU](https://www.un.org/es/observances/womens-day/background), celebra *"[...] la lucha de las mujeres por su participación en la sociedad y su desarrollo íntegro como persona, en pie de igualdad con el hombre."* *[Wikipedia](https://es.wikipedia.org/wiki/D%C3%ADa_Internacional_de_la_Mujer)*
- Con el ocaso del domingo 10 de marzo *(en Ecuador)* se inicia el mes sagrado de **Ramadán** en el mundo islámico, el Ramadán es el noveno mes del calendario lunar islámico, es un tiempo de ayuno, oración y reflexión para la comunidad musulmana. Te recomiendo este artículo de el diario [El Mundo](https://www.elmundo.es/como/2024/02/20/65d49c4ce85ece10628b459c.html) para conocer más sobre el Ramadán 2024.
- El domingo 17 de marzo, en Irlanda y algunas ciudades alrededor del mundo que tienen una gran comunidad irlandesa como Chicago, Boston, New York, Sydney, Vancouver y Buenos Aires celebran el Día de San Patricio o **St. Patrick's Day**. Patricio, misionario cristiano, obispo y Santo Patrono de Irlanda murió el 17 de marzo del 461 d.C. De él se cuenta que expulsó a las serpientes de Irlanda.
- En el **calendario celta**, con la llegada del equinoccio de primavera (para el hemisferio Norte), que este año sucede el miércoles 20 de marzo (03:07 GMT), se celebra el festival solar de **Ostara** en honor *Ostare* diosa germana de la fertilidad, de cuyo nombre/palabra se deriva el término *"Easter"* que para los católicos significa *Pascua*.
- Efectivamente, el equinoccio de marzo es el 20 de marzo (03:07 GMT), sin embargo, para Ecuador y parte de la región Andina (GMT -5) sucederá el día martes 19 de marzo a las 22:07.
- Este año conmemoramos la Pasión, Muerte y Resurrección de Cristo o **Semana Santa** la última semana del mes;  iniciamos el día 24 con el **Domingo de Ramos**, el 29 es **Viernes Santo** y el domingo 31 es la **Pascua de Resurrección**.
- En las tradiciones del hemisferio norte (América y Europa), a la luna llena de febrero se la denomina LUNA DE VIENTO / LUNA DEL CUERVO; algunas culturas nativas de Norte América también la conocen como LUNA DE GUSANO, en referencia a las huellas dejadas por las lombrices que empezaban a salir a la superficie luego del deshielo de la temporada invernal.
- Este marzo tendremos una **luna llena en Libra**, de hecho estaremos presenciando un **eclipse lunar penumbral** (*sutil oscurecimiento en la superficie de la Luna*). Esta será una lunación más intensa de lo acostumbrado, muy propicia para evaluarnos si hemos estado demasiado preocupados por las apariencias en general....
- Se esperan las siguientes fases lunares hora de Ecuador (GMT -5) según [Lunarium](https://www.lunarium.co.uk) :

<br/>  

| Fase lunar              | Fecha 	| Hora |
| :---------------- | :------  	| :---- |
| Menguante        |   Domingo 03.03.2024   	| 10:23 |
| Nueva           |   Domingo 10.03.2024   	| 04:00 |
| Creciente    |  Sábado 16.03.2024   	| 23:10 |
| Llena |  Lunes 25.03.2024   	| 02:00 |  

<br/>  


- Concluyo marzo recordando dos hechos históricos importantes para nuestra nación, el 6 de marzo de 1845 sucedió la **revolución Marcista**, y; el 20 de marzo de 1780 nació don **José Joaquín de Olmedo**, prócer, poeta y estadista guayaquileño.
  

### Revisa los meses anteriores:

{% for page in collections.note %}
  <p><a href="{{ page.url }}"><strong>{{ page.data.title }}</strong></a>
	<small> {{ page.data.excerpt }}</small></p>

{% endfor %}


<br/>  
<div class="ocre-river">
{% for page in collections.article | reverse %}

<div class="cards">
  <h2><a href="{{ page.url }}">{{ page.data.title }}</a></h2>
	<img src=" {{ page.data.image }}"/>
  <p> <time datetime="{{ page.date }}">{{ page.date | dateDisplay("LLLL d, y") }}</time><br/>
{{ page.data.description }} </br><small> {{ page.data.excerpt }}</small></p>

{% endfor %}
</div>
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

  [![Youtube icon](/images/youtube.svg)](https://youtu.be/noyqmW9v8Gw?si=I5DZJxCM_bRPccV_)

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
