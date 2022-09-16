# mudi-loja-alura
Curso de Spring MVC: autenticação com Spring Security, API Rest e AJAX


## Banco no docker
```bash
 docker run --name mariadb-mudi -p 3306:3306 -e MYSQL_USER=root -e MYSQL_PASSWORD=root -e MYSQL_ROOT_PASSWORD=root -e MYSQL_DATABASE=mudi -d mariadb:10.5
```

## Baixar as dependências e executar o projeto 
```bash
    mvn clean install spring-boot:run
```