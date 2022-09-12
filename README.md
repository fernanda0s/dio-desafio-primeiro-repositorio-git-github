# repositório do desafio de git/github da DIO
desafio de projeito sobre git/github

## links uteis
[sintaxe basica markdown](https://www.markdownguide.org/basic-syntax/)
[ER DIAGRAM](https://www.lucidchart.com/pages/er-diagrams)

# atualização 
adicionado documento de texto (.txt) explicando sobre modelo entidade-relacionamento

# DESCRIÇÃO PROJETO CONCEITUAL
ESCOPO DE E-COMMERCE
-- A aplicação irá utilizar um banco de dados para realizar a venda de produtos, fornecendo valores e dados.
PRODUTO
- os produtos são vendidos por uma única plataforma online, contudo, estes podem ter vendedores distintos;
- cada produto possui um fornecedor;
- um ou mais produtos podem compor um pedido.
CLIENTE
- o cliente pode se cadastrar no site com seu CPF ou CNPJ;
- o endereço do cliente irá determinar o valor da entrega;
- um cliente pode comprar mais de um pedido;
- os pedidos possuem um periodo de carência para devolução do produto.
PEDIDO
- os pedidos são criados por clientes e possuem informações de compra, endereço e outros;
- um produto ou mais compoem um pedido;
- o pedido pode ser cancelado.
PAGAMENTO
- os pagamentos são realizados por clientes;
- pode ter cadastrado mais de uma forma de pagamento.
ENTREGA
- possuem informações status da entrega, endereço, informações adicionais sobre o pedido e código de rastreio.

## link
![e-commerce drawio](https://user-images.githubusercontent.com/111526515/189658030-da6cbcf8-9bdf-4e60-8b25-da67fd56a1d1.png)
