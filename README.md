# Testes portalDeVendasAPI
Testes de API do Portal de Vendas utilizando Postman e Newman

## PortalDeVendasAPI
Criação de testes de API utilizando Postman, Newman 

## O que é
Este repositório foi criado para de Teste de API Rest do portal de Vendas.

## Quais as tecnologias
- Postman versão web
- node version v20.10.0
- newman v6.0.0
- newman-reporter-html

 
## Como instalar o ambiente

- Primeiro: instale o node em seu computador [baixe aqui](https://nodejs.org/en/download)
- Segundo: realize a instalação do newman de forma global [baixe aqui a dependencia](https://www.npmjs.com/package/newman)
```
npm install -g newman
```
- Terceiro: realize a instalação da dependencia dos relatórios (opcional) [newman-reporter-html
](https://www.npmjs.com/package/newman-reporter-html)
```
npm install -g newman-reporter-html
```
## Como rodar os testes

### Pelo Postman web ou desktop
- Import a collection e o environment
- Execute os teste de forma manual ou automatizada

### Pelo newman

- Abra o console de preferência
- Execute a seguinte linha de comando para rodar os testes
```
newman run ServeRest.postman_collection.json -e serveRest_env.postman_environment.json -r cli
```
- Execute os teste com relatório
```
newman run ServeRest.postman_collection.json -e serveRest_env.postman_environment.json -r cli,htmlextra
```
### Report

Se você optou por rodar os teste com o report htmlextra, você gerou um arquivo html com o resultado dos testes e para verificar as validações você pode abrir a pasta newman que foi criada no local em que os arquivos de collection e environment se encontram.

## Entre em contato
email: de-valerio@hotmail.com

Linkedin: https://www.linkedin.com/in/debora-valerio/
