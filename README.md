# API Web mínima com ASP.NET Core
 
As APIs mínimas são ideais para microsserviços e aplicativos que desejam incluir apenas os arquivos, recursos e dependências mínimos no ASP.NET Core.
 
POST https://localhost:<port>/cadastro/ 
  
GET https://localhost:<port>/cadastro/todos

PUT https://localhost:<port>/cadastro/{id}

DELETE https://localhost:<port>/cadastro/{id}
 
Especificação openAPI (openapi.json): https://localhost:<port>/swagger/v1/swagger.json 

 
 Exemplo de JSON
 ```
{
    "nome": "Ana",
    "idade": 18
}
```

[Tutorial: Criar uma API Web mínima com ASP.NET Core](https://docs.microsoft.com/pt-br/aspnet/core/tutorials/min-web-api?view=aspnetcore-6.0&tabs=visual-studio)

 [documentação da API Web do ASP.NET Core com o Swagger/OpenAPI](https://docs.microsoft.com/pt-br/aspnet/core/tutorials/web-api-help-pages-using-swagger?view=aspnetcore-6.0)
