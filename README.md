# json-server-base

Esse é o repositório com a base de JSON-Server + JSON-Server-Auth já configurada, feita para ser usada no desenvolvimento das API's nos Capstones do Q2.

## Endpoints

Assim como a documentação do JSON-Server-Auth traz (https://www.npmjs.com/package/json-server-auth), existem 3 endpoints que podem ser utilizados para cadastro e 2 endpoints que podem ser usados para login.

### Cadastro

POST /register <br/>
POST /signup <br/>
POST /users

Qualquer um desses 3 endpoints irá cadastrar o usuário na lista de "Users", sendo que os campos obrigatórios são os de email e password.
Você pode ficar a vontade para adicionar qualquer outra propriedade no corpo do cadastro dos usuários.


### Login

POST /login <br/>
POST /signin

Qualquer um desses 2 endpoints pode ser usado para realizar login com um dos usuários cadastrados na lista de "Users"

###  users

Os users será utilizado para cadastrar e logar os usuários, aceitando o email e password. 

### cart

O cart armazena os produtos que o usuário adicionar ao carrinho, podendo apenas adicionar um de cada produto. Necessário estar logado para visualizar e adicionar itens.

### products 

Os produtos estão armazenados no products, possível ser editado apenas pelo dono do recurso e livre para qualquer usuário visualisar, mesmo sem estar logado.