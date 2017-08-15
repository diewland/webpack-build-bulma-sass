# Build bulma.sass with webpack

### Installing

```
npm install
```

### Build

```
npm run build
```

### Structure

```
root/
  |-- dist/
  |   |-- bulma.min.css     <-- sass output
  |   |-- bundle.js
  |-- node_modules/*
  |-- src/
  |   |-- app.js
  |   |-- build-bulma.sass  <-- customize your sass here
  |-- index.html
  |-- LICENSE
  |-- package.json
  |-- webpack.config.js
```

### References
* https://hackernoon.com/webpack-the-basics-2712a7ad640b?token=dUoQB9dKDyvygSSO
* http://bulma.io/documentation/overview/customize/
* https://github.com/webpack-contrib/extract-text-webpack-plugin/issues/434
