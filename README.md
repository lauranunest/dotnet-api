# API Web mínima com ASP.NET Core
 
As APIs mínimas são ideais para microsserviços e aplicativos que desejam incluir apenas os arquivos, recursos e dependências mínimos no ASP.NET Core.
 
POST https://localhost:<port>/cadastro/ 
  
GET https://localhost:<port>/cadastro/todos

PUT https://localhost:<port>/cadastro/{id}

DELETE https://localhost:<port>/cadastro/{id}
 
 Exemplo de JSON
 ```
{
    "nome": "Ana",
    "idade": 18
}
```
