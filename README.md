# dio-gft-desafio-automacao-de-testes# dio-gft-desafio-automacao-de-testes
Este projeto é um exercício do Bootcamp da GFT que visa a compreensão e automação de testes. Para realizar este exercicio foi utilizado o projeto [Restful-Booker](https://restful-booker.herokuapp.com/).
O projeto é fortemente baseado no [exemplo](https://github.com/digitalinnovationone/api-automation-tests-challenge-rest-assured) ministrado pela instrutora Carolina Louzada.
A pasta [postman](https://www.postman.com/) fornece o arquivo com a suite de testes para ser importado pela ferramenta.   
Para a execução é necessario ter instalado e configura JDK 11, maven e [allure](https://github.com/allure-framework)

Para gerar o relatorio allure via plugin utilizar os comandos:

```
mvn clean test
mvn allure:serve
```
