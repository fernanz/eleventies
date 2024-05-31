---
title: Arcanum
subtitle: Sitio de Fernando Mayorga para compartir historias, mitos, arte y literatura del mundo antiguo y no tan antiguo.
layout: layouts/base.njk
---

## Mayo 2024

<div class="intro">

Se creía que Mayo era muy propicio para los enamoramientos que incluso la mujer menos agraciada encontraba novio, de allí que era popular el refrán español: "En mayo todas las feas se casan".  
<br/>
Este mes toma su nombre de la diosa romana *"Maia"* a quien estaba dedicado; Maia es la personificación del crecimiento de las plantas, por ende diosa de la fertilidad y de la Primavera; además, es interesante notar que desde el 28 de abril, hasta el 3 de mayo los romanos también celebraran -*"los floraria"*- o juegos florales en honor a *"Flora"* la diosa de las flores.  
A partir de la Edad Media, los cristianos empezaron a asociar este mes con la devoción a la Virgen María, y fueron los dominicos y los franciscanos quienes empezaron a fomentar esta tradición en Italia, luego el Papa Pío VII (1800 - 1823) la extendió a toda la Iglesia Católica.

</div>

**Data de almanaques y medios digitales:**

- El 1 de mayo, de acuerdo con la tradición Celta, en el hemisferio Norte se celebra uno de los cuatro festivales del fuego, el que anuncia el verano, el festival del *buen fuego*: **Beltane**. En esta época, los antiguos celtas honraban a *Bel* o *Belenos* cuyo nombre significa *"dios resplandeciente"*; era un dios que traía vitalidad, fuerza y juventud a todo el mundo, en consecuencia también sus rituales estaban relacionados con la fertilidad. 
- El 1 de Mayo es el **Día del trabajo**, en Ecuador se traslada al viernes 3 de mayo, es un feriado no recuperable. Este día se conmemoran las luchas históricas y los logros de la clase trabajadora; su origen está en las protestas de mayo (1886) de los obreros de Chicago por mejores condiciones laborales; curiosamente Estados Unidos y Canadá celebran el "Día del trabajo" el primer lunes de septiembre.
- La fiesta nacional mexicana del **Cinco de Mayo**, también celebrada en Estados Unidos, este año cae en día domingo. México celebra la victoria en la Batalla de Puebla ante la Francia Imperial de Napoleón III.  
- Mayo es el mes dedicado a la Virgen María y todas las madres en gran parte del mundo: España celebra el **"Día de la Madre"** el primer domingo del mes; México, Guatemala, El Salvador y Bélice el 10 de mayo; Francia el último domingo de mayo. Entre los países que celebramos el **Día de la Madre** el SEGUNDO DOMINGO DE MAYO están Japón, Venezuela, Colombia, Uruguay, Perú, Puerto Rico, Honduras, Chile, Estados Unidos y por supuesto Ecuador.  
- El domingo 19 de mayo es **Pentecostés** *(quincuagésimo día después de la Pascua)* importante celebración cristiana que recuerda la venida del Espíritu Santo quien desciende sobre los Apóstoles *(Hechos, Capítulo 2)*.
- En las tradiciones del hemisferio norte (América y Europa), a la luna llena de mayo se la denomina LUNA DE LAS PAREJAS / LUNA DE LAS FLORES gracias al abundante florecimiento de la Primavera en apogeo. Para los pueblos nativos Dakota y Lakota, la luna llena de mayo se llama "planting moon" o luna de la siembra.
- En mayo tendremos una **luna llena en sagitario**, a nivel astrológico se piensa que esta luna invoca nuestro lado más explorador y culto, abre nuestra consciencia y nos ayuda a visualizar el lado más profundo de nuestra existencia.
- Mayo nos trae cinco fases lunares y se esperan las siguientes fases lunares hora de Ecuador (GMT -5) según [Lunarium](https://www.lunarium.co.uk) :

<br/>  

| Fase lunar              | Fecha 	| Hora |
| :---------------- | :------  	| :---- |
| Menguante        |   Miércoles 01.05.2024   	| 06:27 |
| Nueva           |   Martes 07.05.2024   	| 22:21 |
| Creciente    |  Miércoles 15.05.2024   	| 06:47 |
| Llena |  Jueves 23.05.2024   	| 08:52 |  
| Menguante        |   Jueves 30.05.2024   	| 12:12 |  

<br/>  

- El viernes 24 de Mayo de celebramos el triunfo de la **Batalla de Pichincha**, este hecho histórico sucedió en 1822 y sellaría definitivamente la Independencia de nuestra nación de la Corona española, esta fecha es feriado nacional.
- El jueves 30 de mayo, el santoral católico, marca el día de **Juana de Arco, Doncella de Orleans** (1412 - 1431) también conocida como *Jeanne D'Arc; Giovanna d'Arco; Joan of Arc*. Hija de labradores humildes es famosa por salvar a Francia de la desgracia de la invasión extranjera; la tradición cuenta que guiada por visiones, santos y ángeles, Juana llevó a los ejércitos de Francia a la Victoria; fue capturada por los ingleses en Ruan, acusada de brujería, herejía, travestismo y tenencia de armas entre otras cosas, fue sentenciada  a morir quemada en la hoguera.  
  
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

<div id="serra" class="full-width">
<img class="wide" src="https://res.cloudinary.com/magnvs/image/upload/ar_16:9,c_fill,e_sharpen,g_auto,h_375,w_1000/v1711594290/IMG_1620_kjrplp.jpg"/>
</div>

<div class="nakedLink">
<div style="width:50px;display:block;float:left;margin:0;padding-right:15px;">

  [![Youtube icon](/images/youtube-red.svg)](https://youtu.be/ra0L_53uUbY?si=L9Wm-vQFAsykolMM)    

</div>
</div>
<h2 style="margin-top:1.8em;">Richard Serra (1938-2024)</h2>
<div style="clear:both;margin-bottom:2em;">  

El pasado 26 de marzo falleció en su país el escultor norteamericano Richard Serra, era conocido por trabajar esculturas urbanas de grandes dimensiones con acero corten. ¿Qué tan importante fue su obra para el arte de nuestro tiempo? Pues, el escritor *Manfred Schneckenburger*, anotaría al respecto: *"Richard Serra dominó la escultura estadounidense durante tres décadas. Rompió con las convenciones como ningún otro escultor, si bien conservó el lenguaje elemental de la plasticidad en su forma más estricta. Serra es ese bicho raro, es un escultor genuino que sometió paisajes y ciudades enteras a su escultura. Al hacerlo tomó el peso, la masa, la gravedad y su desarrollo hacia la dirección, la secuencia y el horizonte y los tranformò en aspectos escultóricos."*. *Iker Seisdedos* escribe para El Pais una muy buena, concisa y no empalagosa reseña biográfica del escultor: [Muere Richard Serra, escultor del acero y del tiempo](https://elpais.com/cultura/2024-03-27/muere-richard-serra-escultor-del-acero-y-del-tiempo.html).

</div>  

<div class="pearl-river">

## RECOMENDACIÓN DEL MES

<figure>
<img class="fit" src="https://res.cloudinary.com/magnvs/image/upload/v1711657542/IMG_1622_rvdgzp.jpg"/>
</figure>

**Somos estrellas - Una guía moderna de astrología** de *Juliana McCarthy* es una buena opción para aprender a leer tu carta astral, fácil de seguir y para aprender sobre tu signo solar, lunar,  tu signo ascendente y el significado de los aspectos planetarios entre otras nociones básicas de la astrología.  
La versión física del libro la adquirí en la Librería Española, está en USD$ 18.99; si prefieres la digital de Amazon USD$ 9.99 abajo está el link.  

<div class="middle">
<iframe type="text/html" sandbox="allow-scripts allow-same-origin allow-popups" width="336" height="550" frameborder="0" allowfullscreen style="max-width:100%" src="https://read.amazon.com/kp/card?asin=B07PK9WP6Q&preview=inline&linkCode=kpe&ref_=cm_sw_r_kb_dp_G6MJ1B0NCFB3H7MJJMZC&tag=fernanz-20" ></iframe>
</div>
</div>  

<figure>
<img class="fit" src="https://res.cloudinary.com/magnvs/image/upload/v1711656482/IMG_20210518_131436_c8r70x.jpg"/>
<figcaption> Carlos Aurelio Rubira (2021). Detalle del retrato realizado por la artista Hellen Constante para la ciudad de Ambato.</figcaption>
</figure>  


<script data-letterbirduser="fmayorga-uno" src="https://letterbird.co/embed/v1.js"></script>
<div class="fleuron">&#10086;</div>
