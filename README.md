<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Site sobre Pães</title>
    <style>
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f9f9f9;
            color: #333;
            line-height: 1.6;
        }
        header {
            background-color: #8B4513;
            color: white;
            padding: 20px;
            text-align: center;
        }
        nav {
            margin-top: 10px;
        }
        nav a {
            margin: 0 15px;
            text-decoration: none;
            color: #FFD700;
            font-weight: bold;
            transition: color 0.3s;
        }
        nav a:hover {
            color: #FFF;
        }
        section {
            margin: 40px auto;
            max-width: 800px;
            padding: 20px;
            background-color: white;
            border-radius: 8px;
            box-shadow: 0 0 10px rgba(0,0,0,0.1);
        }
        h1, h2, h3 {
            color: #8B4513;
        }
        ul {
            list-style-type: disc;
            margin-left: 20px;
        }
        img {
            max-width: 200px;
            margin: 10px;
            border-radius: 8px;
            box-shadow: 0 0 5px rgba(0,0,0,0.2);
        }
        .galeria {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
        }
        footer {
            text-align: center;
            padding: 10px;
            background-color: #8B4513;
            color: white;
            margin-top: 20px;
        }
        @media (max-width: 600px) {
            nav a {
                display: block;
                margin: 10px 0;
            }
            .galeria {
                flex-direction: column;
                align-items: center;
            }
        }
    </style>
</head>
<body>
    <header>
        <h1>Site sobre Pães</h1>
        <nav>
            <a href="#home">Página Inicial</a>
            <a href="#tipos">Tipos de Pães</a>
            <a href="#historia">História do Pão</a>
            <a href="#receitas">Receitas</a>
            <a href="#galeria">Galeria</a>
        </nav>
    </header>

    <section id="home">
        <h2>Página Inicial</h2>
        <p>Bem-vindo ao nosso site dedicado ao fascinante mundo dos pães! Aqui, você encontrará informações sobre tipos variados, sua história milenar e receitas deliciosas. Explore as seções abaixo para descobrir mais.</p>
        <ul>
            <li><a href="#tipos">Tipos de Pães</a></li>
            <li><a href="#historia">História do Pão</a></li>
            <li><a href="#receitas">Receitas</a></li>
            <li><a href="#galeria">Galeria</a></li>
        </ul>
    </section>

    <section id="tipos">
        <h2>Tipos de Pães</h2>
        <p>Existem diversos tipos de pães ao redor do mundo, cada um com características únicas. Aqui vai uma lista detalhada:</p>
        <ul>
            <li><strong>Pão Francês (Baguette):</strong> Originário da França, é longo, crocante por fora e macio por dentro. Ideal para sanduíches.</li>
            <li><strong>Pão de Forma:</strong> Macio e fatiado, perfeito para torradas. Muito popular em cafés da manhã.</li>
            <li><strong>Pão Sírio (Pita):</strong> Plano e inflado, usado para wraps e acompanhamentos.</li>
            <li><strong>Pão de Centeio:</strong> Escuro e denso, com sabor forte, comum na Europa Oriental.</li>
            <li><strong>Pão Ázimo:</strong> Sem fermento, usado em tradições judaicas e cristãs.</li>
            <li><strong>Pão de Milho:</strong> Feito com farinha de milho, popular no Brasil e EUA.</li>
            <li><strong>Ciapatta:</strong> Italiana, plana e com bolhas grandes, perfeita para bruschetta.</li>
            <li><strong>Pão de Queijo:</strong> Brasileiro, feito com polvilho e queijo, leve e crocante.</li>
        </ul>
    </section>

    <section id="historia">
        <h2>História do Pão</h2>
        <p>O pão tem raízes antigas, datando de cerca de 10.000 anos atrás, durante a Revolução Agrícola no Oriente Médio. Os primeiros pães eram feitos de grãos moídos e água, assados em pedras quentes. Sua importância histórica é imensa: foi um alimento básico para civilizações antigas, como egípcios, gregos e romanos, simbolizando sustento e prosperidade. No Egito Antigo, o pão era tão valorizado que era usado como moeda. Ao longo dos séculos, evoluiu com a fermentação (descoberta acidental), levando a variedades modernas. Hoje, representa cultura, tradição e inovação culinária global.</p>
        <p>Para mais detalhes, visite <a href="https://en.wikipedia.org/wiki/History_of_bread" target="_blank">Wikipedia - História do Pão</a>.</p>
    </section>

    <section id="receitas">
        <h2>Receitas</h2>
        <p>Aqui estão algumas receitas populares e simples de pães. Experimente em casa!</p>
        <h3>1. Pão de Forma Caseiro</h3>
        <p><strong>Ingredientes:</strong> 500g farinha de trigo, 300ml leite morno, 50g manteiga, 1 ovo, 10g fermento biológico, sal a gosto.</p>
        <p><strong>Modo de Preparo:</strong> Misture o fermento com leite morno. Adicione farinha, sal, ovo e manteiga. Sove por 10 minutos. Deixe descansar por 1 hora. Asse em forma untada a 180°C por 30 minutos.</p>
        
        <h3>2. Baguette Francesa</h3>
        <p><strong>Ingredientes:</strong> 500g farinha de trigo, 300ml água, 10g sal, 5g fermento seco.</p>
        <p><strong>Modo de Preparo:</strong> Misture todos os ingredientes. Sove por 15 minutos. Deixe fermentar por 2 horas. Modele em baguetes e asse a 220°C por 20-25 minutos.</p>
        
        <h3>3. Pão de Milho</h3>
        <p><strong>Ingredientes:</strong> 200g farinha de milho, 100g farinha de trigo, 200ml leite, 50g manteiga, 1 ovo, sal.</p>
        <p><strong>Modo de Preparo:</strong> Misture tudo em uma tigela. Despeje em forma untada. Asse a 180°C por 25 minutos.</p>
        
        <h3>4. Pão de Queijo</h3>
        <p><strong>Ingredientes:</strong> 500g polvilho doce, 200g queijo parmesão ralado, 200ml leite, 100ml óleo, 3 ovos, sal.</p>
        <p><strong>Modo de Preparo:</strong> Ferva leite e óleo. Misture com polvilho. Adicione ovos, queijo e sal. Forme bolinhas e asse a 180°C por 20 minutos.</p>
    </section>

    <section id="galeria">
        <h2>Galeria</h2>
        <p>Imagens dos pães mais representativos:</p>
        <div class="galeria">
            <img src="https://example.com/baguette.jpg" alt="Baguette Francesa" title="Baguette Francesa">
            <img src="https://example.com/pao-forma.jpg" alt="Pão de Forma" title="Pão de Forma">
            <img src="https://example.com/pita.jpg" alt="Pão Pita" title="Pão Pita">
            <img src="https://example.com/pao-centeio.jpg" alt="Pão de Centeio" title="Pão de Centeio">
            <img src="https://example.com/pao-milho.jpg" alt="Pão de Milho" title="Pão de Milho">
            <img src="https://example.com/ciabatta.jpg" alt="Ciabatta" title="Ciabatta">
            <img src="https://example.com/pao-queijo.jpg" alt="Pão de Queijo" title="Pão de Queijo">
        </div>
        <p><em>Nota: Substitua os URLs das imagens por links reais para visualizar. Para uma galeria interativa, considere adicionar JavaScript para um slideshow.</em></p>
    </section>

    <footer>
        <p>&copy; 2023 Site sobre Pães. Todos os direitos reservados.</p>
    </footer>
</body>
</html>
