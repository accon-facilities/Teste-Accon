

<h2>Problema: Loja OOP</h2> 
<h3>Descrição do Problema</h3>
<p>Você foi contratado para gerenciar o estoque de uma loja de importados e temos algumas tarefas para você. Crie classes que representem produtos, com métodos para calcular o preço total com base na quantidade comprada. Utilize estruturas de repetição para processar diferentes itens no carrinho de compras. Os produtos devem ser restaurados de um Banco de Dados utilizando as ferramentas disponíveis.</p>

<strong>Banco de Dados:</strong></br>
<ul>Quanto ao banco de dados, você deverá criar scripts em SQL que cumprem as seguintes tarefas:</ul>
<li>Criar as seguintes tabelas e suas respectivas colunas</li>
  <ul>
    <li>Endereço (identificador do endereço, rua, número, complemento, bairro, cidade, estado e país)</li>
    <li>Usuários (Identificador do usuário, nome e endereço)</li>
    <li>Detalhes de pedidos (identificador do pedido, identificador do usuário que fez a compra, id do item pedido, quantidade, data e horário do pedido)</li>
    <li>Fornecedor (identificador do fornecedor, nome, endereço e quantidade de compras efetuadas com o vendedor)</li>
    <li>Estoque (identificador do item, nome do produto, quantidade de produtos, valor pelo qual foi comprado o item, valor pelo qual será vendido, valor total do estoque, fornecedor e número de vendas do item)</li>
    <li>Pedidos (identificador do pedido, identificador do usuário que fez a compra, valor total da compra e endereço de entrega)</li>
  </ul>
<li>Popular o banco com as seguintes entidades</li>
<ul>
  <li>Dois usuários</li>
  <li>Dois Fornecedores</li>
  <li>Cinco itens no estoque</li>
  <li>Três pedidos de compras</li>
  <li>Um endereço para cada usuário e fornecedor</li>
</ul>
<li>Selecionar os seguintes dados:</li>
<ul>
  <li>Nome de um fornecedor, país e quantidade de compras feitas no fornecedor</li>
  <li>As duas últimas compras feitas no sistema e de qual fornecedor elas vieram</li>
  <li>O nome de um usuário e seu endereço completo</li>
</ul>
<li>Apagar um item do estoque.</li>



<strong>API</strong>:</br>
<p>Considerando o modelo de banco de dados que foi criado anteriormente, implemente uma API usando o ASP.NET Core que cumpra os seguintes requisitos:</p>
<ul>
<li>Criar Produto: O sistema deve permitir ao usuário criar um novo produto, fornecendo detalhes como nome, preço unitário e quantidade em estoque.
<li>Visualizar Produto: O sistema deve permitir ao usuário visualizar os detalhes de um produto existente.
<li>Atualizar Produto: O sistema deve permitir ao usuário atualizar os detalhes de um produto existente.
<li>Deletar Produto: O sistema deve permitir ao usuário deletar um produto existente.
<li>Adicionar Produto ao Carrinho: O sistema deve permitir ao usuário adicionar um produto ao carrinho de compras.
<li>Concluir a compra.
</ul>

<h2>Requisitos do Sistema</h2>
<li>Orientação a Objetos: O sistema deve ser implementado usando os princípios da Programação Orientada a Objetos (OOP), incluindo conceitos como polimorfismo, composição, herança e encapsulamento.
<li>Gestão de Produtos: O sistema deve permitir a criação, visualização, atualização e exclusão (CRUD) de produtos.
<li>Gestão de Carrinho de Compras: O sistema deve permitir a adição e remoção de produtos no carrinho de compras.
<li>Cálculo de Preço Total: O sistema deve calcular o preço total dos itens no carrinho de compras.
<li>Tratamento de Erros: O sistema deve ser capaz de lidar com erros de entrada do usuário, utilizando loops e condicionais para validar as entradas.
<li>Sintaxe C#: O sistema deve ser implementado em C#, demonstrando um bom domínio da sintaxe da linguagem


