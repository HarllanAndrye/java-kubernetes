# Aplicação Java no Kubernetes

![Java](https://img.shields.io/badge/-Java-333333?style=flat&logo=java)
![Spring Boot](https://img.shields.io/badge/-Spring_Boot-333333?style=flat&logo=spring)
![Apache Maven](https://img.shields.io/badge/-Apache_Maven-333333?style=flat&logo=apache-maven&logoColor=C71A36)
![Docker](https://img.shields.io/badge/-Docker-333333?style=flat&logo=docker)
![MySQL](https://img.shields.io/badge/-MySQL-333333?style=flat&logo=mysql)
![Kubernetes](https://img.shields.io/badge/-Kubernetes-333333?style=flat&logo=kubernetes)

### Rodando sua aplicação Java no Kubernetes. Do deploy ao debug sem medo!

Este projeto foi feito baseado nas aulas da Digital Innovation One e pode ser encontrado [aqui](https://github.com/sandrogiacom/java-kubernetes).

**Descrição do projeto**

Neste projeto você terá o desafio de construir um ambiente **Kubernetes** local para que possamos aprender a tecnologia sem medo de errar. Vamos criar os recursos necessários para fazer o **deploy** no cluster e configurar nossa aplicação a fim de fazer debug enquanto ela está rodando no Kubernetes.

O que foi utilizado no projeto:
- Java 11 (foi utilizado o openjdk-11);
- Maven;
- IDE IntelliJ;
- Docker;
- MySQL;
- Kubernetes (minikube e kubectl).

### :computer: Rodar a aplicação local
---

Há alguns scripts que podem ajudar na instalação das ferramentas de desenvolvimento: `https://github.com/sandrogiacom/k8s`.


**Contruindo a aplicação**
```bash
$ cd java-kubernetes
$ mvn clean install
```

**Iniciando o banco de dados**
```bash
$ make run-db
```

**Executando a aplicação**
```bash
$ java --enable-preview -jar target/java-kubernetes.jar
```

Após executar o comando acima, os seguintes endereços da API estarão disponíveis:
```
http://localhost:8080/app/users

http://localhost:8080/app/hello
```

### :computer: Rodar a aplicação no Docker
---

TODO :hammer_and_wrench:


### :computer: Rodar a aplicação no Kubernetes
---

TODO :hammer_and_wrench:

