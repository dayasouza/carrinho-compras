# Carrinho de Compras
<img src="/assets/img/carrinho.png">

## Sobre
<p> Nosso segundo desafio será criar um Carrinho de compras, algo muito comum no nosso dia a dia, principalmente em relação às compras online.

Já estamos com o HTML aberto, para visualizá-lo, clicamos com o botão direito e depois em "Open with Live Server". Feito isso, a página abre no navegador.

Na lateral direita, identificamos que já temos um item no carrinho, um celular. Para adicionar outro item, clicamos na combobox, na lateral esquerda da página.

Feito isso, abre uma lista com produtos. Selecionamos Óculos VR e clicamos no botão "Adicionar". Ao fazer isso, o produto aparece no carrinho, que também disponibiliza o valor total dos produtos.

Como é muito comum que as pessoas adicionem e depois limpe os itens do carrinho, criaremos esse botão para as informações serem resetadas, ou seja, os itens removidos e o valor zerado. Esse é nosso desafio!</p>

### Resolução
<p>Para a resolução desse desafio, foi criado duas funções a <strong> adicionar() </strong> e a <strong>limpar() </strong></p>
<p>Na função adicionar foi recuperado o nome e o valor do produto que está em um combobox, para isso tive que manipular a string utilizando a função <strong>split()</strong></p>
<p>Depois foi recuperado outros dados do html, como a quantidade, e com isso feito o calculo inicial do valor unitário do produto multiplicado pela quantidade. E adicionado ao carrinho de compras. </p>
<p>Após recuperar todos esses dados foi implementado o calculo do valor total do carrinho.</p>
<p>E pra finalizar, foi criada enfim a função limpar que limpa todos os campos ao ser clicado no botão, para que o carrinho fique vazio.</p>

#### Meus aprendizados...

<p>Efetuando esse projeto aprendi sobre manipulação de string em JavaScript, algo que ainda não tinha aprendido</p>
<p>Também aprendi como recuperar, manipular e adicionar dados ao HTML.</p>

<h2> Tecnologias <h2>
<div>
  <img src="https://img.shields.io/badge/HTML-239120?style=for-the-badge&logo=html5&logoColor=white">
  <img src="https://img.shields.io/badge/CSS-239120?&style=for-the-badge&logo=css3&logoColor=white">
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black">
</div>