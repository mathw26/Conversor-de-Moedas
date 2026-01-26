💱 Conversor de Moedas em Python

Este projeto é um conversor de moedas em Python que utiliza uma API de câmbio em tempo real para converter valores em reais (BRL) para outras moedas internacionais.

O objetivo do projeto é praticar:

Consumo de APIs

Manipulação de JSON

Estruturas de decisão

Dicionários em Python

Entrada e saída de dados no terminal

🚀 Funcionalidades

Consulta cotações atualizadas usando API externa

Conversão de Real (BRL) para:

💵 Dólar (USD)

💶 Euro (EUR)

💷 Libra (GBP)

🇦🇷 Peso Argentino (ARS)

🇯🇵 Iene (JPY)

🇨🇱 Peso Chileno (CLP)

Menu interativo no terminal

Opção de finalizar a conversão

🛠️ Tecnologias Utilizadas

Python 3

Requests (para consumo da API)

API de Câmbio: ExchangeRate API

📦 Pré-requisitos

Antes de rodar o projeto, você precisa ter instalado:

Python 3.x

Biblioteca requests

Instale a dependência com:

pip install requests

▶️ Como executar o projeto

Clone este repositório:

git clone https://github.com/seu-usuario/seu-repositorio.git


Acesse a pasta do projeto:

cd seu-repositorio


Execute o arquivo:

python conversor.py

🧠 Como o projeto funciona

O programa consome a API de câmbio usando o Real (BRL) como base

Exibe as cotações das moedas disponíveis

Solicita ao usuário:

O valor em reais

A moeda desejada para conversão

Realiza o cálculo e exibe o valor convertido no terminal

📌 Exemplo de uso
Digite quantos reais você tem: R$ 100

Escolha a moeda que deseja converter:

[1]- Dólar
[2]- Euro
[3]- Libra
[4]- Pesos Argentinos
[5]- Yene
[6]- Pesos Chilenos

Qual moeda você quer saber sua conversão? 1

Você teria 19.85 Dólares

📈 Possíveis melhorias futuras

Tratamento de erros (ex: falha na API)

Loop para múltiplas conversões sem reiniciar o programa

Interface gráfica (GUI)

Conversão entre quaisquer moedas

Versão web (Flask ou FastAPI)
