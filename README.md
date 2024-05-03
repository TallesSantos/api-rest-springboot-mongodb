<h1 align="center">Projeto Spring boot com MongoDB </h1>
<p align="center" >
        <a href="https://skillicons.dev">
          <img src="https://skillicons.dev/icons?i=git,spring,mongo" />
        </a>
</p>

<h2>Sobre o projeto</h2>

<p>Projeto construído no curso "Java COMPLETO Programação Orientada a Objetos + Projeto ~Nélio alves".

<p> <a href="https://www.udemy.com/course/java-curso-completo"/>  << Link do curso >> </a> </p>

<h2>Características do projeto:</h2>

<p> Projeto consciste em integrar banco de dados noSQL utilizando mongoDb </p>

<h2>Instalação e execução do projeto</h2>

p>Você precisara ter o Java rodando em sua maquina </p>

<p>Clone o projeto em sua máquina.</p>

<p>Abra-o de preferência com a IDE inteliJ e atualize as dependências do projeto (caso elas n atualizem automaticamente).</p>

<p>Banco de dados mongoDb instalado <em> Observação: certifique-se que o mongoDb esteja rodando na porta 27017 e possua uma Coleção "workshop_mongo" </p> 
  
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



