---
title: Arcanum
subtitle: Sitio de Fernando Mayorga para compartir historias, mitos, arte y literatura del mundo antiguo y no tan antiguo.
layout: layouts/base.njk
---

## Agosto 2024

<div class="intro">
En agosto, entre el 10 y el 14, presenciaremos un evento celeste en plenitud: la "Lluvia de las Perseidas" o "Lágrimas de San Lorenzo", es una "lluvia" de estrellas fugaces que "da la impresión" que procede de la constelación de Perseo y se la puede observar a simple vista sin necesidad de un telescopio. Aunque visisble todo el mes en el hemisferio Norte, en Ecuador el mejor sitio para observar este fenómeno es en el Parque Nacional Cotopaxi. Su nombre está relacionado en primer lugar al mito del origen del semidios Perseo, de como su madre Dánae fue fecundada por Zeus transformado en lluvia dorada; luego para los cristianos, este fenómeno representa las lágrimas doradas que brotaron de San Lorenzo durante su terrible martirio en la parrilla.
<br/><br/>
"Sextilis" era el sexto mes del primitivo calendario lunar romano, el cual, a partir del año 8 a.C. pasó a llamarse Augustus "Agosto" en honor al primer emperador de Roma: Cayo Julio César Augusto, también conocido como Octaviano.  
</div>

**Data de almanaques y medios digitales:**

- En el **calendario celta**, el 1 de agosto, señala uno de los cuatro mayores festivales del año: **Lughnasadh** o el festival de Lugh, dios celta de la luz, el fuego y los dones.  El nombre anglosajón de este festival es **Lammas** (*masa de pan*) es tiempo de gratitud por la abundancia de la Madre Tierra. Es el punto intermedio entre el solsticio de verano y el equinoccio de otoño.
- El lunes 5 de agosto, Esmeraldas celebra su fecha de Independencia, es un feriado local. Fue en el año de 1820 cuando los pueblos de Esmeraldas y Río Verde se levantaron contra el dominio hispano, allí destacan los nombres del líder Manuel Víctor Lavayen y del cura Ramón Estupiñán. 
- En nuestro país, agosto, tiene un feriado nacional: Diez de Agosto o el "Primer grito de Independencia", éste feriado obligatorio se traslada al viernes 9.  El Diez de agosto de 1809, un grupo de notables quiteños desconocieron la autoridad de la Corona Española impuesta por Napoleón en la persona de José Bonaparte y formaron una Junta de Gobierno autónoma. La Historia recuerda a personajes tales como Juan Pío Montúfar, Manuela Cañizares y José Cuero y Caicedo. 
- El viernes 16 es el día principal de las fiestas patronales de San Jacinto de Yaguachi (Guayas), la romeria y la visita a la basilica menor del santo están entre las actividades principales.  
- El 19 de agosto (1821) recordamos la Batalla de Cone o Batalla de Yaguachi, uno de los enfrentamientos bélicos previos a la Batalla de Pichincha; tropas de la División Protectora de Quito (independentistas guayaquileños) con refuerzos de tropas grancolombianas y al mando del Gral. Antonio José de Sucre derrotaron a los realistas comandados por el coronel Francisco González. Yaguachí Viejo - Cone, en la actualidad es una parroquia rural del cantón Yaguachi (Guayas). 
- En las tradiciones del hemisferio norte (América y Europa), a la luna llena de agosto se la llama LUNA DE ESTURIÓN / LUNA DE TRIGO, es una luna generosa, es la luna de la cosecha en pleno apogeo, de la época en que abunda el pez esturión especialmente en los Grandes Lagos de Norte América. Esta es la tercera luna llena de cuatro que se esperan en esta estación, de allí que también se la denomina como "Luna azul".
- En agosto tendremos una **superluna llena en acuario**, así como la luna llena de julio trajo el inicio de nuevas revoluciones, ahora es tiempo de romper con las viejas tradiciones y apostar por la innovación.  
- Para julio tenemos las siguientes fases lunares, hora de Ecuador (GMT -5) según [Lunarium](https://www.lunarium.co.uk) :

<br/>  

| Fase lunar              | Fecha 	| Hora |
| :---------------- | :------  	| :---- |
| Nueva           |   Domingo 04.08.2024   	| 06:12 |
| Creciente    |  Lunes 12.08.2024   	| 10:18 |
| Llena |  Lunes 19.08.2024   	| 13:25 |  
| Menguante        |   Lunes 26.08.2024   	| 04:25 |  

<br/>  

- En el santoral católico el recordamos los siguientes: <u>8 de agosto</u>, **Santo Domingo de Guzmán** (1170-1221), fundador de la orden mendicante que lleva su nombre, orden que popularizó el rosario e hizo uso de él para conseguir adeptos.  <u>10 de agosto</u>, **San Lorenzo, Mártir** (?-258), diácono que padeció durante la persecución del emperador romano Valeriano, se dice que el terrible martirio que soportó con heroica fortaleza hizo que varios senadores que lo presenciaron se convirtieran al cristianismo; San Lorenzo fue quemado lentamente sobre una parrilla. <u>18 de agosto</u>, **Santa Elena** (?-329), madre del emperador romano Constantino el Grande, su vida está ligada a la búsqueda y encuentro de la Santa Cruz en Tierra Santa. <u>23 de agosto</u>, **Santa Rosa de Lima** (1586-1617), la primera santa de América, considerada como la creadora de los servicios sociales en el Virreinato del Perú. <u>25 de agosto</u>, **San Luis, Rey** (1214-1270), Rey de Francia que encabezó dos cruzadas hacia Oriente *-1238 y 1267-*. <u>28 de agosto</u>, **San Agustín de Hipona** (354-430), Obispo de Hipona y Doctor de la Iglesia, fundó la orden religiosa que lleva su nombre.

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

En el santoral católico el 25 de julio es el día de Santiago Apóstol, también llamado "el Mayor" fue el hermano de San Juan el Evangelista; Santiago fue uno de los más cercanos a Jesús, impulsivo y de temperamento ardiente se ganó el epíteto de *"Hijo del Trueno"* (Marcos 3:13–17).  

Después de la Ascención de Cristo partió a predicar en Hispania. Allí, estando en Cesaraugusta -actual Zaragoza- en las riberas del Ebro tuvo una visión de la Virgen María, que aún estaba viva, se le apareció de pie sobre un pilar de mármol y le pidió que se construyera allí una iglesia en torno a aquel pilar de mármol; con la ayuda de sus discípulos levantó la iglesia que luego bautizaría como Santa María del Pilar, la tradición cuenta que era el año 40 d.C.

A su regreso a Jerusalén fue apresado y decapitado por orden de Herodes Agripa - Circa 44 d.C. - siendo así, el primero de los apóstoles en ser martirizado. Dos de sus discípulos recogieron su cuerpo y lo llevaron de vuelta a Hispania para sepultarlo, llegando hasta Galicia.

Varios siglos después de perdida la memoria del sitio exacto del entierro del santo, fue en el siglo IX, cuando era obispo de Iría Flavia, Teodomiro cuando se descubrió un sarcófago de mármol que contenía los restos de Santiago y de sus discípulos. Fue allí en el lugar señalado por la estrella al ermitaño Pelagio, en el “campus estellae”, actual Compostela. Allí se construyó el templo que se convertiría en uno de sitios de peregrinación medieval tan importante como Roma y Jerusalén.
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
