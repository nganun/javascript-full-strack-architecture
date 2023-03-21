# JavaScript Full Strack Architecture

## BasicApp

1. Create project

```sh
scoop install yarn
yarn global add webpack@2.6.1
mkdir BasicApp
cd BasicApp
yarn init # Enter to end
```

2. Add webpack config

```js
module.exports = {
  entry: './src/app.js',
  output: {
    filename: './dist/app.bundle.js'
  }
}
```

3. Webpack the js

```sh
webpack
```

