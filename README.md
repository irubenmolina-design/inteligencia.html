!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, user-scalable=no">
    <title>Inteligencias</title>
    
    <!-- Configuración para iPhone (Modo App) -->
    <meta name="apple-mobile-web-app-capable" content="yes">
    <meta name="apple-mobile-web-app-status-bar-style" content="black-translucent">
    <meta name="apple-mobile-web-app-title" content="Inteligencias">
    <link rel="apple-touch-icon" href="https://via.placeholder.com/180/000000/FFFFFF?text=IA">

    <style>
        :root {
            --bg-color: #000000;
            --pill-bg: #1a1a1a;
            --text-color: #ffffff;
            --accent-color: #333333;
        }

        body {
            background-color: var(--bg-color);
            color: var(--text-color);
            font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Helvetica, Arial, sans-serif;
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            min-height: 100vh;
            margin: 0;
            padding: 20px;
        }

        h1 {
            font-size: 2.5rem;
            font-weight: 700;
            margin-bottom: 2rem;
            letter-spacing: -0.05em;
        }

        .container {
            width: 100%;
            max-width: 400px;
            display: flex;
            flex-direction: column;
            gap: 15px;
        }

        .pill {
            background-color: var(--pill-bg);
            border: 1px solid var(--accent-color);
            color: var(--text-color);
            text-decoration: none;
            padding: 18px 25px;
            border-radius: 50px;
            font-size: 1.1rem;
            font-weight: 500;
            text-align: center;
            transition: transform 0.2s, background-color 0.2s;
            display: block;
        }

        /* Efecto al tocar en iPhone */
        .pill:active {
            transform: scale(0.96);
            background-color: var(--accent-color);
        }

        .footer {
            margin-top: 3rem;
            font-size: 0.8rem;
            color: #666;
        }
    </style>
</head

