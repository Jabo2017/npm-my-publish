# npm-my-publish


# 注册[npm账号](https://www.npmjs.com/)



## 删除多余配置 build/webpack.prod.conf.js  配置output

## 修改package.json : "private": false
> 增加 "main":"dist/npm-my-publish.min.js",


## config/index.js 修改 ： assetsSubDirectory: '/',


## 修改main.js
>import NpmMyPublish from './components/Button'

>export default NpmMyPublish


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

# 注意包名不要重复

>在[npm官网搜索](https://www.npmjs.com/) 发布的包名  npm-my-publish 即可找到