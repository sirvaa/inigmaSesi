```
<!DOCTYPE html>
<html>
<head>
 <title>Senha Secreta</title>
 <style>
  body { font-family: Arial, sans-serif; }
  #resultado { color: green; }
 </style>
</head>
<body>
 <h1>Senha:</h1>
 <input type="password" id="senha" />
 <button onclick="verificarSenha()">Verificar</button>
 <p id="resultado"></p>

 <script>
  function verificarSenha() {
   var senha = document.getElementById('senha').value;
   if (senha === 'elefante') {
    document.getElementById('resultado').innerHTML = 'Você acertou!';
    document.getElementById('resultado').style.color = 'green';
   } else {
    document.getElementById('resultado').innerHTML = 'Senha incorreta';
    document.getElementById('resultado').style.color = 'red';
   }
  }
 </script>
</body>
</html>
```# inigmaSesi
