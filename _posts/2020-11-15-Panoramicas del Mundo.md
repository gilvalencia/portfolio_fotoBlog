---
layout: "post"
title:  "Panorámicas del mundo"
date:   2020-11-15 12:44:54 +0000
avatar: assets/img/simb-color.png
categories: jekyll IGIC
author: "José Antonio Gil Valencia"
permalink: "Portoflio Fotográfico_Panorámicas"
---
<style>
    .tooltip {
    position: relative;
    display: inline-block;
    border-bottom: 1px dotted black;
    }

    .tooltip .tooltiptext {
    visibility: hidden;
    width: 300px;
    background-color: black;
    color: #fff;
    text-align: left;
    border-radius: 6px;
    padding: 10px 10px;

    /* Position the tooltip */
    position: absolute;
    right: 100%;
    z-index: 1;
    }

    .tooltip:hover .tooltiptext {
    visibility: visible;
    }

</style>

<center>
<img src="src/fotosEncabezado_panoramica.jpg">
</center>
<br>
Las <b>fotografías panorámicas</b> son la solución perfecta para situaciones en las que nuestro objetivo <b>no pueda abarcar toda la escena</b> que nos interesa incluir en el encuadre, o en el caso de que la foto por fines estéticos o compositivos necesiten tener un aspecto apaisado.

Muchas cámaras compactas traen incorporado un modo panorámico parecido al de los móviles, que nos ayuda a hacer la foto mediante una guía en la pantalla LCD y nos monta las imágenes automáticamente con mejor o peor resultado.

La mayoría de cámaras para principiantes no cuentan con este tipo de ayuda y aunque la tuviesen, personalmente seguiría utilizando el <b>método tradicional de hacer varias fotografías y unirlas en el ordenador</b>.

En este blog explicaré cómo desarrollar esta técnica de realizar panorámicas, teniendo en cuenta ese aspecto de la inmersión en el ambiente a fotografiar y controlar los diferentes elementos que tienes en escena.
    
<h2>Cómo realizar panorámicas tradicionales</h2>

<!--DIAPOSITIVA 1----------------------------------->
<h1><u>Inicios</u>:</h1>

<table>
    <tr>
        <td style="background-color:#E5E3E2">
            <ul>
                <li><h3>Antes de que existiera la función <b><i>Photomerge</i></b> de <i>Adobe Photoshop</i>, lo tradicional era realizar varias fotografías en horizontal o en vertical y unirlas manualmente a través de deformaciones en el mismo software.</h3></li>
                <li><h3>Como se aprecia en la fotografía de ejemplo, la idea es realizar un <b>barrido de izquierda a derecha</b> en el entorno a fotografiar.</h3></li>
                <li><h3>El <b>problema</b> en estos casos era la mezcla y unión de determinadas partes de la fotografía.</h3></li>
                <li><h3>Es fundamental contar con una <b>base con una resolución de al menos 150ppp</b>, con un <b>formato de 6237x2044 pixeles</b> para poder realizar en ella la composición final en el software de edición fotográfica.</h3></li>
            </ul>
        </td>
    </tr>
</table>

<center>
    <img src="src/panoramica_fotosEnteraApartados_inicios.jpg">
</center> 

<button type="button" id="btn1dp1" onclick="diapo('1')" style="display:block">Ejemplos de Primeras Panorámicas</button>
<button type="button" id="btn2dp1" onclick="diapob('1')" style="display:none">Ocultar Ejemplos</button>

<div id="diapo1" style="display:none">
        <table>
        <tr>
            <th>Principado de Mónaco (2009)</th>
        </tr>
        <tr>
            <td valign="top">
                <center>
                    <img src="src/panoramica_fotosEncabezado_ejemploTradicional_01.jpg">
                    <br>
                    <img src="src/panoramica_fotosEncabezado_ejemploTradicional_01_normal.jpg">
                </center> 
            </td>
        </tr>
        <tr>
            <th>Circo Montañoso de Gredos (2011)</th>
        </tr>
        <tr>
            <td valign="top">
                <center>
                    <img src="src/panoramica_fotosEncabezado_ejemploTradicional_02.jpg">
                    <br>
                    <img src="src/panoramica_fotosEncabezado_ejemploTradicional_02_normal.jpg">
                </center> 
            </td>
        </tr>
        </table>
</div>
<br>

<!--DIAPOSITIVA 2----------------------------------->
<h1><u>Conversión de tus archivos con plugin informático</u>:</h1>

El efecto nativo <b><i>Photomerge</b></i> de <i>Adobe Photoshop</i> permite unir los <b>píxeles comunes que encuentre</b> de un lote de fotografías que el usuario inserte dentro del software. La secuencia sería la siguiente:

<center>
    <img src="src/panoramica_photomerge_01.jpg">
