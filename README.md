# SpringBootTech
Spring Boot pratice with lots of technologies

# Swagger local
http://localhost:9010/boot-tech/swagger-ui.html

# Technologies are used
- Swagger
- Flyway
- JPA/Hibernate
- Lombok
- jxls
- Spring Security, OAuth2
- RESTful API

# Setup https
- Using this command to generate keystore (with PKCS12 format):
```
keytool -genkeypair -alias tuzaku -keyalg RSA -keysize 2048 -storetype PKCS12 -keystore keystore.p12 -validity 3650 -storepass tzk@20200923
```

# Refs:
- https://www.thomasvitale.com/https-spring-boot-ssl-certificate/
- https://www.baeldung.com/rest-api-search-language-spring-data-querydsl
- https://www.baeldung.com/spring-security-integration-tests