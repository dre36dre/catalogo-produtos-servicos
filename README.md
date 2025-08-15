Catálogo de Produtos e Simulação de Pedidos
Sistema de catálogo de produtos e simulação de pedidos baseado em microsserviços, desenvolvido com Spring Boot e Spring Cloud. O projeto demonstra conceitos de arquitetura distribuída, descoberta de serviços e roteamento via API Gateway.

Arquitetura
O sistema é composto por quatro módulos:

Product Service – Gerencia cadastro e consulta de produtos.

Order Service – Cria e gerencia pedidos de clientes.

Eureka Server (Service Registry) – Permite que os microsserviços se descubram dinamicamente.

API Gateway – Ponto de entrada único para requisições, roteando para os microsserviços corretos.

Funcionalidades
Cadastro e listagem de produtos.

Criação e simulação de pedidos.

Consulta de status de pedidos.

Comunicação entre microsserviços via HTTP usando descoberta de serviços.

Roteamento de requisições via API Gateway.

Tecnologias
Java 17+

Spring Boot 3.x

Spring Cloud Eureka (Service Registry)

Spring Cloud Gateway (API Gateway)

Spring Data JPA

H2 Database

Lombok

Maven

Benefícios
Estrutura modular e escalável.

Facilita integração com outros sistemas via API Gateway.

Demonstra conceitos práticos de Spring Cloud, como descoberta de serviços e roteamento.
