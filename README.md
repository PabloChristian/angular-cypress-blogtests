# dio-angular-cypress-blogtests
Projeto feito na Digital Innovation One para testes E2E utilizando Cypress em uma aplicação do tipo blog feito em Angular.

## Executando a Aplicação
Para executar a aplicação, execute os seguintes passos no terminal de comando:
```bash
1. Instale as dependências:
npm install
2. Inicie a aplicação:
ng serve

Acesse a URL `http://localhost:4200/` para visualizar.
```
## Executando os Testes
Para executar os testes, execute os seguintes passos no terminal de comando:
```bash
npm install cypress --save-dev
npm run cypress
#para abrir o cypress:
cypress open
```
## Scaffolding de Código
Crie o seu próprio componente na aplicação:
```bash
Criando um novo componente:
ng generate component component-name

Criando um serviço, modúlo, interface e outras opções:
ng generate directive|pipe|service|class|guard|interface|enum|module
```

## Build da Aplicação
Para realizar o build da aplicação, execute os passos abaixo:
```bash
Digite o comando abaixo:
ng build

Os artefatos de construção serão armazenados no diretório 'dist/'.
Utiliza a flag '--prod' para uma construção em ambiente de produção.
```
