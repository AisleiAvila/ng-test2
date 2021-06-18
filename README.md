# NgTest1

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 11.0.1.

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory. Use the `--prod` flag for a production build.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via [Protractor](http://www.protractortest.org/).

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI Overview and Command Reference](https://angular.io/cli) page.


## Dicas

##### Utilização dos seguintes pacotes:
* <b>karma-chrome-launcher</b> - Responsável pela realização dos testes no Chrome;
* <b>karma-chrome-launcher</b> - Responsável pela realização dos testes no Firefox;
* <b>karma-junit-reporter</b> - Responsável pela geração de relatórios dos testes.

##### Scripts para execução dos testes:
* <b>test</b> - Realiza os testes no navegador Chrome. É aberta janela do navegador;
* <b>test-common</b> - Realiza os testes nos navegadores Chrome e Firefox. São abertas janelas dos nevegadores;
* <b>test-ci</b> - Realiza testes nos navegadores Chrome e Firefox. Não são abertas janelas dos navegadores;
* <b>test-coverage</b> - Realiza testes no navegador Chrome e emite relatório de cobertura dos testes. Exemplo de nome de arquivo gerado nos testes: TESTS-Chrome_Headless_91.0.4472.101_(Windows_8.1)

##### Script para execução da aaplicação e da API
* <b>all</b> - Executa a aplicação e a API. Aplicação acessada através da URL Http://localhost:4200 e API acessada através da URL Http://localhost:3000/photos
##### Execução dos scripts:
* <b>test</b> - ng test ou npm run test
* <b>test-common</b> - npm run test-common
* <b>test-ci</b> - npm run test-ci
* <b>test-coverage</b> - npm run test-coverage
* <b>all</b> - npm run all

