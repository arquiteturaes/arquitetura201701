# Requisito : Controle de Estoque
## Objetivo :
O requisito trata a necessidade de controle de estoque e o detalhamento de suas funções. O usuário poderá ter acesso aos fornecedores, a quantidade de produtos disponiveis, adicionar produtos e gerar os relatórios(quantidade de produtos defeituosos, quantidade de produtos adicionados em determinado período, estatística de produtos, etc)

## Diagrama de Caso de Uso:
![casoUso](https://raw.githubusercontent.com/arquiteturaes/arquitetura201701/master/Imagens/casoUsoControleEstoque.png)
## Casos de uso :
# Caso de uso Adicionar produto
## Pré-condição:
.O usuário deve estar logado no sistema
## Objetivos:
	.Adicionar algum produto já cadastrado no sistema.
	.Adicionar produto novo.
## Pós-condição:
	.O sistema deverá gravar no estoque a quantidade de produtos inseridas ou o produto novo cadastrado.
# Caso de uso Verificar quantidade de produtos
## Pré-condição:
.O usuário deve estar logado no sistema
.Pelo menos um produto deve estar cadastrado no sistema
## Objetivos:
	.Verificar quantidade de determinado produto.
	.Verificar se um produto que não esteja mais disponível, o sistema ainda deve mostrar porém com a quantidade zerada.
## Pós-condição:
## Caso de uso Fornecedores
## Pré-condição:
.O usuário deve estar logado no sistema
## Objetivos:
	. O usuário pode cadastrar fornecedor.
	.O usuário pode consultar fornecedor.
	.O usuário pode excluir fornecedor.
## Pós-condição:
	O sistema deverá gravar ou excluir do sistema o fornecedor cadastrado/excluído.

# Caso de uso Gerar relatórios
## Pré-condição:
.O usuário deve estar logado no sistema
## Objetivos:
	. O usuário pode gerar relatórios de produtos retirados do estoque em determinado período.
	.O usuário pode gerar relatórios de produtos com defeitos.
	.O usuário pode gerar relatórios da quantidade de uso dos produtos.
## Pós-condição:
	O sistema deverá gerar o relatório.
