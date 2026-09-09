# Normalização de Banco de Dados

A normalização é o processo de organização dos dados em tabelas relacionadas, reduzindo redundâncias e evitando problemas de inserção, atualização e exclusão.

## 1ª Forma Normal (1FN)

Uma tabela está na 1FN quando cada campo possui apenas um valor atômico e não existem grupos repetitivos.

## 2ª Forma Normal (2FN)

Além de estar na 1FN, todos os atributos devem depender da chave primária completa. A separação de `PRODUTO` evita dependências parciais.

## 3ª Forma Normal (3FN)

Além de estar na 2FN, nenhum atributo não-chave deve depender de outro atributo não-chave. Os dados do cliente ficam em uma tabela própria.


## Benefícios

- Redução da duplicidade de dados;
- Maior consistência e integridade;
- Atualizações mais simples e seguras;
- Melhor organização dos relacionamentos.
