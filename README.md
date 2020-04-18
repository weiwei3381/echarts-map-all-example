# echarts 地图示例

## 背景

Echarts 新版本对于地图（map）的支持越来越弱，官方示例极少，而且需要使用百度地图 api，很不方便。而之前 echarts2 对于地图的支持非常好，并自带地图数据，以下是 echarts2 版本的地图示例。

![地图示例1](https://s1.ax1x.com/2020/04/18/Jnlqgg.png)

## 安装

项目使用`node`和`npm`，下载下来之后，在文件根目录运行`npm install`命令安装相关依赖。

## 用法

安装完毕后，在文件根目录运行`npm start`开启服务器，在浏览器中输入`http://127.0.0.1:8001`即可访问服务器。文件目录如下所示：

```batch
echarts_map_examples
 ├── echarts
 ├── echarts-example
 ├── node_modules
 ├── package-lock.json
 ├── package.json
 ├── README.md
 └── zrender
```

点击`echarts`可进入 echarts2.0 页面，查看相关文档，`echarts-example`里面存有 echarts2 的相关示例，并对代码进行了精简，更好读；`zrender`目录存放了 zrender 的离线文档和 API，echarts 依赖该类库。

## 示例

启动服务器后，在浏览器中输入`http://127.0.0.1:8001/echarts-example/map/`即可查看所有的地图示例，一共 27 个，包括模拟迁徙、大规模标注、范围标注、省市地图下钻等等。

![Jn1YVI.png](https://s1.ax1x.com/2020/04/18/Jn1YVI.png)

![JnmzE8.png](https://s1.ax1x.com/2020/04/18/Jn1RiV.png)

![JnntUO.png](https://s1.ax1x.com/2020/04/18/Jn1hzF.png)

![Jnnf2j.png](https://s1.ax1x.com/2020/04/18/Jn1Hd1.png)
