# CP2 – Vinheria Agnello <br>
Checkpoint desenvolvido por Cainã Sandes Batista, RM: 568571. <br>
Apresentado ao curso de Engenharia de Software. <hr>

<h3>Nome do Projeto:</h3> 
<p>Portal da Vinheria Agnello</p>

<h3>Descrição do Caso:</h3> 
<p>
A Vinheria Agnello é uma empresa familiar localizada em São Paulo, com mais de 15 anos de tradição no mercado de vinhos nacionais e internacionais. 
Seu diferencial está no atendimento especializado, com recomendações de harmonização, informações sobre vinícolas, tipos de uvas e ocasiões de consumo. 
Com a pandemia, a loja física foi impactada e surgiu a necessidade de criar um portal de e-commerce, capaz de transmitir ao usuário uma experiência próxima à vivida na loja física.
</p>

<h3>Estrutura do projeto:</h3> <p>
<ul>
  <li>vinheria-agnello (folder)</li>
  <ul>
    <b><li>index.html</b> – Página inicial com apresentação da vinheria e links de navegação.</li>
    <li>src/css/style.css</li>
    <li>src/css/efeitos.css</li>
    <li>src/assets/imgs/11...</li>
    <li><b>src/pages/historia.html</b> – Página "Sobre nós", contando a trajetória da vinheria e seus diferenciais.</li>
    <li><b>src/pages/produtos.html</b> – Catálogo de vinhos em tabela, com imagens e botões de compra.</li>
    <li><b>src/pages/armazenagem.html</b> – Página de dicas e cuidados para armazenamento de vinhos, com imagem e vídeo explicativo.</li>
    <li><b>src/pages/contato.html</b> – Formulário de contato com campos de nome, e-mail e mensagem, além de link para redes sociais.</li>
</ul>
  </ul>
</ul>

<h3>Objetivo:</h3> <p>
O projeto tem como finalidade o desenvolvimento de um site para a Vinheria Agnello, simulando a criação de um portal de e-commerce. <br>
O trabalho reforça os conceitos de estruturação de páginas HTML, aplicação de estilos com CSS e utilização de recursos multimídia. <p>

<h3>Desenvolvimento:</h3> <p>
O site foi construído com 5 páginas (index + 4 adicionais), organizadas em pastas específicas para código e imagens, e 2 arquivos css (styles.css e efeitos.css), organizados em mesma pasta e importação dentro de html e css.<br>
Foram aplicados:
  
<ul>
  
  <li><b>Pseudo-classes</b></li>
  <ul>
    <li><code>nav ul li a:hover::before</code> – cria um sublinhado animado ao passar o mouse nos links do menu;</li>
    <li><code>input:focus</code> e <code>textarea:focus</code> – destacam os campos de formulário ativos, mudando a borda e adicionando sombra;</li>
    <li><code>button:not([type="submit"]):hover</code> e <code>button[type="submit"]:hover</code> – aplicam mudança de cor, sombra e leve aumento no botão ao passar o mouse.</li>
  </ul>
  
  <li><b>Pseudo-elementos</b></li>
  <ul>
    <li><code>nav ul li a::before</code> – adiciona uma linha sob os links, que cresce com o hover;</li>
    <li><code>h2::after</code> – insere uma linha decorativa abaixo dos títulos principais, reforçando a hierarquia visual.</li>
  </ul>
  
  <li><b>Keyframes</b></li>
  <ul>
    <li><code>@keyframes mov</code> – define uma animação suave de entrada dos elementos principais, fazendo o conteúdo surgir com translação vertical;</li>
    <li>Aplicado em <code>.conteudo-principal</code>, que é animado assim que a página carrega.</li>
  </ul>
  
  <li><b>Transformações</b></li>
  <ul>
    <li><code>transform: rotate(1deg);</code> – dá leve inclinação às imagens para criar um efeito visual mais dinâmico;</li>
    <li><code>transform: rotate(0deg) scale(1.01);</code> – usado no hover das imagens, corrigindo a rotação e aumentando levemente o tamanho;</li>
    <li><code>transform: scale(1.02);</code> – aumenta sutilmente o botão ao passar o mouse, simulando resposta tátil.</li>
  </ul>
  
  <li><b>Transições</b></li>
  <ul>
    <li><code>transition: all 0.3s ease-in-out;</code> – aplicada em links, botões, inputs, imagens e áreas de texto, suavizando todas as mudanças de estado (hover, foco, etc.);</li>
    <li><code>transition: width 0.3s ease;</code> – faz a linha sob os links crescer de forma fluida ao interagir com o menu.</li>
  </ul>
  
</ul>
  
</ul>
<p>
A estilização é funcional entre todas as páginas, o código está indentado e organizado, visando clareza e manutenção.
</p>

<h3>Publicação:</h3> <p>
O projeto foi publicado no GitHub Pages para visualização online. <br>
🔗 Link: https://sednas22.github.io/CP2-vinheria-agnello/
</p>







