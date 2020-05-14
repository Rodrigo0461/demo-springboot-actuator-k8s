# Demo Spring Boot 2.X Actuators with K8S
Spring Boot Actuators K8S (Liveness Probe / Readiness Probe)


### Pre-requisitos 📋

 [Minikube](https://kubernetes.io/es/docs/tasks/tools/install-minikube/) - Para tener un cluster k8s LOCAL

Instalar Minikube en MacOS

```
brew install minikube
```

# Spring Boot Actuator's

Supervisan nuestra aplicación, recopilan métricas, comprenden y analizan el tráfico y el estado de nuestra base de datos, y todo ello sin falta de tener que implementarlo por nuestra cuenta.
Los Actuators se utilizan principalmente para exponer información operacional sobre nuestra aplicación en ejecución (health, metrics, info, dump, env, etc.)

# ¿Cómo se instala?

Validar que venga en el pom.xml, de lo contrario agregarlo.

```
<dependency>
       <groupId>org.springframework.boot</groupId>
       <artifactId>spring-boot-starter-actuator</artifactId>
</dependency>
```
