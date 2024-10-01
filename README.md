# Sistema de Mercado
Este sistema foi criado em C para simular o funcionamento básico de um supermercado. Ele permite cadastrar produtos, adicionar itens ao carrinho de compras e calcular o valor total da compra. O programa usa estruturas para representar os produtos e os itens do carrinho e armazena essas informações em arrays.

Como o Sistema Funciona
O código começa definindo alguns limites, como o número máximo de produtos que podem ser cadastrados (MAX_PRODUTOS) e a quantidade máxima de itens que o carrinho pode conter (MAX_CARRINHO). A estrutura Produto guarda informações como o código, nome, preço e quantidade disponível de cada produto. A estrutura Carrinho armazena o produto escolhido e quantas unidades dele foram adicionadas ao carrinho.

O programa é dividido em várias funções:

Menu Principal: A função menu() exibe as opções que o usuário pode escolher, como cadastrar produtos, listar os produtos disponíveis, comprar produtos, visualizar o carrinho e finalizar a compra.

Cadastro de Produtos: A função cadastrarProduto() permite que o usuário adicione novos produtos ao sistema. O usuário informa o código, nome e preço de cada produto, e esses dados são armazenados.

Listar Produtos: A função listarProdutos() exibe todos os produtos que foram cadastrados no sistema. Se nenhum produto tiver sido cadastrado, o sistema avisa o usuário.

Comprar Produtos: A função comprarProduto() permite ao usuário adicionar produtos ao carrinho. O usuário informa o código do produto e a quantidade que deseja comprar. Se o produto já estiver no carrinho, a quantidade é atualizada.

Visualizar Carrinho: A função visualizarCarrinho() mostra todos os itens que estão no carrinho, incluindo o nome do produto, preço e quantidade de cada item.

Fechar Pedido: A função fecharPedido() calcula o valor total da compra, somando os preços dos itens no carrinho multiplicados pela quantidade comprada. Depois de finalizar o pedido, o carrinho é esvaziado.

Funções Auxiliares

pegarProdutoPorCodigo() encontra um produto pelo código fornecido e retorna suas informações.
temNoCarrinho() verifica se o produto já está no carrinho. Se estiver, retorna a posição dele, senão retorna -1.
Como Compilar e Executar
Salve o código com a extensão .c, por exemplo, supermercado.c.
Abra o terminal no diretório onde o arquivo foi salvo.
Compile o código.

Funcionalidades do Sistema
Cadastrar Produtos: Permite cadastrar novos produtos com código, nome e preço.
Listar Produtos: Exibe todos os produtos cadastrados no sistema.
Comprar Produtos: Adiciona produtos ao carrinho de compras.
Visualizar Carrinho: Mostra os produtos no carrinho, com preços e quantidades.
Fechar Pedido: Calcula o valor total da compra e esvazia o carrinho.
