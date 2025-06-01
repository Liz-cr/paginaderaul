<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Pagina de Coco</title>
    <style>
        body {
            background-color: black;
            color: orange;
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
        }
        .navbar {
            display: flex;
            justify-content: center;
            background-color: #333;
            padding: 10px;
        }
        .navbar a {
            color: orange;
            text-decoration: none;
            font-size: 18px;
            margin: 0 25px;
            padding: 10px;
            transition: background-color 0.3s, color 0.3s;
        }
        .navbar a:hover {
            background-color: #39ff14;
            color: black;
            border-radius: 5px;
        }
        .container {
            display: flex;
            padding: 20px;
        }
        .column {
            padding: 10px;
        }
        .menu {
            width: 20%;
            background-color: #222;
            padding: 15px;
        }
        .menu a {
            display: block;
            color: orange;
            text-decoration: none;
            padding: 8px;
            transition: background-color 0.3s;
        }
        .menu a:hover {
            background-color: #39ff14;
            color: black;
        }
        .text-content {
            width: 50%;
        }
        .image-container {
            width: 30%;
        }
        .image-container img {
            width: 100%;
            border: 2px solid orange;
        }
    </style>
</head>
<body>

    <div class="navbar">
        <a href="#">Universidad</a>
        <a href="#">Mestría</a>
        <a href="#">Doctorado</a>
        <a href="#">Mensiones Honorificas</a>
        <a href="#">Premios</a>
    </div>

    <div class="container">
        <div class="column menu">
            <h3>Articulos Publicados</h3>
            <a href="#">Opción 1</a>
            <a href="#">Opción 2</a>
            <a href="#">Opción 3</a>
            <a href="#">Opción 4</a>
            <a href="#">Opción 5</a>
            <a href="#">Opción 6</a>
            <a href="#">Opción 7</a>
            <a href="#">Opción 8</a>
            <a href="#">Opción 9</a>
            <a href="#">Opción 10</a>
            <a href="#">Opción 11</a>
            <a href="#">Opción 12</a>
            <a href="#">Opción 13</a>
        </div>

        <div class="column text-content">
            <h1>Neuro científico. Raúl Hernández Pérez </h1>
            <p>Investiga cómo el cerebro subyace a los procesos cognitivos y el comportamiento, como la percepción, la atención, la memoria, el lenguaje y la toma de decisionesen los perros.</p>
        </div>

        <div class="column image-container">
            <img src="https://images.unsplash.com/photo-1560807707-8cc77767d783" alt="Border Collie" title="Te amo Lizbeth">
        </div>
    </div>

</body>
</html>
