<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Minha Página Web</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f0f0f0;
            color: #333;
            margin: 0;
            padding: 0;
        }
        header {
            background-color: #007bff;
            color: white;
            padding: 20px;
            text-align: center;
        }
        footer {
            background-color: #343a40;
            color: white;
            text-align: center;
            padding: 10px;
            position: fixed;
            width: 100%;
            bottom: 0;
        }
        .content {
            padding: 20px;
            text-align: center;
        }
        button {
            padding: 10px 20px;
            background-color: #28a745;
            color: white;
            border: none;
            border-radius: 5px;
            cursor: pointer;
        }
        button:hover {
            background-color: #218838;
        }
    </style>
</head>
<body>

<header>
    <h1>Bem-vindo! Disciplina 11</h1>
</header>

<div class="content">
    <p>Página HTML talento tech.</p>
    <button onclick="exibirMensagem()">Clique aqui</button>
</div>

<footer>
    <p>&copy; 2025 Minha Página Web. Felipe Silva.</p>
</footer>

<script>
    function exibirMensagem() {
        alert("Você clicou no botão!");
    }
</script>

</body>
</html>
