### Desafio: Construir uma API de Lista de Tarefas (Todo List)

**Objetivo:** Criar uma API RESTful para gerenciar uma lista de tarefas, incluindo autenticação de usuários, operações CRUD e tratamento de erros.

#### Requisitos:

1. **Configurar o Projeto:**
   - Escolha um framework backend como o Flask, se preferir faça tudo na raça.
   - Inicialize um repositório Git para controle de versão.

2. **Operações CRUD para Tarefas:**
   - Crie os seguintes endpoints para as operações:
     - `POST /todos` - Criar um novo item de tarefa.
     - `GET /todos` - Recuperar todos os itens de tarefa do usuário logado.
     - `GET /todos/:id` - Recuperar um item de tarefa específico.
     - `PUT /todos/:id` - Atualizar um item de tarefa específico.
     - `DELETE /todos/:id` - Deletar um item de tarefa específico.

4. **Validação de Dados:**
   - Valide os dados da requisição (por exemplo, o título da tarefa deve ser obrigatório, comprimento máximo, etc.) usando uma biblioteca como `marshmallow`.

5. **Tratamento de Erros:**
   - Trate erros para requisições inválidas e cenários de não encontrado com códigos de status HTTP apropriados.

6. **Integração com Banco de Dados:**
   - Use um banco de dados (por exemplo, MongoDB, PostgreSQL ou SQLite) para persistir itens de tarefas e informações do usuário.
   - Configure um esquema para os itens de tarefa (por exemplo, título, descrição, status de conclusão, referência do usuário).

7. **Registro de Logs:**
   - Registre requisições e erros.

8. **Testes:**
   - Escreva testes unitários e de integração para os endpoints da API usando um framework de testes.

9. **Documentação:**
   - Escreva um arquivo README detalhando como configurar o projeto, como usar a API e quaisquer dependências.

#### Tarefas Bônus:

- **Paginação:** Implemente paginação para o endpoint `GET /todos`.
- **Ordenação:** Permita que os usuários ordenem as tarefas por data de criação ou status de conclusão.

### Entregáveis:

1. Código-fonte em um repositório Git.
2. Uma API RESTful funcional com funcionalidade CRUD.
3. Documentação sobre como usar a API.
4. Testes unitários.