Depen: Spring Web, Validation, h2/maridb, JPA, modelMapper

Sistema de ecommerce para venda de livros.

O Sistema deve permitir o cadastro de livros por GENERO, nome, autor e preço.

Para o cadastro de um livro.
Verbo HTTP: POST
URI: /livros
Corpo:
{
"nome":"Adeus e Obrigado Pelos Peixes",
"autor":{
"id":1
},
"preco":39.90,
"categoria": "FICCAO_CIENTIFICA"
}

Resposta 201
{
"vitrine": "localhost:8080/livros/{ID}"
}