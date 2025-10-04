<div align="center">
  <h1>💰 Gerenciador Financeiro Pessoal</h1>
  <p><strong>Aplicação Full Stack com Java Spring Boot + HTMX para controle de gastos simples, eficiente e dinâmico.</strong></p>

  <img src="https://img.shields.io/badge/Status-Finalizado-28a745?style=for-the-badge" alt="Status do Projeto">
  <img src="https://img.shields.io/badge/Java-17-007396?style=for-the-badge&logo=java" alt="Java 17">
  <img src="https://img.shields.io/badge/Spring_Boot-3.x-6DB33F?style=for-the-badge&logo=spring" alt="Spring Boot 3.x">
</div>

---

## 🔗 Acesso à Aplicação
A versão publicada está disponível em:  
👉 [**Controle de Gastos - GitHub Repository**](https://github.com/Douglas-caron/Controle-de-gastos-2)

---

## 💡 Conceito
O objetivo central deste projeto é oferecer uma ferramenta web intuitiva para gerenciamento de despesas pessoais.  
A aplicação foi desenvolvida com **arquitetura robusta**, separando claramente as responsabilidades entre backend e frontend, e com um frontend dinâmico que proporciona uma experiência semelhante a uma SPA (Single Page Application).

---

## ⭐ Funcionalidades
- 📌 **Cadastro de Despesas:** inclusão de novos gastos com informações básicas.  
- 📋 **Listagem Geral:** visualização de todas as despesas em tabela organizada.  
- ✏️ **Edição:** atualização de registros existentes de forma simples.  
- 🗑️ **Exclusão:** remoção de lançamentos de forma definitiva.  
- ⚡ **Interatividade Instantânea:** interface responsiva sem recarregamento de página (via **HTMX**).  

---

## 🏗️ Arquitetura & Tecnologias
A aplicação foi construída com foco em **separação de camadas**:

- **Backend (API & Regras de Negócio):**  
  Implementado com **Spring Boot**, que gerencia lógica de negócio, persistência com **Spring Data JPA/Hibernate** e exposição de endpoints.  

- **Frontend (Renderização & Interação):**  
  **Thymeleaf** para renderização server-side e **HTMX** para interações dinâmicas, reduzindo a necessidade de JavaScript manual.

| Categoria            | Stack Utilizada                  |
|-----------------------|----------------------------------|
| **Linguagem**         | Java 17                          |
| **Framework**         | Spring Boot 3.x                  |
| **Acesso a Dados**    | Spring Data JPA + Hibernate      |
| **Template Engine**   | Thymeleaf                        |
| **Interatividade**    | HTMX                             |
| **Banco de Dados**    | PostgreSQL                       |
| **Build & Gestão**    | Apache Maven                     |
| **Deploy**            | Render                           |

---

## 🖥️ Guia de Instalação Local

### 1️⃣ Pré-requisitos
- **Java (JDK 17+)** instalado  
- **Maven** configurado no sistema  
- **PostgreSQL** em execução  

### 2️⃣ Clonar Repositório
```bash
git clone https://github.com/Douglas-caron/Controle-de-gastos-2
cd Controle-de-gastos-2
3️⃣ Configurar Banco de Dados
No arquivo src/main/resources/application.properties, ajuste as credenciais de conexão:

properties
Copy code
spring.datasource.url=jdbc:postgresql://localhost:5432/nome_do_banco
spring.datasource.username=seu_usuario
spring.datasource.password=sua_senha
4️⃣ Executar Aplicação
bash
Copy code
./mvnw spring-boot:run
A aplicação estará disponível em: http://localhost:8080

🗺️ Estrutura do Projeto
bash
Copy code
.
├── src
│   ├── main
│   │   ├── java/com/seu_pacote      # Controllers, Models, Repositories
│   │   └── resources
│   │       ├── static               # Arquivos estáticos (CSS, JS, imagens)
│   │       └── templates            # Views Thymeleaf
└── pom.xml                          # Configuração do Maven e dependências
🧑‍💻 Desenvolvedor
Projeto desenvolvido por Douglas Caron 
