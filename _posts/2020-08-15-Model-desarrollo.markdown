---
layout: post
title:  "Modelos de desarrollo."
date:   2020-08-15 
categories: jekyll update
---
<body style="background-color:#FFE5C7;font-family: Century Schoolbook">
<p align="justify">
	Ingeniería de software es la aplicación de enfoques sistemáticos y disciplinados al desarrollo de software, para esto se han creado modelos y metodologías para la correcta utilización del tiempo y recursos que una empresa o entidad disponen.<br>
</p>
<a name="tema5.1"></a>
<br>
<hr size=5 style="background-color: lightseagreen">
<br>
<h1 align="center"><b>MODELOS TRADICIONALES</b></h1>
<p align="justify">
	Es el enfoque metodológico que ordena rigurosamente las etapas del proceso para el desarrollo de software, de tal forma que el inicio de cada etapa debe esperar a la finalización de la etapa anterior.<br>
	Formados por un conjunto de fases o actividades en las que no tienen en cuenta la naturaleza evolutiva del software.<br>
	Las metodologías tradicionales no se adaptan adecuadamente a los cambios, por lo que no son métodos adecuados cuando se trabaja en un entorno, donde los requisitos no pueden predecirse o bien pueden variar.
</p>
Algunos de los modelos tradicionales son:<br>
<ul>
	<li>
		<h3><b>Modelo Secuencial(Clásico).<br></b></h3>
		<center>
			<br><img src="/Proyect-Software/img/tema5/figura1.png" height="150px" align="auto"><br>
			<h5><i><u>figura 1.1: Diseño del modelo Secuencial.</u></i></h5>
		</center>
		<p align="justify">
			<ul>
				<li><p align="justify"><b> Análisis de requisitos.-</b> Se debe comprender el dominio de la información, la función requerida, comportamiento, rendimiento e interconexión.</p></li>
				<li><p align="justify"><b>Diseño.-</b> Proceso de muchos pasos centrado en cuatro atributos: estructura de datos, arquitectura de software, representación de la interfaz.</p></li>
				<li><p align="justify"><b>Generación de código.-</b> El diseño es traducido a lenguaje máquina.</p></li>
				<li><p align="justify"><b>Pruebas.-</b> Detección de errores y asegurar que una entrada definida produce resultados esperados.</p></li>
				<li><p align="justify"><b>Mantenimiento.-</b> Cambios en el software que implican aplicar todos los pasos precedentes en orden.</p></li>
			</ul>
		</p>
	</li>
	<li>
		<h3><b>Modelo Cascada.</b></h3>
		<center>
			<br><img src="/Proyect-Software/img/tema5/figura2.png" height="250px" align="auto"><br>
			<h5><i><u>figura 1.2: Diseño del modelo Cascada.</u></i></h5>
		</center>
		<p align="justify">
			El modelo cascada es de plan-impulsado significa que son procesos en los que todas las actividades del proceso se planifican con antelación y el progreso se mide en contra de este plan, tiene fases separadas y distintas de especificación y desarrollo.<br>El modelo en cascada refleja la necesidad impuesta por la realidad de retornar con frecuencia desde una fase hacia las anteriores con la información generada al avanzar el desarrollo.
			<ul>
				<li>Análisis de requisitos.</li>
				<li>Diseño.</li>
				<li>Codificación.</li>
				<li>Pruebas.</li>
				<li>Integración</li>
				<li>Operación y mantenimiento.</li>
			</ul>
		</p>
	</li>
	<li><h3><b>Construcción de prototipos.</b></h3>
		<center>
			<br><img src="/Proyect-Software/img/tema5/figura3.png" height="250px" align="auto"><br>
			<h5><i><u>figura 1.3: Diseño del modelo de construcción de prototipos.</u></i></h5>
		</center>
		<p align="justify">
			<b>Paradigma:</b><br>Inicia con la recolección de requisitos<br>Se hace un diseño rápido de aspectos visibles para el cliente/usuario para generar un prototipo.<br>El prototipo lo evalúa el cliente/usuario para refinar los requisitos.<br>
			<b>Pudiera presentar problemas debido a:</b><br>
			El cliente solo ve el sistema por “fuera” y no la calidad por “dentro”; el mantenimiento no es prioridad cuando se desarrolla rápido.<br>
			El desarrollador, con frecuencia, hace uso de las herramientas más a la mano no de las más apropiadas
		</p>
	</li>
	
