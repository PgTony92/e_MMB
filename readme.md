##  1、郑维老师 提供的web服务器信息
- http://47.52.242.30/mmb

## 2、请在页面中引入axios.js文件,因为我使用它来发送axaj请求了.

## 3、使用原型方法获取页面数据时的注意事项:
- 请在方法后面再调用then方法,
- 然后在then方法中传入回调函数,此回调函数的参数即是想要的数据.
- 比喻说 获取主页菜单数据.
```
new MMB().getIndexMenu.then(res=>console.log(res);
```

## 4、组长林泽涛为组员初步划分了任务,详见根目录下的图片

## 5、刘诗伟新增了baicaijia.html文件

## 6、因为月底要学习Vue,而axios是Vue标配的ajax模块.所以我使用axios完成了项目的全部ajax请求