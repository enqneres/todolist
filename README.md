### ✅ Principais recursos:
- 🔹 Gerenciamento de tarefas baseado no sistema CRUD (Create, Read, Update, Delete)
- 🔹 Autenticação básica para garantir a privacidade e a segurança dos usuários.
- 🔹 Armazenamento em database in-memory
- 🔹 Manipulador de exceção

### 🔧 Tecnologias utilizadas:
- 👉 Spring Boot
- 👉 Java
- 👉 Maven
- 👉 RESTful APIs
- 👉 Jpa Repository
- 👉 Lombok
- 👉 Amazon CodeWhisperer
- 👉 Swagger/OpenAPI

### 🌐 Endpoints:
1. Criar usuário: 
```
POST /users/
```
Este endpoint permite a criação de um usuário com username e senha.

2. Criar tarefa: 
```
POST /tasks/
```
Este endpoint permite a criação de uma nova tarefa, mediante autenticação do usuário.

3. Listar todas as tarefas: 
```
GET /tasks/
```
Este endpoint retorna todas as tarefas disponíveis.

4. Atualiza uma tarefa existente:
```
PUT /tasks/{id}
```
Este endpoint permite a atualização dos detalhes de uma tarefa existente com base no ID.

5. Deleta uma tarefa por ID:
```
DELETE /tasks/{id}
```
Este endpoint permite a exclusão de uma tarefa específica com base no ID fornecido.

### 📋 Observações e links externos: 
- Deploy da API no Render: https://todolist-rocket-1wx9.onrender.com
- Documentação com Swagger: https://todolist-rocket-1wx9.onrender.com/swagger-ui/index.html#/ 
- Parte dos mappings no código foi feito com IA generativa Amazon CodeWhisperer, através de plugin no IntelliJ
