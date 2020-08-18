---
layout: post
title:  "Fundamentos a la Ingeniería de Software"
date:   2020-08-14
---
<body style="background-color:#FFE5C7;font-family: Century Schoolbook">
<h4><b>¿Cuál es la diferencia entre ingeniería de software y ciencias de la computación?<br></b></h4>
<p align="justify">Las ciencias de la computación estan enfocadas en la teoría y
fundamentos, en cambio la ingeniería de software se enfoca en el sentido práctico del desarrollo y en la distribución de software.</p>
<h4><b>¿Cuál es la diferencia entre ingeniería de software e ingeniería de sistemas?<br></b></h4>
<p align="justify">La ingeniería de sistemas se interesa por todos los aspectos del desarrollo de sistemas basados en computadoras, incluidos hardware, software e ingeniería de procesos. La ingeniería de software es parte de este proceso más general.</p>
<br>
<a name="tema1.1"></a>
<br>
<hr size=5 style="background-color: lightseagreen">
<br>
<h1 align="center"><b>DEFINICIONES Y OBJETIVOS DE LA INGENIERIA DE SOFTWARE</b></h1>
<h1 align="center"><b>¿Que es Software?<br></b></h1>
<p align="justify">Es un producto que diseñan y construyen los ingenieros de software. Esto abarca programas que se ejecutan dentro de una computadora de cualquier tamaño y arquitectura, documentos que comprenden formularios virtuales e impresos y datos que combinan números y texto y también incluyen representaciones de la información de audio, vídeo e imágenes.</p>
<h1 align="left "><b>Objetivo<br></b></h1>
<p align="justify"> Planificar el desarrollo del software como un proceso metodológico de construcción y de gestión de proyectos soportado en estándares utilizados en la industria de la ingeniería de software para diseñar software de calidad.</p>
<h4><b>Atributos de un buen software.<br></b></h4>
<center>
	<img src="/Proyect-Software/img/tema1/figura2.png"><br>
	<h5><i><u>figura 1: Referencia de un buen Software con sus atributos.</u></i></h5>
</center>
<p align="justify">El buen software debe entregar al usuario la funcionalidad y el desempeño requeridos, y debe ser sustentable, confiable y utilizable.<br>Los atributos esenciales de un buen software son:</p>
<ul>
	<li><b style="color: red">Mantenimiento.- </b> <p align="justify">El software debe escribirse de tal forma que pueda evolucionar para satisfacer las necesidades cambiantes de los clientes </p></li>
	<li><b style="color: red">Confiabilidad y seguridad.- </b><p align="justify"> La confiabilidad del software incluye una variedad de características que incluyen confiabilidad, seguridad y protección, el software confiable no debe causar daños físicos o económicos en caso de falla del sistema.</p></li>
	<li><b style="color: red">Eficiencia.- </b><p align="justify">El software no debe desperdiciar los recursos del sistema, como la memoria y los ciclos del procesador. Por lo tanto, la eficiencia incluye la capacidad de respuesta, el tiempo de procesamiento, la utilización de la memoria, etc. </p></li>
	<li>
		<b style="color: red">Aceptabilidad.- </b><p align="justify">El software debe ser aceptable para el tipo de usuarios para el que está diseñado. Esto significa que debe ser comprensible, utilizable y compatible con otros sistemas que utilicen.</p>
	</li>
</ul>
<a name="tema1.2"></a>
<br>
<hr size=5 style="background-color: lightseagreen">
<br>
<h1 align="center"><b>LA EVOLUCION DEL SOFTWARE</b></h1>
<b>Primeros años (1950 - 1960)</b><br>
<ul>
	<li>Lo mas importante era el hardware, el software solo era un complemento.</li>
	<li>Se utilizaba el procesamiento por lotes.</li>
	<li>Aún no existia ninguna documentación o metodología.</li>
</ul>
<b>Segunda Era (1960 - 1970)</b><br>
<ul>
	<li>El software se considera un producto que se distribuye para macro y mini computadoras.</li>
	<li>Inicia la industria del software con la idea de desarrollar el mejor paquete y asi ganar dinero.</li>
	<li>Se introdujo nuevos conceptos de iteracción hombre-maquina, gracias a la multiprogramacion y sistemas multiusuario.</li>
	<li>El mantenimiento del software comenzó a ser algo mucho mas crítico.</li>
</ul>

<b>Tercera Era (1970 - 1990)</b><br>
<ul>
	<li>El uso personal del software aún no era común.</li>
	<li>Incrementa notablemente la dificultad debido a sistemas distribuidos.</li>
	<li>La presión sobre los desarrolladores era muy alta.</li>
	<li>Incrementa el uso de acceso inmediato a los datos.</li>
</ul>

<b>Cuarta Era (1990 - 2000)</b><br>
<ul>
	<li>En esta epoca la industria del software es considerada la cuna de la economía del mundo.</li>
	<li>Se denominan los sistemas cliente/servidor.</li>
	<li>Sistemas de cómputo personales potentes.</li>
	<li>Una gran demanda del internet y el comercio electrónico.</li>
	<li>Gran auge de las tecnologías orientada a objetos.</li>
</ul>
<center>
	<img src="/Proyect-Software/img/tema1/figura1.png"><br>
	<h5><i><u>figura 2: Similitud a la evolucion del software</u></i></h5>
</center>


<a name="tema1.3"></a>
<br>
<hr size=5 style="background-color: lightseagreen">
<br>
<h1 align="center"><b>LA CRISIS DEL SOFTWARE</b></h1>
<p align="justify">
	La crisis del software se identificó por primera vez en 1968, año en el que se desarrolló la primera conferencia sobre desarrollo de software, y en la que se implementaron los términos “crisis del software” para definir a los problemas que surgían en el desarrollo de sistemas de software, e ingeniería del software para describir el conjunto de conocimientos que existían en aquel estado inicial.<br>
	Muchas de las causas de la crisis del software se pueden encontrar en una mitología que surge durante los primeros años del desarrollo del software.<br>Algunos ejemplos de mitos que causan la crisis del software:
	<ul>
		<li><b>De gestión.- </b> "Tenemos ya un libro que está lleno de estándares y procedimientos para construir software."</li>
		<li><b>Del cliente.- </b> "En los clientes que solicitan una aplicación de software los mitos les crean falsas expectativas y finalmente quedan insatisfechos,"Una vez que escribimos el programa y hacemos que funcione, nuestro trabajo ha terminado"</li>
		<li><b>Del cliente.- </b> "En los clientes que solicitan una aplicación de software los mitos les crean falsas expectativas y finalmente quedan insatisfechos,"Una vez que escribimos el programa y hacemos que funcione, nuestro trabajo ha terminado"</li>
		<li><b>De los ingenieros de software.- </b> "Para  administrar  en  forma adecuada  el  proyecto, se  debe  tener un plan detallado de todo el proyecto desde el principio"</li>
	</ul>

</p>


</body>