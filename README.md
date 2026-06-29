<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Marco Zero - Recife</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        
        body {
            font-family: 'Arial', sans-serif;
            background-color: #f8f9fa;
            color: #333;
            line-height: 1.7;
        }
        
        /* 1. CABEÇALHO - Requisito 1 */
        header {
            background: linear-gradient(to right, #0066b3, #004c8c);
            color: white;
            padding: 40px 20px;
            text-align: center;
            box-shadow: 0 4px 6px rgba(0,0,0,0.1);
        }
        
        header h1 {
            font-size: 2.5rem;
            margin-bottom: 10px;
            text-shadow: 2px 2px 4px rgba(0,0,0,0.3);
        }
        
        header p {
            font-size: 1.1rem;
            font-style: italic;
        }
        
        /* 2. CONTEÚDO - Requisito 1 */
        main {
            max-width: 1000px;
            margin: 40px auto;
            padding: 0 20px;
        }
        
        article {
            background: white;
            padding: 35px;
            border-radius: 12px;
            box-shadow: 0 5px 15px rgba(0,0,0,0.08);
            margin-bottom: 30px;
        }
        
        article h2 {
            color: #0066b3;
            font-size: 2rem;
            margin-bottom: 20px;
            border-bottom: 3px solid #ffcc00;
            padding-bottom: 10px;
        }
        
        article p {
            margin-bottom: 20px;
            text-align: justify;
            font-size: 1.05rem;
        }
        
        /* 3. IMAGENS - Requisito 2 */
        .galeria {
            display: flex;
            gap: 20px;
            margin: 30px 0;
            flex-wrap: wrap;
        }
        
        .galeria img {
            width: 100%;
            max-width: 480px;
            height: 300px;
            object-fit: cover;
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0,0,0,0.15);
            flex: 1;
        }
        
        .destaque {
            background: #fff3cd;
            border-left: 5px solid #ffcc00;
            padding: 20px;
            margin: 25px 0;
            border-radius: 8px;
        }
        
        /* 4. TAG SEMÂNTICA TEXTUAL INLINE - Requisito 3 */
        /* Usando <strong>, <em>, <mark> e <abbr> */
        
        strong {
            color: #0066b3;
        }
        
        mark {
            background-color: #ffcc00;
            padding: 2px 6px;
            border-radius: 3px;
        }
        
        abbr {
            text-decoration: underline dotted;
            cursor: help;
        }
        
        /* 5. RODAPÉ - Requisito 1 */
        footer {
            background: #333;
            color: white;
            text-align: center;
            padding: 30px 20px;
            margin-top: 50px;
        }
        
        footer p {
            margin: 8px 0;
        }
        
        .creditos {
            font-size: 0.9rem;
            opacity: 0.8;
            margin-top: 15px;
        }
    </style>
</head>
<body>
    <!-- CABEÇALHO -->
    <header>
        <h1>Marco Zero do Recife</h1>
        <p>O coração da capital pernambucana</p>
    </header>
    
    <!-- CONTEÚDO PRINCIPAL -->
    <main>
        <article>
            <h2>Conheça o Marco Zero</h2>
            
            <p>
                O <strong>Marco Zero</strong> é um dos pontos turísticos mais importantes de <em>Recife</em>. 
                Localizado no bairro do Recife Antigo, é o ponto de onde se iniciam todas as medições 
                oficiais de distâncias rodoviárias da cidade.
            </p>
            
            <div class="galeria">
                <img src="https://images.unsplash.com/photo-1621214046682-8c0a2b0f2a1b?w=800" 
                     alt="Praça do Marco Zero com vista para o mar">
                <img src="https://images.unsplash.com/photo-1694545074751-d11b2a4a7b6e?w=800" 
                     alt="Rosa dos Ventos no chão do Marco Zero">
            </div>
            
            <p>
                Inaugurada em <mark>2000</mark>, a praça abriga a famosa <em>Rosa dos Ventos</em>, obra do artista 
                plástico pernambucano <strong>Cícero Dias</strong>. Com 20 metros de diâmetro, ela indica as direções 
                cardeais e é um dos cenários mais fotografados da cidade.
            </p>
            
            <div class="destaque">
                <p>
                    <strong>Curiosidade:</strong> O nome "Marco Zero" vem do fato de que ali está o 
                    <abbr title="Ponto de referência para medições geográficas">marco inicial</abbr> 
                    de onde são contadas as distâncias de Recife para outras cidades. É considerado o 
                    <em>quilômetro zero</em> da capital.
                </p>
            </div>
            
            <h2>O que fazer no Marco Zero?</h2>
            <p>
                A região é cercada por prédios históricos, como o <strong>Centro de Artesanato de Pernambuco</strong> 
                e a <strong>Caixa Cultural</strong>. Aos domingos, acontece a <mark>Feira de Artesanato</mark> 
                com produtos típicos do Nordeste. Durante o Carnaval, a praça vira palco principal com 
                shows gratuitos de grandes artistas.
            </p>
            
            <p>
                À noite, o local fica todo iluminado e é ponto de encontro de turistas e recifenses. 
                Do Marco Zero você tem vista para o <em>Parque das Esculturas de Francisco Brennand</em> 
                e para os antigos armazéns do porto, que hoje viraram bares e restaurantes.
            </p>
        </article>
    </main>
    </footer>
</body>
</html>