</center> 
<br>
<center>
    <img src="src/panoramica_photomerge_02.jpg">
</center> 
<br>

Como se puede observar, son diferentes tipos de panorámicas las que podemos obtener, en función del paralaje que busquemos en la fotografía. Habrá entornos en los que, por la profundidad de campo, no podamos disponer de un paralaje idóneo. Lo que nos provocará resultados un poco deformes de la realidad, asemejándose a un efecto de óptico de ojo de pez. De ahí que haya que tener en cuenta las condiciones de profundidad de campo y distancia focal de la lente a lo que queramos mostrar. Un ejemplo lo tenemos en las siguientes fotografías:

<center>
    <img src="src/panoramica_photomerge_03.jpg">
</center> 
<br>
La distancia focal desde la cámara al punto de foco (lo principal que queremos representar) es muy poca en proporción a la amplitud de la fotografía. Aunque la foto es brillante, el número de fotografías que la forman (16 en total: 8 en línea superior y 8 en inferior), al procesarla en <i>Adobe Photoshop</i> da la sensación de que deforma la realidad, ya que se aprecia un monumento curvo. Algo diferente pasa con la siguiente fotografía, en la que la distancia focal es mucho mayor, lo que nos ofrece proporciones más reales.

<center>
    <img src="src/panoramica_photomerge_04.jpg">
</center> 
<br>

Estos ejemplos no quieren decir que no podamos utilizar esta herramienta aunque se representen entornos alterados de la realidad. Ni mucho menos. El resultado de una foto de estas características puede resultar muy artístico. Pero el trabajo para conseguirlo es muy costoso.
<br>

<button type="button" id="btn1dp2" onclick="diapo('2')" style="display:block">Ver Otros Ejemplos</button>
<button type="button" id="btn2dp2" onclick="diapob('2')" style="display:none">Ocultar Ejemplos</button>

<div id="diapo2" style="display:none">
    <table>
    <tr>
        <td valign="top">
            <center>
                    <img src="src/panoramica_ejemplosParalaje_01.jpg">
            </center>
            <br>
            <center>
                    <img src="src/panoramica_ejemplosParalaje_02.jpg">
            </center> 
        </td>
    </tr>
    </table>
</div>


<br>

<!--DIAPOSITIVA 3----------------------------------->

<h1><u>¿Qué tener en cuenta a la hora de realizar la captura?</u>:</h1>

Son varios los consejos que te pueden ayudar a la hora de hacer panorámicas. Son sencillos y apenas requieren ningún desembolso importante. Desde mi punto de vista, la experiencia me ha servido y puedo decir que la técnica con el tiempo mejora. Al final, como todo en la vida, es cuestión de práctica. 

<!--MODOS DE DISPARO SEMIAUTOMATICO----------------->
<h2><u>-Consejos</u>:</h2>

<table>
    <tr>
        <td style="background-color:#E5E3E2">
            <ul>
                <li><h3>Lo ideal, si tenemos tiempo, es usar el modo manual pero nos será <b>más sencillo usar automatismos</b>.</h3></li>
                <li><h3>El <b>modo prioridad a la apertura</b> o el <b>modo prioridad a la velocidad de obturación</b> se convertirán en nuestro mejores aliados.</h3></li>
                <li><h3>Para conseguir escenas nítidas será recomendable usar aperturas pequeñas (números f altos) como <b>por ejemplo f/8 o f/11</b>.</h3></li>
            </ul>
        </td>
    </tr>
</table>

<center>
  <img src="src/fotosEnteraApartados_semiautomatico.jpg">
</center> 

<button type="button" id="btn1dp3" onclick="diapo('3')" style="display:block">Ejemplos de Disparo Semiautomático</button>
<button type="button" id="btn2dp3" onclick="diapob('3')" style="display:none">Ocultar Ejemplos</button>

<div id="diapo3" style="display:none">
        <table>
        <tr>
            <th>Apertura Diafragma f/8</th>
            <th>Apertura Diafragma f/11</th>
        </tr>
        <tr>
            <td valign="top">
                <center>
                    <img src="src/fotosPequenas_semiautomatico_01.jpg">
                </center> 
            </td>
            <td valign="top">
                 <center>
                    <img src="src/fotosPequenas_semiautomatico_02.jpg">
                </center> 
            </td>
        </tr>
        </table>
</div>

<br>

<!--SCRIPTS----------------------------------->

<script>
function diapo(a) {
  document.getElementById("diapo"+a).style.display = "block";
  document.getElementById("btn1dp"+a).style.display = "none";
  document.getElementById("btn2dp"+a).style.display = "block";

}
function diapob(b) {
  document.getElementById("diapo"+b).style.display = "none";
  document.getElementById("btn1dp"+b).style.display = "block";
  document.getElementById("btn2dp"+b).style.display = "none";

}
</script>
