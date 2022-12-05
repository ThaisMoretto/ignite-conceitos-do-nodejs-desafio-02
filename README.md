# Desafio: Conceitos do Node.js 

Essa é uma aplicação para gerenciar tarefas (em inglês *todos*).
Será permitida a criação de um usuário com `name` e `username`, bem como fazer o CRUD de *todos*:

- Criar um novo *todo*;
- Listar todos os *todos*;
- Alterar o `title` e `deadline` de um *todo* existente;
- Marcar um *todo* como feito;
- Excluir um *todo*;

Tudo isso para cada usuário em específico. Além disso, existe um plano grátis onde o usuário só pode criar até dez todos e um plano Pro que irá permitir criar todos ilimitados, isso tudo usando middlewares para fazer as validações necessárias.

---

### Requisitos
- [x] Deve ser possível criar um usuário informando `name` e `username`
- [x] Deve ser possível buscar um usuário buscando pelo seu `id`
- [x] Deve ser possível atualizar o plano de um usuário para `true` ou `false`
- [x] Deve ser possível buscar a lista de `todos` de um usuário
- [x] Deve ser possível buscar um único `todo` de um usuário
- [x] Deve ser possível criar um novo `todo`
- [x] Deve ser possível atualizar o `title` e o `deadline` de um *todo*
- [x] Deve ser possível atualizar o status de um *todo* para `done`
- [x] Deve ser possível deletar um `todo`


### Regras de Negócio
- [x] Não deve ser possível cadastrar um usuário com `username` já existente
- [x] Não deve ser possível atualizar o plano para `true` de um usuário inexistente ou caso ele já possua o plano pro ativado
- [x] Não deve ser possível listar `todos` de um usuário inexistente
- [x] Não deve ser possível listar um `todo` que não pertença ao usuário informado
- [x] Não deve ser possível atualizar o `title` e o `deadline` de um *todo* inexistente
- [x] Não deve ser possível atualizar o status de um *todo* inexistente ou que não pertença ao usuário informado
- [x] Não deve ser possível deletar um *todo* inexistente ou que não pertença ao usuário informado

---
---
## Executando a aplicação
Para iniciar a aplicação basta executar o comando:

`yarn dev`

---
---
## Testes unitários
Para iniciar iniciar a execução dos testes unitários basta executar o comando:

`yarn test`