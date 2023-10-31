# Observability playground

Playground for observability with Spring Boot, Micrometer, Prometheus, Grafana.
Using Spring Boot 3.1 docker compose support, Prometheus and Grafana are orchestrated as docker containers, Prometheus
scraping the Spring boot app using the docker-gateway.

## Technology / External Libraries

- Java 21
- Spring Boot 3.1.5 with actuator and micrometer-prometheus-registry
- Prometheus
- Grafana
- Gradle 8.4

## Program description

Some simple Spring Boot app to try out different metrics and monitoring with Prometheus and Grafana.

## Repository Contents

Sources for project  tests and configurations.

## Progress

30.10.23 Create docker compose file and prometheus config. Add all dependencies needed to gradle build file.
