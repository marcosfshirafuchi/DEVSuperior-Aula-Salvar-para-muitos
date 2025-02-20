# <a href="https://imgbb.com/"><img src="https://i.ibb.co/51bfmLv/image-2024-07-01-T11-45-10-371-Z.png" alt="image-2024-07-01-T11-45-10-371-Z" border="0" width="300"></a> Java Spring Professional - Capítulo: JPA, consultas SQL e JPQL

#### Desenvolvido na linguagem Java por:
- [Marcos Shirafuchi](https://github.com/marcosfshirafuchi)
## Formação Desenvolvedor Moderno Módulo: Back end
Capítulo: JPA, consultas SQL e JPQL

## AULA: Salvar entidades associadas para-muitos


<p align = center>
<a href="https://ibb.co/P9KL51C"><img src="https://i.ibb.co/cC0BN2T/Entidades-relacionadas-para-muitos.png" alt="Entidades-relacionadas-para-muitos" border="0"></a>
</p>

```
POST http://localhost:8080/products
{
    "name": "Produto novo",
    "price": 1000.0,
    "categories": [
      {
        "id": 2
      },
      {
        "id": 3
      }
    ]
}
```

O projeto foi desenvolvido na aula do curso Java Spring Professional - Capítulo: "JPA, consultas SQL e JPQL" na aula "Salvar entidades associadas para-muitos" da plataforma DEVSuperior do professor Nélio Alves.

## Principais Tecnologias

- <img width="50px" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/java/java-original-wordmark.svg" title = "Java" /> Java 21 : Utilizaremos a versão LTS mais recente do Java para tirar vantagem das últimas inovações que essa linguagem robusta e amplamente utilizada oferece;
- <img width="50px" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/spring/spring-original-wordmark.svg" title = "Spring boot"/> Spring Boot 3 : Trabalharemos com a mais nova versão do Spring Boot, que maximiza a produtividade do desenvolvedor por meio de sua poderosa premissa de autoconfiguração;
- <img width="50px" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/spring/spring-original-wordmark.svg" title = "Spring Data JPA"/>  Spring Data JPA: Exploraremos como essa ferramenta pode simplificar nossa camada de acesso aos dados, facilitando a integração com bancos de dados SQL;
- <img width="50px" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/sqldeveloper/sqldeveloper-original.svg" title = "H2 Database"/> H2 Database: Banco de dados SQL em memória.
- <img width="100px" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/postman/postman-plain-wordmark.svg" /> Postman: Para testar os métodos http do controller.
