<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Jumpscare Prank</title>
    <style>
        body {
            text-align: center;
            padding: 50px;
            font-family: Arial, sans-serif;
        }

        iframe {
            display: none; /* O iframe não será exibido inicialmente */
        }
    </style>
</head>
<body>
    <h1>Atenção: Este site contém um jumpscare!</h1>
    <p>É apenas uma brincadeira para fins de diversão. Clique no botão abaixo se estiver preparado.</p>
    <button onclick="exibirJumpscare()">Mostrar Jumpscare</button>

    <iframe id="jumpscareVideo" width="560" height="315" src="https://www.youtube.com/embed/T1oT940nozc" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

    <script>
        function exibirJumpscare() {
            // Exibe o iframe ao clicar no botão
            document.getElementById('jumpscareVideo').style.display = 'block';
        }
    </script>
</body>
</html>

