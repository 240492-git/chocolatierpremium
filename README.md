<html>
    <head>
        <link rel="preconnect" href="https://fonts.googleapis.com">
        <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
        <link href="https://fonts.googleapis.com/css2?family=Playwrite+RO:wght@100..400&display=swap" rel="stylesheet">
        <title>Chocolatier</title>
        <style>
            body {
                font-family: Arial, sans-serif;
                background-color: #f4f4f4; /* Cor de fundo da página */
            }
            .form-container {
                margin-top: 20px;
                background-color: #f8d3e3; /* Cor rosa suave para a div */
                padding: 20px;
                border-radius: 8px; /* Bordas arredondadas */
                box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1); /* Sombra leve */
            }
            h1, h2 {
                font-family: 'Playwrite RO', cursive;
            }
            button {
                background-color: #ff69b4; /* Cor rosa para o botão */
                color: white; /* Cor do texto do botão */
                border: none; /* Remove borda padrão */
                padding: 10px 15px; /* Espaçamento interno */
                border-radius: 5px; /* Bordas arredondadas */
                cursor: pointer; /* Muda o cursor ao passar sobre o botão */
            }
            button:hover {
                background-color: #ff1493; /* Cor ao passar o mouse */
            }
        </style>
    </head>
    <body>
        <h1>Chocolatier</h1>
        <h2>O Melhor Chocolate da sua vida!</h2>
        <img src="chocolatetest.png" alt="Chocolate">
        <h2>Descubra a nova experiência dos amantes de chocolate! A nossa chocolatier está prestes a lançar planos de assinatura incríveis, trazendo os melhores chocolates premium diretamente para a sua porta, todo mês.
            Delicie-se com uma seleção exclusiva de chocolates, cuidadosamente escolhidos para tornar seus dias ainda mais especiais. Transforme sua rotina com o sabor irresistível dos nossos chocolates, entregues mensalmente para você.
            Não perca a chance de fazer parte dessa experiência deliciosa! Assine já e permita que o prazer do chocolate premium faça parte do seu cotidiano.
        </h2>

        <h1>Informações Cliente</h1>
        <div class="form-container">
            <form action="https://formspree.io/f/mgvkwqey" method="POST">
                <p>
                    <label>Digite Seu Telefone</label><br>
                    <input placeholder="Digite Aqui" type="text" required="required" name="Telefone">
                </p>
                <p>
                    <label>Digite qual seu Chocolate Preferido</label><br>
                    <textarea name="ChocolatePreferido" required="required"></textarea>
                </p>
                <p>
                    <label>Escolha o Melhor Plano</label><br>
                    <select name="Plano">
                        <option value="Premium">Plano Premium</option>
                        <option value="Intermediaria">Intermediária</option>
                        <option value="Basico">Plano Básico</option>
                    </select>
                </p>
                <button type="submit">Enviar</button>
            </form>
        </div>
    </body>
</html>
