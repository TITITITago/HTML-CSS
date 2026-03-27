<!doctype html>
<html lang='pt-BR'>

<header>
    <title>Bem vindos a Alemanha!</title>
    <link rel="stylesheet" href="style.css">
</header>

<body>

    <div class='container'>
<h1>Bem vindos a Alemanha!</h1>
        <main>

            <article>
                

                <h2>Conhecendo sua capital!</h2>
                <p>
                    Berlim, capital vibrante e maior cidade da Alemanha, é um centro cosmopolita com profunda carga
                    histórica da Segunda
                    Guerra Mundial e da Guerra Fria. Oferece mais de 365 museus, intensa vida cultural, áreas verdes
                    extensas (como o
                    Tiergarten) e marcos icônicos como o Portão de Brandemburgo, o Muro de Berlim (East Side Gallery) e
                    o Memorial do
                    Holocausto.
                </p>


                <p>
                    Berlim é mais antiga do que a própria Alemanha unificada, tendo sido fundada em 1237. Foi a capital
                    da Prússia por
                    mais de 600 anos antes da criação do Império Alemão em 1871.
                </p>
            </article>

            <article>
                <h2>Veja Pontos Turísticos Icônicos</h2>

                <p>A Alemanha é um país que equilibra perfeitamente o peso da história com uma modernidade vibrante e
                    paisagens naturais que parecem saídas de livros.
                </p>
            </article>
            
            <article>
                <h3>Castelo de Neuschwanstein (Baviera)</h3>
                <img src="https://upload.wikimedia.org/wikipedia/commons/f/f8/Schloss_Neuschwanstein_2013.jpg">
                <p>O "Castelo de Conto de Fadas" por excelência. Construído pelo rei Ludwig II no século XIX, ele serviu de inspiração para o castelo da Cinderela de Walt Disney. Localizado no topo de uma colina nos Alpes Bávaros, a vista das torres surgindo entre a neblina ou a neve é simplesmente inesquecível.</p>
                <a href=https://everything-everywhere.com/unesco-world-heritage-sites-in-germany/ target='_blank'>
                    Confira!
                </a>
            </article>

            <article>
                <h3>Portão de Brandemburgo (Berlim)</h3>
                <img src="https://simplesmenteberlim.com/wp-content/uploads/2012/08/PortaoDeBrandenburgo21.jpg">
                <p>Mais do que um monumento neoclássico, o Portão de Brandemburgo é o maior símbolo da história alemã. Durante a Guerra Fria, ele ficou isolado entre o Leste e</p>
                <a href=https://everything-everywhere.com/unesco-world-heritage-sites-in-germany/ target='_blank'>
                    Confira!
                </a>
            </article>

            <article>
                <h3>Catedral de Colônia (Colônia)</h3>
                <img src=https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRC4w7oAbHCbpLAXIQuM7oaiIpk3cPA68-DcQ&s>
                <p>Esta obra-prima da arquitetura gótica é um dos monumentos mais visitados do país. Suas torres gêmeas dominam o horizonte da cidade e levaram mais de 600 anos para serem concluídas. O interior abriga o Relicário dos Três Reis Magos, uma joia da arte medieval.</p>
                <a href=https://everything-everywhere.com/unesco-world-heritage-sites-in-germany/ target='_blank'>
                    Confira!</a>
            </article>
            

    <footer>
    <hr>
    <address>
        Escrito por <a href="mailto:contato@turismoalemanha.com">Guia de Turismo Alemanha</a>.<br> 
        Visite-nos em:<br>
        Rua das Flores, 123, Berlim, Alemanha<br>
        Telefone: +49 30 1234-5678
    </address>
    </footer>

        </main>

    </div>

</body>

</html>

-------------------------------------------------

<!doctype html>
<html lang='pt-BR'>

<head>
  <meta charset="UTF-8">
  <title>Bem-vindos à Alemanha!</title>
  <link rel="stylesheet" href="style.css">
</head>

<body>

  <div class='container'>
    <header>
      <h1>Bem-vindos à Alemanha!</h1>
    </header>

    <main>
      <table border="1">
        <thead>
          <tr>
            <th>Cidade / Estado</th>
            <th>Ponto Turístico</th>
            <th>Início da Construção</th>
            <th>População (Cidade)</th>
          </tr>
        </thead>
        <tbody>
          <tr>
            <td>Füssen (Baviera)</td>
            <td>Castelo de Neuschwanstein</td>
            <td>5 de setembro de 1869</td>
            <td>~ 15.000</td>
          </tr>
          <tr>
            <td>Berlim</td>
            <td>Portão de Brandemburgo</td>
            <td>1788 - 1791</td>
            <td>~ 3,8 milhões</td>
          </tr>
          <tr>
            <td>Colônia</td>
            <td>Catedral de Colônia</td>
            <td>15 de agosto de 1248</td>
            <td>~ 1,1 milhão</td>
          </tr>
        </tbody>
      </table>
    </main>
  </div>

</body>

</html>

------------------------------------------------

