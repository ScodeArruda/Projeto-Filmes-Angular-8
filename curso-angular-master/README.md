# Projeto Angular 8 - Web site de filme

## Acesse o site para ver uma prévia https://scode-filmes.web.app

## Instalação

1. clone o repositório `git clone git@github.com:ScodeArruda/Projeto-Angular-8.git`
2. Entre no projeto e instale as dependencias `npm install`

## Ambiente Local

Execute `ng serve` para que o projeto suba localmente. Acesse a url `http://localhost:4200/`. O projeto já está com reload automático conforme as alterações que você realizar no código

## Simulando o Back-end

Execute `npm install -g json-server` para instalar globalmente o servidor json. Após a instalação entre na pasta do projeto e execute `json-server --watch db.json`, com isso um servidor será inicializado na url `http://localhost:3000/`, após a inicialização sera possível realizar requisições http.

## Gerando componente

Execute `ng generate component nome-do-componente` para criar um novo componente. Você também pode usuar `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Build

Execute `ng build` para gerar o compilado do projeto. O projeto vai ser criado dentro do diretório `dist/`. Adicionar `--prod` junto comando de build para gerar minificado e pronto para o ambiente de produção.

![image](https://user-images.githubusercontent.com/74998751/110945883-02407100-831d-11eb-9551-e2f6e736da4f.png)
![image](https://user-images.githubusercontent.com/74998751/110945927-11bfba00-831d-11eb-9a2b-61bd573d2291.png)
![image](https://user-images.githubusercontent.com/74998751/110945959-1d12e580-831d-11eb-98b4-19e39c7bd6e2.png)
