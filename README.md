# Project-Estante-Virtual

Sistema de gerenciamento de emprestimo, venda, troca e doação de livros.

Iniciando a modelagem.

troca:
- nome
- email
- endereço
- telefone
- cpf

livro:
- titulo
- autor
- ano publicacao
- editora
- número de Paginas
- preço
- estoque
- tags
- categoria
- descrição

venda:
- nome 
- email
- cpf
- cep
- endereço

Pedido:
- user
- data pedido
- tipo

Usuario:
- nome
- email
- cpf
- senha
- endereço
- username

Doador:
- nome
- email
- histórico de doações
- cpf ou cnpj
- endereço
- telefone

emprestimo:
- nome
- email
- endereço
- telefone
- cpf

Pagamento:
- tipo


#Metodologia
1. Definição das entidades
2. Definição dos Átomos 
 * Definição dos seus Quarks
3. Definição das Moléculas
4. Definição dos Organimos
5. Definição das Rotas

##Definição das entidades
Não foi definido a modelagem do banco, apenas identificamos as entidades sem relacionamento dos mesmos.
- venda
- Pedido
- Usuario
- Doador
- emprestimo
- troca
- livro
- Pagamento

##Definição dos Átomos
Nessa etapa definimos todos os Átomos(campos) necessários para o sistema, porém ainda sem ligarmos o Átomo à entidade, pois um mesmo átomo pode estar em mais de 1 Molécula.

Átomos (não finalizados):

- username
- nome
- email
- password
- telefone
 - tipo
 - ddd
 - numero
- endereco
 - logradouro
 - nome
 - numero
 - complemento
 - cep
 - estado
 - pais
- cpf
- cnpj
- valor
- user_id
- doador_id
- venda_id
- Pedido_id
- emprestimo_id
- troca_id
- livro_id
- Pagamento_id


##Definição dos seus Quarks

##Definição das Moléculas

##Definição dos Organimos

##Definição das Rotas

##Planejamento

##Semana 1

##Semana 2

##Semana 3

##Semana 4

##Reuniões
