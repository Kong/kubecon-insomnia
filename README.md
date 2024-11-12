## OpenAPI Spec starter for the workshop

This spec file is based on the following repository made by @filfreire: https://github.com/filfreire/groceries-insomnia

You can also follow instruction to run the python application in a container to follow along locally. For remote environment, we can use https://groceries-demo.dev.insomnia.moe.

### How to create Run in Insomnia button

Go to https://insomnia.rest/create-run-button to generate the following markdown or html snippet with your own Insomnia export file url (you can use your Github repository).

[![Run in Insomnia}](https://insomnia.rest/images/run.svg)](https://insomnia.rest/run/?label=insomnia%20session&
uri=https%3A%2F%2Fraw.githubusercontent.com%2Fmarckong%2Finsomnia-session%2Fmaster%2Fexport.json)

### URLs for demo sessions

#### REST
- Docs: https://rickandmortyapi.com
- https://rickandmortyapi.com/api/character

#### GraphQL
- Docs: https://rickandmortyapi.com
- https://rickandmortyapi.com/graphql

#### WebSocket
- Docs: https://docs.cdp.coinbase.com/exchange/docs/websocket-overview
- wss://ws-feed.exchange.coinbase.com
```
{
  "type": "subscribe",
  "product_ids": ["ETH-USD", "ETH-EUR"],
  "channels": [
    "level2",
    "heartbeat",
    {
      "name": "ticker",
      "product_ids": ["ETH-BTC", "ETH-USD"]
    }
  ]
}
```
