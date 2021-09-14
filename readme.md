# 使用方式
1. 安装node-dev ```yarn global add node-dev```
2. 打开qq.com运行```node-dev server.js 8888```
3. 打开ajjj.com运行```node-dev server.js 9990```
4. 设置hosts
```
127.0.0.1 qq.com
127.0.0.1 ajjj.com
```
5. 打开两个页面 qq.com:8888/index.html 和 ajjj.com:9990/index.html
6. 记得删除hosts里面添加的内容 否则无法访问qq.com

## 主要信息
看一下qq.com里面的server.js的内容，预留位置，然后替换，回调。具体去参考笔记
JSONP的实现的部分代码比较多
笔记地址：https://www.yuque.com/docs/share/4cfec37d-3b5b-4ab9-a221-5c32698607ef?# 《跨域》
