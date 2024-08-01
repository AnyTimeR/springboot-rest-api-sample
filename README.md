# CRUD Completo com Spring Boot REST API

Este projeto é um exemplo de CRUD (Create, Read, Update, Delete) completo utilizando Spring Boot e uma API RESTful. O objetivo é demonstrar como construir uma aplicação backend robusta com Java e Spring Boot, integrando-a com um banco de dados PostgreSQL e disponibilizando-a na nuvem.

## Ferramentas Utilizadas

- **Java**: Linguagem de programação utilizada para o desenvolvimento do backend.
- **Maven**: Ferramenta de automação de compilação e gerenciamento de dependências.
- **Apache Tomcat**: Servidor web utilizado para hospedar a aplicação.
- **Spring Boot**: Framework para construção de aplicações Java, facilitando a configuração e inicialização.
- **PostgreSQL 16**: Banco de dados relacional utilizado para armazenar as informações.
- **pgAdmin 4**: Interface gráfica para gerenciamento do PostgreSQL.
- **REST API**: Arquitetura utilizada para construção da interface de comunicação entre o cliente e o servidor.
- **Hospedagem Cloud**: Plataforma de hospedagem na nuvem para disponibilização da aplicação.
- **Heroku**: Serviço de hospedagem em nuvem onde a aplicação está disponibilizada.

## JDev Treinamento

Este projeto foi desenvolvido como parte do curso oferecido pelo JDev Treinamento.

## Estrutura do Projeto

- `src/main/java`: Código-fonte da aplicação.
- `src/main/resources`: Arquivos de configuração e recursos estáticos.
- `pom.xml`: Arquivo de configuração do Maven.
- `README.md`: Documentação do projeto.

## Como Executar o Projeto

1. **Pré-requisitos**:
   - Java 11 ou superior instalado.
   - Maven instalado.
   - PostgreSQL 16 instalado e configurado.
   - Conta no Heroku (opcional para hospedagem).

2. **Clonar o Repositório**:
   ```sh
   git clone https://github.com/seu-usuario/seu-repositorio.git
   ```

3. **Configurar o Banco de Dados**:
   - Criar um banco de dados PostgreSQL.
   - Configurar as credenciais no arquivo `application.properties`.

4. **Compilar e Executar a Aplicação**:
   ```sh
   mvn clean install
   mvn spring-boot:run
   ```

5. **Acessar a Aplicação**:
   - A aplicação estará disponível em `http://localhost:8080`.
