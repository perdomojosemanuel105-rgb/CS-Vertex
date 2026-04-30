# CS-Vertex
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>CS2 Skin Hub | Elite Selection</title>
    <link href="https://fonts.googleapis.com/css2?family=Rajdhani:wght@600;700&display=swap" rel="stylesheet">
    <style>
        :root {
            --cs-orange: #ff8400;
            --black-90: rgba(10, 10, 10, 0.95);
            --glass-black: rgba(0, 0, 0, 0.85);
        }

        body {
            margin: 0;
            padding: 0;
            font-family: 'Rajdhani', sans-serif;
            color: white;
            /* RUTA ACTUALIZADA A TU CARPETA IMG */
            background: url('img/counterstrike-3lourqobllt98xdr.jpg') no-repeat center center fixed;
            background-size: cover;
            min-height: 100vh;
        }

        /* Capa para mejorar la lectura sobre el fondo */
        .overlay-dark {
            background: linear-gradient(180deg, rgba(0,0,0,0.7) 0%, rgba(0,0,0,0.3) 50%, rgba(0,0,0,0.9) 100%);
            min-height: 100vh;
            width: 100%;
        }

        /* MENÚ PRINCIPAL CON TODAS LAS OPCIONES */
        header {
            background: var(--black-90);
            border-bottom: 3px solid var(--cs-orange);
            padding: 20px 0;
            position: sticky;
            top: 0;
            z-index: 1000;
            box-shadow: 0 4px 20px rgba(0,0,0,0.8);
        }

        .nav-container {
            max-width: 1200px;
            margin: 0 auto;
            display: flex;
            justify-content: center;
            gap: 40px;
        }

        nav a {
            text-decoration: none;
            color: white;
            font-size: 1.2rem;
            font-weight: 700;
            text-transform: uppercase;
            letter-spacing: 2px;
            transition: 0.3s ease;
        }

        nav a:hover, nav a.active {
            color: var(--cs-orange);
            text-shadow: 0 0 10px var(--cs-orange);
        }

        /* ÁREA DE CONTENIDO[cite: 2] */
        .main-content {
            display: flex;
            justify-content: center;
            align-items: center;
            padding: 80px 20px;
        }

        /* TARJETA DE LA GALIL */
        .skin-card {
            background: var(--glass-black);
            backdrop-filter: blur(10px);
            border: 1px solid rgba(255, 132, 0, 0.4);
            width: 360px;
            padding: 30px;
            border-radius: 4px;
            text-align: center;
            transition: 0.4s;
        }

        .skin-card:hover {
            border-color: var(--cs-orange);
            transform: translateY(-10px);
            box-shadow: 0 0 40px rgba(255, 132, 0, 0.3);
        }

        .tag {
            background: var(--cs-orange);
            color: black;
            font-weight: 700;
            padding: 4px 12px;
            text-transform: uppercase;
            display: inline-block;
            margin-bottom: 20px;
            font-size: 0.8rem;
        }

        .weapon-img-box {
            height: 180px;
            display: flex;
            align-items: center;
            justify-content: center;
            margin-bottom: 25px;
        }

        .weapon-img-box img {
            max-width: 100%;
            filter: drop-shadow(0 10px 20px rgba(0,0,0,1));
        }

        .skin-title {
            font-size: 1.7rem;
            margin: 0;
            text-transform: uppercase;
            letter-spacing: 1px;
        }

        .skin-desc {
            color: #ccc;
            margin: 10px 0 30px 0;
            font-size: 0.9rem;
        }

        /* BOTÓN DE DESCARGA MEDIAFIRE[cite: 1, 2] */
        .btn-mediafire {
            display: block;
            background: var(--cs-orange);
            color: black;
            text-decoration: none;
            padding: 15px;
            font-weight: 700;
            font-size: 1.1rem;
            text-transform: uppercase;
            border-radius: 2px;
            transition: 0.3s;
        }

        .btn-mediafire:hover {
            background: #ffa441;
            box-shadow: 0 0 25px var(--cs-orange);
            transform: scale(1.02);
        }

    </style>
</head>
<body>

    <div class="overlay-dark">
        
        <!-- MENÚ ACTUALIZADO[cite: 2] -->
        <header>
            <nav class="nav-container">
                <a href="#" class="active">Skins Armas</a>
                <a href="#">Modelos Personajes</a>
                <a href="#">Servidores</a>
                <a href="#">Comunidad</a>
            </nav>
        </header>

        <main class="main-content">
            
            <!-- TARJETA DE LA GALIL CON TU LINK[cite: 1, 2] -->
            <div class="skin-card">
                <span class="tag">Rifle de Asalto</span>
                
                <div class="weapon-img-box">
                    <!-- Asegúrate de que galil.png esté en la carpeta 'img'[cite: 1, 2] -->
                    <img src="img/galil.png" alt="Galil AR" onerror="this.src='https://via.placeholder.com/300x150/000/ff8400?text=V_GALIL.MDL'">
                </div>

                <div class="info-box">
                    <h3 class="skin-title">Galil AR | Custom</h3>
                    <p class="skin-desc">Archivo: v_galil.mdl <br> Calidad: Recién Fabricado</p>
                </div>

                <!-- TU ENLACE DE MEDIAFIRE INTEGRADO[cite: 1, 2] -->
                <a href="https://www.mediafire.com/file/01wux4gtbw5ddhu/v_galil.mdl/file" 
                   target="_blank" 
                   class="btn-mediafire">
                    Descargar de Mediafire
                </a>
            </div>

        </main>

    </div>

</body>
</html>
