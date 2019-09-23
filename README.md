<div align="center">
<h1> eslint-config-sharongrossman :straight_ruler: </h1>

![BuildStatus](https://travis-ci.org/SharonGrossman/eslint-config-sharongrossman.svg?branch=master) 
[![Greenkeeper badge](https://badges.greenkeeper.io/SharonGrossman/eslint-config-sharongrossman.svg)](https://greenkeeper.io/) [![semantic-release](https://img.shields.io/badge/%20%20%F0%9F%93%A6%F0%9F%9A%80-semantic--release-e10079.svg)](https://github.com/semantic-release/semantic-release)


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
  "extends": ["sharongrossman"]
```

React config
```json
  "extends": ["sharongrossman/react"]
```


## License

[MIT](LICENSE) © [Sharon Grossman](https://github.com/sharongrossman)
</div>