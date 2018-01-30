# car
这是一个二手车平台项目
###  运行方法
- 确保安装NodeJS
- mongoDB服务器环境
- 使用mongo命令开启mongoose服务器
```
mongod --dbpath C:\data
```
- 使用mongo命令创建yayuncun服务器
```
use yayuncun
```
- 在init_util文件夹中 node _mokedata.js 将模拟数据写入mongoose数据库
- node app.js 将页面挂载到本地的3000端口
- 打开http://127.0.0.1:3000将看到此项目~
