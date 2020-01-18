# 1 webpack入门
## 1.1 初始化项目
新建一个目录，初始化npm

```
  npm init
```

webpack是运行在node环境中的,我们需要安装以下两个npm包
```
npm i -D webpack webpack-cli
```
* npm i -D 为npm install --save-dev的缩写
* npm i -S 为npm install --save的缩写
新建一个文件夹`src` ,然后新建一个文件`main.js`,写一点代码测试一下
```
console.log("hello,webpack");
```

配置package.json命令
```
"script": {
    "build": "webpack src/main.js"
}
```
执行
```
npm run build
```
此时如果出现了一个dist文件夹，并且内部含有main.js说明已经打包成功了

## 1.2 开始我们的配置
