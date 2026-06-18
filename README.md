<!DOCTYPE html>
<html lang="pt-br">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Blog Tech</title>

    <style>
        body {
            margin: 0;
            font-family: Arial, sans-serif;
            background-color: #f2f2f2;
        }

        header {
            background-color: #183C63;
            color: #FFFFFF;
            text-align: center;
            padding: 20px;
        }

        main {
            background-color: #FFFFFF;
            color: #183C63;

            max-width: 800px;
            margin: 20px auto;
            padding: 20px;

            display: flex;
            gap: 20px;
            align-items: flex-start;
        }

        img {
            width: 80px;
            height: 80px;
        }

        .conteudo {
            display: flex;
            flex-direction: column;
        }

        .artigo-autor {
            font-weight: bold;
        }

        /* Botão de like */
        button {
            margin-top: 10px;
            padding: 8px 12px;
            border: none;
            border-radius: 6px;
            cursor: pointer;
            font-size: 16px;
            background-color: #eee;
        }

        button:hover {
            background-color: #ddd;
        }
    </style>

</head>

<body>

    <header>
        <h1>Meu blog tech</h1>
        <p>Vou compartilhar conhecimentos sobre tecnologia e programação</p>
    </header>

    <main>

        <img src="imagem.png" alt="Logotipo de tecnologia e educação com livro e cérebro digital">

        <div class="conteudo">

            <h2>Meu primeiro post</h2>

            <p class="artigo-autor">Por: Marcelo Paludetto</p>

            <p>
                Boas-vindas ao meu novo blog! Aqui vou compartilhar dicas de programação e curiosidades da área de tecnologia.
            </p>

            <!-- Botão de like -->
            <button>
                ❤️ <span>0</span>
            </button>

        </div>

    </main>

    <script>
        const botao = document.querySelector("button");

        botao.addEventListener("click", botaoClicado);

        function botaoClicado() {
            let texto = botao.querySelector("span");
            texto.textContent++;
        }
    </script>

</body>

</html>
