# Aplicação Java Hello World

## Descrição
Este projeto é uma aplicação Java simples que utiliza uma API Rest para gerar uma saída "Hello World".

## Requisitos
- Java 11 ou superior
- Maven 3.6.0 ou superior

## Estrutura do Projeto
O projeto segue a estrutura padrão do Maven:

├── src  
│   
├── main  
│  
│  
├── java  
│  
│  
└── resources  
│  
└── test  
│  
├── java  
│  
└── resources  
├── pom.xml  
└── README.md

## Configuração
1. Clone o repositório:
   ```sh
   git clone <URL_DO_REPOSITORIO>
   cd <NOME_DO_REPOSITORIO>
   ```

Compile o projeto:
mvn clean install

Execução
Para executar a aplicação, utilize o seguinte comando:

```sh
mvn spring-boot:run
```

Endpoints
A aplicação expõe os seguintes endpoints:
GET /hello
Retorna uma mensagem "Hello World".
Exemplos de Uso
Requisição:

```sh
curl http://localhost:8080/hello
```

Resposta:

```json
{
  "message": "Hello World"
}
```

## Contribuição
Faça um fork do projeto.  
Crie uma branch para sua feature (git checkout -b feature/nova-feature).  
Commit suas mudanças (git commit -am 'Adiciona nova feature').  
Faça o push para a branch (git push origin feature/nova-feature).  
Abra um Pull Request.  

Autor: Renan