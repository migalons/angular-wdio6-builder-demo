# AngularWdioBuilderDemo

This project is intended to show how to include your e2e test developed using [webdriver.io](http://webdriver.io)(v6) framework, into angular workspace, so you can integrate these test into angular lifecycle, replacing protractor test.

For enabling this, it includes a custom angular builder: [@migalons/angular-wdio-builder](http://github.com/migalons/angular-wdio-builder)


_This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 9.0.5._

## Running end-to-end tests

- Install dependencies with `npm i`.

    _Note: Personally, sometimes I had some difficulties trying to install chromedriver npm dependency, because of the binary download. But this is easy to fix following [instructions](https://github.com/giggio/node-chromedriver)._

- Run `npm run e2e` or `npx ng e2e` to execute the end-to-end tests via [wdio](http://www.webdriver.io/).

- For trying different options with builder parameters, just try to run with `npm run e2e:custom-config-file` or `npm run e2e:custom-options`

- Also it's possible to try different ng comand line options, for example:
```shell script
npx ng e2e
```
```
npx ng e2e -c custom-config-file
```
```
PORT=1234 npx ng e2e --port 1234
```

