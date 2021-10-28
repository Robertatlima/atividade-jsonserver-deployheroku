# json-server-base

Esse é o repositório com a base de JSON-Server + JSON-Server-Auth já configurada, feita para ser usada no desenvolvimento das API's nos Capstones do Q2.

## Endpoints

A api possui endpoints para cadastro de novo usuario, login, cadastrar estados que desejam conhecer e criar grupos de seu interesse

### Cadastro

POST /register
POST /signup
POST /users

Qualquer um desses 3 endpoints irá cadastrar o usuário na lista de "Users", sendo que os campos obrigatórios são os de email e password.
Você pode ficar a vontade para adicionar qualquer outra propriedade no corpo do cadastro dos usuários.

### Login

POST /login
POST /signin

Qualquer um desses 2 endpoints pode ser usado para realizar login com um dos usuários cadastrados na lista de "Users"

### estados

POST / states
Para cadastro de novos estados- é necessario esta logado.

GET/states
Para listar os estados- Qualquer um pode acessar

### Grupos

POST / groups
Para cadastro de novos grupos- é necessario esta logado.

GET/groups
Para listar os grupos- É preciso estar logado para acessar.
