# Azure with mongodb

[Document](https://docs.microsoft.com/en-us/azure/developer/javascript/tutorial/vscode-function-app-http-trigger/tutorial-vscode-serverless-node-install?tabs=bash)

```bash
curl -X POST https://ts-cosmosdb-mongodb-function-app.azurewebsites.net/api/category?code=9MUId4QqXEXu7kQ%3D%3D \
   -H 'Content-Type: application/json' \
   -d '{"document":{"name":"John"}}' --verbose

curl -X POST https://ts-cosmosdb-mongodb-function-app.azurewebsites.net/api/category?code=9MUId4QqXEXu7kQ%3D%3D \
   -H 'Content-Type: application/json' \
   -d '{"document":{"name":"Sally"}}' --verbose

curl -X GET https://ts-cosmosdb-mongodb-function-app.azurewebsites.net/api/category?code=9MUId4QqXEXu7kQ%3D%3D \
   -H 'Content-Type: application/json' --verbose

curl -X GET https://ts-cosmosdb-mongodb-function-app.azurewebsites.net/api/category?code=9MUId4QqXEXu7kQ%3D%3D \
   -H 'Content-Type: application/json' \
   -d '{"id":"61926c307e1e05bf61207cf8"}' --verbose

curl -X DELETE https://ts-cosmosdb-mongodb-function-app.azurewebsites.net/api/category?code=9MUId4QqXEXu7kQ%3D%3D \
   -H 'Content-Type: application/json' \
   -d '{"id":"61926c307e1e05bf61207cf8"}' --verbose
```