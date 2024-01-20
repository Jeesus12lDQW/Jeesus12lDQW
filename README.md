<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Pregunta</title>
</head>
<body>

    <h1>Pregunta:</h1>
    <p>¿Go rapidin?</p>

    <button onclick="responder('si')">Sí</button>

    <script>
        function responder(respuesta) {
            if (respuesta === 'si') {
                // Redirige al usuario a otra página o realiza alguna acción
                alert('¡Perfecto! Vamos al cuarto a conversar.');
                // Puedes redirigir a otra página usando window.location.href
                // window.location.href = 'nueva_pagina.html';
            } else {
                // Otra acción en caso de otra respuesta
                alert('Quizás en otro momento entonces.');
            }
        }
    </script>

</body>
</html>

