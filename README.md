# Projeto Faculdade - Programação Orientada a Objetos

#### Desafio: Implementar um banco de dados PostgreSQL ao back-end e criar um front-end e conectar ao back

#### Instruções de como utilizar esse projeto no VSCode

- Faça o clone do repositório
- Na pasta *banco* utilize o comando `mvn install` para instalar as dependências do back-end
- Ainda no back-end vá em `src/resources/application.properties` e redefina a *url*, *username* e *password* de acordo com o banco de dados que está usando
- No back-end vá em `src/java/apresentacao/WebConfig.java` e redefina a parte de `allowedOrigin('A porta do front que está usando')`
- Na parte do front-end, vá na pasta front-end e dê um `yarn install` ou `npm install`
- Vá no html e executa com a extensão *live server*
- Na parte do back vá em `src/apresentacao/AcessoADado.java` e executa com *run java*