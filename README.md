# Padrão de Projeto Com Spring
Neste projeto  foi explorado 3 tipos de padrões de projeto para a criação de uma Api:

* Singleton.
* Strategy/Repository.
* Facade.

## Tecnologia de uso

* [Spring initializr](https://start.spring.io/)
* Java 11
* Spring Boot 2.7.5
* Maven


### Dependencies para o Spring

* Spring Data JPA
* Spring Web
* OpenFeign 
   * [ViaCep API](https://viacep.com.br/)
* H2 DataBase
* Lombok

### Documentação
A documentação dessa Api foi feita com Swagger, foi necessário ser injetado nas dependencias do **pom.xml**

* [OpenApi](https://springdoc.org/#javadoc-support)
    * Utilize a versão atualizada na documentação
```
<dependency>
    <groupId>org.springdoc</groupId>
    <artifactId>springdoc-openapi-ui</artifactId>
    <version>1.6.12</version>
</dependency>
```

### Links que podem te ajudar
These additional references should also help you:

* [Primeiros Passos Com Spring Boot](https://www.devmedia.com.br/primeiros-passos-com-o-spring-boot/33654)
* [Padrões de Projetos Com Java](https://www.devmedia.com.br/guia/padroes-de-projeto-em-java/34456)
