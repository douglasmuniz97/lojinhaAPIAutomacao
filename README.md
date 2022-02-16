## Lojinha API Automação
Esse é um repositório que contém a automação de alguns testes de API Rest de um software denominado lojinha.  Os sub-tópicos abaixo descrevem algumas decisões tomadas nas estruturação do projeto.

## Tecnologias Utilizadas

- Java (https://www.java.com/pt-BR/)
- Junit (https://www.java.com/pt-BR/)
- RestAssured (https://www.java.com/pt-BR/)
- Maven (https://www.java.com/pt-BR/)

## Testes Automatizados
Testes para validar as partições de equivalência relacionadas ao valor do produto na Lojinha, que estão vinculados diretamente a regra de negócio que diz que o valor do produto deve estar entre 0 e 7 mil reais.

## Notas gerais

- Sempre utilizamos a anotação before Each para capturar o token que
  será utilizado posteriormente nos métodos de testes

- Armazenamos os dados que são enviados para a API através do uso de classes POJO
- Criamos dados iniciais através do uso se Data Factory, para facilitar a criação e controle dos mesmos.
- Nesse projeto fazemos o uso do JUnit 5, o que nos da a possibilidade de usar a anotação DisplayName para dar descrições em português para nossos testes.
