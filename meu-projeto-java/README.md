# Meu Projeto Java

Este é um projeto Java simples que demonstra a estrutura básica de um aplicativo Java utilizando Maven.

## Estrutura do Projeto

```
meu-projeto-java
├── src
│   ├── main
│   │   ├── java
│   │   │   └── App.java
│   │   └── resources
│   └── test
│       ├── java
│       │   └── AppTest.java
│       └── resources
├── pom.xml
└── README.md
```

## Pré-requisitos

- Java JDK 11 ou superior
- Maven 3.6 ou superior

## Como Configurar

1. Clone este repositório:
   ```
   git clone https://github.com/seu-usuario/meu-projeto-java.git
   ```
2. Navegue até o diretório do projeto:
   ```
   cd meu-projeto-java
   ```

## Como Executar

Para compilar e executar o projeto, use os seguintes comandos:

1. Compile o projeto:
   ```
   mvn clean install
   ```
2. Execute a aplicação:
   ```
   mvn exec:java -Dexec.mainClass="App"
   ```

## Como Testar

Para executar os testes, utilize o comando:

```
mvn test
```

## Contribuições

Sinta-se à vontade para contribuir com melhorias ou correções. Faça um fork do repositório e envie um pull request.