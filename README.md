HTML5-
======

<!DOCTYPE html>
<html lang="es">
<head>
<meta charset='utf-8'>
<link rel="stylesheet" href= "jota.css">
</head>
<body>
<div id ='contenido'>
<header>
<hgroup>
<h1>Aplicando las nuevas Etiquetas de HTML5<h1>
</hgroup>
<nav>
<ul>
<li>Inicio</li>
<li>Tutoriales</li>
<li>Contacto</li>
<li>Media</li>
</ul>
</nav>
<header>
<section>
<div id='textoPr'>
<hgroup>
<h1>LENGUAJES DE PROGRAMCON</h1>
</hgroup>
<p>HTML:<meter min = '0' max='100' value='70'>70%</meter></p>
<p>PHP:<meter min = '0' max='100' value='20'>20%</meter></p>
<p>CSS:<meter min = '0' max='100' value='80'>80%</meter></p>

<h1>Datos Personales</h1>
<form>
<label for= 'nombre'>Nombre:</label>
<input type= 'text' id ='naombre' placeholder ='Escribe tu nombre' required>
<label for= 'correo'>E-mail:</label>
<input type= 'email' id ='correo'placeholder='Escribe tu e-mail' required>
<label for= 'edad'>Edad:</label>
<input type= 'number' id ='edad'>
<label for= 'calificacion'>Calificacion:</label>
<input type= 'range' id ='calificacion' min='0' max='10'value='0'>
<label for= 'fecha'>Fecha:</label>
<input type= 'date' id ='fecha'>
<input type= 'submit' value='enviar' id='btnSubmit'>
</form>
<h1>Video</h1>
<video width = '320' height= '240' controls 'controls'>
<source src='HTML5 - Video.mp4' type = 'video/mp4' />
</video>
<h1>Audio</h1>
<audio controls='control' autoplay='autoplay' loop='loop'>
<source src='Wisin El Sobreviviente - Que Viva La Vida (WWW.ELGENERO.COM).mp3' type='audio/mp3'/>
</audio>
</div>
</section>
</div>
<footer>
<canvas id ='miCanvas'>
</canvas>
</body>
</html>

HTML5
