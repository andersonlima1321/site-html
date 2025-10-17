<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <!--meta http-equiv="refresh" content="5; url=Resultado.html"-->
    <title>Sorteio de Nomes</title>
    <link rel="stylesheet" href="./css/index.css"> <!-- Opcional: para adicionar estilo -->
</head>
<body>
    <h1>Sorteio de Nomes</h1>

    <input type="text" id="nomeInput" placeholder="Digite um nome..."><br><br>
    <button id="adicionarBtn">Adicionar à Lista</button>

    <h2>Lista de Nomes</h2>
    <ul id="listaNomes">
        <!-- Os nomes serão adicionados aqui -->
    </ul>

    <button id="sortearBtn" >Sortear Nomes</button>
    
    <!--h1>Nomes Sorteados</h1-->
    <div> 
        <ol class="mover.centros" id="resultados">

        </ol>
    </div>
     

    <script src="./js/index.js"></script>
</body>
</html>
