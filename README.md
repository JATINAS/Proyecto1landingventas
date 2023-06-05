# Proyecto1landingventas
This repository is about project 1, "LANDING DE VENTAS"

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" ref="CSS/styles.css">
    <title>IRON BYCICLE</title>
    <style>
        .header {
            position: absolute;
            top: 50%;
            left: 50%;
            transform: translate(-50%,-50%);
            font-size: 500%;
            font-family:'Times New Roman', Times, serif;
            color: white;
        }
        

        .barranav {
            margin: 0%;
            padding: 0%;
            overflow: hidden;
            background-color: rgb(2, 155, 198);
            position: -webkit-sticky;
            position: sticky;
            top: 0;
        }

        .barranav a {
            float: left;
            display: block;
            color: black;
            text-align: center;
            padding: 2% 1%;
            text-decoration: none;
            font-size: 120%;
        }

        .barranav a:hover {
            background-color: slategray;
            color: white;
        }

        .imglogo {
            float: left;
            margin: 10px 50px 10px 10px;
        }

        .contenedor {
            position: relative;
        }

        .imgheader {
            width: 100%;
            height: 400px;
        }

        .buscador {
            float: right;
            display: block;
            padding: 2% 1%;           
        }

        .fondo {
            background-color: dimgray;
        }

        .column {
            float: left;
            width: 30%;
            border-radius: 20px;
       }

        .rowcolumn {
            content: "";
            display: table;
            clear: both;
            margin-bottom: 5%;
            margin-top: 5%;
        }

        .rowfooter {
            content: "";
            display: table;
            clear: both;
        }

        .columnfooter {
            float: left;
            width: 45%;
       }

       .end {
            content: "";
            display: table;
            clear: both;
            background-color: rgb(2, 155, 198);
            margin-top: 3%;
            width: 100%;
       }

       .endcolumn {
            float: left;
       }

        a.one:link, a.one:visited {
            background-color: white;
            color: black;
            border: 2px solid rgb(2, 155, 198);
            padding: 5px 15px;
            text-align: center;
            text-decoration: none;
            display: inline-block;
        }

        a.one:hover, a.one:active {
            background-color: rgb(2, 155, 198);
            color: white;
        }

        @media screen and (max-width: 800px) {
            .column, .rowfooter, .columnfooter {
                width: 100%;
                margin-top: 5%;
            }
        }

        @media  and (max-width: 500px) {
            .barranav{
                float: none;
                width: 100%
            }
            
        }

        @media and (max-width: 800px) {
            .end {
                float: none;
                width: 100%;
            }
        }

        @media and (max-width: 800px) {
            .endcolumn {
                float: none;
                width: 30%;
                margin: 0%;
                padding: 0%;
                margin-top: 5%;
                font-size: 5%;
            }
        }


    </style>
