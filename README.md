<h1>Projeto Spring boot com MongoDB </h1>

<h2>Sobre o projeto</h2>

<h2>Instalação e execução do projeto</h2>

<h2> API Endpoints </h2>
A api fornece os seguintes endpoints:

<h3>Users</h3>

<p >GET /users - Retorna toda a lista de usuarios (não retorna sua lista de posts) .</p>

<p>GET /users/id - retorna um usuario (não retorna sua lista de posts) . </p>

<p>POST /users - Registra um novo usuário sem nenhum post .</p>

<p>UPDATE /users/id - atualiza os atributos de um usuário . </p>

<p>DELETE /users/id -Deleta o usuário com o id passado . </p>

<h3>Posts</h3>

<p>GET /posts/id - Retorna todos os posts do usuário com o id passado .</p>

<p>GET /posts/titlesearch - Retorna todos os posts que o título corresponda com o parâmetro passado . </p>

<p>POST /posts/fullsearch - Retorna todos os posts filtrando pelas queryes passadas por parâmetro  .</p>



