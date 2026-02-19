# books <!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Gracias por el Libro | Donaciones</title>
    <style>
        :root {
            --beige: #fdf6e3;
            --cafe: #5c4033;
            --dorado: #c5a059;
            --texto: #2c2c2c;
        }

        body {
            font-family: 'Georgia', serif;
            background-color: var(--beige);
            color: var(--texto);
            margin: 0;
            display: flex;
            justify-content: center;
            align-items: center;
            min-height: 100vh;
            padding: 20px;
        }

        .container {
            max-width: 500px;
            background: #ffffff;
            padding: 40px;
            border-radius: 15px;
            box-shadow: 0 10px 30px rgba(0,0,0,0.1);
            text-align: center;
            border-top: 8px solid var(--cafe);
        }

        h1 {
            color: var(--cafe);
            font-size: 2rem;
            margin-bottom: 10px;
        }

        .icon {
            font-size: 50px;
            margin-bottom: 20px;
        }

        p {
            line-height: 1.6;
            font-size: 1.1rem;
            margin-bottom: 30px;
        }

        .donation-box {
            background-color: #fafafa;
            border: 1px dashed var(--dorado);
            padding: 20px;
            border-radius: 10px;
            margin-bottom: 30px;
        }

        .btn-donate {
            display: inline-block;
            background-color: var(--cafe);
            color: white;
            padding: 15px 30px;
            text-decoration: none;
            border-radius: 50px;
            font-weight: bold;
            transition: transform 0.3s, background-color 0.3s;
            box-shadow: 0 4px 15px rgba(92, 64, 51, 0.3);
        }

        .btn-donate:hover {
            background-color: var(--dorado);
            transform: translateY(-3px);
        }

        footer {
            margin-top: 20px;
            font-size: 0.9rem;
            color: #888;
        }
    </style>
</head>
<body>

    <div class="container">
        <div class="icon">📖✨</div>
        <h1>¡Gracias por leer!</h1>
        <p>
            Regalar un libro es compartir un mundo. Si la historia que te llevaste te gustó y quieres apoyar para que pueda seguir rescatando y regalando más libros, cualquier granito de arena es bienvenido.
        </p>

        <div class="donation-box">
            <p style="margin-bottom: 15px; font-weight: bold;">¿Me invitas un café de agradecimiento?</p>
            <a href="paypal.me/DavidEscobarSalguero" class="btn-donate">☕ Donar con PayPal / Café</a>
        </div>

        <footer>
            "Un libro es un regalo que puedes abrir una y otra vez."
        </footer>
    </div>

</body>
</html>
