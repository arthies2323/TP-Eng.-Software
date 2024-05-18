# Documentação da Arquitetura do Projeto

## Introdução

Nesta documentação, descreveremos a arquitetura do projeto para a aplicação ODS 11 - Cidades e Comunidades Sustentáveis. Este projeto visa desenvolver uma aplicação web informativa para promover a conscientização sobre o desenvolvimento urbano sustentável.

## Escolhas de Tecnologias

### Frontend:
- HTML, CSS e JavaScript para a estruturação, estilo e interatividade do site.
- Possivelmente um framework CSS, como Bootstrap ou Tailwind CSS, para facilitar o desenvolvimento responsivo e melhorar a aparência do site.

### Backend:
- Java, utilizando o framework Spring Boot, para o desenvolvimento do backend da aplicação.
- Spring MVC para o controle de requisições HTTP.
- Thymeleaf como mecanismo de template para a geração de páginas HTML dinâmicas.

### Banco de Dados:
- Banco de dados relacional, provavelmente com MySQL, para armazenar dados da aplicação.

## Projeto Arquitetural

### Visão Geral da Arquitetura
A arquitetura do projeto segue uma abordagem baseada em microserviços, dividindo a aplicação em componentes frontend e backend. O frontend é desenvolvido em HTML, CSS e JavaScript, enquanto o backend é implementado em Java com o framework Spring Boot. A comunicação entre os componentes é realizada por meio de requisições HTTP.

### Detalhes da Arquitetura
- **Frontend:** O frontend consiste em páginas HTML estáticas e estilos CSS para fornecer uma interface de usuário amigável e responsiva. O JavaScript é utilizado para adicionar interatividade à aplicação.

- **Backend:** O backend é composto por controladores de requisições implementados com o Spring MVC, que lidam com as requisições HTTP dos clientes. Os serviços de informações e projetos processam essas requisições, consultando e atualizando dados no banco de dados.

- **Banco de Dados:** O banco de dados relacional armazena os dados da aplicação, como informações sobre projetos e detalhes sobre o desenvolvimento urbano sustentável.

## Justificativa do Modelo Escolhido

O modelo arquitetural baseado em microserviços foi escolhido por sua capacidade de dividir a aplicação em componentes independentes e escaláveis. Isso permite um desenvolvimento mais ágil e modular, facilitando futuras atualizações e manutenção da aplicação.

Além disso, as tecnologias escolhidas, como Spring Boot para o backend e HTML/CSS/JavaScript para o frontend, são amplamente utilizadas, oferecendo suporte robusto e uma vasta comunidade de desenvolvedores.

