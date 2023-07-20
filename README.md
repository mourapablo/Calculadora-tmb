# Calculadora-tmb
Feito em html css e js calculadora da Taxa Metabolica basal
<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet" href="brincando.css">
</head>
<body>
    <header id="cabecalho">
        <div class="same-size">
        <h1>calculo para consumo de calorias</h1>
        <label for="nomes">Digite se nome:</label>
        <input type="text" id="nomes"><br><br>
        <label for="idade">Digite sua idade:</label>
        <input type="number" id="idade"><br><br>
        <label for="altura">Digite sua altura (cm):</label>
        <input type="number" id="altura"><br><br>
        <label for="pesos">Digite seu peso atual(kg):</label>
        <input type="number" id="pesos"><br><br>
        
        
        
        <label for="exer">Nível de atividade física:</label>
        <select id="exer">
          <option value="sedentario">Sedentário</option>
          <option value="leve">Leve (1-3 dias por semana)</option>
          <option value="moderado">Moderado (3-5 dias por semana)</option>
          <option value="ativo">Ativo (6-7 dias por semana)</option>
          <option value="muitoativo">Muito ativo (2 vezes por dia, treinos intensos)</option>
        </select><br><br>
        <label for="sexo">Sexo:</label>
        <select id="sexo">
           
            <option value="masculino">Masculino</option>
            <option value="feminino">Feminino</option>
          </select><br><br>
        
        <button onclick="calcular()">Calcular TMB</button>
        
        <p id="res"></p>
    </div>
    </header>
        
</body>
<script src="exer.js"></script>
</html>
