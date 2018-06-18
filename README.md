# npm-publish


# 注册[npm账号](https://www.npmjs.com/)



## 删除多余配置 build/webpack.prod.conf.js  配置output

## 修改package.json : "private": false
> 增加 "main":"dist/npm-publish.min.js",


## config/index.js 修改 ： assetsSubDirectory: '/',


## 修改main.js
>import NpmPublish from './components/Button'

>export default NpmPublish


# 发布前打包
> npm run build

```
会生成一个dist目录

```

## 修改 .gitignore
> 删除 /dist/   【需要发布dist目录】



> 在控制台中 命令行操作

>》 npm login


> 发布

>》 npm publish

