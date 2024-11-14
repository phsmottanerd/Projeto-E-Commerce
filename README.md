🚀 E-commerce Project
🎯 Objetivo do Projeto
Este projeto tem como objetivo a criação de um E-commerce completo, simulando uma plataforma de compras online com clientes, produtos, pedidos, pagamentos e entregas. O sistema foi projetado para gerenciar as principais funcionalidades de um comércio eletrônico de forma eficiente e organizada, com um banco de dados estruturado para garantir a integridade e a fluidez do processo.

🔧 Funcionalidades do Projeto
O E-commerce simula todas as operações de uma plataforma real, com as seguintes funcionalidades:

1. 👥 Clientes (PJ e PF)
Cliente PJ e Cliente PF podem ser cadastrados, com informações como nome, CNPJ/CPF, e-mail e telefone.
Cada conta pode ser associada a um tipo de cliente, mas não pode ter ambos os tipos.
2. 🛒 Carrinho de Compras
Os clientes podem adicionar produtos ao carrinho e gerenciar a quantidade e o preço total.
O carrinho se mantém atualizado conforme o cliente navega pelos produtos.
3. 🏷️ Produtos
Catálogo de produtos com descrição, preço e imagem.
Cada produto pertence a uma categoria (ex: Eletrônicos, Moda, Casa e Decoração).
4. 📦 Pedidos
Um pedido é gerado assim que o cliente finaliza a compra, com os detalhes dos produtos e do cliente.
Status do pedido: Em processamento, Pagamento Confirmado, Enviado, Entregue.
5. 💳 Pagamentos
O cliente pode escolher entre várias formas de pagamento (cartão de crédito, boleto, PayPal, etc.).
O status do pagamento é atualizado e vinculado ao pedido realizado.
6. 🚚 Entrega
O status da entrega é atualizado em tempo real, com código de rastreamento para o cliente acompanhar seu pedido.
🗂️ Banco de Dados e Modelagem
Este projeto utiliza um banco de dados MySQL para armazenar todas as informações relacionadas aos clientes, produtos, pedidos, pagamentos e entregas. A modelagem foi feita para garantir integridade referencial entre as entidades.

💾 Entidades:

Clientes (PJ e PF)
Produtos
Pedidos
Pagamentos
Entrega
🔗 Relacionamentos:

Um cliente pode ter múltiplos pedidos.
Um pedido pode conter múltiplos produtos.
Cada pedido possui um status de pagamento e um status de entrega.


