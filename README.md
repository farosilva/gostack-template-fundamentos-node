<h1>Desafio - Fundamentos Node</h1>

<p>Desafio para criar uma aplicação para continuar treinando os conceitos aprendidos com o Node, agora junto ao Typescript, utilizando conceitos de <b>models</b>, <b>repositories</b> e <b>services</b>. Uma aplicação para armazenar transações financeiras de entrada e saída. Deve permitir o cadastro e a listagem dessas transações.</p>

<ul>
  <li>
    <b>POST /transactions</b>
    A rota deve receber <i>title</i>, <i>value</i> e <i>type</i> dentro do corpo da requisição,
    sendo <b>type</b> o tipo da transição, que deve ser <i>income</i> para entradas (depósitos)
    e <i>outcome</i> para saídas (retiradas).
  </li>
  <li>
    <b>GET /transactions</b>
    A rota deve retornar uma listagem com todas as transações que você cadastrou até agora junto
    com o valor de soma de entradas, retiradas e total de crédito.
  </li>
</ul>

<h5>Regras:</h5>
<ul>
  <li>Não será possível retirar do caixa, um valor maior que o saldo disponível.</li>
</ul>
