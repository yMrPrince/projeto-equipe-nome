# projeto-equipe-nome
index.html

<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>GameZone</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

    <header>
        <h1>GameZone</h1>
        <p>Loja Gamer Fictícia</p>
    </header>

    <main>

        <section class="produto">
            <h2>PlayStation 5</h2>
            <p>Console de nova geração.</p>
            <button>Comprar</button>
        </section>

        <section class="produto">
            <h2>Xbox Series S</h2>
            <p>Console compacto e poderoso.</p>
            <button>Comprar</button>
        </section>

        <section class="produto">
            <h2>Cadeira Gamer</h2>
            <p>Conforto para jogar por horas.</p>
            <button>Comprar</button>
        </section>

    </main>

    <footer>
        <p>Projeto desenvolvido pela equipe.</p>
    </footer>

</body>
</html>


---

style.css

body {
    font-family: Arial, sans-serif;
    background-color: #111;
    color: white;
    margin: 0;
    padding: 0;
}

header {
    background-color: #1f1f1f;
    text-align: center;
    padding: 20px;
}

main {
    display: flex;
    justify-content: center;
    gap: 20px;
    padding: 20px;
    flex-wrap: wrap;
}

.produto {
    background-color: #222;
    padding: 20px;
    border-radius: 10px;
    width: 220px;
    text-align: center;
}

button {
    background-color: #00bfff;
    border: none;
    padding: 10px;
    color: white;
    border-radius: 5px;
    cursor: pointer;
}

footer {
    text-align: center;
    padding: 20px;
}


---

README.md
