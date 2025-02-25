# Web API 

# Escopo do projeto
Criar uma web API para o catálogo de produtos/categorias que pode atender uma rede de lojas ou supermercados

Objetivos:
```
° Criar um serviço RESTful que permita que aplicativos clientes gerenciem o catálogo de produtos e categorias 
° Expor endpoints para criar, ler, editar e excluir produtos e também consultar produtos, e um produto específico
° Expor endpoints para criar, ler, editar e excluir categorias e também consultar categorias, uma categoria específica e os produtos de uma categoria

° Para Categorias, precisamos armazenar: o nome e o caminho da imagem
° Para Produtos, precisamos armazenar: nome, descrição, valr unitário, caminho da imagem, estoque, data do cadastro e categoria
```
Definição dos recursos, dos endpoints e do mapeamento:

Endpoint da API: /v1/api/produtos
```
° GET /v1/api/produtos
° GET /v1/api/produtos/1
° POST /v1/api/produtos
° PUT /v1/api/produtos/1
° DELETE /v1/produtps/1
```

Endpoint da API: /v1/api/categorias
```
° GET /v1/api/categorias
° GET /v1/api/categorias/1
° GET /v1/api/categorias/1/produtos
° POST /v1/api/categorias
° PUT /v1/api/categorias/1
° DELETE /v1/categorias/1
```

Implementar a segurança
```
° Permitir o acesso às APSs somente a usuários autenticados
° Definir uma políticade autorização de acessos aos usuários
° Expor endpoint para criar, ler, editar e excluir usuários e tambpem para consultar usuários e um usuário específico
° Para os usuários precisamos armazenar: nome, email, senha
```
Código de status HTTP usados nos responses (tratamento de erros):
```
200 - OK
201 - Created
202 - Accepted
204 - No Content
304 - Not Modified
400 - Bad Request
401 - Unauthorized
403 - Forbiddem
404 - Not Found
409 - Conflit
500 - Internal Server Error
```

