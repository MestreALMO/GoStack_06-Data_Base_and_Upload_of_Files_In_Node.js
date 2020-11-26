# GoFinances 

## O que se trata o projeto
O projeto GoFinances é uma simulação de transações financeiras. 

## Funcionalidades:
### Cadastrar transações:
Cada transação possui os campos __titulo, valor, tipo, categoria__ , o campo __tipo__ recebe o valor __income__ se a transação for para inserir  o valor 
equivalentedo ao valor informado no campo __valor__ , ou o campo __tipo__ recebe o valor __outcome__ se a transação for para tirar o valor equivalente 
ao informado no campo __valor__.
Quando cadastramos uma transação, precisamos informar uma categoria para a transação e quando irformarmos a categoria o sistema vai verificar
se a categoria informada exste no banco de dados na tabela __categoria__ , se a categoria não existir a categoria informada será criada na tabela
__categoria__ e a transação irá ser cadastrada no banco de dados na tabela __transações__ e se a categoria existir então só será inserida a
transação na tebela transação__.

### Listar todas transações feitas fazendo um balano de quanto entrou, de quanto saiu e do total
Todas as transações com os campos __id, tituto, type, value, categoria_id__ e será feito no final um balanço de todo o valor que entrou,
todo o valor que saiu e o total.

### Deletar transação: 
As transações poderam se deletadas

### Fazer transações importando arquivo CSV:
Em um arquivo CSV com os campos __titulo, tipo, valor, categoria__ vamos informar seus valores e fazer upload desse arquivo contendo
as transações e elas seram cadastradas exatamente como na funcionalidade __Cadastras transações__.

## Conceitos aplicados no projeto:
- Banco de dados com o TypeORM, conceitos de migrations para criar tabelas e suas estruturas
- Upload de arquivos
- Arquitetura para divisão de responsabilidades no código
- Tratativa de erros
- Tipagem com typescript

## Tecnologias utilizadas:
- Node.js
- TypeORM 
- Banco de dados Postgres
- Multer
- Typescript
