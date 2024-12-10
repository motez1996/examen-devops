# examen-devops

Ce projet est une application Spring Boot qui expose une API `/salutation` et utilise Spring Boot Actuator pour le monitoring.

## Points clés

- L'API `/salutation` renvoie "Bonjour Master DevOps II".
- Le port de l'application est 8080.
- Les endpoints de Spring Boot Actuator sont exposés sur le port 8888 (ex. `/actuator/health`, `/actuator/info`).

## Lancer l'application

```bash
./mvnw spring-boot:run
