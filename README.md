# Bootcamp teste de API
Teste de API Rest do manual a CI/CD 


## O que é:
Este repositório foi criado para o bootcamp de Teste de API Rest. 

## Tecnologias utilizadas
- Postman versão web
- node version v19.0.1
- newman v6.1.3
- newman-reporter-html

## Documentações 

- Analise Técnica: Analise/
- Doc da API: [Consulte Swagger](https://serverest.dev/#/)

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

Se você optou por rodar os teste com o report htmlextra, você gerou um arquivo html com o resultado dos testes e para verificar as validações você pode abrir a pasta **newman** que foi criada no local em que os arquivos de collection e environment se encontram. 

## Evidência dos testes 

![execuo-ezgif com-video-to-gif-converter (2)](https://github.com/EdenilsonAlves/serveRest-API/assets/98066667/b07c7d41-cdbd-4ccc-9021-1e1d7a6c661c)

## Evidência do report

![20240627_011624-ezgif com-video-to-gif-converter](https://github.com/EdenilsonAlves/serveRest-API/assets/98066667/1a11ba9c-eb46-4b00-b743-744a36c04809)

## Entre em contato 

e-mail: Edenilson.tech.ti@gmail.com

Linkedin: https://www.linkedin.com/in/edenilson-rafael
