## 📄 Sobre o projeto

Este projeto consiste no desenvolvimento de uma API REST utilizando Spring Boot e JPA, com foco em um sistema de pedidos (e-commerce simplificado), abordando desde a modelagem de domínio até a implementação completa das operações de CRUD e regras de negócio.

A aplicação foi construída de forma incremental, iniciando com a criação da estrutura base do projeto, configuração do banco de dados H2 para testes e integração com JPA. Em seguida, foram implementadas as entidades principais como User, Order, Product e Category, além de enums como OrderStatus para controle de estado dos pedidos.

O projeto explora diferentes tipos de relacionamentos entre entidades, incluindo:

* One-to-many (Produto e itens de pedido)
* Many-to-many com atributos extras (OrderItem)
* One-to-one (Pagamento)

Também foram implementadas funcionalidades como cálculo de subtotal e total dos pedidos, além da camada de serviços para encapsular as regras de negócio e o uso de injeção de dependência com Spring.

Posteriormente, foram adicionadas operações completas de CRUD para usuários, bem como tratamento de exceções personalizado para operações como busca, atualização e remoção de dados.

Por fim, o projeto inclui melhorias como documentação no README e configuração de CI com GitHub Actions (gradle.yml), demonstrando preocupação com boas práticas de desenvolvimento e organização do projeto.

Este projeto demonstra conceitos importantes como:

* Arquitetura em camadas
* JPA / Hibernate
* Modelagem de domínio
* Relacionamentos entre entidades
* Tratamento de exceções
* Boas práticas em APIs REST
