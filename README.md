# Serverless Plugin Typescript Express

[![serverless](http://public.serverless.com/badges/v3.svg)](http://www.serverless.com). 

Credits:
- [@hewmen](https://github.com/hewmen/serverless-plugin-typescript)
- [@eliasjcjunior](https://github.com/eliasjcjunior/serverless-plugin-typescript-express)

## Features

   * Integrates with serverless-offline (live reload without restart server)
   * It's not necessary complementary configuration

## Installation and use

```sh
yarn add --dev sls-plugin-typescript-express
```
or
```
npm install --save-dev sls-plugin-typescript-express
```

Add the following plugin to your `serverless.yml`:

```yaml
plugins:
  - 'sls-plugin-typescript-express'
```

### `tsconfig.json`

The default `tsconfig.json` file used by the plugin looks like this:

```json
{
    "compilerOptions": {
      "target": "es6",
      "module": "commonjs",
      "outDir": "dist",
      "sourceMap": true,
      "experimentalDecorators": true,
      "emitDecoratorMetadata": true,
      "isolatedModules": false,      
      "lib": [ 
        "es6", 
        "dom" 
      ]
    },
    "include": [
      "src/**/*"
    ],
    "exclude": [
      "node_modules"
    ]
  } 
```

## Contributions welcome!

[Open a new PR](https://github.com/nordible/sls-plugin-typescript-express/pulls) here on GitHub.

## Bugs and Issues

Have a bug or an issue? [Open a new issue](https://github.com/nordible/sls-plugin-typescript-express/issues) here on GitHub.


### The input folder src cannot be overwritten

## License

Code licensed under [MIT](https://opensource.org/licenses/MIT). Everything else is [CC](http://creativecommons.org/)

## Follow us

* [twitter.com/nordiblehq](https://twitter.com/nordiblehq)
* [fb.com/nordible](https://www.facebook.com/nordible)

&copy; [nordible](https://nordible.com/)
