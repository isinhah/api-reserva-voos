<h1 align="center">
  Sistema de Reserva de Passagens Aéreas
</h1>

## Descrição

API REST desenvolvida para gerenciar a reserva de passagens aéreas. Através desta API, passageiros podem buscar voos disponíveis, reservar assentos e obter tickets para suas reservas.

## Fluxo do Projeto

1. **Buscar Voos Disponíveis**: Passageiros podem procurar os voos disponíveis.
2. **Buscar Assentos Disponíveis**: Após selecionar um voo, o passageiro pode procurar os assentos disponíveis para esse voo específico.
3. **Criar Reserva**: O passageiro cria uma reserva especificando o ID do assento escolhido e o ID do voo.
4. **Criação Automática de Ticket**: Após a reserva ser criada, a disponibilidade do assento é atualizada e um ticket é gerado automaticamente. O ticket inclui o ID da reserva, o número do ticket e o ID do voo.
5. **Consultar Ticket**: O passageiro pode buscar informações sobre o ticket utilizando o ID da reserva.

## Endpoints
**Documentação Local**: http://localhost:8080/swagger-ui/index.html

<details>
    <summary><b>Voos</b></summary>
    <img src="./media/flights.png" alt="Voos">
</details>
<details>
    <summary><b>Assentos</b></summary>
    <img src="./media/seats.png" alt="Assentos">
</details>
<details>
    <summary><b>Reservas</b></summary>
    <img src="./media/reservations.png" alt="Reservas">
</details>
<details>
    <summary><b>Tickets</b></summary>
    <img src="./media/tickets.png" alt="Tickets">
</details>

## Tecnologias
- Linguagem: Java
- Framework: Spring Boot (Web, Jpa, Security)
- Banco de Dados: PostgreSQL
- Maven
- Flyway Migrations
- Java JWT
- JUnit 5
- Mockito

## Diagramas
<details>
    <summary>Diagrama de Classes</summary>
    <img src="./media/uml_diagram.png" alt="Diagrama de Classes">
</details>
<details>
    <summary>Diagrama de Entidade e Relacionamento</summary>
    <img src="./media/db_diagram.png" alt="Diagrama de Entidade e Relacionamento">
</details>

## Configuração e Execução

Pré-requisito: Java 17
1. Clone o repositório
2. Instale as dependências do **pom.xml** com Maven
3. Crie o database no PostgreSQL com as configurações do **application.properties**
4. Execute o **Application.java**

## Autor
Isabel Henrique

https://www.linkedin.com/in/isabel-henrique/
