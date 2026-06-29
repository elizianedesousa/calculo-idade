<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Lugares Turísticos na Europa</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        
        body {
            font-family: 'Segoe UI', Arial, sans-serif;
            background-color: #f5f7fa;
            color: #333;
            line-height: 1.6;
        }
        
        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 20px;
        }
        
        header {
            text-align: center;
            padding: 50px 20px;
            background: linear-gradient(135deg, #2c3e50, #3498db);
            color: white;
            margin-bottom: 40px;
        }
        
        header h1 {
            font-size: 2.8rem;
            margin-bottom: 10px;
        }
        
        header p {
            font-size: 1.2rem;
            opacity: 0.9;
        }
        
        .intro {
            text-align: center;
            margin-bottom: 50px;
            padding: 0 20px;
        }
        
        .intro h2 {
            font-size: 2rem;
            color: #2c3e50;
            margin-bottom: 15px;
        }
        
        .cards-container {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            gap: 30px;
        }
        
        .card {
            background: white;
            border-radius: 15px;
            box-shadow: 0 5px 15px rgba(0,0,0,0.1);
            overflow: hidden;
            width: 350px;
            transition: transform 0.3s ease;
        }
        
        .card:hover {
            transform: translateY(-10px);
        }
        
        .card img {
            width: 100%;
            height: 220px;
            object-fit: cover;
        }
        
        .card-content {
            padding: 25px;
        }
        
        .card-content h3 {
            font-size: 1.5rem;
            color: #2c3e50;
            margin-bottom: 10px;
        }
        
        .card-content .local {
            color: #3498db;
            font-weight: 600;
            margin-bottom: 15px;
            display: block;
        }
        
        .card-content p {
            color: #555;
            margin-bottom: 20px;
            text-align: justify;
        }
        
        .tag {
            display: inline-block;
            background: #e3f2fd;
            color: #1976d2;
            padding: 5px 12px;
            border-radius: 20px;
            font-size: 0.85rem;
            margin-right: 8px;
            margin-bottom: 8px;
        }
        
        footer {
            text-align: center;
            padding: 30px;
            background: #2c3e50;
            color: white;
            margin-top: 60px;
        }
    </style>
</head>
<body>
    <header>
        <h1>Destinos Imperdíveis na Europa</h1>
        <p>Conheça os lugares mais incríveis para sua próxima viagem</p>
    </header>
    
    <main class="container">
        <section class="intro">
            <h2>Explore o Velho Continente</h2>
            <p>A Europa reúne história, cultura, gastronomia e paisagens de tirar o fôlego. Confira 6 destinos que você precisa conhecer.</p>
        </section>
        
        <section class="cards-container">
            <!-- Card 1: Paris -->
            <div class="card">
                <img src="https://images.unsplash.com/photo-1431274172761-fca41d930114?w=600" alt="Torre Eiffel em Paris">
                <div class="card-content">
                    <h3>Torre Eiffel</h3>
                    <span class="local">Paris, França</span>
                    <p>O símbolo mais famoso de Paris e da França. Com 330 metros de altura, oferece uma vista panorâmica incrível da cidade luz. Melhor horário para visitar: pôr do sol.</p>
                    <span class="tag">Romântico</span>
                    <span class="tag">Histórico</span>
                    <span class="tag">Arquitetura</span>
                </div>
            </div>
            
            <!-- Card 2: Roma -->
            <div class="card">
                <img src="https://images.unsplash.com/photo-1552832230-c0197dd311b5?w=600" alt="Coliseu em Roma">
                <div class="card-content">
                    <h3>Coliseu</h3>
                    <span class="local">Roma, Itália</span>
                    <p>Anfiteatro construído no século I d.C., palco de gladiadores e espetáculos do Império Romano. É Patrimônio Mundial da UNESCO e uma das 7 Maravilhas do Mundo Moderno.</p>
                    <span class="tag">História Antiga</span>
                    <span class="tag">UNESCO</span>
                    <span class="tag">Cultural</span>
                </div>
            </div>
            
            <!-- Card 3: Santorini -->
            <div class="card">
                <img src="https://images.unsplash.com/photo-1613395877344-13d4a8e0d49e?w=600" alt="Casas brancas de Santorini">
                <div class="card-content">
                    <h3>Oia, Santorini</h3>
                    <span class="local">Grécia</span>
                    <p>Ilha grega famosa pelas casinhas brancas com telhados azuis e o pôr do sol mais bonito do mundo. Formada por uma erupção vulcânica, tem praias de areia preta e vermelha.</p>
                    <span class="tag">Praia</span>
                    <span class="tag">Pôr do sol</span>
                    <span class="tag">Fotogênico</span>
                </div>
            </div>
            
            <!-- Card 4: Londres -->
            <div class="card">
                <img src="https://images.unsplash.com/photo-1513635269975-59663e0ac1ad?w=600" alt="Big Ben em Londres">
                <div class="card-content">
                    <h3>Big Ben e Parlamento</h3>
                    <span class="local">Londres, Inglaterra</span>
                    <p>O relógio mais famoso do mundo fica ao lado do Palácio de Westminster. Símbolo de Londres, o Big Ben na verdade é o nome do sino dentro da torre Elizabeth.</p>
                    <span class="tag">Monarquia</span>
                    <span class="tag">Política</span>
                    <span class="tag">Clássico</span>
                </div>
            </div>
            
            <!-- Card 5: Barcelona -->
            <div class="card">
                <img src="https://images.unsplash.com/photo-1583422409516-2895a77efded?w=600" alt="Sagrada Família em Barcelona">
                <div class="card-content">
                    <h3>Sagrada Família</h3>
                    <span class="local">Barcelona, Espanha</span>
                    <p>Basílica projetada por Antoni Gaudí, em construção desde 1882. Mistura estilos gótico e Art Nouveau. A previsão é que fique pronta em 2026, 100 anos após a morte de Gaudí.</p>
                    <span class="tag">Arquitetura</span>
                    <span class="tag">Gaudí</span>
                    <span class="tag">Inacabada</span>
                </div>
            </div>
            
            <!-- Card 6: Amsterdã -->
            <div class="card">
                <img src="https://images.unsplash.com/photo-1534351590666-13e3e96b5017?w=600" alt="Canais de Amsterdã">
                <div class="card-content">
                    <h3>Canais de Amsterdã</h3>
                    <span class="local">Amsterdã, Holanda</span>
                    <p>A "Veneza do Norte" tem mais de 100 km de canais construídos no século XVII. Passeio de barco é obrigatório. A cidade também é famosa pelas bicicletas e museus.</p>
                    <span class="tag">Canais</span>
                    <span class="tag">Bicicleta</span>
                    <span class="tag">Museus</span>
                </div>
            </div>
        </section>
    </main>
    
    <footer>
        <p>&copy; 2026 - Projeto HTML/CSS | JoyClass ArcelorMittal</p>
        <p>Imagens: Unsplash</p>
    </footer>
</body>
</html>
