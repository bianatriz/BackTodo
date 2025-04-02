# Todo App

Este é um aplicativo de lista de tarefas (**Todo App**) desenvolvido com **Angular** no front-end, **Node.js** no back-end e **MongoDB** como banco de dados.

Essa aplicação é uma adaptação do projeto do Mozilla Dev que você pode encontrar [aqui](https://developer.mozilla.org/en-US/docs/Learn_web_development/Core/Frameworks_libraries/Svelte_Todo_list_beginning) e foi  desenvolvida em aula. Foi com ele que eu aprendi o básico do NodeJS e Angular.

![image](https://github.com/user-attachments/assets/4ffccb55-2931-4408-bdec-02211dcd02ff)


## Funcionalidades

- Criar, ler, atualizar e excluir tarefas (**CRUD**)
- Interface responsiva com Angular
- API para gerenciar as tarefas

---

## Como Rodar o Projeto

### 1. Clonar o Repositório

```sh
git clone https://github.com/seu-usuario/todo-app.git
cd todo-app
```

### 2. Configurar o Back-end

1. Acesse o diretório do **back-end**:
   ```sh
   cd back-end
   ```
2. Instale as dependências:
   ```sh
   npm install express nodemon mongoose
   ```
3. Inicie o servidor Node.js com MongoDB:
   ```sh
   nodemon index "URL_DO_BANCO_MONGO_AQUI"
   ```

### 3. Configurar o Front-end

1. Acesse o diretorio do **front-end**:
   ```sh
   cd ../front-end
   ```
2. Instale as dependências do Angular:
   ```sh
   npm install
   ```
3. Inicie o servidor Angular:
   ```sh
   ng serve
   ```

---

## Considerações Finais

- Certifique-se de ter o **MongoDB** rodando antes de iniciar o back-end.
- Para modificar a **URL do banco MongoDB**, edite a linha de comando do `nodemon index <URL>`.
- O front-end consumirá a API exposta pelo back-end automaticamente.

---

Desenvolvido por [Ana B](https://github.com/bianatriz) 🚀

