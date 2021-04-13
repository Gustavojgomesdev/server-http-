<p align="center">
  <img src="https://miro.medium.com/max/5120/1*1dB4wl4G2fYYfgKba_XLog.png"width="200">
</p>

# Criando um Servidor HTTP

## Orientações 
>Projeto com o objetivo de criar um servidor em HTTP, que receba requisições GET, e retorne um JSON uja chave extenso seja a versão por extenso do número inteiro enviado no path. Os números podem estar no intervalo [-99999, 99999].

> Exemplo: 
<p align="center">
  $ curl http://localhost:3000/1
{ "extenso": "um" }
</p>

## Requisitos básicos para rodar o servidor na sua máquina: 
* Node JS 
* Docker

## Passo para rodar o servidor: 

* Clone o repositório na sua máquina: > https://github.com/Gustavojgomesdev/server-https-.git
* Entre no diretório: > cd server-https-
* Escreva no seu terminal esse comando para dar início ao Docker: > docker-compose up 

## Servidor rodando 
* Digite no navegador: =>  http://localhost:3000
* Feito isso digite: http://localhost:3000/1
* O servidor irá retonar: {"extenso":"um"}
