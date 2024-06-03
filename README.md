# Previsão do Tempo API

Esta é uma aplicação de backend em Python que fornece dados da previsão do tempo dos próximos 5 dias para São Paulo, utilizando a API do OpenWeatherMap. Os dados são armazenados em um banco de dados MongoDB para consulta posterior.

## Pré-requisitos

Antes de iniciar, verifique se você possui os seguintes pré-requisitos instalados em seu ambiente de desenvolvimento:

- Python 3
- MongoDB
- Docker

## Configuração

docker pull ghcr.io/carloseduardogn/previsao-tempo-api-eduardo:previsao-tempo-api-eduardo-v2

## Execução

Execute no terminal o comando:

docker run -p 8000:8000 -e MONGODB_URI="mongodb+srv://tempobom:KVwb3kXwtyVE7hFo@tempobom.llgg1f5.mongodb.net/?retryWrites=true&w=majority&appName=tempobom" -e MONGODB_DB="weather_db" -e OPENWEATHERMAP_API_KEY="20b8d053788d43ea2d42b5c834234969" previsao-tempo-api-eduardo

## Acesso

Acesse a URL:

http://localhost:8000/weather/SaoPaulo

```
