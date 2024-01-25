# dredd-demo
[Dredd](https://dredd.org/en/latest/quickstart.html#advanced-examples) demo for API testing

## Install
```
npm install
```

## Run server
```
node app.js
```

## Run API tests
```
npx dredd api-description.apib http://127.0.0.1:3000
```
## Run tests using the Dredd configuration file
```
npx dredd
```
## Github actions
GH actions will check if Dredd tests are passing whenever there is a new push to main. Configuration of the workflow lives in
```
.github/workflows/pull-request.yml
```