<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <title>Formulário de Contato</title>
    <style>
        body { font-family: sans-serif; background-color: #f4f4f9; padding: 20px; }
        .container { max-width: 400px; background: white; padding: 20px; border-radius: 8px; shadow: 0 2px 10px rgba(0,0,0,0.1); margin: auto; }
        h2 { color: #333; text-align: center; }
        .group { margin-bottom: 15px; }
        label { display: block; margin-bottom: 5px; font-weight: bold; }
        input, select, textarea { width: 100%; padding: 10px; border: 1px solid #ccc; border-radius: 4px; box-sizing: border-box; }
        button { width: 100%; padding: 10px; background-color: #28a745; color: white; border: none; border-radius: 4px; cursor: pointer; font-size: 16px; }
        button:hover { background-color: #218838; }
    </style>
</head>
<body>

<div class="container">
    <h2>Fale Conosco</h2>
    <form action="/enviar-dados" method="POST">
        
        <div class="group">
            <label for="nome">Nome:</label>
            <input type="text" id="nome" name="nome" placeholder="Seu nome completo" required>
        </div>

        <div class="group">
            <label for="email">E-mail:</label>
            <input type="email" id="email" name="email" placeholder="email@exemplo.com" required>
        </div>

        <div class="group">
            <label for="assunto">Assunto:</label>
            <select id="assunto" name="assunto">
                <option value="suporte">Suporte Técnico</option>
                <option value="vendas">Vendas</option>
                <option value="feedback">Sugestão/Feedback</option>
            </select>
        </div>

        <div class="group">
            <label for="mensagem">Mensagem:</label>
            <textarea id="mensagem" name="mensagem" rows="4" placeholder="Como podemos ajudar?"></textarea>
        </div>

        <button type="submit">Enviar Mensagem</button>

    </form>
</div>

</body>
</html>

-----------------------------------


/* --- Reset e Base --- */
* {
    box-sizing: border-box;
    margin: 0;
    padding: 0;
}

body {
    font-family: 'Segoe UI', Roboto, Helvetica, Arial, sans-serif;
    background-color: #f0f2f5;
    color: #333;
    line-height: 1.6;
    display: flex;
    justify-content: center;
    padding: 40px 20px;
}

/* --- Container Principal --- */
.container {
    width: 100%;
    max-width: 900px;
    background: #ffffff;
    padding: 40px;
    border-radius: 15px;
    box-shadow: 0 10px 30px rgba(0,0,0,0.08);
}

/* --- Títulos --- */
h1 {
    text-align: center;
    color: #1a1a1a;
    font-size: 2.5rem;
    margin-bottom: 40px;
    border-bottom: 4px solid #d32f2f;
    display: inline-block;
    width: 100%;
    padding-bottom: 10px;
}

h2 {
    color: #d32f2f;
    border-left: 6px solid #000;
    padding-left: 15px;
    margin: 35px 0 20px 0;
    font-size: 1.8rem;
}

h3 {
    color: #2c3e50;
    margin: 30px 0 15px 0;
    font-size: 1.4rem;
}

/* --- Artigos e Seções --- */
article {
    margin-bottom: 40px;
    padding-bottom: 20px;
    border-bottom: 1px dashed #eee;
}

p {
    margin-bottom: 15px;
    color: #555;
    font-size: 1.1rem;
}

/* --- Animação das Imagens --- */
img {
    width: 100%;
    height: auto;
    border-radius: 12px;
    margin: 25px 0;
    display: block;
    transition: all 0.4s cubic-bezier(0.165, 0.84, 0.44, 1);
    box-shadow: 0 4px 10px rgba(0,0,0,0.1);
}

img:hover {
    transform: scale(1.03);
    box-shadow: 0 15px 35px rgba(0,0,0,0.2);
    cursor: zoom-in;
}

/* --- Estilização dos Links (Botões) --- */
article a {
    display: inline-block;
    background-color: #2c3e50;
    color: #fff;
    padding: 12px 25px;
    text-decoration: none;
    border-radius: 8px;
    font-weight: 600;
    transition: all 0.3s ease;
    margin-top: 10px;
}

article a:hover {
    background-color: #d32f2f;
    transform: translateY(-2px);
    box-shadow: 0 5px 15px rgba(211, 47, 47, 0.3);
}

/* --- Tabela --- */
table {
    width: 100%;
    border-collapse: collapse;
    margin: 30px 0;
    border-radius: 10px;
    overflow: hidden; /* Garante que o border-radius funcione */
    box-shadow: 0 2px 8px rgba(0,0,0,0.05);
}

th, td {
    padding: 18px;
    text-align: left;
    border-bottom: 1px solid #f0f0f0;
}

thead th {
    background-color: #2c3e50;
    color: #fff;
    text-transform: uppercase;
    font-size: 0.85rem;
    letter-spacing: 1px;
}

tbody tr:hover {
    background-color: #f8f9fa;
}

/* --- Rodapé --- */
footer {
    text-align: center;
    margin-top: 50px;
    color: #888;
}

/* --- Responsividade --- */
@media (max-width: 768px) {
    .container { padding: 20px; }
    h1 { font-size: 2rem; }
    table { font-size: 0.9rem; }
}
