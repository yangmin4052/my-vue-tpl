# my-vue-tpl

> My Vue.js template
> 这是我的 Vue 模板

## 使用方法

```bash
# 创建你的项目文件夹
mkdir a-vue-project

# 打开你的项目文件夹
cd a-vue-project

# git 初始化你的项目文件夹
git init

# 拉取我的代码，执行
git pull git@github.com:yangmin4052/my-vue-tpl.git
```

## 本模板配置了

```
eslint
prettier
os
scss
```

### eslint 说明

文件.eslintrc 中

```.eslintrc
'space-before-function-paren': 0
```

这一行是为了兼容 prettier，表示函数名与括号之间允许无空格。

### prettier 说明

prettier 是一个较为武断的格式化工具，所以在配置 eslint 时需要作出一定让步如果你使用的是 vscode 或其他一些 prettier 插件支持的编辑器，你可以使用 prettier 插件格式化你的代码，这很方便，但是你的同事未必和你使用同一种编辑器，所以为了使你们的代码风格一致，我在这里使用 prettier 模块来解决此问题，在你更改完你的代码后，执行以下命令

```bash
npm run format
```

当然，如果你使用的是 vscode 等 prettier 插件支持的编辑器，你需要根据文件 .prettierrc 中配置的那样设置你的编辑器，这样你仍然可以使用编辑器的插件来进行格式化。当然，如果我的 .prettierrc 中配置如果不符合你的要求，你需要根据你自己的要求来更改。

### os 说明

本模块是为了自动获取 ip，这样你的浏览器地址将不会是

```浏览器地址栏
localhost:8080/#/
```

而是类似于

```浏览器地址栏
10.136.0.0:8080/#/
```

* 注意：本人已经在 win7 测试可行，windows 其他版本未测试，mac 本的 ip 获取方式不同，需要您根据 mac 本的情况自行配置

### scss 说明

鉴于本人使用 scss，所以配置了 scss，你如果使用的是 css，也不会有问题

## Build Setup

```bash
# install dependencies
npm install

# serve with hot reload at localhost:8080
npm run dev

# build for production with minification
npm run build

# build for production and view the bundle analyzer report
npm run build --report
```

For a detailed explanation on how things work, check out the [guide](http://vuejs-templates.github.io/webpack/) and [docs for vue-loader](http://vuejs.github.io/vue-loader).
