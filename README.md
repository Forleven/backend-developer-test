# Backend Developer - Test

![Forleven Logo](https://site.forleven.com/img/logotipo_green.png)

Desenvolva uma API Rest para um cadastro de estudantes com intuito de consultar, criar novos registros, realizar atualizações e exclusões nestes (CRUD) utilizando um banco de dados.
Em um cenário de trabalho esta API seria consumida por um desenvolvedor front-end trabalhando em par contigo.

Crie um repositório **público** no github em uma conta pessoal sua e nos envie o link como resposta no email de seu entrevistador ou caso tenha problemas para localiza-lo envie no career@forleven.com 

## Informações técnicas

Utilizar linguagens suportadas pela Forleven que são Java ou Kotlin, preferencialmente Java que é a linguagem predominante no back-end da empresa.
Banco de dados preferencialmente MySQL/MariaDB ou algum banco similar ao mesmo (Postgre, SQLite ou H2).

- Escrever uma aplicação que exponha uma API Rest
- Esta API deve conter ao menos um CRUD básico

## Regras de negócio

- Cadastrar campos nome, sobrenome e matrícula;
- Todos os campos devem ser preenchidos;
- Todos os campos devem conter mais de 3 caracteres;
- O campo de matrícula não pode se repetir dentro da base;

## Dicas

Estamos avaliando seu perfil Back-end, caso queira você pode construir um front para sua aplicação, mas não é o foco, concentre-se na melhor solução possível para o seu back-end.

API de exemplo para você se inspirar: https://swapi.dev/

## Bônus

- Cadastrar múltiplos telefones, dar a opção cadastrar N telefones ao registro de um estudante.
- Usar frameworks consolidados como Spring (spring jpa, spring boot, spring web).

## Super Bônus

- Fazer deploy da aplicação em qualquer serviço a sua escolha como AWS, Heroku, Google Cloud, Azure, etc (muitos desses serviços possuem disponilizam um acesso gratuito).
  - Dica: Você pode fazer deploy da app usando H2 como banco para não precisar realizar deploy de um banco

## Quais são os itens que avaliamos ?

Os itens abaixo são alguns dos pontos que usamos como parâmetros para realizar avaliações, você pode se utilizar deles para realizar uma auto avaliação ao escrever este teste.

- Readme do projeto
- Uso de boas práticas da linguagem baseado em code quality com o plugin SonarLint para o IntelliJ
- Coesão das dependências usadas na ferramenta de compilação escolhida (maven ou gradle)
- Coesão no uso do GIT
- Escrita de teste unitários e coverage
- Estrutura do projeto com uso de DTO, controller, service, repository, model/entity
- Uso de docker quando pertinente
- Conceitos de Clean Code
- Conceitos de SOLID
- Uso de arquivo para configuração como application.yml ou application.properties
