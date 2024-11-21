## Para testar o consumo da api foi feito um projeto usando react native e TypeScript.

### Necessário instalar as dependências com:
   npm install
### Para rodar o projeto:
   npx expo start
   
   após isso, utilizaremos abriremos a interface web com: 
   
   w
   O servidor estará rodando em:
   
   http://localhost:8081

### A primeira página será de de login:
   Passando o email e a senha para autentica um usário existente no banco de dados na rota:
   
   http://localhost:3000/auth/signin
   
   retornará o um token que o usuário foi autenticado.

### Criar conta:
   Necessário passar o email, nome e senha para criação:
   Pegando os campos e enviando uma requisição com método Post para:
   
   http://localhost:3000/user
   retornara um Alert indicando que o usuário foi cadastrado com sucesso ou não.
   podendo também deletar um post com um x no canto do comentário feito na rota com o método Delete:
   
   http://localhost:3000/post/:id

### Página de posts:
   Após o login ou cadastro de um usuário, será mostrado a tela com posts feitos do usuário:
   
   http://localhost:3000/posts
   e um botão para abrir uma nova e adicionar novos posts, com o método Post:
   
   http://localhost:3000/post
