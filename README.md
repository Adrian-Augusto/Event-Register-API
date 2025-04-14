# 📅 Event Register API

Uma API simples para registrar eventos com suporte a mensageria via RabbitMQ e testes unitários com JUnit + Mockito.

---

## 🚀 Funcionalidades

- ✅ Criar, listar, editar e excluir eventos
- 📤 Enviar eventos para uma fila RabbitMQ após cadastro
- 📥 Consumir mensagens da fila (simulação de notificação/log)
- 🧪 Testes unitários com JUnit e Mockito

---

## 🛠️ Tecnologias

- Java 17
- Spring Boot
- Spring Data JPA
- RabbitMQ (mensageria)
- H2 Database (ambiente de teste)
- JUnit 5
- Mockito

---

## 📦 Instalação

### Pré-requisitos:

- Java 17+
- Maven
- RabbitMQ rodando localmente (porta padrão: 5672)

### Clone o projeto:

```bash
git clone https://github.com/seu-usuario/event-register-api.git
cd event-register-api
