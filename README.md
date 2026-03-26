## EUREKA SERVER FOR TASK MANAGEMENT

## Eureka Server Configuration 
- [application.yaml] file
```bash 
server:
    port: 8070

eureka:
    instance:
      hostname: localhost
      prefer-ip-address: true
    client:
      register-with-eureka: false
      fetch-registry: false
      service-url:
        defaultZone: http://${eureka.instance.hostname}:${server.port}/eureka/

```

## 👤 Author

**Swagat Murmu**  
*Master of Computer Applications (MCA)*
- **Primary Skills:** 
  - **Backend:** Java & Spring Boot
  - **Frontend:** React & JavaScript
  - **Database:** SQL
