# HomeBankingTeste-

<html>
  <head>
    <title>Controle de Despesas</title>
    <meta charset="utf-8">
    <link rel="stylesheet" href="Untitled-100.css"/>
  </head>
  <body>
    <div class="login-card">
        <h2>Seja bem-vindo ao seu HomeBanking </h2>
        <h3>Insira suas credenciais</h3>

        <!-- Inserindo qualquer nome e qualquer senha sera redirecionado para a homebanking-->

        <input spellcheck="false" class="control" type="text" placeholder="Nome"/>
        <input spellcheck="false" class="control" id="password" type="password" placeholder="Senha"/>
        <button onclick="redirecionar()">Entrar</button>

    <script>
        // Redirecionando ao HomeBanking 
       function redirecionar() {
          window.location.href = "file:///C:/Users/Dommus-9/index.html1.html";
       }
    </script>
  </body>
</html>
