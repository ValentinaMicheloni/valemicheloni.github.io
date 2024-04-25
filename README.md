<html lang="es"><head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ficha Personal</title>
    <link rel="stylesheet" href="c:\Users\Usuario\OneDrive\Documentos\UADE\Diseño y desarrollo web\Styles.css.css">
</head>
<body>
    <header>
        <h1>Diseño y Desarrollo web</h1>
    </header>
    <main>
        <div class="left-block">
            <img src="c:\Users\Usuario\Downloads\Fotos Personales.jpeg" alt="Foto Personal">
        </div>
        <div class="right-block">
            <p><strong>Nombre y Apellido:</strong> Valentina Micheloni</p>
            <p><strong>Carrera:</strong> Licenciatura en Gestión Tecnologica de la Información </p>
            <p><strong>Curso:</strong> 2763</p>
            <p><strong>Proyecto:</strong>Pequeños Placeres</p>
            <p><strong>Sitio profesional:</strong> <a href=" https://valentinamicheloni.github.io/" target="_blank">Pequeños Placeres</a></p>
            <p><strong>Descripción:</strong>Emprendimiento pastelero dedicado a endulzar la vida de las personas</p>
            <p><strong>Prototipo:</strong> <a href="" target="_blank">Enlace prototipo de Pequeños Placeres</a></p>
            <p><strong>Repositorio:</strong> <a href="https://valeemicheloni.github.io/" target="_blank">Enlace repositorio</a></p>
        </div>
    </main>
    <footer>
        <img src="c:\Users\Usuario\Downloads\Logotipo Uade.jpeg" width="150px" height="100px" alt="Logo UADE" >
    </footer>


<span id="PING_CONTENT_AUTOPLAY_DETECTION" style="display: none;"></span></body></html>


@import url("https://fonts.googleapis.com/css2?family=Poppins:wght@400;500;600;700;800&display=swap");
 
body {
    front-family: "Poppins", sans-serif;
    margin: 0;
    padding: 0;
}

header {
    text-align: center;
    text-transform: uppercase;
    background-color: darksalmon;
    color: black;
    ;
    padding: 20 px 0;
}

main {
    display: flex;
    justify-content: space-around;
    margin-top: 21px;
}

.left-block {
    flex: 1;
    text-align: center;
}

.left-block img {
    width: 150px;
    height: auto;
    margin-bottom: 10px;
}

.right-block { 
    flex: 2;
    padding: 0 20px;
}

.right-block p {
    margin-bottom: 10px;
}

a {
    color: black;
    text-decoration: none;
}

a:hover {
    text-decoration: underline;
}

footer { 
    text-align: center;
    padding: 16px 0;
    background-color: darksalmon;
}  
