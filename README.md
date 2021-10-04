# Hora Extra Dialogflow Webhook

_URL do projeto_: <https://glitch.com/edit/#!/hora-extra-dialogflow-webhook?path=README.md>

_URL do serviço_: <https://hora-extra-dialogflow-webhook.glitch.me/webhook>

Baseado em [sheetdb/dialogflow-example](https://github.com/sheetdb/dialogflow-example)

## Ferramentas utilizadas

- Chatbot: [Dialogflow](https://dialogflow.cloud.google.com/)
- Serviço de [Google Sheets](https://docs.google.com/spreadsheets/) como JSON: [SheetDB](https://sheetdb.io/)
- Hospedagem de Node.js gratuito/editor de projeto Node.js: [Glitch](https://glitch.com/)
- Servidor Web para Node.js: [Express](https://expressjs.com/)

## Pacotes NPM utilizados

- [`actions-on-google`](https://www.npmjs.com/package/actions-on-google): dependência do pacote de Dialogflow relacionado a Google Assistant e Actions SDK
- [`dialogflow`](https://www.npmjs.com/package/dialogflow): biblioteca oficial para uso do Dialogflow em Node.js
- [`dialogflow-fulfilment`](https://www.npmjs.com/package/dialogflow-fulfillment): biblioteca oficial para uso de features relacionados a Fulfillments do Dialogflow em Node.js
- [`axios`](https://www.npmjs.com/package/axios) Requisições HTTP de maneira facilitada
- [`body-parser`](https://www.npmjs.com/package/body-parser) Tratamento de encoding UTF utilizado durante o recebimento de requests via Express
- [`express`](https://www.npmjs.com/package/express) Servidor Web utilizado

## Estrutura de arquivos

```
.
├── .env
├── README.md
├── package.json
├── server.js
└── src
    └── seo.json
```

- `.env`: arquivo contendo valores de ambiente a serem utilizados pelo projeto
- `README.md`: este arquivo, o qual contém dados sobre o projeto
- `package.json`: arquivo de configuração do projeto
- `server.js`: arquivo de entrada do Node.js e contém todo o código do projeto
- `src/seo.json`: arquivo com alguns metadados gerados pelo glitch

### Dados contidos no arquivo `.env`

- `SHEETDB_URL`: URL acessível via POST da planilha via [SheetDB](https://sheetdb.io/)
- `SHEETDB_LOGIN`: Login usado para acesso à planilha via [SheetDB](https://sheetdb.io/) quando [Basic Auth](https://developer.mozilla.org/en-US/docs/Web/HTTP/Authentication#basic_authentication_scheme) está habilitado
- `SHEETDB_PASSWORD`: Senha usada para acesso à planilha via [SheetDB](https://sheetdb.io/) quando [Basic Auth](https://developer.mozilla.org/en-US/docs/Web/HTTP/Authentication#basic_authentication_scheme) está habilitado

