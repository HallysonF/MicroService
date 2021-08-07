# Projeto Micro Serviços

Repositório da  API Micro Serviços para cadastro e compra de produtos. Utilizaremos Java, Spring Boot, Hibernate Envers e lombok.Desenvolvimento no bootcamp Santander Fullstack.

O desafio consiste em desenvolver um projeto com uma  arquitetura de software baseada em microsserviços. 

## Download do projeto

Faça o clone do projeto:

```bash
$ git clone https://github.com/HallysonF/MicroService.git
$ cd MicroService
```

### Desenvolvimento da API- MICRO SERVIÇOS

Para o desenvolvimento da API foi utilizado Java, Spring Boot, Hibernate Envers,Lombok, shop-Cart e Service Discovery.

- Java

  Um projeto Java é composto por classes e essas classes possui tipos, modicadores de acesso, interfaces etcc.

- Spring Boot
  
  O Spring Boot facilita a criação de aplicativos autônomos baseados em Spring de nível de produção que você pode "simplesmente executar".

- Hibernate

  O Hibernate é um framework para o mapeamento objeto-relacional escrito na linguagem Java, mas também é disponível em .Net com o nome NHibernate. Wikipédia
- Envers

  O módulo Envers é um modelo central do Hibernate que funciona tanto com o Hibernate quanto com o JPA. Na verdade, você pode usar Envers em qualquer lugar que o Hibernate funcione, seja autônomo, dentro do WildFly ou JBoss AS, Spring, Grails, etc.

  O módulo Envers visa fornecer uma solução fácil de auditoria / controle de versão para classes de entidade. Hibernate.
- Lombok

  Uma biblioteca java que se conecta automaticamente ao seu editor e ferramentas de construção, aprimorando o seu java.
Nunca escreva outro método getter ou equals novamente, com uma anotação sua classe tem um construtor completo, Automatiza suas variáveis de registro e muito mais.
  
- No projeto foi utilizado o shop-cart que consiste em um carrinho de compras utilizando um outro tipo de armazenamento. 

- E uma comunicação entre serviços o service discovery e essencial para essa comunicação. Todo micro serviço que for iniciado
vai se registrar no service discovery, a partir desse momento o service discovery tera a localização exata do micro serviço
e ele passará a ser o interlocutor entre esses micro serviços direcionando as chamadas corretamente até o micro serviço chamado. 
##IDE para desenvolvimento

Para Desenvolvimento de todo o projeto foi utilizado o IDE InteliJ para mais informações
* [Jet Brains](https://www.jetbrains.com/pt-br/idea/)
## Banco de Dados

Para o Banco de dados SQL foi utilizado o SGBD H2 - é um sistema de gerenciamento de banco de dados relacional escrito em Java. Ele pode ser incorporado em aplicativos Java ou executado no modo cliente-servidor. O software está disponível como software de código aberto Mozilla Public License 2.0 ou Eclipse Public License original. Wikipedia (inglês)

## Realização de Testes
Para realização de testes foi utilizado o Postman - um API Client que facilita aos desenvolvedores criar, compartilhar, testar e documentar APIs. Isso é feito, permitindo aos usuários criar e salvar solicitações HTTP e HTTPs simples e complexas, bem como ler suas respostas. Mais informações
* [Postman](https://www.postman.com/)
