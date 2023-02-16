# ASPNETCore7-REST_API-JWT-BearerEvents-Swagger-Extensions_ContagemAcessos
Exemplo de API REST para contagem de acessos criada com o .NET 7 + ASP.NET Core, empregando extensões definidas em uma Class Library para utilização de JWT (JSON Web Tokens) + JwtBearerEvents e de configurações para que o Swagger suporte tokens.

Utilize o JSON a seguir como Body na requisição que gera o token:

```json
{
    "userID": "usr01_apis",
    "password": "Usr01ApiValido01!"
}
```