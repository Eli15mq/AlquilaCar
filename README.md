<!doctype html>

<html>

<head>
	<meta charset="utf-8">
	<title>Alquila Car</title>

<style type="text/css">
	 @charset "UTF-8";
	#mainwrapper header {
		/*Header */
		background-color:#000000;
		overflow: auto;
		font-family: montserrat, sans-serif;
		font-style: normal;
		font-weight: 400;
	}
	#mainwrapper header #logo {
		/* Company Logo text */
		width: 28%;
		float: left;
		padding-left: 2%;
		padding-top: 12px;
		padding-bottom: 12px;
		color: rgba(146,146,146,1.00);
	}
	#mainwrapper header nav {
		/*Nav bar containing links in header */
		text-align: right;
		padding-top: 12px;
		padding-bottom: 12px;
		padding-right: 2%;
		width: 68%;
		float: left;
		color: rgba(146,146,146,1.00);
	}
	header nav a {
		/* Links in header */
		padding-right: 2%;
	}
	details summary {
		padding-right: 10%;
		padding-top: 10%;
	}

	* {
		padding:0px;
		margin:0px;
	}
	#desplegable {
		margin:auto;
		Width:500px;
		font-family: "Gill Sans", "Gill Sans MT", "Myriad Pro", "DejaVu Sans Condensed", Helvetica, Arial, "sans-serif"
	}

	ul, ol {
		list-style:none;
	}

	.nav li a {
		background: #000000;
		color:#FFFFFF;
		text-decoration: none;
		padding: 10px 14px;
		display:block;	
	}
	.nav li a:hover { 
		background-color: #2A2A33;
	}
	.nav > li {
		float:left;
	}
	.nav li ul {
		display:none;
		position: absolute;
		min-width: 100px;
	}
	.nav li:hover > ul {
		display:block;
	}
	.nav li ul li {
		position:relative;
	}
	.nav li ul li ul {
		right: -100px;
		top:0px;
	}
	#content #mainContent h1, #content #mainContent h2 {
		/* Styling for main headings */
		color:#1B165F;
		font-weight:400px;
		font-family:Impact, Haettenschweiler, "Franklin Gothic Bold", "Arial Black", "sans-serif";
		font-size: 40px;
	}
	#content #mainContent h3 {
		/*Captions ot Taglines */
		font-style: normal;
		font-weight: 200px;
		color:#003AA9;
		font-size: 140%;
		font-family:Cambria, "Hoefler Text", "Liberation Serif", Times, "Times New Roman", "serif";
	}
	#content #mainContent #bannerImage {
		/*Container for main banner image */
		width: 100%;

	}
	#content #mainContent p {
		/* All paragraphs under maincontent */
		color:#000000;
		font-family: source-sans-pro, Segoe, "Segoe UI", "DejaVu Sans", "Trebuchet MS", Verdana, "sans-serif";
		font-style: normal;
		font-weight: 200;
		text-align: justify;
	}
	#content #mainContent #authorInfo {
		/* Author info section */
		background-color:#003A8A;
		position: relative;
	}
	#content #mainContent #authorInfo h2, #content #mainContent #authorInfo p {
		color: rgba(255,255,255,1.00);
		padding-left: 2%;
		padding-top: 11px;
		font-size: 30px;
		position: relative;
	}
	#content #mainContent #authorInfo p {
		color: rgba(255,255,255,1.00);
		padding-left: 2%;
		font-size: 16px;
		padding-top: 0px;
		padding-bottom: 11px;
		padding-right: 2%;
		position: relative;
	}

	#autos {
	    height: 102px;
	    width: 622px;
	    border-width: 2px;
	    border-style: solid;
	    border-color: rgb(0, 2, 107);
	    border-image: initial;
		margin-top: 0;
		margin-bottom: 1rem;
	}

	#contenedor {
		height: 505px;
		width: 624px;
		margin-top: 0px;
		margin-right: auto;
		margin-bottom: auto;
		margin-left: auto;
		background-color: rgb(196, 217, 255);
		border: 3px solid #0B006A;
		position:absolute;

	}
	#content #mainContent #carroElemento1 p{
		font-family: 'Times New Roman', Times, serif;
		font-size: 22px;
	}
	#content #mainContent #carroElemento2 p{
		font-family: 'Times New Roman', Times, serif;
		font-size: 22px;
	}
	#content #mainContent #carroElemento3 p{
		font-family: 'Times New Roman', Times, serif;
		font-size: 22px;
	}
	#content #mainContent #carroElemento4 p{
		font-family: 'Times New Roman', Times, serif;
		font-size: 22px;
	}
	#content #mainContent #carroElemento5 p{
		font-family: 'Times New Roman', Times, serif;
		font-size: 22px;
	}
	footer article {
		/* Footer articles */
		width: 46%;
		float: left;
		font-size: 10px;
		padding-left: 2%;
		padding-right: 2%;
		text-align:left;
		font-family:"Gill Sans", "Gill Sans MT", "Myriad Pro", "DejaVu Sans Condensed", Helvetica, Arial, "sans-serif";
		font-style: normal;
		font-weight: 200;
		color:#144083;
		position: relative;
	}
	footer article h3 {
		/* Footer article titles */
		text-align:left;
		font-family:"Gill Sans", "Gill Sans MT", "Myriad Pro", "DejaVu Sans Condensed", Helvetica, Arial, "sans-serif";
		font-style: normal;
		font-weight: 400;
		font-size: 10px;

	}
	#mainContent {
		/* Container for the blog post in individal blog view */
		padding-left: 2%;
		width: 71%;
		float: left;
		padding-right: 2%;
		padding-top: 41px;
	}
	#mainwrapper #content #sidebar {
		/* Sidebar*/
		width: 25%;
		height: 100%;
		padding-left: 2%;
		padding-right: 2%;
		float: left;
		background-color: rgba(246,246,246,1.00);
		margin-top: 150px;
		padding-top: 32px;
	}
	#mainwrapper {
		/* Container of all content */
		width: 80%;
		overflow: auto;
		margin-left: 10%;
	}
	#content #sidebar input {
		/* Search box in sidebar */
		width: 100%;
		height: 500%;
	}
	#content #sidebar #adimage {
		width: 100%;
		background-color: rgba(208,207,207,1.00);
		margin-top: 46px;
		float: none;
		overflow: auto;
	}
	nav ul li {
		list-style-type: circle;
		color:#003DD8;
		padding-top: 8px;
		padding-bottom: 8px;
	}
	nav ul {
		padding-left: 10%;
	}
	nav ul li a {
		font-family:Baskerville, "Palatino Linotype", Palatino, "Century Schoolbook L", "Times New Roman", "serif";
		color:#003DD2;
		text-decoration: none;
	}

	#footerbar {
		/* Footer bar at the bottom of the page */
		clear: both;
	    background-color: #001C58;
	    width: 100%;
	    min-height: 9em;
	    color: #ffff;
	}

	#footerbar > article{
		margin-top: 20px;
		color: #ffff;
		margin-bottom: 20px;
	}

	footer {
		/* Container for footer artices */
		width: 71%;
		padding-left: 2%;
		padding-right: 2%;
	}
	.notOnDesktop {
		/*element to be displayed only in mobile view and tabet view */
		display: none;
	}

	#mainContent #bannerImage img {
		/* Actual banner image */
		width: 100%;
	}

	#sidebar #adimage img {
		width: 100%;
		float: left;
	}

	#mainwrapper header nav a {
		color:aliceblue;
		text-decoration: none;
	}

	/* Tablet view */
	@media screen and (max-width:769px) {
	.notOnDesktop {
		/* Search box shown only in mobile view and Tablet view */
		display: block;
		text-align: right;
		padding-right: 8px;
		padding-top: 8px;
		padding-bottom: 8px;
		width: 96%;
	}
	#content .notOnDesktop input {
		height: 28px;
	}
	#mainContent {
		/* Container for the blog post */
		padding-top: 0px;
		float: none;
		width: 96%;
	}
	#sidebar input {
		/* Search box in sidebar */
		display: none;
	}
	#mainwrapper #content #sidebar {
		/* Sidebar*/
		float: none;
		width: 92%;
		padding-top: 13px;
		overflow: auto;
		margin-top: 3px;
		margin-left: 2%;
		padding-bottom: 13px;
	}
	#content #sidebar #adimage {
		/* Image in sidebar */
		width: 60%;
		margin-top: 0px;
		float: left;
	}
	#content #sidebar nav {
		/* Navigation links in sidebar */
		width: 36%;
		float: left;
		padding-left: 4%;
	}
	#sidebar nav ul {
		margin-top: 0px;
	}
	footer {
		/* Footer region */
		width: 96%;
		padding-left: 2%;
		padding-right: 2%;
	}
	#content footer article {
		/*Each footer article */
		width: 46%;
		font-family: Cambria, "Hoefler Text", "Liberation Serif", Times, "Times New Roman", "serif";
	}

	#mainwrapper header {
		/* Header */
		width: 100%;
	}


	.ContentCard__ctaLink {
		line-height: normal;
		font-weight: 700;
		color: #000;
		font-size: 1.6rem;
		margin-top: 16px;
		border-bottom: 20px solid #1a00ef;
		margin-left: 7px;
	}

	#catalogo {
		margin-left: 0px;
		font-style:normal;
		color:#FFFFFF;
		font-size: 15px;
		font-family:"Gill Sans", "Gill Sans MT", "Myriad Pro", "DejaVu Sans Condensed", Helvetica, Arial, "sans-serif";
	}

	.ContentCard__titleInner {
		line-height: normal;
		font-weight: 700;
		border-bottom: 2px solid #efdf00;
		color: #000;
		font-size: 1.6rem;
		margin-top: 16px;
	}

	/* Mobile view */
	@media screen and (max-width:480px) {
	#mainwrapper header #logo {
		/* Company Logo text in header */
		width: 96%;
		margin-left: 2%;
	}
	#mainwrapper header nav {
		/*navigation links in header */
		text-align: center;
		background-color: rgba(255,255,255,1.00);
		width: 98%;
	}
	#content #sidebar #adimage {
		/* Container for image in sidebar */
		width: 100%;
	}
	#content #sidebar nav {
		/* Navigation bar for links in sidebar */
		width: 96%;
		padding-top: 7px;
	}
	#sidebar nav ul li {
		display: inline-block;
		width: 32%;
		text-align: center;
	}
	#mainwrapper #content #sidebar {
		/* sidebar */
		padding-bottom: 0px;
	}
	#content .notOnDesktop {
		/* Search box shown only in mobile and tablet view */
		width: 100%;
		text-align: center;
		padding-left: 0px;
		padding-right: 0px;
	}
	#content .notOnDesktop input {
		width: 80%;
		text-align: center;
	}
	#content #mainContent h3 {
		/* Title under maincontent, if any */
		font-size: 14px;
	}
	#content footer article {
		/* Each foter article */
		width: 96%;
	}
	}
	}
 </style>
