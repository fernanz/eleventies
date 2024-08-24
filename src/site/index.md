---
title: Arcanum
subtitle: Sitio de Fernando Mayorga para compartir historias, mitos, arte y literatura del mundo antiguo y no tan antiguo.
layout: layouts/base.njk
---

## Septiembre 2024

<div class="intro">

Este era el séptimo -**"September"**- mes en el primitivo calendario lunar romano, de allí su nombre. Septiembre marca un nuevo cambio de estación por su equinoccio, en el hemisferio se inicia el Otoño, en el sur la Primavera; en los andes es momento de celebrar un nuevo raymi, "Kuya" o "Killa Raymi" la festividad de la Luna, la feminidad y de la siembra. En este mes una gran parte del mundo se prepara para el inicio del año escolar.

</div>

**Data de almanaques y medios digitales:**

- El primer lunes de septiembre Estados Unidos y Canadá celebran el Día del Trabajo *"Labor Day"*, este año cae en el segundo día del mes. Se honra y se celebran la contribución del movimiento laboral.  
- El 14 de septiembre, tanto católicos como ortodoxos celebran la **Exaltación de la Santa Cruz** festividad que honra la cruz en la que Jesús de Nazaret hizo su sacrificio. Hacia el año 320 Santa Elena emperatriz encontró la Vera Cruz en Jerusalén, siglos después en el 614 Cosroes II de Persia invade la ciudad y se lleva la cruz; sin embargo, el emperador Heraclio la recupera y la retorna a Jerusalén con una ceremonia que recorrió la ciudad presidida por él mismo, fue el 14 de septiembre del 628 d.C.
- En el **calendario celta**, con la llegada del equinoccio de Otoño (para el hemisferio Norte), que este mes sucede el domingo 22 (12:43 GMT), se celebra el festival solar de la recogida de la cosecha y la celebración de la abundancia de la Tierra antes de la llegada del Invierno; a esta festividad también la conocen como el Banquete de Avalon *"Feast of Avalon"*. Para algunas religiones paganas, este equinoccio, es la festividad de **Mabon** o "el banquete", el Festival de Dionisos, Cornucopia; para los druidas en cambio era *Alban Elfed* o "La luz del agua".
- El equinoccio de septiembre, para Ecuador y parte de la región Andina (GMT -5) sucederá el mismo día domingo 22 de marzo a las 07:43.
- El jueves 26 de septiembre celebramos el **Día de la Bandera Nacional**. (Decreto del Congreso Nacional, 1955). 
- En las tradiciones del hemisferio norte (América y Europa), a la luna llena de septiembre se la denomina LUNA DE LA COSECHA, es tiempo de la segunda cosecha anual importante para almacenar el alimento para los meses fríos que se aproximan; algunas culturas nativas de Norte América también la conocen como LUNA LLENA DEL MAÍZ, en referencia a que el maíz debe ser cosechado en estas regiones. 
- En este mes tendremos una **luna llena en Piscis**, en esta ocasión habrá un **eclipse lunar parcial** (*una parte del disco lunar esta oscura*). Este eclipse será completamente visible en América del Sur, el Este de Norte América y, el Oeste de Europa y Africa.  
- Se esperan las siguientes fases lunares hora de Ecuador (GMT -5) según [Lunarium](https://www.lunarium.co.uk) :

<br/>  

| Fase lunar              | Fecha 	| Hora |
| :---------------- | :------  	| :---- |
| Nueva           |   Lunes 02.09.2024   	| 20:55 |
| Creciente    |  Miércoles 11.09.2024   	| 01:05 |
| Llena |  Martes 17.09.2024   	| 21:34 |  
| Menguante        |   Martes 24.09.2024   	| 13:49 |

<br/>  

- Concluímos con las siguientes fechas importantes en el santoral católico: <u>16 de septiembre</u>, **San Cipriano, Obispo y Mártir** (?-258), Obispo de Cártago padeció la persecución de los emperadores Valeriano y Galieno muriendo decapitado por su fe; los cristianos le rezan para pedir ayuda ante las adversidades económicas, par deshacer hechizos y trabajos de magia negra. A este santo e le atribuye *"El libro de San Cipriano"* el cual es un grimorio muy controversial. <u>21 de septiembre</u>, **San Mateo Evangelista y Apóstol**, Publicano converso, autor del evangelio que lleva su nombre del cual se dice lo escribió en arameo alredor del año 70 d.C. Después de la muerte de Jesús partió a predicar en Etiopía durante largos años hasta el día en que murió martirizado. <u>29 de septiembre</u>, **San Gabriel Arcángel, San Miguel Arcángel, San Rafael Arcángel** Según la Biblia (Tobias 12, 15; Revelaciones 8, 2) hay 7 Arcángeles que tienen acceso a la presencia del Señor, sin embargo solo da nombre a tres de ellos: **Gabriel** "Fortaleza de Dios", **Miguel** "¡Quién como Dios?" y **Rafael** "Dios sana". San Miguel es "uno de los principales príncipes" (Libro de Daniel 10,13; 10,21; 12,1) y en la Iglesia Católica siempre ha tenido una gran devoción por su poder para liberar de los ataques del demonio.  <u>30 de septiembre</u>, **San Jerónimo** (?-419), Doctor máximo de la Iglesia, presbítero y anacoreta, traductor de la versión oficial de las sagradas Escrituras al latín, patrón de los bibliófilos y traductores. 

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

<div id="santiago" class="full-width">
<img class="wide" src="https://res.cloudinary.com/magnvs/image/upload/v1722418552/IMG_1966_aw6l2e.jpg"/>
</div>

<div class="nakedLink">
<div style="width:50px;display:block;float:left;margin:0;padding-right:15px;">

  [![Youtube icon](/images/youtube-red.svg)](https://youtu.be/aGv5MQwCWO4?si=4Orzu1XLupTHrGFU)    

</div>
</div>
<h2 style="margin-top:1.8em;">Santiago Apostol</h2>
<div style="clear:both;margin-bottom:2em;">  

Uno de los santos más populares de la cristiandad desde tiempos medievales; apostol, peregrino y caballero: *Santiago el Mayor*. De perfil legendario jugó un papel importante en el imaginario popular del período de Reconquista hispano a finales del siglo XV, convirtiéndose en el protector de la cristiandad contra los musulmanes e incluso llegando a América con los conquistadores quienes en su honor bautizaron varias de sus fundaciones con su nombre como es el caso de Santiago de Guayaquil, Santiago de Chile, Santiago de Cuba y Santiago de los Caballeros (República Dominicana), entre otras. Santiago es el Patrón de España y en su nombre se creó la orden religiosa y militar que lleva su nombre cuya función, en principio, era la de  proteger a los peregrinos del Camino de Santiago.  

En el santoral católico el 25 de julio es el día de Santiago Apóstol, Santiago también llamado "el Mayor" fue el hermano de San Juan el Evangelista y fue uno de los más cercanos a Jesús; fue impulsivo y de temperamento ardiente que se ganó el epíteto de *"Hijo del Trueno"* (Marcos 3:13–17).  

Después de la Ascención de Cristo partió a predicar en Hispania. Allí, estando en Cesaraugusta -actual Zaragoza- en las riberas del Ebro tuvo una visión de la Virgen María, que aún estaba viva, se le apareció de pie sobre un pilar de mármol y le pidió que se construyera allí una iglesia en torno a aquel pilar de mármol; con la ayuda de sus discípulos levantó la iglesia que luego bautizaría como Santa María del Pilar, la tradición cuenta que era el año 40 d.C.

A su regreso a Jerusalén fue apresado y decapitado por orden de Herodes Agripa - Circa 44 d.C. - siendo así, el primero de los apóstoles en ser martirizado. Dos de sus discípulos recogieron su cuerpo y lo llevaron de vuelta a Hispania para sepultarlo, llegando hasta Galicia.

Varios siglos después de perdida la memoria del sitio exacto del entierro del santo, fue en el siglo IX, cuando era obispo de Iría Flavia, Teodomiro que se descubrió un sarcófago de mármol que contenía los restos de Santiago y de sus discípulos. Fue allí en el lugar señalado por la estrella al ermitaño Pelagio, en el “campus estellae”, actual Compostela. Allí se construyó el templo que se convertiría en uno de sitios de peregrinación medieval tan importante como Roma y Jerusalén.  

En Santiago de Compostela se celebra el año jubilar cada vez que el 25 de julio coincide en domingo. El próximo año jubilar Compostelano será el 2027.
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
<img class="fit" src="//res.cloudinary.com/magnvs/image/upload/IMG_20240726_172141_kllzl2.jpg"/>
<figcaption> Esquina de las calles Rocafuerte y Rafael Morales, parque central del Cantón Pujilí, prov. de Cotopaxi (2024).</figcaption>
</figure>

<div class="no-river">

<script data-letterbirduser="fmayorga-uno" data-showheader="true" src="https://letterbird.co/embed/v1.js"></script>
<div class="fleuron">&#10086;</div>

</div>
