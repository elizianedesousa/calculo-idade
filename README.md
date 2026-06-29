<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Outros Pontos Turísticos - Recife Antigo</title>
    <style>
        * { margin: 0; padding: 0; box-sizing: border-box; }
        body { font-family: 'Arial', sans-serif; background-color: #f8f9fa; color: #333; line-height: 1.7; }
        header { background: linear-gradient(to right, #c41e3a, #a01830); color: white; padding: 40px 20px; text-align: center; }
        header h1 { font-size: 2.5rem; margin-bottom: 10px; }
        nav { background: #333; padding: 15px; text-align: center; }
        nav a { color: white; text-decoration: none; font-weight: bold; padding: 10px 20px; }
        nav a:hover { background: #c41e3a; border-radius: 5px; }
        main { max-width: 1000px; margin: 40px auto; padding: 0 20px; }
        .ponto-turistico { background: white; padding: 35px; border-radius: 12px; box-shadow: 0 5px 15px rgba(0,0,0,0.08); margin-bottom: 40px; }
        .ponto-turistico h2 { color: #c41e3a; font-size: 2rem; margin-bottom: 20px; border-bottom: 3px solid #0066b3; padding-bottom: 10px; }
        .ponto-turistico p { margin-bottom: 20px; text-align: justify; font-size: 1.05rem; }
        /* IMAGENS DOS LUGARES - Requisito 2 */
        .ponto-turistico img { width: 100%; height: 350px; object-fit: cover; border-radius: 10px; margin: 20px 0; box-shadow: 0 4px 8px rgba(0,0,0,0.15); }
        .info-box { background: #e3f2fd; border-left: 5px solid #0066b3; padding: 20px; margin: 25px 0; border-radius: 8px; }
        strong { color: #c41e3a; }
        footer { background: #333; color: white; text-align: center; padding: 30px 20px; margin-top: 50px; }
    </style>
</head>
<body>
    <header>
        <h1>Recife Antigo: Mais Tesouros</h1>
        <p>Além do Marco Zero, conheça outros lugares incríveis</p>
    </header>
    
    <nav>
        <a href="index.html">← Voltar para o Marco Zero</a>
    </nav>
    
    <main>
        <!-- PONTO TURÍSTICO 1 -->
        <section class="ponto-turistico">
            <h2>1. Paço do Frevo</h2>
            <img src="https://images.unsplash.com/photo-1543722530-d2c3201371e7?w=900" alt="Fachada do Paço do Frevo no Recife Antigo">
            <p>
                O <strong>Paço do Frevo</strong> é um museu dedicado 100% ao frevo, ritmo declarado 
                <em>Patrimônio Imaterial da Humanidade</em> pela UNESCO. Localizado num casarão histórico de 
                1888, o espaço celebra essa expressão cultural pernambucana através de exposições, 
                oficinas e apresentações.
            </p>
            <div class="info-box">
                <p><strong>Endereço:</strong> Praça do Arsenal da Marinha, s/n - Recife Antigo</p>
                <p><strong>Funcionamento:</strong> Terça a sexta, das 9h às 17h. Sábados e domingos, das 14h às 18h</p>
                <p><strong>Entrada:</strong> Gratuita às terças-feiras</p>
            </div>
            <p>
                No museu você encontra <strong>sombreiros</strong>, estandartes, partituras originais e 
                pode até aprender os primeiros passos do frevo com instrutores. A vista do terraço 
                para o Rio Capibaribe é espetacular.
            </p>
        </section>
        
        <!-- PONTO TURÍSTICO 2 -->
        <section class="ponto-turistico">
            <h2>2. Embaixada dos Bonecos Gigantes</h2>
            <img src="https://images.unsplash.com/photo-1610641818989-c2051b5e2cfd?w=900" alt="Bonecos gigantes de Olinda expostos">
            <p>
                A <strong>Embaixada dos Bonecos Gigantes</strong> guarda os famosos bonecos que desfilam no 
                Carnaval de Olinda. São mais de 500 bonecos que retratam personalidades como 
                <em>Chico Science</em>, Michael Jackson, Alceu Valença e até figuras políticas.
            </p>
            <div class="info-box">
                <p><strong>Localização:</strong> Rua do Bom Jesus, 183 - Recife Antigo</p>
                <p><strong>Curiosidade:</strong> Cada boneco tem cerca de 3,5 metros de altura e pesa 20kg</p>
                <p><strong>Dica:</strong> Melhor horário pra fotos é de manhã, com menos movimento</p>
            </div>
            <p>
                O espaço funciona o ano todo e é uma ótima opção pra quem visita Recife fora do Carnaval. 
                Os bonecos são feitos de fibra de vidro e madeira, e o processo de criação leva até 
                <strong>3 meses</strong> por boneco. Você pode tirar fotos com todos eles!
            </p>
        </section>
    </main>
</body>
</html>
