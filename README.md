### API com banco de dados e login 


- Link teste API: https://app-test-query-builder.herokuapp.com/

#### Endpoints
##### Sem autenticação
- POST(/usuarios) Para cadastrar um novo usuario
- POST(/logar) Para dar acesso as outras funcionalidades

###### (Necessário usuar o token do tipo Bearer)

##### Com autenticação

#### Usuário
-GET(/perfil) Obter dados do usuario pelo token

-PUT(/perfil) Editar dados do usuario

#### Produtos

-GET(/produtos) Para listar todos os produtos

-GET(/produtos/id) Para listar um produto específico

-POST(/produtos) Para cadastrar um novo produto

-PUT(/produtos/id) Para editar um produto já cadastrado

-DELETE(/produtos/id) Para excluir um produto expecifico
