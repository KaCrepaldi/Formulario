# Formulario

<!DOCTYPE html>
<html lang="en">
<head>
     <meta charset="UTF-8">
     <meta http-equiv="X-UA-Compatible" content="IE=edge">
     <meta name="viewport" content="width=device-width, initial-scale=1.0">
     <link rel="stylesheet" href="style.css.html">
     <title>JavaScript</title>
</head>
<body>

    <div clas="container">

          <div class="mensagem"></div>

        <form id="formulario-02">
          <h2>Faça seu cadastro</h2>
          <input type="text" placeholder="digite seu nome" class="obrigatorio" name="nome">
          <input type="text" placeholder="digite seu email" class="email" name="email">
          <input type="text" placeholder="digite seu telefone" class="" name="telefone">
          <input type="text" placeholder="digite seu cep" class="numerico" name="cep"> 00000-000
          <input type="text" placeholder="digite sua cidade" class="obrigatorio" name="cidade">
          <input type="text" placeholder="digite seu uf" class="uf" name="uf">
          <button type="submit">Enviar</button>
     </form>
        
      <div id="resultado">
          
        </div>

      </div>


        <script type="text/JavaScript" src="./script.js"></script>
</body>
</html>


