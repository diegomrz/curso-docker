<h1 align="center">
  Curso Docker na Udemy
</h1>

<h2 align="center">
  <img alt="GitHub language count" src="https://img.shields.io/github/languages/count/diegomrz/curso-docker">

  <a href="https://www.linkedin.com/in/diegomrz/">
    <img src="https://img.shields.io/badge/linkedin-diegomrz-blue">
  </a>

  <a href="https://www.udemy.com/curso-docker/">
    <img alt="Curso Docker" src="https://img.shields.io/badge/curso-Docker-blue">
  </a>
  
  <a href="https://www.udemy.com/curso-docker/">
    <img alt="Curso Docker" src="https://img.shields.io/badge/conclusão-36/60-brightgreen">
  </a>
</h2>

### Módulos
 - Introdução
 - Conceitos
 - Instalação
 - Uso Básico do Docker
 - Deixando de Ser Apenas um Usuário
 - Redes
 - Coordenando Múltiplos Containers
 - Projeto Cadastro Simples 
 - Projeto para Envio de E-mails com Workers 

### Comandos
- Listar imagens:\ docker images
- Remover imagem:\ docker rmi <IdImage ou NameImage>
- Executar container:\ docker start <IdContainer ou NameContainer>
- Parar container:\ docker stop <IdContainer ou NameContainer>
- Remover container:\ docker stop <IdContainer ou NameContainer>
- Listar containers em execução:\ docker ps
- Listar containers em execução e parados:\ docker ps -a

### Criar containers de Bancos de Dados
- $ docker run --name some-postgres -e POSTGRES_PASSWORD=mysecretpassword -d postgres
- $ docker run --name some-mysql -e MYSQL_ROOT_PASSWORD=my-secret-pw -d mysql:tag
- $ docker run --name some-mongo -d mongo:tag
