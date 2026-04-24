[README.md](https://github.com/user-attachments/files/27034968/README.md)
# 🎯 Jogo do Número Secreto

Um jogo simples onde você tenta adivinhar um número entre 1 e 100.

## Como Jogar

1. Digite um número
2. Clique em "Chutar"
3. Receba a dica se o número é maior ou menor
4. Continue até acertar!

## Tecnologias

- HTML5<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Jogo do Número Secreto</title>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;700&display=swap" rel="stylesheet">
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Inter', sans-serif;
            background: linear-gradient(135deg, #1354A5, #041832);
            color: #fff;
            min-height: 100vh;
            padding: 40px 20px;
        }

        .container {
            max-width: 600px;
            margin: 0 auto;
        }

        h1 {
            font-size: 2.5rem;
            margin-bottom: 10px;
            text-align: center;
        }

        .subtitle {
            text-align: center;
            color: #b0b0b0;
            margin-bottom: 40px;
            font-size: 1.1rem;
        }

        section {
            background: rgba(255, 255, 255, 0.05);
            border: 1px solid rgba(24, 117, 232, 0.3);
            border-radius: 12px;
            padding: 25px;
            margin-bottom: 20px;
            backdrop-filter: blur(10px);
        }

        h2 {
            color: #64B5F6;
            font-size: 1.5rem;
            margin-bottom: 15px;
        }

        p {
            margin-bottom: 10px;
            line-height: 1.6;
            color: #e0e0e0;
        }

        ol {
            margin-left: 20px;
            color: #e0e0e0;
            line-height: 1.8;
        }

        li {
            margin-bottom: 10px;
        }

        .tech-list {
            display: flex;
            gap: 10px;
            flex-wrap: wrap;
            margin-top: 10px;
        }

        .tech-badge {
            background: #1875E8;
            padding: 8px 15px;
            border-radius: 20px;
            font-size: 0.9rem;
        }

        footer {
            text-align: center;
            margin-top: 40px;
            color: #808080;
            font-size: 0.9rem;
        }

        @media (max-width: 600px) {
            h1 {
                font-size: 2rem;
            }

            section {
                padding: 20px;
            }

            h2 {
                font-size: 1.3rem;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>🎯 Jogo do Número Secreto</h1>
        <p class="subtitle">Um jogo simples e divertido em JavaScript</p>

        <section>
            <h2>Sobre</h2>
            <p>
                Um jogo onde você tenta adivinhar um número entre 1 e 100. 
                Receba dicas se o número é maior ou menor e veja quantas tentativas levou para acertar.
            </p>
        </section>

        <section>
            <h2>Como Jogar</h2>
            <ol>
                <li>Digite um número de 1 a 100</li>
                <li>Clique em "Chutar"</li>
                <li>Receba a dica (maior ou menor)</li>
                <li>Continue até acertar!</li>
            </ol>
        </section>

        <section>
            <h2>Tecnologias</h2>
            <div class="tech-list">
                <div class="tech-badge">HTML5</div>
                <div class="tech-badge">CSS3</div>
                <div class="tech-badge">JavaScript</div>
            </div>
        </section>

        <section>
            <h2>Como Usar</h2>
            <p>1. Abra o arquivo <strong>index.html</strong> no navegador</p>
            <p>2. Começe a jogar!</p>
        </section>

        <section>
            <h2>Estrutura do Projeto</h2>
            <p>
                📁 index.html<br>
                📁 style.css<br>
                📁 app.js<br>
                📁 img/
            </p>
        </section>

        <footer>
            <p>Desenvolvido por <strong>Kaio Costa</strong> 🇧🇷</p>
            <p>Florianópolis, SC</p>
        </footer>
    </div>
</body>
</html>
- CSS3
- JavaScript

## Como Usar

Abra o arquivo `index.html` no navegador.

## Autor

Kaio Costa
[README.html](https://github.com/user-attachments/files/27034973/README.html)