</ul>
<a name="tema5.2"></a>
<br>
<hr size=5 style="background-color: lightseagreen">
<br>
<h1 align="center"><b>MODELOS AGILES</b></h1>
Enfatizan el desarrollo rápido, ponen el énfasis en la programación.
<ul>
	<li>
		<h3><b>Modelo Scrum.<br></b></h3>
		<center>
			<br><img src="/Proyect-Software/img/tema5/figura4.png" height="250px" align="auto"><br>
			<h5><i><u>figura 2.1: Equipo de desarrollo de Scrum.</u></i></h5>
		</center>
		<p align="justify">
			Scrum se basa en la teoría de control de procesos empírica o empirismo. El empirismo asegura que el conocimiento procede de la experiencia y de tomar decisiones basándose en lo que se conoce. Esta metodología emplea un enfoque iterativo e incremental para optimizar la predictibilidad y el control del riesgo, realiza entregas del proyecto en sí.<br>
			El equipo de desarrollo de Scrum tal como se lo muestra en la <i>figura 1:</i><br>
			<ul>
			<li><p align="justify"> <b>Scrum Master: </b>Es un líder que está bajo el servicio del equipo scrum, este miembro ayuda al equipo y a los clientes externos a comprender las interacciones que pueden ser de ayuda y cuáles no lo son, además él es el encargado de asegurar que el equipo adopte las teorías, prácticas y reglas de la metodología scrum.
			</p></li>
			<li><p align="justify"><b>Product Owner: </b>Es la persona responsable de transmitir al equipo de desarrollo la visión del producto que se desea crear, aportando la perspectiva de negocio.</p></li>
			<li><p align="justify"><b> Cliente: </b>Son los destinatarios finales de la aplicación a desarrollar, el público objetivo del mismo. No forman parte del proceso de creación directamente, aunque podrían estar en la fase de revisión de entregables si se considera necesario.</p></li>
			<li><p align="justify"><b>Equipo Scrum: </b>Equipo responsable de desarrollar y entregar el producto. Mantiene una organización horizontal en la que cada miembro del equipo se auto-gestiona y organiza libremente en la definición y ejecución de los distintos sprints</p></li>
			</ul>
		</p>
	</li>
	<li>
		<h3><b>Programacion Extrema (XP).<br></b></h3>
		<center>
			<br><img src="/Proyect-Software/img/tema5/figura5.png" height="250px" align="auto"><br>
			<h5><i><u>figura 2.2: Diseño del modelo XP.</u></i></h5>
		</center>
		<p align="justify">
			La programación extrema es una metodología que se basa en una serie de reglas y principios que se han utilizado a lo largo de toda la historia del desarrollo de software, aplicando conjuntamente cada una de ellas de manera que creen un proceso ágil.<br>
			Además la programación extrema se basa en la simplicidad, la comunicación y el reciclado continúo de código
		</p>
		<b>Pretende:</b>
		<ul>
			<li>La satisfacción del cliente.</li>
			<li>Potenciar al máximo el trabajo en grupo.</li><li>educir el costo del cambio en las etapas de vida del sistema.</li>
			<li>Combinar las que han demostrado ser las mejores practicas de desarrollo de software y llevarlas al extremo.</li>
		</ul>
		<b>Establece cuatro variables:</b>
		<ul>
			<li>Coste.</li>
			<li>Tiempo.</li>
			<li>Calidad.</li>
			<li>Ámbito.</li>
		</ul>
		<b>Plantea cuatro valores:</b>
		<ul>
			<li>Comunicación.</li>
			<li>Sencillez.</li>
			<li>Retroalimentación.</li>
			<li>Valentía.</li>
		</ul>
		<b>Define cuatro actividades básicas:</b>
		<ul>
			<li>Codificar.</li>
			<li>Hacer pruebas.</li>
			<li>Escuchar.</li>
			<li>Diseñar.</li>
		</ul>
	</li>
	<li>
		<h3><b>Crystal Clear.<br></b></h3>
		<center>
			<br><img src="/Proyect-Software/img/tema5/figura6.png" height="250px" align="auto"><br>
			<h5><i><u>figura 2.3: Diseño del modelo Crystal Clear.</u></i></h5>
		</center>
		<p align="justify">
			Crystal es una metodología en la cual se establecen códigos de color como parte de la definición de la complejidad de la misma, si es más oscuro entonces el método es más pesado, cuánto más crítico es el sistema más rigor se necesita.<br>Además Crystal Clear sugiere que se defina un color para cada proyecto en función de su criticidad y tamaño.<br>
			Cada letra de la <i>figura 2.3</i> representa a los riesgos potenciales:<br>
			<b>C:</b> pérdida de confort debido a un fallo del sistema<br>
			<b>D:</b> pérdida de dinero discrecional (nuestro dinero)<br>
			<b>E:</b> pérdida de dinero esencial (este es el dinero del cual no se puede disponer)<br>
			<b>L:</b> pérdida de vidas por el fallo del sistema<br>
			Además el color indica el numero de personas que se requiere:<br>
			<b>Clear:</b> es para equipos de 8 personas o menos.<br>
			<b>Amarillo:</b> para equipos de 10-20 personas.<br>
			<b>Naranja:</b> para equipos de 20-50 personas.<br>
			<b>Rojo:</b> para equipos de 50-100 y así sucesivamente pasando por el marrón y violeta.<br>
		</p>
	</li>
</ul>
</body>