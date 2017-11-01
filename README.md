<p align="center">
    <a href="https://ivueui.zcyso.com">
        <img width="200" src="https://ivueui.zcyso.com/assets/logo.svg">
    </a>
</p>

# iVueui

[![GitHub issues](https://img.shields.io/github/issues/ivueui/ivueui.svg?style=flat-square)](https://github.com/ivueui/ivueui/issues)
[![GitHub forks](https://img.shields.io/github/forks/ivueui/ivueui.svg?style=flat-square)](https://github.com/ivueui/ivueui/network)
[![GitHub stars](https://img.shields.io/github/stars/ivueui/ivueui.svg?style=flat-square)](https://github.com/ivueui/ivueui/stargazers)
[![NPM downloads](https://img.shields.io/npm/dt/ivueui.svg?style=flat-square)](https://npmjs.org/package/ivueui)
[![NPM downloads](http://img.shields.io/npm/dm/ivueui.svg?style=flat-square)](https://npmjs.org/package/ivueui)
[![iView](https://img.shields.io/npm/v/ivueui.svg?style=flat-square)](https://www.npmjs.org/package/ivueui)
[![GitHub license](https://img.shields.io/badge/license-MIT-blue.svg?style=flat-square)](https://raw.githubusercontent.com/ivueui/ivueui/master/LICENSE)

[![NPM](https://nodei.co/npm/ivueui.png)](https://nodei.co/npm/ivueui/)

### A high quality UI Toolkit built on Vue.js.

> 此分支版本为 Vue.js 2.x.
>
> The branch for Vue.js 1.x can be found [here](https://github.com/ivueui/ivueui/tree/master).

## Docs

### [iVueui文档](https://ivueui.zcyso.com)
## Install

> 请先安装 Webpack!

Using npm:
```
npm install ivueui --save
```

Using a script tag for global use:

```html
<script type="text/javascript" src="ivueui.min.js"></script>
<link rel="stylesheet" href="dist/styles/ivueui.css">
```

You can find more info [on the website](https://ivueui.zcyso.com/docs/guide/install).

## Usage

```vue
<template>
    <Slider v-model="value" range />
</template>
<script>
    export default {
        data () {
            return {
                value: [20, 50]
            }
        }
    }
</script>
```

Using css via `import`:

```js
import 'ivueui/dist/styles/ivueui.css';
```
## Links
- [Vue](https://github.com/vuejs/vue)
- [Webpack](https://github.com/webpack/webpack)
- [Ionicons](https://github.com/driftyco/ionicons)
- [草莓图标](https://github.com/xiangsudian/caomei)
- [Ant Design](https://github.com/ant-design/ant-design)

## License
[MIT](http://opensource.org/licenses/MIT)

Copyright (c) 2016-present, iVueui
