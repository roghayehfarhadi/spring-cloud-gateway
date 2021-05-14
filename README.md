# Gateway
## Table of Contents
- [Introduction](#introduction)
- [Features](#features)
- [Technologies](#technologies)

## Introduction
This project provides a library for building an API Gateway on top of Spring WebFlux.
Spring Cloud Gateway aims to provide a simple,
yet effective way to route to APIs and provide crosscutting concerns to them 
such as: security, monitoring/metrics, and resiliency.

This project handle rate limiting on Profile service.
If we have more than 3 requests per second, we will get an error .
 
## Features
These service can perform,
* Rate limiting 
## Technologies
* [Spring Boot](https://spring.io/projects/spring-boot)
* [Spring cloud Gateway](https://spring.io/projects/spring-cloud-gateway)
* [Eureka](https://spring.io/guides/gs/service-registration-and-discovery/)
* [Redis](https://redis.io/)
