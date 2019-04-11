# TeaStore

> <https://github.com/DescartesResearch/TeaStore>

**Size of the project:** ~19,000 SLoC

## Description

The TeaStore is a test application which emulates a simple web store for tea and tea supplies. It features UI elements for database generation and service resetting in addition to the store itself. The TeaStore contains four backend services written in Java, the frontend service for the web ui written in Java and JavsScript. Additionally there is a registry service providing information about the services that are online. The Services communicate using REST and are using the Netflix Ribbon client side load balancer.

## Services
- [WebUI](https://github.com/DescartesResearch/TeaStore/tree/master/services/tools.descartes.teastore.webui) (Java servlet, JavaScript)

- [Authentication](https://github.com/DescartesResearch/TeaStore/tree/master/services/tools.descartes.teastore.auth) (Java servlet)

- [Image](https://github.com/DescartesResearch/TeaStore/tree/master/services/tools.descartes.teastore.image) (Java servlet)

- [Recommender](https://github.com/DescartesResearch/TeaStore/tree/master/services/tools.descartes.teastore.recommender) (Java servlet)

- [Persistence](https://github.com/DescartesResearch/TeaStore/tree/master/services/tools.descartes.teastore.persistence) (Java servlet)

- [Registry](https://github.com/DescartesResearch/TeaStore/tree/master/services/tools.descartes.teastore.registry) (Java servlet)	- Non-functional service


## Architecture

![](images/tea-store-architecture.png)
