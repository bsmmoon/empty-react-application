# empty-react-application

## What is this
It is an empty React application

## Why
Because every damn time I wanna create a new project I end up wasting my precious time

## How to use
### Installation
Copy the repo and use it as you wish
### How to run
```
npm build
npm start
```

## What happened
Just FYI

### Installation
https://www.codecademy.com/articles/react-setup-v

but, as always, tutorial didn't work (2018-08-26), proving the point of making this repo.

### Fixes
- `configuration.module has an unknown property 'loaders'`
  - replaced `loaders` to `rules` in `webpack.config.js`
- `Minified exception` blabla
  - replaced `"start": "webpack-dev-server"` to `"start": "webpack-dev-server --mode=development"` in `package.json`
- `React.createElement: type is invalid`
  - replaced `var App = require('./components/App')` to `import App from './components/App.js'` in `index.js`

### .gitignore
```
# Dependency directories
node_modules/
```

## References
- https://www.codecademy.com/articles/react-setup-v (and previous pages if you are interested)
