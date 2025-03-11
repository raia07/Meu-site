<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>BH CULT</title>
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Poppins', sans-serif;
            background-color: #fff;
            color: #990000; /* Vermelho */
            margin: 0;
            padding: 0;
        }
        header {
            background-color: #990000; /* Vermelho */
            color: white;
            text-align: center;
            padding: 20px;
        }
        header h1 {
            margin: 0;
            font-size: 40px;
        }
        header p {
            font-size: 25px;
            margin: 10px 0;
        }
        .content {
            margin: 20px;
        }
        .map-container {
            margin-top: 20px;
        }
        .buttons {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            margin-top: 20px;
        }
        .btn {
            background-color: #990000; /* Vermelho */
            color: white;
            padding: 10px 20px;
            margin: 10px;
            border: none;
            cursor: pointer;
            border-radius: 5px;
            font-size: 18px;
            transition: background-color 0.3s;
        }
        .btn:hover {
            background-color: #660000; /* Tom mais escuro de vermelho */
        }
        .description {
            margin-top: 20px;
            background-color: white;
            padding: 20px;
            border-radius: 5px;
            box-shadow: 0 4px 8px rgba(0,0,0,0.1);
            display: none;
            color: #333;
        }
        .description img {
           width: 100%; /* Ocupa toda a largura disponível */
           max-width: 800px; /* Limita a largura máxima */
           height: auto; /* Mantém a proporção da imagem */
           display: block;
           margin: 20px auto; /* Centraliza a imagem */
           border-radius: 5px;   
        }
        .content {
           max-width: 900px; /* Define uma largura máxima */
           margin: 0 auto; /* Centraliza o conteúdo */
           padding: 20px; /* Adiciona espaçamento interno */
        }
        .description {
           max-width: 800px; /* Mantém a descrição centralizada */
           margin: 20px auto; /* Centraliza a seção de descrição */
           padding: 20px;
           text-align: center;
        }
        .map-container {
           max-width: 900px; /* Limita o tamanho do mapa */
           margin: 20px auto; /* Centraliza o mapa */
           border-radius: 10px;
           overflow: hidden; /* Garante que a borda arredondada apareça */
        }
        iframe {
           width: 100%;
           border: none;
        }
    </style>
