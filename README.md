# AngularConsumeAPI

Para rodar o projeto é preciso rodar o comando `npm i `para instalar as dependências necessárias para o projeto, depois pode rodar o `ng serve` para rodar a aplicação. Depois navegue para `http://localhost:4200/`.

Obs.: Essa aplicação utiliza um json server para simular as requisições de servidor Web, então é necessário além de iniciar a aplicação, também iniciar o servidor json, para isso primeiro você precisa rodar no terminal o comando `npm i -g json-server`, para instalar globalmente o json-server. Depois navegar até a pasta backend `cd backend` e por último rodar o comando` json-server --watch database.json` ou `npx json-server --watch database.json`, para iniciar o servidor json na porta 3000.
