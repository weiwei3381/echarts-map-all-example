# echarts地图示例

## 背景

Echarts新版本对于地图（map）的支持越来越弱，官方示例极少，而且需要使用百度地图api，很不方便。而之前echarts2对于地图的支持非常好，并自带地图数据，以下是echarts2版本的地图示例。
![地图示例1](https://s1.ax1x.com/2020/04/18/JnF9VH.png)
![地图示例2](https://s1.ax1x.com/2020/04/18/JnFPIA.png)
![地图示例3](https://s1.ax1x.com/2020/04/18/JnFARP.png)

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

点击`echarts`可进入echarts2.0页面，查看相关文档，`echarts-example`里面存有echarts2的相关示例，并对代码进行了精简，更好读；`zrender`目录存放了zrender的离线文档和API，echarts依赖该类库。

## 示例

启动服务器后，在浏览器中输入`http://127.0.0.1:8001/echarts-example/map/`即可查看所有的地图示例，一共27个，包括模拟迁徙、大规模标注、范围标注、省市地图下钻等等。
![JnmXut.png](https://s1.ax1x.com/2020/04/18/JnmXut.png)
![JnmzE8.png](https://s1.ax1x.com/2020/04/18/JnmzE8.png)
![JnntUO.png](https://s1.ax1x.com/2020/04/18/JnntUO.png)
![Jnnf2j.png](https://s1.ax1x.com/2020/04/18/Jnnf2j.png)
