# Service-based Web Shop v1

> <https://github.com/xJREB/service-based-web-shop-v1>

**Size of the project:** ~2,500 SLoC

## Description

This app emulates a simple WebShop system and contains 6 backend services and one frontend service that provides read access to most of the other services resources. The services are implemented in Java with the help of the the Dropwizard framework and are using REST for the communication. This project was part of a controlled experiment, so you can ignore everything related to e.g. exercises.

## Services
- [WebUI](https://github.com/xJREB/service-based-web-shop-v1/tree/master/src/WebUI) (JavaScript, Vue.js)

- [Category](https://github.com/xJREB/service-based-web-shop-v1/tree/master/src/CategorySrv) (Java, Dropwizard)

- [Customer](https://github.com/xJREB/service-based-web-shop-v1/tree/master/src/CustomerSrv) (Java, Dropwizard)

- [Notification](https://github.com/xJREB/service-based-web-shop-v1/tree/master/src/NotificationSrv) (Java, Dropwizard)

- [Order](https://github.com/xJREB/service-based-web-shop-v1/tree/master/src/OrderSrv) (Java, Dropwizard)

- [Product](https://github.com/xJREB/service-based-web-shop-v1/tree/master/src/ProductSrv) (Java, Dropwizard)

- [Warehouse](https://github.com/xJREB/service-based-web-shop-v1/tree/master/src/WarehouseSrv) (Java, Dropwizard)

## Architecture
![](images/service-based-web-shop-v1-architecture.png)