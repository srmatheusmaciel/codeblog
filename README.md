# CodeBlog - Plataforma de Publicação de Artigos

CodeBlog é um projeto desenvolvido com **Spring Boot** e **Thymeleaf**, projetado para fornecer uma plataforma simples e eficiente para publicação e gerenciamento de artigos.

## 🚀 Tecnologias Utilizadas

- **Java 11**
- **Spring Boot 2.7.5**
- **Spring Data JPA**
- **Spring Security**
- **Thymeleaf**
- **PostgreSQL**
- **Hibernate Validator**
- **Spring Boot DevTools**
- **JUnit & Spring Security Test**

## 🏗️ Arquitetura do Projeto

O projeto segue a arquitetura MVC (Model-View-Controller) com as seguintes camadas:

```
📦 codeblog
├── 📂 configuration  # Configurações do sistema
├── 📂 controller    # Controladores (Endpoints)
├── 📂 model         # Entidades do banco de dados
├── 📂 repository    # Interfaces de acesso a dados
├── 📂 service       # Regras de negócio
├── 📂 utils         # Métodos utilitários
```

## 📦 Dependências (Maven)

O projeto utiliza as seguintes dependências:
```xml
<dependencies>
    <dependency>
        <groupId>org.springframework.boot</groupId>
        <artifactId>spring-boot-starter-data-jpa</artifactId>
    </dependency>
    <dependency>
        <groupId>org.springframework.boot</groupId>
        <artifactId>spring-boot-starter-security</artifactId>
    </dependency>
    <dependency>
        <groupId>org.springframework.boot</groupId>
        <artifactId>spring-boot-starter-thymeleaf</artifactId>
    </dependency>
    <dependency>
        <groupId>org.springframework.boot</groupId>
        <artifactId>spring-boot-starter-web</artifactId>
    </dependency>
    <dependency>
        <groupId>org.thymeleaf.extras</groupId>
        <artifactId>thymeleaf-extras-springsecurity5</artifactId>
    </dependency>
    <dependency>
        <groupId>org.postgresql</groupId>
        <artifactId>postgresql</artifactId>
        <scope>runtime</scope>
    </dependency>
</dependencies>
```

## 🛠️ Como Executar o Projeto

1. **Clone o repositório**:
   ```bash
   git clone https://github.com/srmatheusmaciel/codeblog.git
   ```
2. **Configure o banco de dados PostgreSQL** no arquivo `application.properties`:
   ```properties
   spring.datasource.url=jdbc:postgresql://localhost:5432/codeblog
   spring.datasource.username=seu_usuario
   spring.datasource.password=sua_senha
   ```
3. **Execute o projeto**:
   ```bash
   mvn spring-boot:run
   ```

## 📝 Licença

Este projeto é distribuído sob a licença MIT. Sinta-se à vontade para contribuir! 🚀
