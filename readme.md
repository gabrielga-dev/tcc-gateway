![campus-formiga.jpg](doc/images/campus-formiga.jpg)

Olá! Este é o gateway do TCC: "APLICAÇÃO DE UMA ARQUITETURA DE MICROSSERVIÇOS EM UM SISTEMA WEB PARA CONECTAR 
PRODUTORES DE EVENTOS E PRESTADORES DE SERVIÇOS".

**Atenção:** É importante a leitura de como executar o "ms-mailer" antes de qualquer outro microsserviço. Caso você 
ainda não tenha lido, acesse o repositório por <a href="https://github.com/gabrielga-dev/tcc-ms-mailer">aqui</a>.

Sua principal função é redirecionar todas as requisições efetuadas pelo front-end do projeto para os seus respectivos
microsserviços.

Para executar o microsserviço, basta rodar o seguinte comando:
```
mvn spring-boot:run
```
ou simplesmente importando o projeto em sua IDE de preferência e executando através dela.