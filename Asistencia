<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Generador de Ideas Mejorado</title>
    <style>
        body {
            margin: 0;
            padding: 0;
            font-family: "Poppins", sans-serif;
            background: linear-gradient(135deg, #6a11cb, #2575fc);
            height: 100vh;
            display: flex;
            justify-content: center;
            align-items: center;
            color: white;
        }

        .card {
            background: rgba(255, 255, 255, 0.15);
            backdrop-filter: blur(15px);
            padding: 40px;
            border-radius: 20px;
            text-align: center;
            max-width: 450px;
            width: 90%;
            box-shadow: 0 8px 25px rgba(0,0,0,0.2);
            animation: fadeIn 1s ease;
        }

        @keyframes fadeIn {
            from {opacity: 0; transform: translateY(20px);}
            to {opacity: 1; transform: translateY(0);}
        }

        h1 {
            margin-bottom: 10px;
            font-size: 28px;
            font-weight: 600;
        }

        p {
            margin-bottom: 25px;
            opacity: 0.8;
            font-size: 16px;
        }

        button {
            padding: 15px 25px;
            background: #ffffff;
            border: none;
            border-radius: 10px;
            font-size: 16px;
            cursor: pointer;
            color: #2575fc;
            font-weight: bold;
            transition: transform 0.2s, box-shadow 0.2s;
        }

        button:hover {
            transform: scale(1.05);
            box-shadow: 0 5px 15px rgba(255,255,255,0.4);
        }

        .resultado {
            margin-top: 25px;
            font-size: 22px;
            font-weight: bold;
            min-height: 40px;
            animation: aparecer 0.4s ease forwards;
        }

        @keyframes aparecer {
            from {opacity: 0; transform: scale(0.9);}
            to {opacity: 1; transform: scale(1);}
        }
    </style>
</head>
<body>

<div class="card">
    <h1>Generador de Ideas</h1>
    <p>Pulsa el botón para generar una idea aleatoria</p>

    <button onclick="generarIdea()">Generar idea</button>

    <div class="resultado" id="resultado"></div>
</div>

<script>
    const ideas = [
        "Crear una aplicación que ayude a organizar tareas diarias",
        "Diseñar una página web interactiva para aprender idiomas",
        "Desarrollar un juego sencillo en JavaScript",
        "Crear un blog con artículos cortos pero útiles",
        "Lanzar un canal educativo sobre tecnología",
        "Hacer un generador de nombres o historias",
        "Construir una herramienta web para emprendedores",
        "Diseñar un portafolio moderno para mostrar proyectos",
        "Crear un mini chatbot sencillo con JavaScript",
        "Hacer una herramienta para crear logos básicos"
    ];

    function generarIdea() {
        const index = Math.floor(Math.random() * ideas.length);
        const resultado = document.getElementById("resultado");
        
        resultado.style.opacity = 0;

        setTimeout(() => {
            resultado.textContent = ideas[index];
            resultado.style.opacity = 1;
        }, 200);
    }
</script>

</body>
</html>
