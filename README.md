# ✈️ Sistema de Reserva de Passagens Aéreas

## 📄 Descrição

API REST desenvolvida para gerenciar a reserva de passagens aéreas. Através desta API, passageiros podem buscar voos disponíveis, reservar assentos e obter tickets para suas reservas.

---

## ⚙️ Funcionalidades

- **Busca de voos**: Passageiros podem pesquisar voos disponíveis com base em critérios específicos.
- **Seleção de assentos**: Permite a visualização e escolha de assentos disponíveis em um voo.
- **Criação de reservas**: Possibilita a criação de uma reserva associando o assento e o voo escolhidos.
- **Geração automática de tickets**: Um ticket é gerado automaticamente após a confirmação da reserva, incluindo detalhes importantes.
- **Consulta de tickets**: Passageiros podem consultar informações sobre seus tickets a qualquer momento.

---

## 🛠️ Tecnologias

- **Linguagem**: Java
- **Framework**: Spring Boot (Web, JPA, Security)
- **Gerenciador de Dependências**: Maven
- **Banco de Dados**: PostgreSQL
- **Migração de Banco**: Flyway Migrations
- **Segurança**: Java JWT
- **Testes**: JUnit 5, Mockito
- **Documentação da API**: SpringDoc

---

## 📝 Endpoints

**Documentação local**: http://localhost:8080/swagger-ui/index.html

---

## 📈 Diagramas

<details>
    <summary><b>Diagrama de Classes</b></summary>
    <img src="./media/uml_diagram.png" alt="Diagrama de Classes"  width=650>
</details>
<details>
    <summary><b>Diagrama de Entidade e Relacionamento</b></summary>
    <img src="./media/db_diagram.png" alt="Diagrama de Entidade e Relacionamento"  width=800>
</details>

---

## 🗂️ Imagens do Projeto

<details>
    <summary><b>Voos</b></summary>
    <img src="./media/flights.png" alt="Voos" width=500>
</details>
<details>
    <summary><b>Assentos</b></summary>
    <img src="./media/seats.png" alt="Assentos" width=500>
</details>
<details>
    <summary><b>Reservas</b></summary>
    <img src="./media/reservations.png" alt="Reservas" width=500>
</details>
<details>
    <summary><b>Tickets</b></summary>
    <img src="./media/tickets.png" alt="Tickets" width=500>
</details>

---

## ➡️ Fluxo da Aplicação

1. O passageiro busca voos disponíveis.
2. O passageiro seleciona um voo e consulta os assentos disponíveis.
3. O passageiro cria uma reserva informando o ID do voo e o ID do assento.
4. A disponibilidade do assento é atualizada e um ticket é gerado automaticamente com os dados da reserva.
5. O passageiro consulta o ticket utilizando o ID da reserva.

---

## ⚙️ Configuração e Execução

**Pré-requisitos**:

- **Java 17**
- **Maven**
- **PostgreSQL**

**Passos para Configuração**:

1. Clone o repositório
2. Acesse o diretório do projeto
3. Configure o banco de dados no arquivo `application.yml` (URL, usuário, senha)

```bash
# Executar a aplicação
mvn spring-boot:run

# Para parar a aplicação, pressione Ctrl + C no terminal.
```

---

## 🙋‍♀️ Autor

👩‍💻 Projeto desenvolvido por [Isabel Henrique](https://www.linkedin.com/in/isabel-henrique/)

🤝 Fique à vontade para contribuir!
