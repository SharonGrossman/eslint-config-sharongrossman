# eslint-config-sharongrossman :straight_ruler:
![BuildStatus](https://travis-ci.org/SharonGrossman/eslint-config-sharongrossman.svg?branch=master)

## Description
ESLint shareable configuration

## Installation

```
$ yarn add --dev eslint-config-sharongrossman
```

In order to use the config, you must install a couple of plugins

```
$ yarn add --dev eslint-plugin-unicorn eslint-plugin-lodash eslint-plugin-import
```

For an additional React configuration you need to install the plugin

```
$ yarn add --dev eslint-plugin-react
```

## Usage

In your eslintrc.json file
```json
{
  "extends": ["sharongrossman"]
}
```

React config
```json
{
  "extends": ["sharongrossman/react"]
}
```


## License

[MIT](LICENSE) © [Sharon Grossman](https://github.com/sharongrossman)