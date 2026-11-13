<!DOCTYPE html>
<html lang="es-MX">
<head>
    <meta charset="UTF-8">
    <title>Plataforma Aprende Programación</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        body {
            background-color: #e8f4fc;
            font-family: Arial, sans-serif;
            padding: 60px 20px;
        }
        .contenedor {
            background-color: #ffffff;
            max-width: 700px;
            margin: 0 auto;
            padding: 40px;
            border-radius: 16px;
        }
        h1 {
            color: #1976D2;
            text-align: center;
            margin-bottom: 20px;
        }
        p {
            font-size: 18px;
            text-align: center;
            margin-bottom: 30px;
        }
        button {
            display: block;
            margin: 0 auto;
            padding: 14px 24px;
            font-size: 18px;
            border: none;
            border-radius: 10px;
            background-color: #2196F3;
            color: white;
            cursor: pointer;
        }
    </style>
</head>
<body>
    <div class="contenedor">
        <h1>¡Hola Mundo! 👋</h1>
        <p>Bienvenido a nuestra plataforma para aprender programación en español</p>
        <button onclick="mostrarMensaje()">Presiona aquí</button>
    </div>

    <script>
        function mostrarMensaje() {
            alert("¡Hola Mundo! ✅ Iniciamos la plataforma de programación en español");
        }
    </script>
</body>
</html>
