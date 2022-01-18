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

### Rotas
As rotas criadas foram tasks, hobbies, favgames e dreams.

### Hobbies 

Os hobbies aceitam apenas objetos escritos pelo dono dos recursos e pode ser lido por qualquer um logado.

### tasks

As tasks podem ser escritas apenas pelo dono do recurso mas pode seer lido por qualquer um.

### favgames 

Os jogos favoritos podem ser apenas escritos e lidos pelo dono do recurso.

### dreams 

Os sonhos podem ser escritos por qualquer um logado e lido por qualquer um.