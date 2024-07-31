---
title: Arcanum
subtitle: Sitio de Fernando Mayorga para compartir historias, mitos, arte y literatura del mundo antiguo y no tan antiguo.
layout: layouts/base.njk
---

## Julio 2024

<div class="intro">

Este es el mes dedicado a uno de los santos más populares de la cristiandad desde tiempos medievales; apostol, peregrino y caballero: *Santiago el Mayor*. De perfil legendario jugó un papel importante en el imaginario popular del período de Reconquista hispano a finales del siglo XV, convirtiéndose en el protector de la cristiandad contra los musulmanes e incluso llegando a América con los conquistadores quienes en su honor bautizaron varias de sus fundaciones con su nombre como es el caso de Santiago de Guayaquil, Santiago de Chile, Santiago de Cuba y Santiago de los Caballeros (República Dominicana), entre otras. Santiago es el Patrón de España y en su nombre se creó la orden religiosa y militar que lleva su nombre cuya función, en principio, era la de  proteger a los peregrinos del Camino de Santiago.
<br/><br/>
*"Quintilis"* era el quinto mes del primitivo calendario lunar romano, calendario que fue reformado por Julio César en el año 46 a.C. adaptándolo a los ciclos estacionales producidos por el movimiento solar. Después del asesinato de Julio César (44 a.C.), para honrar su memoria se cambió el nombre de Quintilis por el de Iulius *"Julio"*.
</div>

**Data de almanaques y medios digitales:**

- Cada 26 de julio, inicia el año nuevo según el calendario de los antiguos mayas (Sincronario Maya Galáctico); este año 2024 pasaremos del kin "Mago entonado blanco" al **"Tormenta rítmica azul"**. En consecuencia, cada 25 de julio, en este calendario, da término al año; este es el "Día fuera de tiempo", un día de reflexión y preparación para el nuevo ciclo que inicia al día siguiente.  Más detalles en este artículo del [Clarin](https://www.clarin.com/astrologia/calendario-maya-2024-energias-sincronario-maya-galactico-ano-comienza_0_bzG2Nyfqih.html).  
- El 4 de julio Estados Unidos celebra el **Día de la Independencia** cuya declaración se firmó en 1776.  
- En nuestro país, julio, no tiene feriados nacionales; sin embargo hay una extensa agenda de feriados locales, la mayoría celebran fechas de cantonización o creación. El diario [El Universo](https://www.eluniverso.com/noticias/ecuador/que-dias-son-feriado-en-julio-del-2024-en-ecuador-nota/) recoge las fechas más notadas para Ecuador en este mes.  
- El 24 de julio (1783) se conmemora el natalicio del Gral. Simón Bolívar, militar y político venezolano que logró la independencia de la Corona Española de Venezuela, Colombia, Ecuador, Perú y Bolivia. Creó la Gran Colombia, estado que se desintegró en 1830 el mismo año de su muerte.
- El 25 de julio, Santiago de Guayaquil celebra 489 años de Fundación. Con una extensa [Agenda de actividades](https://www.guayaquil.gob.ec/wp-content/uploads/2024/07/Calendario-de-Actividades-Julio-2024.pdf), la M. I. Municipalidad de Guayaquil hace homenaje todo el mes -fiestas julianas- a la ciudad.  A diferencia de muchas de las ciudades fundadas por los conquistadores hispanos, la fecha exacta en que Guayaquil fue fundada ha sido tema de controversia dándose varias hipótesis y ninguna conclusión aceptada oficialmente; fue así que, en 1929 el Concejo Municipal decidió fijar el 25 de julio de 1535 como fecha de Fundación, además este día coincide con el del santo patrón de la ciudad, el Apóstol Santiago. 
- En las tradiciones del hemisferio norte (América y Europa), a la luna llena de julio se la llama LUNA DE TRUENO / LUNA DE CIERVO,  es la luna de las tormentas de verano, la época en que los ciervos arrojan sus astas para volverlas a crecer más fuertes y renovadas.  
- En julio tendremos una **luna nueva en cáncer** y la **luna llena en capricornio**, período entre lunas que nos invita a salir de nuestra zona de confort; además, para los astrológos este será un mes donde veremos desmoronarse algunas estructuras sociales y económicas, es un mes que traerá el inicio de nuevas revoluciones.  
- Para julio tenemos las siguientes fases lunares, hora de Ecuador (GMT -5) según [Lunarium](https://www.lunarium.co.uk) :

<br/>  

| Fase lunar              | Fecha 	| Hora |
| :---------------- | :------  	| :---- |
| Nueva           |   Viernes 05.07.2024   	| 17:57 |
| Creciente    |  Sábado 13.07.2024   	| 17:48 |
| Llena |  Domingo 21.07.2024   	| 05:17 |  
| Menguante        |   Sábado 27.07.2024   	| 21:51 |  

<br/>  

- En el santoral católico el 25 de julio es el día de Santiago Apóstol, también llamado "el Mayor" fue el hermano de San Juan el Evangelista; Santiago fue uno de los más cercanos a Jesús, impulsivo y de temperamento ardiente se ganó el epíteto de *"Hijo del Trueno"* (Marcos 3:13–17). Después de la Ascención de Cristo partió a predicar en Hispania, a su regreso a Jerusalén fue apresado y decapitado por orden de Herodes Agripa - Circa 44 d.C. - siendo así, el primero de los apóstoles en ser martirizado.

### Revisa los meses anteriores:

{% for page in collections.note %}
  <p><a href="{{ page.url }}"><strong>{{ page.data.title }}</strong></a> &middot; <small> {{ page.data.excerpt }}</small></p>

{% endfor %}


<br/>  
<div class="artic-sky">

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

<div class="peach-sky">
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
<img class="wide" src="https://res.cloudinary.com/magnvs/image/upload/v1722418012/Imagen_HEIF_wx5qqw.heic"/>
</div>

<div class="nakedLink">
<div style="width:50px;display:block;float:left;margin:0;padding-right:15px;">

  [![Youtube icon](/images/youtube-red.svg)](https://youtu.be/aGv5MQwCWO4?si=4Orzu1XLupTHrGFU)    

</div>
</div>
<h2 style="margin-top:1.8em;">Richard Serra (1938-2024)</h2>
<div style="clear:both;margin-bottom:2em;">  

El pasado 26 de marzo falleció en su país el escultor norteamericano Richard Serra, era conocido por trabajar esculturas urbanas de grandes dimensiones con acero corten. ¿Qué tan importante fue su obra para el arte de nuestro tiempo? Pues, el escritor *Manfred Schneckenburger*, anotaría al respecto: *"Richard Serra dominó la escultura estadounidense durante tres décadas. Rompió con las convenciones como ningún otro escultor, si bien conservó el lenguaje elemental de la plasticidad en su forma más estricta. Serra es ese bicho raro, es un escultor genuino que sometió paisajes y ciudades enteras a su escultura. Al hacerlo tomó el peso, la masa, la gravedad y su desarrollo hacia la dirección, la secuencia y el horizonte y los tranformò en aspectos escultóricos."*. *Iker Seisdedos* escribe para El Pais una muy buena, concisa y no empalagosa reseña biográfica del escultor: [Muere Richard Serra, escultor del acero y del tiempo](https://elpais.com/cultura/2024-03-27/muere-richard-serra-escultor-del-acero-y-del-tiempo.html).

</div>  

<div class="purple-river">

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

<div class="no-river">

<script data-letterbirduser="fmayorga-uno" data-showheader="true" src="https://letterbird.co/embed/v1.js"></script>
<div class="fleuron">&#10086;</div>

</div>
