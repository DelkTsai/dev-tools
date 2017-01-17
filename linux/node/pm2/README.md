# PM2
使用PM2守护Nodejs命令行程序。pm2是nodejs的一个带有负载均衡功能的应用进程管理器的模块，类似有Supervisor，forever，用来进行进程管理。

### 一、安装：
```js
npm install pm2 -g
```
### 二、启动：
```js
pm2 start app.js
pm2 start app.js --name my-api     #my-api为PM2进程名称
```
