# Vini-Moraes-Desafio-DER-Ecommerce
Repositorio criado para o Desafio DER de modelagem de banco de dados  BootCamp Dio e Heineken
Informações sobre as Entidade Relacionamento e seus Atributos. Refiz a modelagem para um padrão que achei mais enxuto.

Explicativas:

Relacionamentos Refinados:
Clientes 1:N Pedidos
Um cliente pode ter vários pedidos, mas um pedido pertence a um único cliente.

Pedidos 1:1 Pagamentos
Cada pedido tem um ou mais pagamentos associados a ele.

Pedidos 1:1 Entrega
Cada pedido tem uma entrega associada a ele.

Produtos 1:N Estoque
Um produto pode estar em estoque várias vezes, mas cada item de estoque se refere a um único produto.

Fornecedores 1:N Produtos
Um fornecedor pode fornecer vários produtos, mas cada produto tem um fornecedor principal.

Vendedores 1:N Produtos
Cada produto pode ser vendido por diferentes vendedores.

Pedidos N:N Produtos (Vendas de Produtos como entidade associativa)
Um pedido pode conter vários produtos e um produto pode estar em vários pedidos. A entidade "Vendas de Produtos" serve para registrar esta relação, incluindo o vendedor.

Clientes 1:N Pedidos
Um cliente pode comprar vários pedidos.

Clientes N:1 Devoluções
Cada pedido tem um período de carência para devolução do produto.


VINI MORAES


