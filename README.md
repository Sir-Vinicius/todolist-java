# Todolist
Este projeto foi feito seguindo o curso Gratuito da Rocketseat sobre Java usando a tecnologia Spring

## Descrição
O Todolist é um projeto de lista de tarefas desenvolvido em Java com o uso do framework Spring Boot.
Este projeto foi feito

## Conteúdo Seguido do Curso

O curso incluiu os seguintes tópicos:

- Construção back-end de uma aplicação de To-Do List
- Integração com Banco de Dados
- Implementando segurança nos dados do usuário
- Atualizando tarefas e validação de rotas
- Deploy do Back-End

## Tecnologias Utilizadas
- Java 17
- Spring Boot
- Spring Data JPA
- H2 Database (em ambiente de desenvolvimento)
- BCrypt (para criptografia de senhas)
- Lombok (para geração de código mais limpo)
- Maven (gerenciamento de dependências)
- Docker (opcional para implantação)

Para executar o projeto localmente, certifique-se de ter o Java 17 e o Maven instalados.

## Endpoints
- `POST /tasks`: Cria uma nova tarefa.
- `GET /tasks`: Lista todas as tarefas do usuário autenticado.
- `PUT /tasks/{id}`: Atualiza uma tarefa existente.
