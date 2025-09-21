# Reverse Proxy Service — Nidam

## Purpose
Gateway that fronts the platform. Acts as a reverse proxy and gateway for:
- `/react-ui` → React SPA
- `/auth` → Authorization Server
- `/bff` → BFF

Read the documentation: https://nidam.derbyware.com

**Part of the Nidam (6 repositories):**
- registration, token-generator, reverse-proxy, nidam, bff, nidam-spa — links:
    - https://github.com/Mehdi-HAFID/registration
    - https://github.com/Mehdi-HAFID/token-generator
    - https://github.com/Mehdi-HAFID/reverse-proxy
    - https://github.com/Mehdi-HAFID/nidam
    - https://github.com/Mehdi-HAFID/bff
    - https://github.com/Mehdi-HAFID/nidam-spa

## Run locally
```bash
mvn spring-boot:run 

#OR

# Build
mvn clean package

# Run
java -jar target/registration-*.jar
```

[//]: # (TODO change to the new one)
![Nidam Architecture](https://nidam.derbyware.com/img/v2/Nidam-v2-Routing.svg "New Nidam Architecture")

