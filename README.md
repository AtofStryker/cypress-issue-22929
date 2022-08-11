#### reproduction steps on Windows 10, Powershell, Node 16.16.0, Cypress 10.3.1

##### the following works
```
npx cypress open
```

##### the following cannot find the project configuration
```
cd .\node_modules\.bin\; .\cypress open
```

#### specifying the config relately yields the following
```
cd .\node_modules\.bin\; .\cypress open --config-file ..\..\cypress.config.js
```

