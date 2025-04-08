# listaMercadoBack
**

# Sistema Lista de Mercado
## Requisitos

- Ser capaz de gerenciar varias listas de mercado(e marcar seu status como conclu[idas ou não)
- ser capaz de cadastrar produtos e consulta-los
- ser capaz de incluir produtos nas listas e especificar suas quantidades, bem como marcar se o item ja foi comprado ou náo
- ser capaz de atribuir valores aos itens comprados para depois ter uma gestão dos custos da lista
- ser capaz de adicionar quantidades (kg, unidades, litros, etc)


## Casos de Uso - Produto
### Cadastrar produtos
Informar o nome de um determinado produto e o sistema o armazena no banco

### Consultar produtos
Informar palavras chaves para consultar ou mesmo buscar produtos a partir de uma lista
### Alterar dados de produtos
Basicamente alterar o nome do produto e termos sua efetivação no banco de dados


## Casos de Uso - Lista
### Criação de listas
Criar uma nova lista inserindo a data e o local onde foi feita a compra (nome do supermercado/feira, etc)
### Apagar uma lista
Remover uma lista que foi criada por engano e remover todos os seus itens que foram criados
### Inserção de itens na lista
Criar um item assinado a uma lista de produto, bem como deixar disponível a possibilidade de modificar a quantidade e preço que foi pago.
### Alteração de itens da lista
Alterar apenas quantidade, preço pago e status
### Remoção de itens da lista
Pode remover um item que foi cadastrado na lista
### Fechamento da lista
Concluir a lista como sendo completa e gerar seu custo total a partir dos itens comprado.
**