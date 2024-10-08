<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Persona Form</title>
</head>
<body>
    <h1>Defina seu Perfil</h1>
    <form action="/submit_form" method="POST">
        <label for="company">Nome da Empresa/Pessoa:</label>
        <input type="text" id="company" name="company" required><br><br>

        <label for="sector">Setor de Atuação:</label>
        <input type="text" id="sector" name="sector" required><br><br>

        <label for="size">Tamanho da Empresa:</label>
        <select id="size" name="size">
            <option value="pequena">Pequena</option>
            <option value="media">Média</option>
            <option value="grande">Grande</option>
        </select><br><br>

        <label for="goals">Objetivos Estratégicos:</label>
        <input type="text" id="goals" name="goals"><br><br>

        <label for="market_position">Posição no Mercado:</label>
        <input type="text" id="market_position" name="market_position"><br><br>

        <button type="submit">Enviar</button>
    </form>
</body>
</html>