</head>
<body>
    <header>
        <h1>BH CULT</h1>
        <p>Não conhece BH?</p>
        <p></p>
        <p>Sabia que BH é muito rica em Cultura?</p>
        <p></p>
        <p>Consulte abaixo alguns dos principais pontos culturais para você conhecer e aproveitar!!</p>
    </header>
    <div class="content">
        <div class="buttons">
            <button class="btn" onclick="showDescription('palacio')">Palácio das Artes</button>
            <button class="btn" onclick="showDescription('sesc')">Sesc Palladium</button>
            <button class="btn" onclick="showDescription('francisco')">Teatro Francisco Nunes</button>
            <button class="btn" onclick="showDescription('pampulha')">Museu de Arte da Pampulha</button>
            <button class="btn" onclick="showDescription('oficios')">Museu de Artes e Ofícios</button>
            <button class="btn" onclick="showDescription('mineiro')">Museu Mineiro</button>
            <button class="btn" onclick="showDescription('ccbb')">Centro Cultural Banco do Brasil (CCBB)</button>
            <button class="btn" onclick="showDescription('unimed')">Centro Cultural Unimed-BH Minas</button>
            <button class="btn" onclick="showDescription('sesiminas')">Centro Cultural Sesiminas</button>
            <button class="btn" onclick="showDescription('feira')">Feira Hippie</button>
            <button class="btn" onclick="showDescription('arena')">Escola Livre de Artes Arena da Cultura</button>
            <button class="btn" onclick="showDescription('una')">Casa Una Anima Lab</button>
        </div>

        <div class="map-container">
            <iframe src="https://www.google.com/maps/d/embed?mid=1biYS4bCe2rLKBCupwYtbF58YOnmEouw" width="100%" height="500"></iframe>
        </div>

        <div class="description" id="palacio">
            <h3>Palácio das Artes</h3>
            <p>O Palácio das Artes é um centro cultural em Belo Horizonte, localizado na Avenida Afonso Pena. Com diversas apresentações artísticas, como teatro, música e dança, é um dos principais pontos culturais da cidade. Sua arquitetura clássica e a variedade de eventos fazem deste local um ponto imperdível para os amantes da arte.</p>
            <img src="https://a.travel-assets.com/findyours-php/viewfinder/images/res70/262000/262504-Minas-Gerais-State.jpg" alt="Palácio das Artes">
        </div>
        <div class="description" id="sesc">
            <h3>Sesc Palladium</h3>
            <p>O Sesc Palladium é um renomado espaço cultural de Belo Horizonte, situado na Avenida do Contorno. O teatro oferece uma programação diversificada que inclui peças teatrais, apresentações musicais e sessões de cinema. O espaço é um ponto de encontro de artistas e público, fomentando a cultura e a arte na cidade.</p>
            <img src="https://i0.wp.com/bhpostnoticias.com/wp-content/uploads/2023/06/14_12_02-Fachadas-Palladium-Foto-Nereu-JR-6551-scaled.jpg?w=2560&ssl=1" alt="Sesc Palladium">
        </div>
        <div class="description" id="francisco">
            <h3>Teatro Francisco Nunes</h3>
            <p>Localizado no Parque Municipal, o Teatro Francisco Nunes é um tradicional palco cultural de Belo Horizonte. Com uma arquitetura imponente e uma programação de qualidade, oferece aos visitantes uma rica experiência teatral, com apresentações que vão desde peças clássicas até produções contemporâneas.</p>
            <img src="https://prefeitura.pbh.gov.br/sites/default/files/styles/slideshow/public/estrutura-de-governo/cultura/2019/teatro%20Francisco%20Nunes%20cheio_2.jpg?itok=Zn-LbzXa" alt="Teatro Francisco Nunes">
        </div>
        <div class="description" id="pampulha">
            <h3>Museu de Arte da Pampulha</h3>
            <p>O Museu de Arte da Pampulha, situado na orla da Lagoa da Pampulha, é um dos maiores exemplos da arte moderna no Brasil. A arquitetura de Oscar Niemeyer e o acervo que reúne obras de artistas como Cândido Portinari e Alfredo Volpi, tornam o museu um local essencial para quem deseja compreender a arte moderna em Minas Gerais.</p>
            <img src="https://prefeitura.pbh.gov.br/sites/default/files/estrutura-de-governo/fundacao-municipal-de-cultura/2019/2017_10_10_MAP_foto_Ricardo_Laf_09%20copy.jpg" alt="Museu de Arte da Pampulha">
        </div>
        <div class="description" id="oficios">
            <h3>Museu de Artes e Ofícios</h3>
            <p>O Museu de Artes e Ofícios, localizado na Praça Rui Barbosa, no Centro de Belo Horizonte, é dedicado aos ofícios e artes tradicionais. Com um acervo que inclui peças de diferentes períodos e regiões, o museu oferece aos visitantes uma rica experiência cultural sobre as profissões e práticas artísticas de Minas Gerais e do Brasil.</p>
            <img src="https://www.blogdoarcanjo.com/wp-content/uploads/2016/04/museu-artes-oficios-2.jpg" alt="Museu de Artes e Ofícios">
        </div>
        <div class="description" id="mineiro">
            <h3>Museu Mineiro</h3>
            <p>O Museu Mineiro, situado na Praça Rui Barbosa, é um espaço dedicado à arte sacra e à cultura mineira. Com um acervo que inclui esculturas, pinturas e objetos litúrgicos, o museu revela a história de Minas Gerais e a religiosidade de sua população, sendo um local imperdível para quem deseja conhecer mais sobre a cultura local.</p>
            <img src="https://portalbelohorizonte.com.br/sites/default/files/arquivos/arte-e-cultura/2021-11/museu-mineiro_qu4rto-studio-2152_easy-resize.com_.jpg" alt="Museu Mineiro">
        </div>
        <div class="description" id="ccbb">
            <h3>Centro Cultural Banco do Brasil (CCBB)</h3>
            <p>O CCBB, localizado na Praça da Liberdade, é um centro cultural com uma programação variada de artes plásticas, cênicas e musicais. Considerado um dos mais importantes espaços culturais do país, o CCBB promove exposições de artistas renomados, além de uma série de eventos que envolvem a cena artística contemporânea.</p>
            <img src="https://dynamic-media-cdn.tripadvisor.com/media/photo-o/11/fb/49/25/faxada.jpg?w=1000&h=-1&s=1" alt="CCBB">
        </div>
        <div class="description" id="unimed">
            <h3>Centro Cultural Unimed-BH Minas</h3>
            <p>O Centro Cultural Unimed-BH Minas é um espaço dedicado à arte, com uma grande variedade de eventos culturais. Situado na Avenida do Contorno, o centro oferece teatro, música e uma biblioteca, promovendo a democratização do acesso à cultura e à arte em Belo Horizonte.</p>
            <img src="https://storage.googleapis.com/site-minas-tenis-gcp/media/3srbz1qz/fachada-centro-cultural.jpg" alt="Centro Cultural Unimed-BH Minas">
        </div>
        <div class="description" id="sesiminas">
            <h3>Centro Cultural Sesiminas</h3>
            <p>O Centro Cultural Sesiminas, em Belo Horizonte, é um espaço de arte e cultura com uma programação diversificada. Com apresentações de música, teatro e dança, o Sesiminas é um ponto importante na cena cultural da cidade, promovendo eventos para todas as idades e gostos.</p>
            <img src="https://www.minasgerais.com.br/imagens/atracoes/1618328633kdTsc394bH.jpg" alt="Centro Cultural Sesiminas">
        </div>
        <div class="description" id="feira">
            <h3>Feira Hippie</h3>
            <p>A tradicional Feira de Artes, Artesanato e Produtores de Variedades de Belo Horizonte, mais conhecida como Feira Hippie, é um dos maiores e mais tradicionais eventos de arte e cultura da cidade. Localizada na Avenida Afonso Pena, ela é oficialmente denominada Feira de Artes, Artesanato e Produtores de Variedades de Belo Horizonte, e se destaca como um importante ponto de encontro de artistas, artesãos e produtores locais.
                <p></p>
                A feira ocupa uma vasta área de 45 mil m², se estendendo por cerca de 1 km, e conta com aproximadamente 1.500 expositores que oferecem uma grande variedade de produtos, como arte, artesanato, roupas, bijuterias, objetos de decoração e muito mais. É um espaço vibrante, onde é possível encontrar tanto itens tradicionais quanto criações contemporâneas, tudo com um toque especial da cultura mineira.
                <p></p>
                Além da diversidade de produtos, a feira também é famosa pela sua área de alimentação, onde é possível saborear pratos típicos e petiscos variados, tornando a visita ainda mais completa. Com uma programação que vai além da compra e venda, a Feira Hippie é um lugar para vivenciar o espírito cultural de Belo Horizonte e interagir diretamente com a arte local.
                <p></p>
                A Feira Hippie ocorre aos domingos e feriados, atraindo visitantes de todas as partes da cidade e turistas, sendo uma excelente oportunidade para conhecer mais da arte e do cotidiano mineiro em um ambiente único e cheio de histórias.</p>
            <img src="https://portalbelohorizonte.com.br/sites/default/files/arquivos/compras-e-moda/2021-11/screenshot-2021-11-26-15.30.14.png" alt="Feira Hippie">
        </div>
        <div class="description" id="arena">
            <h3>Escola Livre de Artes Arena da Cultura</h3>
            <p>A Escola Livre de Artes Arena da Cultura é um centro de formação artística em Belo Horizonte. Além de cursos e oficinas, o local oferece uma programação cultural, com apresentações de teatro, dança e música, promovendo a troca de experiências entre artistas e público.</p>
            <img src="https://www.otempo.com.br/adobe/dynamicmedia/deliver/dm-aid--7ff845e5-efd3-4f6b-a84c-5b8d9c8402f5/politica-pbh-escola-livre-de-artes-arena-da-cultura-1708813410.jpg?preferwebp=true&quality=90&width=1200" alt="Arena da Cultura">
        </div>
        <div class="description" id="una">
            <h3>Casa Una Anima Lab</h3>
            <p>A Casa Una Anima Lab é um espaço cultural dedicado à arte e à educação, com foco em projetos interativos e criativos. Com uma programação diversificada, que inclui exposições, palestras e oficinas, é um excelente local para quem busca conhecer mais sobre o universo artístico em Belo Horizonte.</p>
            <img src="https://www.belohorizonte.com.br/wp-content/uploads/2022/08/Casa-Una-7-scaled.jpg" alt="Casa Una Anima Lab">
        </div>
    </div>

    <script>
        function showDescription(id) {
            // Esconde todas as descrições
            let descriptions = document.querySelectorAll('.description');
            descriptions.forEach(function(desc) {
                desc.style.display = 'none';
            });

            // Exibe a descrição correspondente ao botão clicado
            let description = document.getElementById(id);
            description.style.display = 'block';
        }
    </script>
</body>
</html>