</head>
<body class="fondo">
    <header>
        
        <div class="contenedor">
            <img class="imgheader" src="images/encabezado.jpg" alt="Ciclista">
            <h1 class="header">IRON BYCICLE</h1>
        </div>
        
        <div class="barranav">
            <img class="imglogo" src="images/logo_bici.jpg" alt="Logo oficial" width="50" height="50">
                <a href="index.html">Inicio</a>
                <a href="#">Conocenos</a>
                <a href="#">Contactanos</a>
                <div class="buscador">
                    <input type="text" placeholder="Ingresa tu correo" id="user" name="user">
                    <input style="background-color: rgb(2, 155, 198); color: white; border-color: white; font-weight: bold;" type="submit" value="Enviar">
                </div>
                <a href="#" style="float:right">Iniciar sesion</a>
        </div>
    </header>

    <jumbotron>
        <div class="rowcolumn">
            
            <div class="column" style="background-color: white;">
                <img src="images/bicicletaplegable.webp" alt="Bicicleta plegable" style="width: 100%; align-items: center; height: 405px; border-radius: 20px;">
                <h2 style="text-align: justify; padding: 5%;">BICICLETA PLEGABLE</h2>
                <p style="text-align: justify; padding: 5%;">Bicicleta plegable, dividida en tres secciones, ideal para viajes a largas distancias y mayor comodidad a la hora de transportarla.</p>
            </div>

            <div class="column" style="margin-left: 5%; margin-right: 5%; background-color: white;">
                <img src="images/Bicicletamontana.jpg" alt="Bicicleta de montaña" style="width: 100%; align-items: center; height: 405px; border-radius: 20px;">
                <h2 style="text-align: justify; padding: 5%;">BICICLETA DE MONTAÑA</h2>
                <p style="text-align: justify; padding: 5%;">Bicicletas de varias marcas enfocadas en viajes con terrenos dificiles, variedad de tamaños segun el ususario, amortiguadores, accesorios y mas.</p>
            </div>

            <div class="column" style="background-color: white;">
                <img src="images/bicicletaruta.jpg" alt="Bicicleta de ruta" style="width: 100%; align-items: center; height: 405px; border-radius: 20px;">
                <h2 style="text-align: justify; padding: 5%;">BICICLETA DE RUTA</h2>
                <p style="text-align: justify; padding: 5%;">Bicicleta ideal para carreteras, extremadamente ligeras, tamaños variados, accesorios disponibles. </p>
            </div>
        </div>
    </jumbotron>

    <footer>
        <div class="rowfooter">

            <div class="columnfooter" style="margin-right: 2%;">
                <img src="images/footer2.jpeg" alt="footer2" style="height: auto; width: 100%;">
            </div>
    
            <div class="columnfooter" style="text-align: right;color: white; font-family:Arial, Helvetica, sans-serif; padding: 1%; padding-top: 3%;">
                <br><br><br>
                <p style="text-align: center;">TE ASESORAMOS CON TUS COMPRAS</p>
                <h2 style="text-align: justify; width: 100%;">Busca la ayuda de nuestros vendedores para brindarte un servicio personalizado en cualquiera de nuestras sucursales</h2>
                <p style="text-align: justify; width: 100%;">IRON BYCICLE es una tienda de bicicletas de varios diseños y tipos ofrecemos una alta calidad en nuestros productos y servicios con la absoluta certeza de que nuestros clientes saldran satisfechos de la sucursal.</p>
            </div>
        </div>

        <div class="end">

            <div class="endcolumn" style="width: 30%; background-color: blueviolet;">
                <a href="#facebook"><img  id="face" src="images/face.png" alt="icono de facebook" width="10%" height="2%" style="padding: 1%; margin-left: 30%;" ></a>
                <a href="#twitter"><img id="twitter" src="images/twiter.png" alt="icono de twitter" width="10%" height="2%" style="padding: 1%; padding-left: 1%;"></a>
                <a href="#instagram"><img id="insta" src="images/insta.png" alt="icono de instagram" width="10%" height="2%" style="padding: 1%; padding-left: 1%;"></a>
                <a href="#whatsapp"><img id="whats" src="images/whats.png" alt="icono de whatsapp" width="10%" height="2%" style="padding: 1%; padding-left: 1%;"></a>
            </div>

            <div class="endcolumn" style="width: 10%;">
                <h3>BICICLETAS</h3>
                <a class="one" href="#catalogo" target="_blank">Catalogo</a>
            </div>

            <div class="endcolumn" style="width: 10%; margin-left: 10%;">
                <h3>SOPORTE</h3>
                <a class="one" href="#catalogo" target="_blank" style="margin-bottom: 5%;">Cotizaciones</a>
                <a class="one" href="#catalogo" target="_blank" style="margin-top: 5%;">Certificaciones</a>
                <a class="one" href="#catalogo" target="_blank" style="margin-top: 10%;">Ayuda tecnica</a>
            </div>

            <div class="endcolumn" style="width: 10%; margin-left: 10%;">
                <h3>ACERCA DE</h3>
                <a class="one" href="#catalogo" target="_blank" style="margin-bottom: 5%;">Blog</a>
                <a class="one" href="#catalogo" target="_blank" style="margin-top: 5%;">Partners</a>
                <a class="one" href="#catalogo" target="_blank" style="margin-top: 10%;">Apoyos</a>
            </div>

        </div>
    </footer>
    
    
</body>
</html>
