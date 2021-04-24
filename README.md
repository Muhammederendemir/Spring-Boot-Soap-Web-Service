# Spring Boot Soap Web Service

> Spring Boot Soap Web Service
>
<img src="https://raw.githubusercontent.com/Muhammederendemir/Spring-Boot-Soap-Web-Service/master/images/spring-boot-soap-web-service-img.png" alt="Spring Boot Soap Web Service" width="100%" height="100%"/> 

## Prerequisites

* Java 11
* Maven 3.3+

## Used Technologies

* Spring Boot 2.4.3
* Spring Boot Web
* Maven Jib Plugin
* Maven Clean Plugin
* Spring Boot Test
* jaxb2-maven-plugin
* wsdl4j

## Postman Request

> You can access the Postman from the following url.

http://localhost:8080/ws

```xml

<soapenv:Envelope xmlns:soapenv="http://schemas.xmlsoap.org/soap/envelope/"
                  xmlns:gs="http://com/muhammederendemir/soap">
    <soapenv:Header/>
    <soapenv:Body>
        <gs:getCountryRequest>
            <gs:name>Turkey</gs:name>
        </gs:getCountryRequest>
    </soapenv:Body>
</soapenv:Envelope>
```

### Usage

<img src="https://raw.githubusercontent.com/Muhammederendemir/Spring-Boot-Soap-Web-Service/master/images/postman-ws-ss.png" alt="Postman Request" width="100%" height="100%"/> 
