# Webpack Frontend Starterkit

[![Dependabot badge](https://flat.badgen.net/dependabot/wbkd/webpack-starter?icon=dependabot)](https://dependabot.com/)

En el proyecto realizo la pagina web de coocalpro "www.cooclalpro.com", utilizando los parametros realizados en clase con el profesor juan carlos en el espacio academico de programacion 3.

Ingresamos a github, iniciamos seccion y creamos un repositorio.

luego de haber creado el repositorio descargamos la carpeta utilizando git clone y copiando la url. (git clone + url)

luego vamos a instalar el node_modules utulizando git (npm install)

creamos el codigo index.html.

creamos el codigo. scss

luego vamos a installar el boostrap ya que ingresamos elementos que contiene este elemto. (npm install boostrap).

vamos a darle (npm update) para cargar los archivos.

para ejecutar la pagina le damos (npm start) y la ubica como localhost en el navegador.

ESTE ES EL CODIGO QUE REALISE EN EL INDEX.HTML

<html>
<head>
<title>Proyecto Coocalpro</title>
<link rel="stylesheet" href="maquetacion.css" type="text/css"/></head>
<body>
<div id ="contenedor">
<div id ="cabecera">
<div class="search">
<input name="searchword" id="mod_search_searchword" maxlength="20" alt="Buscar" class="inputbox" type="text" size="10" value="buscar..."  onblur="if(this.value=='') this.value='buscar...';" onfocus="if(this.value=='buscar...') this.value='';" /> </div>
 </div>
 <div id ="menu">
 <center><span >¿Quienes somos?</span>&nbsp&nbsp&nbsp&nbsp&nbsp
 <span >Contactenos</span>&nbsp&nbsp&nbsp&nbsp&nbsp
 <span >Misión</span>&nbsp&nbsp&nbsp&nbsp&nbsp
 <span >Visión</span>
 </div></center>
 </div>
 <div id ="imagencoocalpro">
 <img src="imagen1.jpg">
 </div>
 <div id ="izquierda">
 <div class="card" style="width: 18rem;">
 <div class="card-body">
 <center><h5 class="card-title"> MENU PRINCIPAL </h5></center>
 <div class="card-body">
 <center><br><a href="#" class="card-link">INICIO</a></br></center>
 <center><br><a href="#" class="card-link">DOCUMENTOS NORMATIVOS</a></br></center>
 <center><br><a href="#" class="card-link">¿ QUIENES SOMOS ?</a></br></center>
 <center><br><a href="#" class="card-link">GALERIA IMAGENES</a></br></center>
 <center><br><a href="#" class="card-link">GALERIA IMAGENES</a></br></center>
 <center><br><a href="#" class="card-link">PAGOS EN LINEA</a></br></center>
 </div>
 </div>
 </div>
 <div class="card" style="width: 18rem;">
 <div class="card-body">
 <center><h5 class="card-title"> RECURSOS </h5></center>
 <div class="card-body">
 <center><br><a href="#" class="card-link">SECCION AHORROS</a></br></center>
 <center><br><a href="#" class="card-link">SECCION DE CREDITOS</a></br></center>
 <center><br><a href="#" class="card-link">ESCUELA DEPORTIVA</a></br></center>
 <center><br><a href="#" class="card-link">TDMAFINIDAD</a></br></center>
 <center><br><a href="#" class="card-link">RECREACION</a></br></center>
 </div>
 </div>
 </div>
 <div class="card" style="width: 18rem;">
 <div class="card-body">
 <center><h5 class="card-title"> PROTECCION DE DATOS </h5></center>
 <div class="card-body">
 <center><br><a href="#" class="card-link">PROTECCION DE DATOS PERSONALES</a></br></center>
 </div>
 </div>
 </div>
 <div class="card" style="width: 18rem;">
 <div class="card-body">
 <center><h5 class="card-title"> SOCIAL </h5></center>
 <center><br><a href="#" class="card-link">FACEBOOK</a></br></center>
 <center><br><a href="#" class="card-link">INSTAGRAM</a></br></center>
 </div>
 </div>
 </div>
 </div>
 <div id ="centro">
 <div id ="imagen01">
 <img src="imagen01.jpg" width="450" height="400">
 </div>
 <div class="card" style="width: 30rem;height: 900rem">
 <div class="card-body">
 <center><h5 class="card-title"> BIENVENIDOS A COOCALPRO </h5></center>
 <img src="imagen02.jpg" width="450" height="300">
 <img src="imagen03.jpg" width="450" height="300">
 <img src="imagen04.jpg" width="450" height="300">
 <img src="imagen05.jpg" width="450" height="300">
 </div>
 </div>
 </div>
 <div id ="derecha">
 <div class="art-BlockHeader">
 <div class="l"></div>
 <div class="r"></div>
 <div class="art-header-tag-icon">
	<center> <div class="t">
  EVENTOS</div></center>
  </div>
  </div>
	<div class="art-BlockContent">
	<div class="art-BlockContent-body">
<center><div class='eventcalq'><table class="mod_eventlistcalq_calendar" cellspacing="0" cellpadding="0">
<caption class="mod_eventlistcalq_calendar-month"><a href="/index.php?&amp;el_mcal_month=3&amp;el_mcal_year=2020" rel="nofollow">&lt;&lt; </a>&nbsp;Abril&nbsp;2020&nbsp;<a href="/index.php?&amp;el_mcal_month=5&amp;el_mcal_year=2020" rel="nofollow"> &gt;&gt;</a></caption>
<tr><th class="mod_eventlistcalq_daynames" abbr="Lun">&nbsp;Lu&nbsp;</th><th class="mod_eventlistcalq_daynames" abbr="Mar">&nbsp;Ma&nbsp;</th><th class="mod_eventlistcalq_daynames" abbr="Mie">&nbsp;Mi&nbsp;</th><th class="mod_eventlistcalq_daynames" abbr="Jue">&nbsp;Ju&nbsp;</th><th class="mod_eventlistcalq_daynames" abbr="Vie">&nbsp;Vi&nbsp;</th><th class="mod_eventlistcalq_daynames" abbr="Sab">&nbsp;Sa&nbsp;</th><th class="mod_eventlistcalq_daynames" abbr="Dom">&nbsp;Do&nbsp;</th></tr>
<tr><td class="mod_eventlistcalq">&nbsp;</td><td class="mod_eventlistcalq">&nbsp;</td><td class="mod_eventlistcalq_calday">&nbsp;&nbsp;1</td><td class="mod_eventlistcalq_calday">&nbsp;&nbsp;2</td><td class="mod_eventlistcalq_calday">&nbsp;&nbsp;3</td><td class="mod_eventlistcalq_calday">&nbsp;&nbsp;4</td><td class="mod_eventlistcalq_calday">&nbsp;&nbsp;5</td></tr>
<tr><td class="mod_eventlistcalq_calday">&nbsp;&nbsp;6</td><td class="mod_eventlistcalq_calday">&nbsp;&nbsp;7</td><td class="mod_eventlistcalq_calday">&nbsp;&nbsp;8</td><td class="mod_eventlistcalq_calday">&nbsp;&nbsp;9</td><td class="mod_eventlistcalq_calday">10</td><td class="mod_eventlistcalq_calday">11</td><td class="mod_eventlistcalq_calday">12</td></tr>
<tr><td class="mod_eventlistcalq_calday">13</td><td class="mod_eventlistcalq_calday">14</td><td class="mod_eventlistcalq_calday">15</td><td class="mod_eventlistcalq_calday">16</td><td class="mod_eventlistcalq_calday">17</td><td class="mod_eventlistcalq_calday">18</td><td class="mod_eventlistcalq_calday">19</td></tr>
<tr><td class="mod_eventlistcalq_calday">20</td><td class="mod_eventlistcalq_caltoday">21</td><td class="mod_eventlistcalq_calday">22</td><td class="mod_eventlistcalq_calday">23</td><td class="mod_eventlistcalq_calday">24</td><td class="mod_eventlistcalq_calday">25</td><td class="mod_eventlistcalq_calday">26</td></tr>
<tr><td class="mod_eventlistcalq_calday">27</td><td class="mod_eventlistcalq_calday">28</td><td class="mod_eventlistcalq_calday">29</td><td class="mod_eventlistcalq_calday">30</td><td class="mod_eventlistcalq">&nbsp;</td><td class="mod_eventlistcalq">&nbsp;</td><td class="mod_eventlistcalq">&nbsp;</td></tr>
</table>
</div></center>
<div class="cleared"></div>
</div>
</div>
<div class="card" style="width: 18rem;">
<div class="card-body">
<center><br><a href="#" class="card-link">CONSULTA NUESTROS 
PROXIMOS EVENTOS</a></br></center>
</div>
</div>
<div class="card" style="width: 18rem;">
<div class="card-body">
<center><h5 class="card-title"> ACT.WEB DIAN R.T.E </h5></center>
<div class="card-body">
<center><br><a href="#" class="card-link">2018</a></br></center>
<center><br><a href="#" class="card-link">2019</a></br></center>
</div>
</div>
</div>
<div class="card" style="width: 18rem;">
<div class="card-body">
<center><h5 class="card-title"> INGRESO ASOCIADOS </h5></center>
<div class="card-body">
<center><br><a href="#" class="card-link">CONSULTA ESTADO DE CUENTA EN LINEA</a></br></center>
</div>
</div>
</div>
<div class="card" style="width: 18rem;">
<div class="card-body">
<center><h5 class="card-title"> VISOR DE NOTICIAS </h5></center>
<div class="card-body">
<center><br><a href="#" class="card-link">EFIGAS</a></br></center>
<center><br><a href="#" class="card-link">NOTICIAS COVID-19</a></br></center>
<center><br><a href="#" class="card-link">ACTUALIDAD DEPORTES</a></br></center>
<center><br><a href="#" class="card-link">PRESIDENCIA DE LA REPUBLICA</a></br></center>
<center><br><a href="#" class="card-link">RECREACION</a></br></center>
</div>
</div>
</div>
</div>
<div id ="pie">
<CENTER><div class="cleared"></div>
<div class="art-Footer">
<div class="art-Footer-inner">
<div class="art-Footer-text" >
<p>Copyright © 2013 
All Rights Reserved.<br/>Vigilada SUPERSOLIDARIA e Inscrito a FOGACOOP <br/>Developer Juan D. Restrepo</p>
</div>
</div>
<div class="art-Footer-background"></div>
</div></CENTER>
</div>
</div>
</body>
</html>

ESTE ES EL CODIGO QUE REALISE EN INDEX.SCSS

@import "~bootstrap/scss/bootstrap";
@import "./home.scss";


     
  
contenedor{
        background-color:white;
        border:2px solid white;
}
cabecera{
        background-color:green;
        height:5%;
}
menu{
        height:10%;
        background-color:#C8CACC;
}
imagencoocalpro{
        height:30%;
        background-color:white;
}
izquierda{
        height:300%;
        background-color:white;
        float:left;
        width:30%;
}

centro{
        height:5%;
        background-color:white;
        float:left;
        width:40%;

}
imagen1{
        height:10%;
        width: 10%;
        background-color:white;
}


derecha{
        height:50%;
        background-color:white;
        float:right;
        width:30%;
}
pie{
        height:20%;
        background-color:green;
        clear:both;
}
card{
  background-color: gray;
}















PASOS PARA LA INSTALACION.

### Installation

```
npm install
```

### Start Dev Server

```
npm start
```

### Build Prod Version

```
npm run build
```

### Features:

* ES6 Support via [babel](https://babeljs.io/) (v7)
* SASS Support via [sass-loader](https://github.com/jtangelder/sass-loader)
* Linting via [eslint-loader](https://github.com/MoOx/eslint-loader)

When you run `npm run build` we use the [mini-css-extract-plugin](https://github.com/webpack-contrib/mini-css-extract-plugin) to move the css to a separate file. The css file gets included in the head of the `index.html`.
