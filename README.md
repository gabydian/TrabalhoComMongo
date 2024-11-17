# TrabalhoComMongo

# **Shows API**

Uma API desenvolvida em **Spring Boot** para gerenciar shows utilizando **MongoDB** como banco de dados. A aplicação permite criar, listar, e buscar shows por ID.

---

## **Configuração do Projeto**

### **Pré-requisitos**
Certifique-se de que possui os seguintes softwares instalados:
- **Java 17** ou superior
- **Maven 3.8+**
- **MongoDB Atlas** ou MongoDB local
- **Postman** (opcional, para testar a API)

---

### **Instalação**
1. Clone o repositório:
   ```bash
   git clone https://github.com/seu-usuario/shows-api.git
   cd shows-api
Configure o arquivo application.properties com as credenciais do seu banco MongoDB:

properties
Copiar código
spring.application.name=Shows
spring.data.mongodb.uri=mongodb+srv://usuario:senha@cluster0.mongodb.net/shows?retryWrites=true&w=majority
server.port=8080
Substitua:

usuario pelo seu nome de usuário no MongoDB.
senha pela sua senha.
Compile o projeto:

bash
Copiar código
mvn clean install
Inicie a aplicação:

bash
Copiar código
mvn spring-boot:run
A API estará disponível em: http://localhost:8080.

