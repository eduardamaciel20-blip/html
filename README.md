<!DOCTYPE html>
<html lang="pt-br">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Blog Tech</title>

    <style>
        /* Reset básico */
        body {
            margin: 0;
            font-family: Arial, sans-serif;
            background-color: #f2f2f2;
        }

        /* Cabeçalho */
        header {
            background-color: #183C63;
            color: #FFFFFF;
            text-align: center;
            padding: 20px;
        }

        /* Área principal */
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

        /* Imagem */
        img {
            width: 80px;
            height: 80px;
        }

        /* Bloco de texto */
        .conteudo {
            display: flex;
            flex-direction: column;
        }

        /* Autor em destaque */
        .artigo-autor {
            font-weight: bold;
        }
    </style>

</head>

<body>

    <!-- Cabeçalho do site -->
    <header>
        <h1>Meu blog tech</h1>
        <p>Vou compartilhar conhecimentos sobre tecnologia e programação</p>
    </header>

    <!-- Conteúdo principal -->
    <main>

        <!-- Imagem do post -->
        <img src="imagem.png" alt="Logotipo de tecnologia e educação com livro e cérebro digital">

        <!-- Conteúdo do post -->
        <div class="conteudo">

            <h2>Meu primeiro post</h2>

            <p class="artigo-autor">Por: Marcelo Paludetto</p>

            <p>
                Boas-vindas ao meu novo blog! Aqui vou compartilhar dicas de programação e curiosidades da área de tecnologia.
            </p>

        </div>

    </main>

</body>

</html>
