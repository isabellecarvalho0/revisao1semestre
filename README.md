<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Problema 3</title>
</head>
<body>
    <h1>Problema 3</h1>
    <input type = "text" id="txtNome" value=""><button onclick="escreve()"> Enviar </button>
    <br>
    <input type = "text" id="txtidade" value=""><button onclick="escreve2()"> Enviar </button>
    <br>
    <input type = "text" id="txtcidade" value=""><button onclick="escreve3()"> Enviar </button>
    <br>
    <div id="msg"></div>
    <script>
         function escreve(){
            var nome = document.querySelector('#txtNome').value;
            document.querySelector('#msg').innerHTML= " Bem-Vindo <b> " + nome + "</b>";
         }
         function escreve2(){
            var idade = document.querySelector('#txtidade').value;
            document.querySelector('#msg').innerHTML= " Sua idade é: <b> " + idade + "</b>";
         }
         function escreve3(){
            var cidade = document.querySelector('#txtcidade').value;
            document.querySelector('#msg').innerHTML= " Sua cidade é:<b> " + cidade + "</b>";
         }
       
    </script>
</body>
</html>