</head>

<body>
	<div id="mainwrapper">
		<header>
			<div id="logo">
				<img src="zarla-alquila-car-1x1-2400x2400-20220110-7ydf4xvrx3c7cktr4wtj.png" width="80" height="50" alt="" />
			</div>
			<div id="desplegable">
				<ul class="nav">
					<li><a href="#">Mantenimientos</a>
						<ul>
							<li><a href="Tipos de mantenimiento.html">Tipos</a></li>
						</ul>
					</li>
					<li><a href="#">Montallantas</a>
						<ul>
							<li><a href="Montallantas.html">Precios</a></li>
						</ul>
					</li>
					<li><a href="#">Alineación</a>
						<ul>
							<li><a href="Alineacion tipos.html">Precios</a></li>
							<li><a href="Empresas aliadas.html">Empresas Aliadas</a></li>
						</ul>
					</li>
					<li><a href="#">Balanceo</a>
						<ul>
							<li><a href="tipos de balanceo.html">Precios</a></li>
							<li><a href="Empresas aliadas balanceo.html">Empresas Aliadas</a></li>
						</ul>
					</li>
				</ul>
			</div>
		</header>
		<div id="content">
			<div class="notOnDesktop">
				<input type="text" placeholder="Search">
			</div>
			<section id="mainContent">
				<h1>Alquila Car</h1>
				<h3>❝<u>Tu llave para un coche de alquiler</u>❞</h3>
				
				<div id="paginaPrincipal">
					<img src="images/ofertasespecialesimagen.png" width="545" height="315" alt="" />
					<br>
					<p>Somos una empresa de renta de automoviles, basamos en el servicio integral de la venta de los
						mejores autos para ayudar a nuestros clientes a escoger los mejores automoviles de tendencia.
						Incluyedo diferentes catalogos de compra y cuotas para ante todo priorizar la accesibilidad de
						los clientes. Primero son sus comodidades.</p>
					<p>Nos basamos en la seguridad de el cliente y complacerlos con el alquiler garantizado que cuide
						sus bolsillos, como el cuidado de sí mismo, de manera que la seguridad para nosotros es un
						dilema importante en todos los ámbitos.</p>
				</div>
				<div id="menu" style="display: none;">

					<p>Dependiendo del tiempo de alquilado el carro se pueden ofrecer diferentes servicios especiales
						que ayudaran a su comidad como a su tranquilidad economica, realizando asi un estable estado del
						automovil seleccionado.
						Para estos diferentes servicios se ofrece al plan del tiempo requerido.
						<br>
						Si son anuales las alquilaciones del automovil para obtener mas beneficios, en el mantenimiento,
						montallantas, alineaciones y balanceo se debera de suscribir al plan semestral de $53,000.
						<br>
						Los precios y servicios que se ofrecen pueden variar de la marca del carro, como tambien de sus
						usos.
					</p>
				</div>
				<div id="autos" style="display: none;">
					<div class="contenedor" id="contenedor">
						<a id="carroContenido1" href="#carroElemento1">
							<img src="images/20220211-MARCAS-CARROS-MAS-CONFIABLES-2022-PORTADA.jpg" alt="" width="120"
								height="100" />
						</a>
						<a id="carroContenido2" href="#carroElemento2">
							<img src="images/20210208-TOP-75-CARROS-MAS-VENDIDOS-DE-COLOMBIA-EN-ENERO-2021-01.jpg"
								width="120" height="100" alt="" />
						</a>
						<a id="carroContenido3" href="#carroElemento3">
							<img src="images/carros-deportivos-potencia.jpg" width="120" height="100" alt="" />
						</a>
						<a id="carroContenido4" href="#carroElemento4">
							<img src="images/5da64f9a11291.r_1571197059653.0-296-1080-1014.jpeg" width="120"
								height="100" alt="" />
						</a>
						<a id="carroContenido5" href="#carroElemento5">
							<img src="images/20220719-100-CARROS-MAS-VENDIDOS-DE-COLOMBIA-EN-PRIMER-SEMESTRE-DE-2022-01.jpg"
								width="120" height="100" alt="" />
						</a>
						<div>
							<div id="carroElemento1" style="display: none;">
								<img src="images/20220211-MARCAS-CARROS-MAS-CONFIABLES-2022-PORTADA.jpg" alt=""
									width="618" height="400" />
								<p id="precio">$5,500,000 COP</p>
								<p id="informacionDelMedioMeCompra">A contado 2021| 57.500 km|Renault Twingo 1.2 Access
								</p>
							</div>
							<div id="carroElemento2" style="display: none;">
								<img src="images/20210208-TOP-75-CARROS-MAS-VENDIDOS-DE-COLOMBIA-EN-ENERO-2021-01.jpg"
									width="618" height="400" alt="" />
								<p id="precio2">$3,300,000 COP</p>
								<p id="informacionDelMedioMeCompra2">A contado 2019| 57.500 km|Fiat 500.14 Sport</p>
							</div>
							<div id="carroElemento3" style="display: none;">
								<img src="images/carros-deportivos-potencia.jpg" width="618" height="400" alt="" />
								<p id="precio3">$4,600,000 COP</p>
								<p id="informacionDelMedioMeCompra3">A contado 2020| 57.500 km|Dodge Journey 2.4 Sxt At
									2400cc</p>
							</div>
							<div id="carroElemento4" style="display: none;">
								<img src="images/5da64f9a11291.r_1571197059653.0-296-1080-1014.jpeg" width="618"
									height="400" alt="" />
								<p id="precio4">$2,800,000 COP</p>
								<p id="informacionDelMedioMeCompra4">A contado 2018| 57.500 km|Bmw Serie 1 120 Cabrio
								</p>
							</div>
							<div id="carroElemento5" style="display: none;">
								<img src="images/20220719-100-CARROS-MAS-VENDIDOS-DE-COLOMBIA-EN-PRIMER-SEMESTRE-DE-2022-01.jpg"
									width="618" height="400" alt="" />
								<p id="precio5">$2,300,000 COP</p>
								<p id="informacionDelMedioMeCompra5">A contado 2017| 57.500 km|Toyota Rav4 Limited 2.5
									Hivrido</p>
							</div>
						</div>
					</div>
				</div>
				<div id="catalogo" style="display: none;">
					<p>
						Te ofrecemos lo mejores catalogos de promocion de las diferentes temporadas.
						Tenemos muchos autos para ayudarte junto con precios justos que te pueden colaborar mucho
					</p>
					<h2 class="ContentCard__title">
						<div class="ContentCard__titleInner">
							Plan Rombo
						</div>
					</h2>
					<p id="informacionDePromociones">
						Te puede interesar:
						¿Conóces el mejor camino para tu Renault cero kilómetros?
						plan Rombo es el mejor camino a tu nuevo Renault.
					</p>
					<img style="display:block" src="images/PlanRombo.png" width="600" height="400" alt="" />
					<a title="" class="ContentCard__ctaLinkLink" data-track="click"
						data-track-button-text="MÁS INFORMACIÓN" data-track-destination="/financiacion/plan-rombo.html"
						data-track-event="navigationClick" href="/financiacion/plan-rombo.html">MÁS INFORMACIÓN</a>

				</div>
				<div id="contactos" style="display: none;">
					<br>
					<p>Para una mejora del servicio dudas e inquietudes podrá recibir atención en:</p>
					<ul>
						<p>Puede contactarnos desde el siguiente E-mail:</p>
						<li>AlquilaCar@gmail.com</li>
						<p>Como también a nuestro número de Whatsapp:</p>
						<li>+57 3166664219</li>
						<p>Otras redes que tenemos a disposicion:</p>
						<li><span><strong>Instagram:</strong></span> @AlquilaCar</li>
						<li><span><strong>Facebook:</strong></span> Alquila_Car1</li>
						<li><span><strong>Twitter:</strong></span> @Alquila_Car0</li>
						<li><span><strong>Yotube:</strong></span> Alquila Car</li>
						<p>Ingrese sus datos en caso del algún inconveniente, será respondido en menos de 24 horas.</p>
						<div class="mb-3">
							<label for="exampleFormControlInput1" class="form-label">Direccion E-mail</label>
							<input type="email" class="form-control" id="exampleFormControlInput1" placeholder="name@example.com">
						</div>
						<div class="mb-3">
							<label for="exampleFormControlTextarea1" class="form-label">Inconveniente</label>
							<textarea class="form-control" id="exampleFormControlTextarea1" rows="3"></textarea>
						</div>
						<button type="button" class="btn btn-info">	Enviar</button>
					</ul>
				</div>

				<div id="authorInfo">
					<h2>Politicas</h2>
					<p>
						Para la empresa es muy importante complacerlos con su automóvil requerido de muy ata calidad,
						por esto mismo estamos pendientes de cualquier inconformidad con el servicio dado.
					</p>
				</div>
			</section>
			<section id="sidebar">
				<input type="text" placeholder="Search">
				<nav>
					<div id="carouselExampleIndicators1" class="carousel slide" data-ride="carousel"
						style="background-color: grey">
						<ol class="carousel-indicators">
							<li data-target="#carouselExampleIndicators1" data-slide-to="0" class="active"></li>
							<li data-target="#carouselExampleIndicators1" data-slide-to="1"></li>
							<li data-target="#carouselExampleIndicators1" data-slide-to="2"></li>
						</ol>
						<div class="carousel-inner" role="listbox">
							<div class="carousel-item active">
								<img class="d-block mx-auto"
									src="images/20211226-CARROS-USADOS-TRASPASOS-2021-COLOMBIA-RECORD-RANKING-01.jpg"
									width="230" height="120" alt="First slide" />
							</div>
							<div class="carousel-item">
								<img class="d-block mx-auto" src="images/NAZ_d39bd89b7cdd45ab8893c911aaa757c8.jpg"
									width="230" height="120" alt="Second slide">
							</div>
							<div class="carousel-item">
								<img class="d-block mx-auto" src="images/trato-venta-coche.jpg" width="230" height="120"
									alt="Third slide">
							</div>
						</div>
						<a class="carousel-control-prev" href="#carouselExampleIndicators1" role="button"
							data-slide="prev">
							<span class="carousel-control-prev-icon" aria-hidden="true"></span>
							<span class="sr-only"><</span>
						</a>
						<a class="carousel-control-next" href="#carouselExampleIndicators1" role="button"
							data-slide="next">
							<span class="carousel-control-next-icon" aria-hidden="true"></span>
							<span class="sr-only">></span>
						</a>
					</div>
					<ul>
						<li><a id="eventClickPrincipal" href="#paginaPrincipal" title="Link">Pagina Principal</a></li>
						<li><a id="eventClickMenu" href="#menu" title="Link">Menu</a></li>
						<li><a id="eventClickGaleria" href="#autos" title="Link">Autos</a></li>
						<li><a id="eventClickCatologo" href="#catalogo" title="Link">Catalogos</a></li>
						<li><a id="eventClickContactenos" href="#contactos" title="Link">Contactenos</a></li>
					</ul>
				</nav>
			</section>
			<footer id="footerbar">
				<article>
					<h3>Politica de privacidad e informacion legal</h3>
					<p>Creado por Elizabeth Mejia Quiceno</p>
					<p>Alquila Car S.A.S - R.M Cali, Tomo 32.063, Folio 52, Hoja B-201.583, Inscripcion 1 NIF B-62084959
					</p>
					<p>©CopyrightAlquilaCar.Reservados todos los derechos</p>
				</article>
			</footer>
		</div>
		<div >
			<!-- Small footerbar at the bottom -->
		</div>
	</div>
	<script src="js/jquery-3.4.1.min.js"></script>
	<script src="js/popper.min.js"></script>
	<script src="js/bootstrap-4.4.1.js"></script>
	<script type="text/javascript">
		document.getElementById("eventClickPrincipal").addEventListener('click', function () {
			document.getElementById("paginaPrincipal").style.display = "block";
			document.getElementById("menu").style.display = "none";
			document.getElementById("autos").style.display = "none";
			document.getElementById("catalogo").style.display = "none";
			document.getElementById("contactos").style.display = "none";
			
			document.getElementById("authorInfo").style.marginTop = "0";
		})

		document.getElementById("eventClickMenu").addEventListener('click', function () {
			document.getElementById("menu").style.display = "block";
			document.getElementById("autos").style.display = "none";
			document.getElementById("paginaPrincipal").style.display = "none";
			document.getElementById("catalogo").style.display = "none";
			document.getElementById("contactos").style.display = "none";

			document.getElementById("authorInfo").style.marginTop = "0";
		})

		document.getElementById("eventClickGaleria").addEventListener('click', function () {
			document.getElementById("autos").style.display = "block";
			document.getElementById("menu").style.display = "none";
			document.getElementById("paginaPrincipal").style.display = "none";
			document.getElementById("catalogo").style.display = "none";
			document.getElementById("contactos").style.display = "none";

			document.getElementById("authorInfo").style.marginTop = "30.1em";
		})

		document.getElementById("eventClickCatologo").addEventListener('click', function () {
			document.getElementById("catalogo").style.display = "block";
			document.getElementById("autos").style.display = "none";
			document.getElementById("menu").style.display = "none";
			document.getElementById("paginaPrincipal").style.display = "none";
			document.getElementById("contactos").style.display = "none";

			document.getElementById("authorInfo").style.marginTop = "0";
		})

		document.getElementById("eventClickContactenos").addEventListener('click', function () {
			document.getElementById("contactos").style.display = "block";
			document.getElementById("catalogo").style.display = "none";
			document.getElementById("autos").style.display = "none";
			document.getElementById("menu").style.display = "none";
			document.getElementById("paginaPrincipal").style.display = "none";

			document.getElementById("authorInfo").style.marginTop = "0";
		})

		document.getElementById("carroContenido1").addEventListener('click', function (event) {
			event.preventDefault();
			document.getElementById("carroElemento1").style.display = "block";
			document.getElementById("carroElemento2").style.display = "none";
			document.getElementById('carroElemento3').style.display = "none";
			document.getElementById("carroElemento4").style.display = "none";
			document.getElementById('carroElemento5').style.display = "none";
		})

		document.getElementById("carroContenido2").addEventListener('click', function (event) {
			event.preventDefault();
			document.getElementById("carroElemento2").style.display = "block";
			document.getElementById("carroElemento1").style.display = "none";
			document.getElementById('carroElemento3').style.display = "none";
			document.getElementById("carroElemento4").style.display = "none";
			document.getElementById('carroElemento5').style.display = "none";
		})

		document.getElementById("carroContenido3").addEventListener('click', function (event) {
			event.preventDefault();
			document.getElementById('carroElemento3').style.display = "block";
			document.getElementById("carroElemento1").style.display = "none";
			document.getElementById("carroElemento2").style.display = "none";
			document.getElementById("carroElemento4").style.display = "none";
			document.getElementById('carroElemento5').style.display = "none";
		})

		document.getElementById("carroContenido4").addEventListener('click', function (event) {
			event.preventDefault();
			document.getElementById("carroElemento4").style.display = "block";
			document.getElementById("carroElemento1").style.display = "none";
			document.getElementById("carroElemento2").style.display = "none";
			document.getElementById('carroElemento3').style.display = "none";
			document.getElementById('carroElemento5').style.display = "none";
		})

		document.getElementById("carroContenido5").addEventListener('click', function (event) {
			event.preventDefault();
			document.getElementById("carroElemento5").style.display = "block";
			document.getElementById("carroElemento1").style.display = "none";
			document.getElementById("carroElemento2").style.display = "none";
			document.getElementById('carroElemento4').style.display = "none";
			document.getElementById('carroElemento3').style.display = "none";

		})
	</script>
</body>

</html>
