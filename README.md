# Todo App

Este é um aplicativo de lista de tarefas (**Todo App**) desenvolvido com **Angular** no front-end, **Node.js** no back-end e **MongoDB** como banco de dados.

![image](https://github.com/user-attachments/assets/2d881603-dab8-42ca-9b33-0a727d60a7a5)


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

1. Acesse o repositorio do **front-end**:
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

Esse projeto foi desenvolvido em sala de aula, foi com ele que eu aprendi o básico do NodeJS e Angular
Desenvolvido por [Seu Nome](https://github.com/seu-usuario) 🚀

