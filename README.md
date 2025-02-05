## Clonei a Pagina do Spotify 
Este projeto consiste em uma replica da página do Spotify versão desktop, 
 aprendida na Imersão Front-End proporcionado pela empresa Alura.💙
<div align="center">
  <a href="https://git.io/typing-svg">
    <img src="https://github.com/pauloandresdf/spotify-clone/blob/main/src/assets/img/print.png" />
  </a>
</div>
<div>
 <h1><strong>Principais funcionalidades:</strong></h1>
<p><strong>1-Busca de Artistas:</strong> <br> Permite que o usuário digite o nome de um artista e veja os resultados correspondentes.</p>
<p><strong>2-Exibição de Cards:</strong> <br>Mostra informações sobre artistas em forma de cards, incluindo nome e imagem.</p>
<p><strong>3-Responsividade:</strong> <br>A interface se adapta a diferentes tamanhos de tela, como desktops, tablets e dispositivos móveis.</p>
<p><strong>4-Interatividade:</strong> <br>A página responde às ações do usuário, como a busca por artistas, atualizando dinamicamente o conteúdo exibido.</p>
<p><strong>5-API Fake:</strong> <br>Utiliza uma API simulada para fornecer dados de artistas, permitindo que o front-end consuma esses dados como se fossem reais.</p>
<p><strong>6-Animações e Transições:</strong> <br>Implementação de efeitos visuais para melhorar a experiência do usuário ao interagir com a interface.</p>
</div>
<h2>🛠 Tecnologias</h2>
    <p>Este projeto foi desenvolvido com as seguintes tecnologias:</p>
    <table>
        <tr>
            <th>Tecnologia</th>
            <th>Descrição</th>
        </tr>
        <tr>
            <td>HTML 🏗️</td>
            <td>Estruturação das páginas</td>
        </tr>
        <tr>
            <td>CSS 🎨</td>
            <td>Estilização dos elementos</td>
        </tr>
        <tr>
            <td>JavaScript ⚙️</td>
            <td>Interatividade e lógica</td>
        </tr>
        <tr>
            <td>CSS Flexbox 📏</td>
            <td>Layout responsivo baseado em flexbox</td>
        </tr>
        <tr>
            <td>CSS Grid 🗂️</td>
            <td>Layout estruturado com grid</td>
        </tr>
        <tr>
            <td>JSON Server 📡</td>
            <td>Simulação de API REST</td>
        </tr>
    </table>
</head>
<body>
    <h1>Instruções</h1>
    <p><strong>1 Código do terminal</strong></p>
    <pre><code>json-server --watch api-artists/artists.json --port 3000</code></pre>
    <p>Dependendo da sua extensão, o <code>3000</code> terá que ser modificado.</p>
    <p>Se caso der o erro <strong>"File api-artists-artists.json not found"</strong>, indica que o arquivo <code>api-artists-artists.json</code> não está no diretório atual.</p>
    <p>Digite:</p>
    <pre><code>cd src</code></pre>
    <p>e tente o código anterior.</p>
    <h2>Testando na sua máquina</h2>
    <p>Para testar essa configuração na sua máquina, siga os passos abaixo:</p>
    <ol>
        <li>Certifique-se de que tem o Node.js instalado. Para verificar, execute:</li>
        <pre><code>node -v</code></pre>
        <li>Se o Node.js não estiver instalado, baixe e instale a versão mais recente em <a href="https://nodejs.org/">nodejs.org</a>.</li>
        <li>Instale o JSON Server globalmente (caso ainda não tenha):</li>
        <pre><code>npm install -g json-server</code></pre>
        <li>Navegue até o diretório do projeto:</li>
        <pre><code>cd caminho/do/projeto</code></pre>
        <li>Execute o servidor JSON:</li>
        <pre><code>json-server --watch api-artists/artists.json --port 3000</code></pre>
        <li>Acesse o servidor no navegador ou via API:</li>
        <pre><code>http://localhost:3000</code></pre>
    </ol>
    
